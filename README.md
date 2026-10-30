# Summary

The UD_Punjabi-DYZ is a manually annotated treebank in Punjabi (also called Eastern Punjabi, Gurmukhi script) language. The Indo-Aryan language is prominently spoken in Punjab region of India and Pakistan with strong diasporas in Western countries like Canada, UK and USA etc. It is written from Left-to-Right with Subject-Object-Verb (SOV) word ordering.


# Introduction

The treebank consists of total 243 sentences (4,618 tokens, 4,270 words excluding punctuation) taken from Punjabi translations of three literary works. The data has been annotated according to Universal Dependencies guidelines.

| Sentences | Punjabi title | Original title | Author | Original (year) | Punjabi translation (year) |
|---|---|---|---|---|---|
| 1–80 (80) | ਸੌ ਸਾਲ ਦਾ ਇਕਲਾਪਾ (Sou Saal Da Iklaapa) | Cien años de soledad (One Hundred Years of Solitude) | Gabriel García Márquez | Spanish, 1967 | 2006 |
| 81–160 (80) | ਦ ਡਾਇਰੀ ਆਫ਼ ਏ ਯੰਗ ਗਰਲ (The Diary of a Young Girl) | Het Achterhuis | Anne Frank | Dutch, 1947 | 2023 |
| 161–243 (83) | ਜ਼ੋਰਬਾ ਦਾ ਗਰੀਕ (Zorba the Greek) | Vios kai Politeia tou Alexi Zormpa | Nikos Kazantzakis | Greek, 1946 | 2017 |

The treebank follows a 4-tier structure: every sentence carries, besides the original Gurmukhi text, a romanized transliteration (`# translit`), an interlinear morpheme gloss (`# gloss`) and an English translation (`# translation`). Token-level transliterations and glosses are given in the MISC column (`Translit=`, `Gloss=`).

All tokens are annotated with lemma, universal part-of-speech tag, universal features and basic dependency relations. The annotation conventions, including the treatment of auxiliaries versus aspectual light (vector) verbs, the lemmatization of the verb "to be" (ਹੈ, ਸੀ, ਹੋਣਾ) and the use of Case=Acc for the oblique form of nominals, are described in the Punjabi language documentation and follow the closely related Hindi and Urdu UD treebanks.


# Acknowledgments

The treebank was annotated by Ali Haider Khan under the supervision of Dr. Luigi Talamo, Dr. Annemarie Verkerk and Dr. Zarina Begum.

## References

* (citation)

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: fiction nonfiction
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Khan, Ali Haider; Talamo, Luigi; Verkerk, Annemarie; Begum, Zarina
Contributing: here
Contact: annemarie.verkerk@uni-saarland.de
===============================================================================
</pre>
