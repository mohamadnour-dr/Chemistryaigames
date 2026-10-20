# Chemistryaigames

hree browser games for first-year general chemistry, drafted with a large language model (Claude Sonnet 4.6, Anthropic) and reviewed by chemistry educators. They accompany the article *Large Language Model-Assisted Design of Chemistry Games for Health Professions Students* (BMC Medical Education, under review).

| Game | File | Play |
|---|---|---|
| Acid Shooter (acid–base chemistry) | `Game1_AcidShooterFinal.html` | [link](https://mohamadnour-dr.github.io/Chemistryaigames/Game1_AcidShooterFinal.html) |
| Periodic Table Treasure Hunt | `Game2_Treasure_Hunt_final.html` | [link](https://mohamadnour-dr.github.io/Chemistryaigames/Game2_Treasure_Hunt_final.html) |
| VSEPR Haunted Lab | `Game3_VSEPR_Haunted_Lab__final.html` | [link](https://mohamadnour-dr.github.io/Chemistryaigames/Game3_VSEPR_Haunted_Lab__final.html) |

Earlier versions are in the `archive` folder. The games run in any browser, need no login, and store no data.

## Known errors and limitations — please read before using the games in class

The files in this repository are the exact versions that were evaluated in the study, so they have **not** been corrected. After classroom use, every text that a student can see (232 text units) was checked item by item by chemists who had not made the games, and the authors adjudicated the results. **22 of 219 scientific statements (10%) were classified as errors.** None of them changes a correct answer, but several appear in explanations and applied notes that students read. If you use the games, please point out these errors to your students or correct the texts in your own copy.

### Errors

| ID | Game | Text in the game | Type | Correct version |
|---|---|---|---|---|
| A18 | Acid Shooter | F⁻ is a moderately strong conjugate base — conjugate of a weak acid = relatively strong base | Overstatement | F⁻ is a weak base (Kb ≈ 1.5 × 10⁻¹¹), but a stronger base than Cl⁻, because HF is a weaker acid than HCl. |
| A28 | Acid Shooter | pKa = 4.76: only ~1.3% dissociated at pH 7 — a true weak acid with partial ionization | Numerical value or condition | pKa = 4.76: a 0.10 M solution is only about 1.3% ionized — a weak acid with partial ionization. |
| A29 | Acid Shooter | Only the −COOH hydrogen ionizes; C−H bonds are far too stable (no resonance stabilization of carbanion) | Factual error | Only the −COOH hydrogen ionizes in water: removing it leaves the negative charge on oxygen, spread over both oxygen atoms. C−H bonds are far less acidic. |
| A42 | Acid Shooter | Blood pH 7.4: pH = 6.35 + log([HCO₃⁻]/[H₂CO₃]) → ratio ≈ 20:1 | Numerical value or condition | Blood pH 7.4: pH = pK′ + log([HCO₃⁻]/[CO₂]), with pK′ ≈ 6.1 at 37 °C → ratio ≈ 20:1 (with pKa 6.35 the ratio would be about 11:1). |
| A54 | Acid Shooter | NH₃ is a moderately strong base: Kb = 1.8×10⁻⁵, pKb = 4.75 | Overstatement | NH₃ is a weak base: Kb = 1.8×10⁻⁵, pKb = 4.75. |
| A69 | Acid Shooter | Phosphate buffer (pKa₂=7.20) is the primary intracellular buffer. | Overstatement | Phosphate (pKa₂ = 7.20) is an important intracellular buffer, together with proteins. |
| T01 | Treasure Hunt | You encounter this element every time you reach for a salt shaker — table salt (NaCl) is mostly this metal. | Factual error | Table salt (NaCl) is made of sodium ions (Na⁺) and chloride ions (Cl⁻). |
| T45 | Treasure Hunt | The Eiffel Tower is built entirely from it. | Overstatement | The Eiffel Tower is built mainly from it. |
| T46 | Treasure Hunt | Many breakfast cereals are 'iron-fortified', meaning they contain actual tiny metal filings you eat. | Overstatement | Many breakfast cereals are 'iron-fortified' with iron salts or finely powdered elemental iron. |
| T56 | Treasure Hunt | Every breath you take pulls this element into your lungs — it makes up 21% of Earth's atmosphere and every cell burns it to release energy. | Overstatement | …it makes up 21% of Earth’s atmosphere and most cells use it to release energy. |
| T62 | Treasure Hunt | I have 2 bonding pairs and 2 lone pairs. | Terminology | In water I form 2 bonds and keep 2 lone pairs. |
| T71 | Treasure Hunt | The entire backbone of your DNA is a chain of these phosphate groups. | Factual error | The backbone of your DNA is a chain of alternating sugar (deoxyribose) and phosphate groups. |
| T83 | Treasure Hunt | Phosphate (PO₄³⁻) carries 3 negative charges at physiological pH — key biochemical anion | Numerical value or condition | At physiological pH, phosphate exists mainly as HPO₄²⁻ and H₂PO₄⁻ — a key biochemical anion. |
| V02 | VSEPR Haunted Lab | No H: L.P = (V.E − 8n)/2 = (16 − 8×2)/2 = 0; n = number of bonds = 2. | Terminology | n = number of atoms bonded to the central atom = 2. |
| V10 | VSEPR Haunted Lab | Its linear geometry allows efficient diffusion across lipid bilayers. | Overstatement | CO₂ is small and non-polar, so it diffuses easily across lipid bilayers. |
| V21 | VSEPR Haunted Lab | Lewis acid-base chemistry: BF₃ accepts lone pairs from drugs and biomolecules — critical in coordination chemistry. | Overstatement | BF₃ is a Lewis acid: its empty p orbital accepts a lone pair from a Lewis base. |
| V30 | VSEPR Haunted Lab | Tetrahedral carbon is the backbone of all organic and pharmaceutical chemistry | Overstatement | Tetrahedral (sp³) carbon is common in organic and pharmaceutical molecules. |
| V31 | VSEPR Haunted Lab | sp³ carbon forms the backbone of every drug molecule. | Overstatement | sp³ carbon is common in drug molecules. |
| V34 | VSEPR Haunted Lab | The perfect tetrahedral shape of CH₄ is the template for every carbon atom in organic chemistry and biochemistry. | Overstatement | The tetrahedral shape of CH₄ is the model for every sp³ carbon atom. |
| V55 | VSEPR Haunted Lab | Lone pair formula: No hydrogen L.P = (V.E − 8n)/2; has hydrogen L.P = (V.E − 2n)/2, where n = number of bonds on the central atom. | Rule of limited validity | General form: L.P = (V.E − 8 × [outer atoms other than H] − 2 × [H atoms]) / 2. |
| V60 | VSEPR Haunted Lab | Column headers: "e⁻ Domains \| Bonds \| Lone Pairs \| Geometry \| Bond Angle" | Terminology | Columns: Electron domains \| Bonded atoms \| Lone pairs \| Molecular geometry \| Bond angle. |
| V61 | VSEPR Haunted Lab | "Electron domains = bonds + lone pairs = 2 + 0 = 2" (CO₂; same line for each door, and "Electron domains = 2 bonds + 0 lone pairs = 2" in the final walkthrough) | Terminology | Electron domains = bonded atoms + lone pairs = 2 + 0 = 2. |

### Interface inconsistencies

- **A63** (Acid Shooter): Level text "Moving fast — aim precisely!" is left over from the first shooter version; all levels move at the same speed.
- **A72** (Acid Shooter): Start screen says that hitting the wrong atom costs a life; only a non-acidic hydrogen costs a life, and a non-hydrogen atom has no penalty (A73).
- **T87** (Treasure Hunt): The opening screen lists a periodic-table puzzle finale, which is in the code but is not reached (replaced by the final screen).
- **V56** (VSEPR Haunted Lab): Instruction screen refers to five doors/rooms; the game has four (left over from the five-door draft).
- **V64** (VSEPR Haunted Lab): Game numbers in the page titles (Acid Shooter "Game 3", Treasure Hunt "Game 1", VSEPR "Game 2") differ from the numbering used in the paper. Also A77 and T90.

### Other limitations

- **Acid Shooter:** Acidic hydrogen atoms are tinted, which gives a visual cue to the correct target (A71).
- **Acid Shooter:** Only one level (acetic acid) asks students to tell acidic from non-acidic hydrogen atoms.
- **Acid Shooter:** Molecules are drawn as flat 2D structural formulas; NH₄⁺ appears as a square with 90° angles rather than a tetrahedron (A78).
- **Treasure Hunt:** Octet expansion of phosphorus is explained with 3d orbitals (T76, T81). This is a common textbook simplification; current bonding models do not require d-orbital participation.
- **VSEPR Haunted Lab:** The lone-pair rule is valid only for the molecules used in the game (see V55); the game covers four molecules with two to four electron domains and no bent molecules, expanded octets, or five or six electron domains.
- **All games:** The games were not changed after the errors were found, so that the files remain the versions that were evaluated. The errors are listed in the repository README.

The full checklists, with the checkers’ verdicts and the authors’ adjudication, are available from the corresponding author on request.

