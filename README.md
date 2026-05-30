# Shobhika Dravida

Shobhika Dravida is a modified version of the Shobhika font, adapted to support Devanagari transcription of Tamil with improved fidelity, legibility, and aesthetics.

This font is made to support specific letters for Tamil transcription in Devanagari. More information about the design and implementation can be found here:

- [https://kubhasena.github.io/rshtikona/devanagari-dravida/](https://kubhasena.github.io/rshtikona/devanagari-dravida/)
- [https://kubhasena.github.io/rshtikona/devanagari-dravida/shobhikadravida](https://kubhasena.github.io/rshtikona/devanagari-dravida/shobhikadravida.html)

## Purpose

Tamil texts are often rendered in Devanagari for readers who are more familiar with Devanagari orthography. Standard Devanagari has limitations for fully legible and faithful Tamil transcription. Shobhika Dravida helps to address this by redesigning some existing letters and introducing new characters.

## Repository Scope

This repository tracks:

- Font source files (`.sfd`) for version-control-friendly change history
- Ready-to-use font binaries (`.otf`) for direct use in other projects

## Implemented Font Changes

The current Shobhika Dravida implementation includes the following modifications:

- Replaced old nuqta-based forms for ऩ, ऱ, ऴ with redesigned forms
- Added new letters: श़, त़, द़
- Added ஃ at U+0B83 (based on existing visarga glyph)
- Added half-forms for ऩ, ऱ, ऴ, त़, and द़
- Associated ॖ to Anchor-2 for improved consonant rendering
- Assigned existing ैॅ glyph to U+0948 + U+0945
- Added ऐॅ at U+0910 + U+0945
- Added conjuncts: ऩ्ऱ, ऱ्ऱ, त़्त़, ऩ्द़, ऩ्द़्ऱ, त़्ऱ, त़्त़्ऱ
- Explicitly defined many conjuncts of ऩ, ऱ, ऴ with other consonants
- Regularized i-matra combining behavior across consonants and conjuncts

## Versioning Workflow

1. Edit source in `.sfd`.
2. Generate updated `.otf`.
3. Commit both source and binary together.

## Credits and Attribution

Shobhika Dravida is based on Shobhika by Prof. K. Ramasubramanian and Prof. Girish Dalvi, and extends it for Tamil transcription in Devanagari as documented in the linked project pages.

Original Shobhika repository:

- [https://github.com/Sandhi-IITBombay/Shobhika](https://github.com/Sandhi-IITBombay/Shobhika)

