# Chemistry 101 Nomenclature Quiz

An interactive browser-based quiz for practicing introductory chemical nomenclature in a college **Chemistry 101** course.

The quiz is designed around the nomenclature material presented in **OpenStax Chemistry 2e, Chapter 2**, especially Sections **2.6: Ionic and Molecular Compounds** and **2.7: Chemical Nomenclature**.

## Features

- **100-question question bank**
- Presents **10 randomly selected questions per quiz session**
- Gives immediate feedback after each answer
- Shows the running score during the quiz
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

- Ammonium — `NH4+`
- Hydroxide — `OH-`
- Nitrate — `NO3-`
- Nitrite — `NO2-`
- Sulfate — `SO4^2-`
- Carbonate — `CO3^2-`
- Phosphate — `PO4^3-`
- Iodate — `IO3-`
- Hypochlorite — `ClO-`
- Chlorite — `ClO2-`
- Chlorate — `ClO3-`
- Perchlorate — `ClO4-`

## Accessibility

The quiz uses strongly saturated feedback colors to make correct and incorrect responses easier to distinguish.

- **Correct answer:** 75% green (`#00BF00`)
- **Incorrect answer:** 75% red (`#BF0000`)
- Correct and incorrect choices also use distinct borders and light background shading.

The stronger colors were selected specifically to improve visual differentiation for users who have difficulty distinguishing conventional low-saturation red and green interface colors.

## How the Quiz Works

1. Open the HTML file in a modern web browser.
2. The program randomly selects **10 questions from the 100-question bank**.
3. Select an answer for each question.
4. The quiz immediately shows whether the answer is correct or incorrect and provides a short explanation.
5. After Question 10, the quiz displays:
   - final score,
   - percentage,
   - and a review of missed questions.
6. Select **New 10-Question Quiz** to start another randomly selected set.

Because each session draws from the full 100-question bank, repeated sessions provide varied practice rather than simply repeating the same ten questions.

## Running Locally

No installation is required.

Download the quiz HTML file and double-click it, or open it from a browser using:

```text
File → Open
```

The application is self-contained and does not require an internet connection after the file has been downloaded.

## Hosting on GitHub Pages

The quiz can be hosted as a static webpage.

A simple repository can contain:

```text
/
├── index.html
└── README.md
```

Rename the quiz HTML file to `index.html` if you want it to load automatically from the root of a GitHub Pages site.

Then enable GitHub Pages for the repository using the repository's Pages settings.

## Source Material

The academic content is based primarily on:

**OpenStax, Chemistry 2e**

Authors:

- Paul Flowers
- Klaus Theopold
- Richard Langley
- William R. Robinson, PhD

Publisher: **OpenStax**

Relevant sections:

### Section 2.6 — Ionic and Molecular Compounds

This section provides the foundation for:

- distinguishing ionic and molecular compounds,
- understanding cations and anions,
- predicting ionic formulas from ion charges,
- recognizing the relationship between metals, nonmetals, and compound type,
- and working with common polyatomic ions.

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

https://openstax.org/books/chemistry-2e/pages/2-7-chemical-nomenclature

OpenStax describes chemical nomenclature as a systematic method for naming compounds and explains separate naming procedures for ionic and molecular compounds.

## Course-Specific Additions

The question bank also contains material requested for the associated Chemistry 101 course, including additional practice with:

- zinc,
- silver,
- iodate,
- alkali metals,
- alkaline-earth metals,
- halogens,
- and noble gases.

These additions supplement the primary OpenStax nomenclature material and reflect topics being emphasized in the course.

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

No build process or package manager is necessary.

## License and Source Attribution

OpenStax textbook material should be used and attributed according to the license terms published by OpenStax for *Chemistry 2e*.

This quiz is an independent study aid and is not an official OpenStax product.

## Repository Files

Recommended repository structure:

```text
chemistry-nomenclature-quiz/
├── index.html
└── README.md
```

The entire quiz application can remain in the single `index.html` file, making it especially convenient for GitHub Pages hosting.
