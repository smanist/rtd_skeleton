# Grouped Navigation Demo

This grouped chapter demonstrates a numbered chapter folder with child pages.
The left sidebar derives the chapter number from the folder name, while the
unnumbered reference pages below it remain unnumbered.

**Sections**

- [Folded detail page](folded-detail.md)
- [Child page TOC](child-page-toc.md)

```{toctree}
:hidden:
:maxdepth: 1

folded-detail
child-page-toc
```

**Summary**

Grouped chapter parents can keep the introduction and final summary together
while moving longer middle sections into child pages. Child pages preserve their
original section heading levels so the split operation is reversible and easy to
review.
