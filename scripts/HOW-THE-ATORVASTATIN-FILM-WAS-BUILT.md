# How the atorvastatin film was built

This is the cut the owner kept (about 3 minutes 11 seconds). Copy the pattern. Change the drug, the pictures, and the facts. Do not change the shape of the film.

## Script pattern

Ten chapters. Each chapter title is a question. That question is the progress-bar chapter and, after the opening, the words at the top of the picture. The spoken lines answer it. They are not written as “Q:” and “A:”.

1. What is this drug? Welcome to Mechanism Diligence. You might be here to understand a drug you were prescribed, or to learn how it works. Name the drug. Brand in brackets, and say the brand may be the name they already know.
2. What is the condition? Define it in one sentence. Show the thing the film follows, and the lookalikes, before any mechanism. For this drug: cholesterol is the molecule, LDL is the larger particle, HDL is the smaller one.
3. What can years of that problem do? The risk, then the line that only a test can confirm it and it cannot be felt.
4. What does the drug block? Class, the enzyme, and the plain effect. One pass. Do not explain the enzyme twice.
5. Where does the work happen? The organ, then the cell. Liver cells make most of the body’s cholesterol.
6. How does it get in? The barrier, then the named transporters. Here, OATP1B1 and OATP1B3. Do not drop the transporters to save time.
7. What happens at the enzyme? The building block, the product, the drug seated in the enzyme, less product, less of what comes after.
8. What happens to the test? The organ takes more back and sends less out. The number falls on a blood test. It takes time. The block lets go. It works only while the drug is taken on the doctor’s schedule.
9. What dose does the label list? Start, range, maximum, and the higher start if a larger drop is needed. Say these are label limits, not a dose chosen for one person. Do not drop the dose.
10. What are the limits? Contraindications, the serious harm, then education only, then mechanismdiligence.com.

Do not say why the tablet was prescribed. Do not say it is taken by mouth together with diet unless that line is requested. Say scientific words as whole words. Do not put spaces inside hyperlipidemia, the drug name, or mevalonate.

Facts for dose, transporters, and contraindications come from the Lipitor prescribing information revised April 2024.

## Picture

1920×1080, black, 24 fps.

- Top left, every scene, same pixels: the lockup at `/workspace/films/brand/logo.png`. Height 104, native aspect, colors kept (white M, teal D, white Mechanism, teal Diligence). Do not stretch it, do not redraw it, and do not change its size from scene to scene.
- Card text sits in the middle of the frame, not under the header. The bottom half is not left empty.
- Opening only: the centered heading is “Mechanism Diligence,” large, and lower than the top edge. The drug name is large. The brand is in brackets. A chemical structure and a 3D model sit side by side, big enough to read, each with a caption: “Chemical structure” and “3D representative structure.”
- After the opening, the centered heading is the chapter question, not the company name. The player does not repeat that question in the corner.
- Subtitles sit above the player bar, on a plate only as wide as the words.
- Labels are larger, in the object’s color, and only on the thing being discussed.
- A card is used for class, dose, and limits. Science scenes are the organ, the cells, the membrane, the enzyme, the particles. One picture per idea. No picture of the drug while the line is about LDL or the artery.
- Each molecule keeps one color for the whole film. On the ibuprofen film: ibuprofen is gold, arachidonic acid is icy blue and drawn as a ball-and-stick lipid, prostaglandin E2 is green, PLA2 is copper, and the COX enzymes are teal. Do not draw arachidonic acid as a jewelry chain.

## Player

Chapters are the questions. White ticks mark the sections. Hovering the bar shows the question. Speeds are 1×, 1.5×, and 2×. Click the picture to pause or play. The question is not also printed at the bottom left of the controls.

## Build

`films/atorva_v4/build.py`

- Voice: en-US-AndrewNeural, rate −8%. One mp3 per sentence. Retry if the service returns nothing. Do not respell a word with spaces.
- Gap 0.22 s inside a chapter, 0.42 s between chapters.
- Plates are drawn in PIL. Photographs drift slowly underneath a locked text overlay. The liver line uses the moving liver clip. Cards and the title stay still so the type does not drift.
- Sentences are concatenated, then the narration is muxed.
- Output: `public/library/atorvastatin/v4.mp4`, poster, and `v4-chapters.json`. The catalog lists it first.
- A downloadable link is an xAI file with a public URL that does not expire.
