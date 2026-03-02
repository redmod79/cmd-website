# Raw Hebrew Parsing Data

## Exodus 20:3 — Verse Parse (hebrew_parser.py --verse "Exo 20:3")

```
======================================================================
  Exodus 20:3
======================================================================

  לֹֽ֣א יִהְיֶֽה־לְךָ֛֩ אֱלֹהִ֥֨ים אֲחֵרִ֖֜ים עַל־פָּנָֽ֗יַ׃

  Hebrew          Lemma        Parsing                   Gloss
  --------------- ------------ ------------------------- --------------------
  לֹֽ֣א           לא           Neg.+NAN                  not
  יִהְיֶֽה        היה          Verb.Qal.Impf.3ms         be
  לְךָ֛֩          ל            Prep.+2ms                 to
  אֱלֹהִ֥֨ים      אלהים        Noun.mp.Abs               god(s)
  אֲחֵרִ֖֜ים      אחר          Adj.mp.Abs                other
  עַל             על           Prep                      upon
  פָּנָֽ֗יַ       פנה          Noun.mp.Abs.+1us          face
```

## Exodus 20:3 — Clause Structure (hebrew_parser.py --clause "Exo 20:3")

```
======================================================================
  CLAUSE STRUCTURE: Exodus 20:3
======================================================================

  Clause 1:
    Type: xYqX
    Domain: Q
    Text: לֹֽ֣א יִהְיֶֽה לְךָ֛֩ אֱלֹהִ֥֨ים אֲחֵרִ֖֜ים עַל פָּנָֽ֗יַ
      [Nega] לֹֽ֣א
      [Pred] יִהְיֶֽה
      [Cmpl] לְךָ֛֩
      [Subj] אֱלֹהִ֥֨ים אֲחֵרִ֖֜ים
      [Adju] עַל פָּנָֽ֗יַ
```

### Clause Type Analysis
- **xYqX**: x = non-verbal element first (negation particle), Y = verb, q = qualifier, X = additional element
- **Domain Q**: Quotative domain (direct speech — God speaking)
- **[Nega]**: Negation particle — לֹא (lo) = "not"
- **[Pred]**: Predicate — יִהְיֶֽה (yihyeh) = imperfect form of היה (hayah, "to be")
- **[Cmpl]**: Complement — לְךָ (leka) = "to you" (2ms)
- **[Subj]**: Subject — אֱלֹהִים אֲחֵרִים (elohim acherim) = "other gods"
- **[Adju]**: Adjunct — עַל פָּנָי (al panay) = "upon my face" / "before me"

### Key Grammatical Notes
- The verb יִהְיֶֽה is Qal Imperfect 3ms — jussive/prohibitive sense with לֹא: "there shall not be"
- The suffix on פָּנָי is 1cs (common singular) — "my face" — referring to God himself
- The preposition עַל (al) = "upon, over, before" — used with פָּנִים (panim, face) forms the spatial/relational phrase "before my face" / "in my presence"

## Deuteronomy 6:4 — Verse Parse (hebrew_parser.py --verse "Deu 6:4")

```
======================================================================
  Deuteronomy 6:4
======================================================================

  שְׁמַ֖ע יִשְׂרָאֵ֑ל יְהוָ֥ה אֱלֹהֵ֖ינוּ יְהוָ֥ה׀ אֶחָֽד׃

  Hebrew          Lemma        Parsing                   Gloss
  --------------- ------------ ------------------------- --------------------
  שְׁמַ֖ע         שׁמע         Verb.Qal.Impv.2ms         hear
  יִשְׂרָאֵ֑ל     ישׂראל       PropN.s.Abs.+NAN          Israel
  יְהוָ֥ה         יהוה         PropN.ms.Abs.+NAN         YHWH
  אֱלֹהֵ֖ינוּ     אלהים        Noun.mp.Abs.+1up          god(s)
  יְהוָ֥ה         יהוה         PropN.ms.Abs.+NAN         YHWH
  אֶחָֽד          אחד          Noun.s.Abs                one
```

### Key Grammatical Notes
- שְׁמַע (shema) — Qal Imperative 2ms: "Hear!" — a direct command to Israel
- אֱלֹהֵינוּ (eloheinu) — Noun mp with 1cp suffix: "our God(s)" — the plural form אלהים with possessive suffix
- אֶחָד (echad) — "one" — functions as predicate: "YHWH [is] one"
- The verse structure: Imperative + Vocative (Israel) + Declarative statement (YHWH our God, YHWH [is] one)
