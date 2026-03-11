README — TEI/EpiDoc encoding of IGUR II 999
1. What has been done

This project consists of a TEI/EpiDoc encoding of the Greek inscription IGUR II 999, based on the edition by L. Moretti (Inscriptiones Graecae Urbis Romae, II 999).

Two complementary encoding layers are combined:

EpiDoc conventions are used to encode the epigraphic text as inscribed, including:

line breaks,

scribal errors,

omissions,

dittographies,

abbreviations and their expansions,

editorial corrections supported by the critical apparatus.

TEI text modeling is used to represent the internal textual organization of the inscription, identifying its epistolary structure, namely:

praescriptum (sender, addressee, greeting),

argumentum (main content of the letter),

clausula (closing formula).

The encoding does not propose a new edition or transcription.
The epigraphic text follows Moretti’s edition; the contribution lies in the formal modeling of the text and its structure.

2. Why this encoding is particularly useful for IGUR II 999

IGUR II 999 is not a standard funerary inscription.
It preserves a private letter, originally conceived as a personal communication, which was later inscribed on stone in order to function as a public and legally binding document.

This hybrid nature makes the inscription especially suitable for TEI modeling because:

the text combines epistolary conventions (names, greeting, farewell) with

legal and documentary functions (property transfer, guarantees, absence of dispute),

and is materialized as a public monument.

The TEI encoding makes this hybridity explicit by:

separating the material layout of the inscription (EpiDoc layer),

from the functional organization of the text as a letter (TEI epistolary model).

In other words, the encoding shows how a private letter is transformed into a public document, not only by inscription on stone, but also by its internal structure.

3. Why a TEI/EpiDoc edition is useful in general

A TEI/EpiDoc edition is not meant to replace a traditional philological edition, but to complement it by making explicit what is usually implicit.

In general, such an edition allows one to:

distinguish clearly between:

the text as materially inscribed,

the editorial interventions,

and the interpretive structure of the text;

encode philological decisions (corrections, expansions, errors) in a formal and transparent way;

support multiple views of the same text (epigraphic, continuous, structural) without rewriting it;

make scholarly interpretations verifiable and reusable, rather than embedded only in prose commentary.

For texts with complex or hybrid functions — such as letters, documents, or legal texts inscribed on stone — TEI is especially useful because it allows the scholar to model what the text does, not only what it says.

4. Summary

What: TEI/EpiDoc encoding of IGUR II 999, based on Moretti’s edition.

How:

EpiDoc for the epigraphic transcription,

TEI for modeling the epistolary structure.

Why this text: IGUR II 999 is a private letter turned into a public legal inscription.

Why TEI: to formalize textual structure, philological decisions, and interpretation in a reusable and transparent way.