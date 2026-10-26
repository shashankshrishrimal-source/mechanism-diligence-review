# V2_Scientific

Mechanism Diligence scientific audio master — October 25, 2026

This revision covers all 19 drugs in the supplied AUDIO-SCRIPTS.md. It is the detailed scientific version for scientists, chemists and students. It is intended to be the source from which Medical and Basic versions are later adapted. Independent clinical review remains pending.

## Files to give Grok

1. **V2_Scientific.md** — complete narration in the original drug order.
2. **V2_Scientific_Evidence.md** — non-spoken sources, label sections, product scope, claim maps, corrections and evidence limits.
3. **scripts/** — individual Markdown scripts and plain-text recording copies. The `.txt` files contain only the words to speak, including the questions.
4. **[TIMING.md](TIMING.md)** — rough per-drug running times, with room for pauses.
5. **[manifest.json](manifest.json)** — public file inventory and SHA-256 checksums. These verify file identity, not clinical approval.

## Start here

Read **[GROK_START_HERE.md](GROK_START_HERE.md)**, then watch the repository's **[cinematic ibuprofen v7](../../films/ibuprofen-v7.mp4)**. Begin the Scientific ibuprofen film with **[scripts/ibuprofen.txt](scripts/ibuprofen.txt)** and its section in the evidence companion.

This folder is the current **V2_Scientific production source**. It controls narration, product/route scope, qualifications, and the opening and closing. Cinematic ibuprofen v7 controls visual style; it does not override the new narration. The root `scripts/` folder and existing films are earlier review material. Preserve them for comparison; do not merge their doses, wording or unresolved claims into V2. A historical hold is not proof that a claim has since been resolved: check the V2 evidence and the current selected-product label before recording.

This package contains all 19 drugs. Independent clinical review remains pending. Make review cuts and retain that statement; this handoff does not authorize publishing a finished film to the website. Original working files and research records are preserved separately. The public evidence companion retains source links, claim maps and limitations; only references to private working-file locations have been removed.

## Opening and closing

Every film starts with:

> Welcome to Mechanism Diligence.
> Let’s talk about {generic name}, which is the generic name.
> {Brand} is a brand name, and it may be the name you already know.

The last line uses the plural for ibuprofen's two named brands. Brands identify a familiar name, not every formulation or combination sold under that name. Glucophage is expressly identified as a historical brand reference. The first answer specifies the selected product and route.

Every film ends with exactly:

> This video is for educational purposes only. It is not personal medical advice, and clinical review is pending. For the sources, references, and to leave feedback, go to mechanismdiligence.com.

These follow the user's new audio directions, replacing the earlier bible's opening and contact-heavy close. The spelling and grammar of “educational purposes” and “references” have been corrected. The close must remain audible and complete.

## Delivery

Use natural US English, as a knowledgeable teacher speaking to one attentive listener in a quiet room. Aim for **120–130 words per minute**, slowing for molecular names, definitions, mechanisms and dose limits. Leave a short pause after each question and each causal step that needs the picture to catch up. TIMING.md gives rough planning estimates including modest pauses and visual holds; exact runtime follows the recorded voice and picture.

Speak complete thoughts, with normal variation in stress and sentence length. Do not use advertising emphasis, a fixed beat after every sentence, a dramatic voice, or a rising tone on every question. Let the question introduce the next idea; the answer should sound like an explanation, not a checklist. Do not rush the safety paragraph to fit a runtime. No music under the science, mascot, patient face, joke or happy-ending flourish.

Questions are spoken. Drug titles, contents, evidence tables and production notes are not. A text-to-speech tool should receive one drug's `.txt` file plus its pronunciation guidance, not the evidence document or this README. Check the rendered audio: spelling a word or supplying a pronunciation guide does not prove it will be pronounced correctly.

Read doses and units in full. Use a consistent pronunciation of CYP (“sip”), followed by its family designation, such as “sip three A four.” Say ATP, AMP, BDNF and DNA as letters; COX as “cocks”; SERT as “sert”; AMPA as “AM-puh.” For OATP1B1, BCRP, NPC1L1, SGLT2 and similar names, use the full name or the letter-by-letter pronunciation supplied in each evidence record. Do not have a voice engine invent pronunciations for strings of letters and digits. Say mechanismdiligence.com as “mechanism diligence dot com.”

## Story and scientific depth

Each film follows the same path: identity and clinical context → relevant physiology → route → physical drug–target event → downstream changes → established knowledge and uncertainty → benefit and harm → time course → bounded adult label regimen → essential restrictions → mechanism recap.

The mechanism chapters carry the explanation. Dosing is supplementary and tied to a named route, formulation and indication. A labeled regimen is not a personal prescription. When the label does not give one universal maximum, the narration does not invent one. Plasma half-life, onset of measured effects, symptom response, and long-term outcomes are kept distinct.

Scientific depth comes from explaining the causal steps and their limits, not from listing every newly reported target. Definitions are given where needed. Established direct interactions are separated from proposed explanations of clinical benefit. Animal experiments are not described in the spoken scripts. A few qualified pathway models remain when they are essential to explaining an unresolved human mechanism; their laboratory origins and limitations are explicit. Detailed animal findings and excluded hypotheses stay in the evidence notes.

For Medical or Basic adaptations, retain the target, the actual action, the principal consequence, essential uncertainty, and the serious restrictions. Simplify wording and remove secondary details; do not turn a proposed mechanism into a fact, a warning into reassurance, or a dose example into an instruction to the viewer.

## Picture discipline

Keep the established cinematic format: full-bleed black, 1920×1080, no baked-in text in 3D plates. Add readable labels afterward, in the molecule's color. Show molecules acting, with the sentence synchronized to the event. Use one labeled route per film; oral is not the default. Albuterol is oral inhalation, adalimumab is subcutaneous, and esketamine is intranasal.

For several mechanisms, repeat a clearly separated target/action/consequence loop. A downstream consequence is not automatically a second direct target. Keep benefit and harm from the same action in a shared frame where a supported causal link exists; do not fabricate one for every adverse effect. Use an explicit “Proposed” overlay when an uncertain pathway is shown, and keep it visible for the whole proposed sequence.

Do not copy experimental stabilizers, extra ligands or species-specific assemblies into a clinical animation as normal human anatomy. The evidence notes identify important examples. These sources do not supply literal travel speeds, concentration ratios or a seamless body-to-atom scale. Use a visible scale break and a new location label rather than suggesting a continuous physically accurate zoom.

## Substantive corrections

- **Ibuprofen:** separated the OTC adult dose from prescription limits; clarified reversible COX inhibition and protective prostanoid functions.
- **Amlodipine:** replaced a pore-plug image with allosteric channel inhibition.
- **Apixaban:** completed the two-of-three dose-reduction criteria and both boxed warnings; distinguished reduced clot formation from clot dissolution.
- **Omeprazole:** explained acid trapping, prodrug activation and covalent inhibition, while separating plasma clearance from pump recovery.
- **Famotidine:** supplied a bounded GERD regimen and the cross-class serious-hypersensitivity contraindication.
- **Albuterol:** corrected the claim that its label stops at cyclic AMP; explained downstream relaxation and systemic effects.
- **Metoprolol:** locked the dose to succinate extended release and stable heart failure; separated immediate contractile effects from long-term benefit.
- **Rosuvastatin:** distinguished uptake transport from BCRP-mediated export.
- **Levothyroxine:** restored the adrenal-insufficiency contraindication and explained tissue conversion to T3.
- **Metformin, sertraline and esketamine:** separated established drug actions from incompletely resolved human therapeutic mechanisms.
- **Adalimumab:** kept TNF binding extracellular and corrected the distinction between formal contraindications and serious warnings.
- **Esketamine:** added respiratory depression, complete contraindication categories, current TRD monotherapy eligibility and monitoring beyond a minimum observation time when needed.

The per-drug sections in V2_Scientific_Evidence.md document the remaining corrections and supporting sources. Current US labels and recent literature were checked, but this is an editorial scientific review, not independent clinical validation. Recheck the selected label before recording and retain the pending-review statement until an actual clinical review is completed.
