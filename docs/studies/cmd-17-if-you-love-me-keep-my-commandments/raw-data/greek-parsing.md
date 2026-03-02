# Raw Greek Parsing Data

## John 14:15

Greek Text (N1904): Ἐὰν ἀγαπᾶτέ με, τὰς ἐντολὰς τὰς ἐμὰς τηρήσετε.

| Word | Lemma | Strong's | Parsing |
|------|-------|----------|---------|
| Ἐὰν | ἐάν | [G1437](https://www.blueletterbible.org/lexicon/g1437/kjv/tr/0-1/){:target="_blank"} | COND (conditional particle) |
| ἀγαπᾶτέ | ἀγαπάω | [G25](https://www.blueletterbible.org/lexicon/g25/kjv/tr/0-1/){:target="_blank"} | V-PAS-2P: Present Active Subjunctive, 2nd Person Plural |
| με | ἐγώ | [G1473](https://www.blueletterbible.org/lexicon/g1473/kjv/tr/0-1/){:target="_blank"} | P-1AS: Pronoun, 1st person, Accusative Singular |
| τὰς | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-APF: Article, Accusative Plural Feminine |
| ἐντολὰς | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-APF: Noun, Accusative Plural Feminine |
| τὰς | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-APF: Article, Accusative Plural Feminine |
| ἐμὰς | ἐμός | [G1699](https://www.blueletterbible.org/lexicon/g1699/kjv/tr/0-1/){:target="_blank"} | S-1SAPF: Possessive adjective, 1st singular, Accusative Plural Feminine |
| τηρήσετε | [τηρέω](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | [G5083](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | V-FAI-2P: **Future Active Indicative**, 2nd Person Plural |

### Critical Finding: N1904 reads τηρήσετε (Future Active Indicative)
- NOT aorist imperative (τηρήσατε) as noted in PROMPT.md as a variant
- The N1904 text reads as a PROMISE/DECLARATION: "If you love me, you WILL keep my commandments"
- The Textus Receptus variant has τηρήσατε (aorist imperative): "If you love me, KEEP my commandments"
- Textual variant confirmed by greek_text_compare.py

### Textual Variant (N1904 vs TR)
- N1904: τηρήσετε (future indicative) -- "you will keep"
- TR: τηρήσατε (aorist imperative) -- "keep!"
- Variant detected between the two text traditions

## 1 John 5:3

Greek Text: αὕτη γάρ ἐστιν ἡ ἀγάπη τοῦ Θεοῦ, ἵνα τὰς ἐντολὰς αὐτοῦ τηρῶμεν· καὶ αἱ ἐντολαὶ αὐτοῦ βαρεῖαι οὐκ εἰσίν

| Word | Lemma | Strong's | Parsing |
|------|-------|----------|---------|
| αὕτη | οὗτος | [G3778](https://www.blueletterbible.org/lexicon/g3778/kjv/tr/0-1/){:target="_blank"} | D-NSF: Demonstrative, Nominative Singular Feminine |
| γάρ | γάρ | [G1063](https://www.blueletterbible.org/lexicon/g1063/kjv/tr/0-1/){:target="_blank"} | CONJ: Conjunction (for, because) |
| ἐστιν | εἰμί | [G1510](https://www.blueletterbible.org/lexicon/g1510/kjv/tr/0-1/){:target="_blank"} | V-PAI-3S: Present Active Indicative, 3rd Singular |
| ἡ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NSF: Article, Nominative Singular Feminine |
| ἀγάπη | ἀγάπη | [G26](https://www.blueletterbible.org/lexicon/g26/kjv/tr/0-1/){:target="_blank"} | N-NSF: Noun, Nominative Singular Feminine |
| τοῦ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-GSM: Article, Genitive Singular Masculine |
| Θεοῦ | θεός | [G2316](https://www.blueletterbible.org/lexicon/g2316/kjv/tr/0-1/){:target="_blank"} | N-GSM: Noun, Genitive Singular Masculine |
| ἵνα | ἵνα | [G2443](https://www.blueletterbible.org/lexicon/g2443/kjv/tr/0-1/){:target="_blank"} | CONJ: Conjunction (that, in order that) |
| τὰς | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-APF: Article, Accusative Plural Feminine |
| ἐντολὰς | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-APF: Noun, Accusative Plural Feminine |
| αὐτοῦ | αὐτός | [G846](https://www.blueletterbible.org/lexicon/g846/kjv/tr/0-1/){:target="_blank"} | P-GSM: Pronoun, Genitive Singular Masculine |
| τηρῶμεν | [τηρέω](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | [G5083](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | V-PAS-1P: Present Active Subjunctive, 1st Plural |
| καὶ | καί | [G2532](https://www.blueletterbible.org/lexicon/g2532/kjv/tr/0-1/){:target="_blank"} | CONJ |
| αἱ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NPF: Article, Nominative Plural Feminine |
| ἐντολαὶ | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-NPF: Noun, Nominative Plural Feminine |
| αὐτοῦ | αὐτός | [G846](https://www.blueletterbible.org/lexicon/g846/kjv/tr/0-1/){:target="_blank"} | P-GSM: Pronoun, Genitive Singular Masculine |
| βαρεῖαι | βαρύς | [G926](https://www.blueletterbible.org/lexicon/g926/kjv/tr/0-1/){:target="_blank"} | A-NPF: Adjective, Nominative Plural Feminine (heavy, burdensome) |
| οὐκ | οὐ | [G3756](https://www.blueletterbible.org/lexicon/g3756/kjv/tr/0-1/){:target="_blank"} | PRT-N: Negative particle |
| εἰσίν | εἰμί | [G1510](https://www.blueletterbible.org/lexicon/g1510/kjv/tr/0-1/){:target="_blank"} | V-PAI-3P: Present Active Indicative, 3rd Plural |

### Key grammatical features:
- αὕτη ... ἐστιν ἡ ἀγάπη τοῦ Θεοῦ = "This IS the love of God" -- definitional equation using estin
- ἵνα τὰς ἐντολὰς αὐτοῦ τηρῶμεν = hina + subjunctive -- likely epexegetical (explanatory): "namely that we keep his commandments"
- τηρῶμεν = Present Active Subjunctive -- ongoing keeping
- βαρεῖαι οὐκ εἰσίν = "are not burdensome/heavy"

## 2 John 1:6

Greek Text: καὶ αὕτη ἐστὶν ἡ ἀγάπη, ἵνα περιπατῶμεν κατὰ τὰς ἐντολὰς αὐτοῦ· αὕτη ἡ ἐντολή ἐστιν, καθὼς ἠκούσατε ἀπ' ἀρχῆς, ἵνα ἐν αὐτῇ περιπατῆτε.

| Word | Lemma | Strong's | Parsing |
|------|-------|----------|---------|
| καὶ | καί | [G2532](https://www.blueletterbible.org/lexicon/g2532/kjv/tr/0-1/){:target="_blank"} | CONJ |
| αὕτη | οὗτος | [G3778](https://www.blueletterbible.org/lexicon/g3778/kjv/tr/0-1/){:target="_blank"} | D-NSF: Demonstrative, Nominative Singular Feminine |
| ἐστὶν | εἰμί | [G1510](https://www.blueletterbible.org/lexicon/g1510/kjv/tr/0-1/){:target="_blank"} | V-PAI-3S: Present Active Indicative, 3rd Singular |
| ἡ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NSF |
| ἀγάπη | ἀγάπη | [G26](https://www.blueletterbible.org/lexicon/g26/kjv/tr/0-1/){:target="_blank"} | N-NSF |
| ἵνα | ἵνα | [G2443](https://www.blueletterbible.org/lexicon/g2443/kjv/tr/0-1/){:target="_blank"} | CONJ |
| περιπατῶμεν | περιπατέω | [G4043](https://www.blueletterbible.org/lexicon/g4043/kjv/tr/0-1/){:target="_blank"} | V-PAS-1P: Present Active Subjunctive, 1st Plural |
| κατὰ | κατά | [G2596](https://www.blueletterbible.org/lexicon/g2596/kjv/tr/0-1/){:target="_blank"} | PREP |
| τὰς | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-APF |
| ἐντολὰς | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-APF |
| αὐτοῦ | αὐτός | [G846](https://www.blueletterbible.org/lexicon/g846/kjv/tr/0-1/){:target="_blank"} | P-GSM |
| αὕτη | οὗτος | [G3778](https://www.blueletterbible.org/lexicon/g3778/kjv/tr/0-1/){:target="_blank"} | D-NSF |
| ἡ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NSF |
| ἐντολή | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-NSF |
| ἐστιν | εἰμί | [G1510](https://www.blueletterbible.org/lexicon/g1510/kjv/tr/0-1/){:target="_blank"} | V-PAI-3S |
| καθὼς | καθώς | [G2531](https://www.blueletterbible.org/lexicon/g2531/kjv/tr/0-1/){:target="_blank"} | ADV (just as) |
| ἠκούσατε | ἀκούω | [G191](https://www.blueletterbible.org/lexicon/g191/kjv/tr/0-1/){:target="_blank"} | V-AAI-2P: Aorist Active Indicative, 2nd Plural |
| ἀπ' | ἀπό | [G575](https://www.blueletterbible.org/lexicon/g575/kjv/tr/0-1/){:target="_blank"} | PREP |
| ἀρχῆς | ἀρχή | [G746](https://www.blueletterbible.org/lexicon/g746/kjv/tr/0-1/){:target="_blank"} | N-GSF: Noun, Genitive Singular Feminine (beginning) |
| ἵνα | ἵνα | [G2443](https://www.blueletterbible.org/lexicon/g2443/kjv/tr/0-1/){:target="_blank"} | CONJ |
| ἐν | ἐν | [G1722](https://www.blueletterbible.org/lexicon/g1722/kjv/tr/0-1/){:target="_blank"} | PREP |
| αὐτῇ | αὐτός | [G846](https://www.blueletterbible.org/lexicon/g846/kjv/tr/0-1/){:target="_blank"} | P-DSF: Pronoun, Dative Singular Feminine |
| περιπατῆτε | περιπατέω | [G4043](https://www.blueletterbible.org/lexicon/g4043/kjv/tr/0-1/){:target="_blank"} | V-PAS-2P: Present Active Subjunctive, 2nd Plural |

### Key grammatical features:
- Two definitional equations: (1) "This IS love, that we walk after his commandments" (2) "This IS the commandment... that ye should walk in it"
- Both use αὕτη ἐστιν (this is) + hina clause
- περιπατέω (to walk) used instead of [τηρέω](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} (to keep) -- metaphorical "walking according to" commandments
- ἀπ' ἀρχῆς (from the beginning) -- connects to the old commandment theme

## Revelation 14:12

Greek Text: Ὧδε ἡ ὑπομονὴ τῶν ἁγίων ἐστίν, οἱ τηροῦντες τὰς ἐντολὰς τοῦ Θεοῦ καὶ τὴν πίστιν Ἰησοῦ.

| Word | Lemma | Strong's | Parsing |
|------|-------|----------|---------|
| Ὧδε | ὧδε | [G5602](https://www.blueletterbible.org/lexicon/g5602/kjv/tr/0-1/){:target="_blank"} | ADV (here) |
| ἡ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NSF |
| ὑπομονὴ | ὑπομονή | [G5281](https://www.blueletterbible.org/lexicon/g5281/kjv/tr/0-1/){:target="_blank"} | N-NSF: Noun, Nominative Singular Feminine (endurance, patience) |
| τῶν | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-GPM |
| ἁγίων | ἅγιος | [G40](https://www.blueletterbible.org/lexicon/g40/kjv/tr/0-1/){:target="_blank"} | A-GPM: Adjective, Genitive Plural Masculine (holy ones, saints) |
| ἐστίν | εἰμί | [G1510](https://www.blueletterbible.org/lexicon/g1510/kjv/tr/0-1/){:target="_blank"} | V-PAI-3S |
| οἱ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-NPM: Article, Nominative Plural Masculine |
| τηροῦντες | [τηρέω](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | [G5083](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} | V-PAP-NPM: Present Active Participle, Nominative Plural Masculine |
| τὰς | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-APF |
| ἐντολὰς | ἐντολή | [G1785](https://www.blueletterbible.org/lexicon/g1785/kjv/tr/0-1/){:target="_blank"} | N-APF |
| τοῦ | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-GSM |
| Θεοῦ | θεός | [G2316](https://www.blueletterbible.org/lexicon/g2316/kjv/tr/0-1/){:target="_blank"} | N-GSM |
| καὶ | καί | [G2532](https://www.blueletterbible.org/lexicon/g2532/kjv/tr/0-1/){:target="_blank"} | CONJ |
| τὴν | ὁ | [G3588](https://www.blueletterbible.org/lexicon/g3588/kjv/tr/0-1/){:target="_blank"} | T-ASF |
| πίστιν | πίστις | [G4102](https://www.blueletterbible.org/lexicon/g4102/kjv/tr/0-1/){:target="_blank"} | N-ASF: Noun, Accusative Singular Feminine (faith) |
| Ἰησοῦ | Ἰησοῦς | [G2424](https://www.blueletterbible.org/lexicon/g2424/kjv/tr/0-1/){:target="_blank"} | N-GSM: Noun, Genitive Singular Masculine (of Jesus) |

### Key grammatical features:
- οἱ τηροῦντες = present active participle with article = substantival: "those who keep" -- ongoing, characteristic action
- τὰς ἐντολὰς τοῦ Θεοῦ = "the commandments of God" -- same word entole (G1785)
- τὴν πίστιν Ἰησοῦ = "the faith of Jesus" -- genitive Iesou could be objective (faith IN Jesus) or subjective (faith LIKE Jesus's own faith)
- Two objects connected by καί: commandments of God AND faith of Jesus -- paired as dual identifying marks
- [τηρέω](https://www.blueletterbible.org/lexicon/g5083/kjv/tr/0-1/){:target="_blank"} (G5083) -- same verb as John 14:15 and 1 John 5:3
