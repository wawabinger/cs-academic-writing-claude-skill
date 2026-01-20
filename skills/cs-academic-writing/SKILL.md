---
name: cs-academic-writing
description: Academic writing assistance for computer science documents. Use when users request help writing or polishing academic content in any language, such as "please write...", "please polish...", "help me draft...", "improve my...", or equivalent phrases in other languages. Covers research papers, theses, dissertations, grant proposals, literature reviews, and reviewer responses. Supports drafting sections (introduction, related work, methodology, results, conclusion), editing/polishing existing text, LaTeX formatting, citation guidance, figure/table creation, and responding to reviewer comments.
---

# CS Academic Writing

Assist with writing and polishing computer science academic documents following established scientific writing conventions.

## Output Format

- **Default**: Plain text
- **Use LaTeX** when content includes:
  - Mathematical formulas or equations
  - Special characters or symbols
  - Algorithm pseudocode
  - Complex formatting (theorems, definitions, proofs)

## Writing Workflow

### When Writing New Content

1. **Clarify scope**: Identify document type (paper, thesis, proposal, review) and target section
2. **Understand context**: Ask about research topic, key contributions, target venue if relevant
3. **Draft content** following structure guidelines below
4. **Review for style**: Apply precision, concision, neutrality principles

### When Polishing Existing Content

1. **Read carefully**: Understand the argument and structure
2. **Check structure**: Logical flow, paragraph organization
3. **Apply style fixes**: Precision, concision, active voice, consistency
4. **Verify technical content**: Citations, terminology consistency, claims supported by evidence

## Section-Specific Guidance

### Introduction
Write in this order:
1. Context and background (why this matters)
2. Problem definition (what gap exists)
3. Existing solutions and their limitations
4. This work's objectives and key ideas
5. Brief roadmap of remaining sections

**Principle**: Convince readers the document is worth reading.

### Related Work / State of the Art
- Group by approach or theme, not chronologically
- Compare and contrast methods
- Identify gaps your work addresses
- Always cite with author names: "Smith et al. [5] proposed..." not "In [5], authors proposed..."

### Methodology / Approach
- Present main ideas in plain language first
- Then provide technical details
- For algorithms: purpose > key ideas > pseudocode > example > complexity
- Justify design choices with objective criteria

### Results / Evaluation
- Specify experimental setup (hardware, software, datasets)
- Present quantitative results with proper units
- Compare with baselines using objective metrics
- Include statistical significance where appropriate

### Conclusion
1. Summarize contributions
2. Remind main results
3. Discuss applications
4. Acknowledge limitations
5. Suggest future work

## Style Rules

Apply these consistently:

| Principle | Guideline |
|-----------|-----------|
| Precision | Define terms on first use (italicize). Use same term throughout. |
| Concision | One idea per sentence. Cut unnecessary words. |
| Neutrality | Use "we" or passive voice. Avoid emotional language. |
| Active voice | Prefer "X shows Y" over "Y is shown by X" |
| Consistency | Same notation, terminology, formatting throughout |
| Objectivity | Support claims with evidence or citations |

### Common Fixes When Polishing

- "I think/believe..." -> Remove or cite evidence
- Synonyms for same concept -> Use single consistent term
- Long sentences -> Split into shorter ones
- Chronological organization -> Reorganize logically
- Vague claims ("very fast", "many") -> Quantify precisely

## LaTeX Patterns

### Inline Math
```latex
The complexity is $O(n \log n)$.
```

### Display Equations
```latex
\begin{equation}
  \sum_{i=1}^{n} x_i = \frac{n(n+1)}{2}
\end{equation}
```

### Algorithm
```latex
\begin{algorithm}
\caption{Algorithm Name}
\begin{algorithmic}[1]
\REQUIRE input description
\ENSURE output description
\STATE $x \leftarrow 0$
\FOR{$i \leftarrow 1$ to $n$}
  \STATE process
\ENDFOR
\RETURN $x$
\end{algorithmic}
\end{algorithm}
```

### Theorem/Definition
```latex
\begin{theorem}[Name]
Statement here.
\end{theorem}

\begin{proof}
Proof here.
\end{proof}
```

## Citation Guidelines

- Cite published sources (journals, conferences) over web pages
- For web resources, include access date
- Reference each work once; use "Smith et al. [5, Chap. 3]" for specific sections
- Build bibliography as you write, not at the end

## Responding to Reviewer Comments

1. Quote the reviewer's point
2. Thank them for the feedback
3. Explain how you addressed it (or why not)
4. Reference specific changes (page, section, line numbers)

**Tone**: Professional, grateful, non-defensive.

## References

For detailed guidelines on structure, style, bibliography, and presentation, see [references/writing-guidelines.md](references/writing-guidelines.md).
