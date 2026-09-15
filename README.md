# CHM-110 Nomenclature Quiz

An interactive browser-based quiz for practicing introductory chemical nomenclature in **CHM-110 / Chemistry 101**.

The quiz is based primarily on **OpenStax Chemistry 2e, Chapter 2**, especially Sections **2.6: Ionic and Molecular Compounds** and **2.7: Chemical Nomenclature**.

<img width="688" height="705" alt="image" src="https://github.com/user-attachments/assets/ee64ab30-bdef-4e25-b96e-c34dc555fa50" />
Live App: https://realityexpander.github.io/CHM-110_nomenclature_quiz/

## Features

- **100-question question bank**
- Presents **10 randomly selected questions per quiz session**
- Gives immediate feedback after each answer
- Shows a running score during the quiz
- Gives a final score after 10 questions
- Reviews only the questions missed
- **New 10-Question Quiz** button generates another randomized set from the 100-question bank
- Randomizes both question selection and answer-choice order
- Runs entirely in the browser
- No server, database, framework, or external JavaScript library is required
- Can be hosted directly with **GitHub Pages**

## Topics Covered

The question bank includes practice with:

- Chemical name → chemical formula
- Chemical formula → chemical name
- Ionic compounds
- Molecular (covalent) compounds
- Metal + nonmetal identification
- Nonmetal + nonmetal identification
- Ionic vs. molecular classification
- Fixed-charge metal ions
- Variable-charge metal ions
- Roman numeral nomenclature
- Molecular prefixes such as:
  - mono-
  - di-
  - tri-
  - tetra-
  - penta-
  - hexa-
- Polyatomic ions
- Zinc compounds
- Silver compounds
- Alkali metals
- Alkaline-earth metals
- Halogens
- Noble gases

## Polyatomic Ions

Questions include commonly encountered ions such as:

- Ammonium: $\mathrm{NH_4^+}$
- Hydroxide: $\mathrm{OH^-}$
- Nitrate: $\mathrm{NO_3^-}$
- Nitrite: $\mathrm{NO_2^-}$
- Sulfate: $\mathrm{SO_4^{2-}}$
- Carbonate: $\mathrm{CO_3^{2-}}$
- Phosphate: $\mathrm{PO_4^{3-}}$
- Iodate: $\mathrm{IO_3^-}$
- Hypochlorite: $\mathrm{ClO^-}$
- Chlorite: $\mathrm{ClO_2^-}$
- Chlorate: $\mathrm{ClO_3^-}$
- Perchlorate: $\mathrm{ClO_4^-}$

## Example Nomenclature Relationships

Examples of the types of relationships practiced in the quiz include:

- Sodium chloride: $\mathrm{NaCl}$
- Magnesium nitride: $\mathrm{Mg_3N_2}$
- Aluminum oxide: $\mathrm{Al_2O_3}$
- Calcium phosphate: $\mathrm{Ca_3(PO_4)_2}$
- Ammonium sulfate: $\mathrm{(NH_4)_2SO_4}$
- Potassium iodate: $\mathrm{KIO_3}$
- Silver nitrate: $\mathrm{AgNO_3}$
- Zinc chloride: $\mathrm{ZnCl_2}$
- Iron(III) chloride: $\mathrm{FeCl_3}$
- Copper(I) oxide: $\mathrm{Cu_2O}$
- Dinitrogen tetroxide: $\mathrm{N_2O_4}$
- Phosphorus pentachloride: $\mathrm{PCl_5}$

## Accessibility

The quiz uses high-saturation feedback colors to make correct and incorrect responses easier to distinguish.

```css
--good:#00FF00;
--goodbg:#60EF60;
--bad:#FF0000;
--badbg:#EF6060;
```

The correct and incorrect choices also use strong borders and contrasting background shading.

These colors were selected to improve visual distinction for users who have difficulty distinguishing lower-saturation red and green interface colors.

## How the Quiz Works

1. Open `index.html` in a modern web browser.
2. The program randomly selects **10 questions from the 100-question bank**.
3. Select an answer for each question.
4. The quiz immediately shows whether the answer is correct or incorrect and provides a short explanation.
5. After Question 10, the quiz displays:
   - final score,
   - percentage,
   - and a review of missed questions.
6. Select **New 10-Question Quiz** to start another randomly selected set.

Because each session draws from the full 100-question bank, repeated sessions provide varied practice.

## Running Locally

No installation is required.

Download `index.html` and open it directly in a browser.

The application is self-contained and does not require an internet connection after the file has been downloaded.

## Hosting on GitHub Pages

A simple repository can contain:

```text
/
├── index.html
└── README.md
```

Because the quiz file is named `index.html`, GitHub Pages can load it automatically from the repository root.

Enable GitHub Pages in the repository settings and choose the branch/folder you want GitHub Pages to publish.

## Source Material

The academic content is based primarily on:

**OpenStax, Chemistry 2e**

Authors:

- Paul Flowers
- Klaus Theopold
- Richard Langley
- William R. Robinson, PhD

Publisher: **OpenStax**

### Section 2.6 — Ionic and Molecular Compounds

This section provides the foundation for:

- distinguishing ionic and molecular compounds,
- understanding cations and anions,
- predicting ionic formulas from ion charges,
- recognizing the relationship between metals, nonmetals, and compound type,
- and working with common polyatomic ions.

Source:

https://openstax.org/books/chemistry-2e/pages/2-6-ionic-and-molecular-compounds

### Section 2.7 — Chemical Nomenclature

This section provides the primary naming rules used in the quiz, including:

- binary ionic compound nomenclature,
- monatomic ions,
- polyatomic ionic compounds,
- metals with variable charges,
- Roman numeral notation,
- molecular compound nomenclature,
- and Greek prefixes used to indicate the number of atoms in molecular compounds.

Source:

https://openstax.org/books/chemistry-2e/pages/2-7-chemical-nomenclature

## Course-Specific Additions

The question bank also contains additional practice requested for this CHM-110 course, including:

- zinc,
- silver,
- iodate,
- alkali metals,
- alkaline-earth metals,
- halogens,
- and noble gases.

These additions supplement the primary OpenStax nomenclature material and reflect topics emphasized in the course.

## Scope

This quiz is intended as a practice and review tool for introductory inorganic nomenclature.

It is not intended to replace:

- assigned course readings,
- instructor notes,
- laboratory materials,
- homework systems,
- or the official OpenStax textbook.

When course-specific naming conventions differ from a general chemistry reference, follow the conventions required by the instructor.

## Technology

The application is written as a single self-contained file using:

- HTML
- CSS
- JavaScript

No build process or package manager is required.

## GitHub LaTeX Compatibility

Chemical formulas in this README use GitHub-supported inline LaTeX math syntax.

Example:

```text
$\mathrm{Ca_3(PO_4)_2}$
```

GitHub renders this as:

$\mathrm{Ca_3(PO_4)_2}$

Subscripts use `_`, superscripts use `^`, and multi-character charges are grouped with braces, for example:

```text
$\mathrm{SO_4^{2-}}$
```

## License and Attribution

OpenStax textbook material should be used and attributed according to the license terms published by OpenStax for *Chemistry 2e*.

This quiz is an independent study aid and is not an official OpenStax product.

## Repository Files

Recommended repository structure:

```text
CHM-110-Nomenclature-Quiz/
├── index.html
└── README.md
```
