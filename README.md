# AI Wrote It, You Pushed It, Who Checks It?

What astrophysics learned from decades of trusting code.

A 15-minute talk by Jessica Syafaq Muthmaina at DevFest Milano 2026 (GDG Milano), Saturday 10 October 2026.

## The talk in one sentence

AI-made work that nobody else can rerun is not knowledge yet, and whoever publishes it owes the checking, instead of overloading maintainers and peer reviewers.

## What is in this repository

| Path | What it is |
|---|---|
| `slides/gdg_lightning.pdf` | The deck, 21 slides, 16:9 |
| `slides/gdg_lightning.tex` | LaTeX Beamer source of the deck |
| `slides/figs/` | Figures and screenshots used on the slides |
| `FIGURE_CREDITS.md` | Where every figure comes from |
| `LICENSE` | CC BY 4.0 for my text and source, figures excluded |

## Slide order

1. Title
2. About me
3. Where I start
4. One upload, 722 papers
5. Twenty-four years, one night
6. My laboratory is code
7. The machines were already in the room
8. Astronomy already has a flood of data
9. Made with AI, checked by a person
10. The rule in my course
11. We can read the papers, but not repeat the work
12. Checked by a computer, but which proof?
13. Who checks the checker?
14. How the internet draws them
15. Many paid tries, not one clever idea
16. What the mathematicians asked for
17. A quote
18. Conclusion
19. How I will not end this talk
20. A question for you
21. References

## Build the slides

The deck compiles with [Tectonic](https://tectonic-typesetting.github.io/), which downloads the LaTeX packages it needs.

```
cd slides
tectonic gdg_lightning.tex
```

It should also build with `xelatex` or `pdflatex` from a full TeX Live install.

## Sources

All references are listed on the last slide. The main ones are the `openai/math` repository, the AGMAI statements, Bastounis, Circelli and Hansen (arXiv 2610.08144), the METR report of 26 August 2026 on the Hugging Face incident, and the Anthropic article "The missing map of the sky".

## Reuse

My slide text and the LaTeX source are under CC BY 4.0, so you may share and adapt them if you give credit. See `LICENSE`.

The figures are not covered by that licence. They belong to their authors, see `FIGURE_CREDITS.md` before you reuse any of them.

## Contact

@your.astrophysicist on Instagram, or https://www.yourastro.space/
