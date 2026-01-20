# Academic Writing Guidelines for Computer Science

## Document Structure

### Standard Organization
1. Cover Page and Title Page
2. Acknowledgments (optional)
3. Table of Contents
4. Introduction
5. Chapters/Sections (body)
6. Conclusion
7. Bibliography
8. Appendices (optional)

### Section Depth
- Long documents: chapters > sections > subsections
- Short documents: sections > subsections
- Avoid deep numbering (e.g., 1.3.2.1.5)

## Introduction Structure
1. Context and background
2. Problem definition
3. Existing solutions and limitations
4. Work objectives and key ideas
5. Document roadmap (brief chapter descriptions)

**Key principle:** Convince the reader the document is worth reading. Explain WHY the topic matters.

## Body Content
- Subject/problem presentation
- State of the art (known results)
- Presentation of approaches
- Reasons for choices
- Description of work and achievements
- Comparison with previous results

**Critical:** Use LOGICAL structure, not chronological. Present results, not the journey.

## Conclusion Structure
1. Work summary and contributions
2. Main results reminder
3. Potential applications
4. Limitations
5. Future work directions

## Style Guidelines

### Core Principles
1. **Precision**: Define concepts when first introduced (italicize). Use consistent terminology.
2. **Concision**: Short sentences. One idea per sentence. Avoid useless words.
3. **Neutrality**: Detached, non-emotional. Avoid first person "I" (use "we" or passive).
4. **Active voice**: More direct than passive. Use present tense for dynamic style.
5. **Correct spelling**: Always spell-check.
6. **Typography**: Follow language-specific rules. Use non-breaking spaces appropriately.

### Common Mistakes to Avoid
- Using synonyms for the same concept (confuses readers)
- Long, convoluted sentences
- Emotional or personal language
- Chronological organization instead of logical
- Vague qualitative claims without evidence

### Good vs Bad Examples

**Precision:**
- Bad: "The number of nodes is n. A graph is vertices V and edges between nodes."
- Good: "An undirected graph G is an ordered pair (V,E), where V is a finite set of vertices..."

**Concision:**
- Bad: "Saving the data can be done using plain text files, representing the data in a readable format for a human being, with a sequence of characters..."
- Good: "There are two ways to store data: plain text or binary format."

**Neutrality:**
- Bad: "I was starting to have second thoughts about programming..."
- Good: (Avoid personal feelings entirely)

**Objectivity:**
- Bad: "We chose language X because we used it in class before."
- Good: "Language X supports multiple inheritance, which is essential for our design because..."

## Bibliography Guidelines

### Reference Sources
- Prefer published references (books, journals, conference proceedings)
- Avoid Wikipedia, Stack Overflow, Quora for citations
- For web resources, always include last visit date

### Citation Format
- Journal article: authors, title, journal, volume, issue, year, pages
- Book: authors, title, edition, publisher, city, year
- Electronic: authors, title, URL, year, last visit date

### Citation Style
- Reference each publication only once
- Mention author names in text: "Lindvall and Sandhal [6] suggest..." not "In [6], the authors suggest..."
- Use brackets [x] for numerical labels

## Avoiding Plagiarism

1. **Paraphrasing**: Cite source when using ideas in your own words
2. **Direct quotes**: Use quotation marks or indented paragraphs
3. **Figures/data**: Always cite source (usually in caption)
4. **Translations**: Cite original, optionally include original text

## Figures and Tables

- Always number and caption (caption above tables, below figures)
- Reference every figure/table in the text
- Figures illustrate but don't replace arguments
- Tables summarize facts and comparisons

## Algorithm Presentation

1. Explain purpose (goals, input, output)
2. Describe main ideas in plain language
3. Detail key ideas
4. Display pseudocode (main parts only if long)
5. Apply to small example
6. Prove correctness
7. State time/space complexity with proof
8. Implementation details in appendix if needed

## Computer Benchmarks

Always specify:
- Hardware configuration
- Software versions and origins
- How measurements were taken (e.g., CPU time measurement method)

## LaTeX Tips

### When to Use LaTeX
- Mathematical formulas: `$\sum_{i=1}^n i = \frac{n(n+1)}{2}$`
- Complex equations
- Theorems, definitions, proofs
- Algorithm pseudocode
- Cross-references
- Bibliography management (BibTeX)

### Useful Packages
- `algorithm`, `algorithmic`: pseudocode
- `amsmath`, `amsthm`: math environments
- `cite`: group successive references
- `babel`: language-specific typography

## Latin Abbreviations

| Abbrev. | Latin | Meaning | Alternative |
|---------|-------|---------|-------------|
| e.g. | exempli gratia | for example | |
| i.e. | id est | in other words | that is |
| cf. | confer | compare | see |
| etc. | et cetera | and other things | |
| et al. | et alia | and others | |

- Don't confuse e.g. (examples) with i.e. (reformulation)
- In US English, follow e.g. and i.e. with a comma
- Don't end e.g. lists with etc.

## Oral Presentation Tips

### Content
- Get to the point, deliver key ideas only
- Don't cover every detail from the written report
- Focus on most important chapters
- Build a new plan for the presentation (not necessarily following document structure)

### Slides
- Use keywords, diagrams, short sentences (not full paragraphs)
- One or few ideas per slide
- 1-2 minutes per slide
- Don't read from slides
- Maintain eye contact with audience

### Timing
- Rehearse and time your presentation
- Never exceed the time limit
- If too long, reconsider content (don't just speak faster)
