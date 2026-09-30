# IQCODE Assessment — Gujarati

> **Source:** Extracted directly from [IQCODE Assessment (2) (1).html](./IQCODE%20Assessment%20%282%29%20%281%29.html).
> **Language Code:** `gu` | **Native Name:** ગુજરાતી | **Pack Label:** `English and Gujarati`
> **Script Direction:** `ltr` | **Font Family:** `Noto Sans Gujarati` | **Line Height:** `1.75` | **Style Class:** `(none — inherits the base class)`
> **Speech Recognition / Voice:** `gu-IN`
> **Instrument:** IQCODE — 26 items (Full Form) / 16 items (Short Form), each rated 1–5

---

## Overview & Provenance

This document contains the complete informant-facing text for the **IQCODE Gujarati Edition** as implemented in the IQCODE HTML assessment: the spoken preamble, the question stem, the five response bands, and all 26 questionnaire items. Gujarati is left-to-right, so the Gujarati line sits directly beneath the English lead on the same edge rather than mirrored.

Every target-language line below is reproduced **verbatim** from the `LANGS.gu` content pack inside the HTML, paired with the English line it sits beside on screen. The IQCODE is administered **bilingually**: the clinician reads the English lead, and the Gujarati line is shown to the informant with a read-aloud control that speaks it using the `gu-IN` voice.

### Placeholders in the Source Text

| Token | Meaning | Substitution |
|:---|:---|:---|
| `19__` | The reference year | Replaced at runtime with the current year minus the reference period |
| `10` | The reference period in years | Replaced with `5` if a five-year reference period is selected |

> These substitutions are made by `trFix(text, ref, year)` in the HTML. The strings below are shown **unsubstituted**, exactly as they are stored in the content pack.

---

## Administration Script

### Preamble — read aloud to the informant before the questionnaire

- **[preamble-1]**
  - **Target Script:** હવે અમે ઇચ્છીએ છીએ કે તમે યાદ કરો કે તમારા મિત્ર અથવા સગા 10 વર્ષ પહેલાં કેવી સ્થિતિમાં હતા અને તેની તુલના તેમની હાલની સ્થિતિ સાથે કરો. 10 વર્ષ પહેલાં 19__ વર્ષ હતું.
  - **English Reference:** *Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}.*
- **[preamble-2]**
  - **Target Script:** નીચે કેટલીક પરિસ્થિતિઓ આપવામાં આવી છે જેમાં આ વ્યક્તિએ પોતાની યાદશક્તિ અથવા બુદ્ધિનો ઉપયોગ કરવો પડે છે. અમે ઇચ્છીએ છીએ કે તમે જણાવો કે છેલ્લા 10 વર્ષોમાં આ બાબતોમાં તેમની કાર્યક્ષમતા સુધરી છે, એ જ રહી છે કે ખરાબ થઈ છે. કૃપા કરીને તેમની હાલની કામગીરીની 10 વર્ષ પહેલાંની કામગીરી સાથે તુલના કરવાનું મહત્વ ધ્યાનમાં રાખો.
  - **English Reference:** *Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago.*
- **[preamble-3]**
  - **Target Script:** તેથી જો 10 વર્ષ પહેલાં પણ આ વ્યક્તિ વારંવાર ભૂલી જતી હતી કે વસ્તુઓ ક્યાં મૂકી છે અને આજે પણ એવું જ કરે છે, તો તેને 'ખાસ ફેરફાર નથી' તરીકે ગણવામાં આવશે. કૃપા કરીને તમે જોયેલા ફેરફારો અનુસાર યોગ્ય જવાબ પર ગોળ કરો.
  - **English Reference:** *So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best.*

### Question Stem — repeated above every item

- **[stem]**
  - **Target Script:** 10 વર્ષ પહેલાંની સરખામણીમાં આ વ્યક્તિ નીચેની બાબતોમાં કેવી છે?
  - **English Reference:** *Compared with 10 years ago, how is this person at…*

---

## Response Bands (5-point scale)

Each item is rated on the same five bands. The numeric value is the score contributed by that item; the IQCODE result is the **mean** of the rated items, reported to two decimals.

| Value | Target Script | English Reference | Keyboard |
|:---|:---|:---|:---|
| **1** | ઘણો સુધારો થયો છે | Much improved | `1` |
| **2** | થોડો સુધારો થયો છે | A bit improved | `2` |
| **3** | ખાસ ફેરફાર નથી | Not much change | `3` |
| **4** | થોડું ખરાબ થયું છે | A bit worse | `4` |
| **5** | ઘણું ખરાબ થયું છે | Much worse | `5` |

- **Can’t rate:** an item the informant genuinely cannot judge is marked *can’t rate* rather than guessed. It is **excluded from the mean**, and at most **3** items (Full Form) or **2** items (Short Form) may be excluded before the assessment is unscoreable.
- In **Normal view** the band numbers are hidden and only the words are shown, so nothing on screen reads as a score to the informant. **Scoring view** shows the numbers.

---

## Questionnaire Items (26)

Items are grouped below by the clinical clusters used in the assessment’s navigation rail. **SF** marks the 16 items that make up the **Short Form**.

### People and names (items 1, 2, 3)

#### Item 1: Faces
- **Target Script:** પરિવારના સભ્યો અને મિત્રોનો ચહેરો ઓળખવો
- **English Reference:** *Recognizing the faces of family and friends*

#### Item 2: Names
- **Target Script:** પરિવારના સભ્યો અને મિત્રોના નામ યાદ રાખવા
- **English Reference:** *Remembering the names of family and friends*

#### Item 3: Facts about people | **Short Form**
- **Target Script:** પરિવારના સભ્યો અને મિત્રો વિશેની માહિતી યાદ રાખવી, જેમ કે વ્યવસાય, જન્મદિવસ અને સરનામા
- **English Reference:** *Remembering things about family and friends e.g. occupations, birthdays, addresses*

---

### Recent memory (items 4, 5, 6)

#### Item 4: Recent events | **Short Form**
- **Target Script:** તાજેતરમાં બનેલી ઘટનાઓ યાદ રાખવી
- **English Reference:** *Remembering things that have happened recently*

#### Item 5: Conversations | **Short Form**
- **Target Script:** થોડા દિવસો પછી થયેલી વાતચીત યાદ કરવી
- **English Reference:** *Recalling conversations a few days later*

#### Item 6: Losing the thread
- **Target Script:** વાતચીત દરમિયાન શું કહેવું હતું તે ભૂલી જવું
- **English Reference:** *Forgetting what he/she wanted to say in the middle of a conversation*

---

### Everyday memory (items 7, 8, 9, 10, 11)

#### Item 7: Address and phone | **Short Form**
- **Target Script:** પોતાનું સરનામું અને ટેલિફોન નંબર યાદ રાખવો
- **English Reference:** *Remembering his/her address and telephone number*

#### Item 8: Day and month | **Short Form**
- **Target Script:** આજે કયો દિવસ અને કયો મહિનો છે તે યાદ રાખવું
- **English Reference:** *Remembering what day and month it is*

#### Item 9: Where things are kept | **Short Form**
- **Target Script:** વસ્તુઓ સામાન્ય રીતે ક્યાં રાખવામાં આવે છે તે યાદ રાખવું
- **English Reference:** *Remembering where things are usually kept*

#### Item 10: Things moved | **Short Form**
- **Target Script:** જે વસ્તુઓ સામાન્ય જગ્યાથી બીજી જગ્યાએ રાખવામાં આવી હોય તે ક્યાં છે તે યાદ રાખવું
- **English Reference:** *Remembering where to find things which have been put in a different place from usual*

#### Item 11: Routine changes
- **Target Script:** રોજિંદા જીવનના નિયમિત કાર્યક્રમમાં થતા ફેરફારોને અનુરૂપ થવું
- **English Reference:** *Adjusting to any change in his/her day-to-day routine*

---

### Machines and learning (items 12, 13, 14)

#### Item 12: Familiar machines | **Short Form**
- **Target Script:** ઘરમાં ઉપયોગમાં લેવાતી પરિચિત મશીનો ચલાવવી આવડવી
- **English Reference:** *Knowing how to work familiar machines around the house*

#### Item 13: New gadgets | **Short Form**
- **Target Script:** ઘરમાં નવી મશીન અથવા સાધનનો ઉપયોગ શીખવો
- **English Reference:** *Learning to use a new gadget or machine around the house*

#### Item 14: Learning in general | **Short Form**
- **Target Script:** સામાન્ય રીતે નવી વસ્તુઓ શીખવી
- **English Reference:** *Learning new things in general*

---

### Memory from long ago (items 15, 16, 21)

#### Item 15: Early-life events
- **Target Script:** બાળપણ અથવા યુવાનીમાં બનેલી ઘટનાઓ યાદ રાખવી
- **English Reference:** *Remembering things that happened to him/her when he/she was young*

#### Item 16: Early-life learning
- **Target Script:** બાળપણ અથવા યુવાનીમાં શીખેલી બાબતો યાદ રાખવી
- **English Reference:** *Remembering things he/she learned when he/she was young*

#### Item 21: Historical events
- **Target Script:** ભૂતકાળની મહત્વપૂર્ણ ઐતિહાસિક ઘટનાઓ વિશે જાણવું
- **English Reference:** *Knowing about important historical events of the past*

---

### Words and reading (items 17, 18, 19, 20)

#### Item 17: Unusual words
- **Target Script:** અસામાન્ય અથવા ઓછા વપરાતા શબ્દોના અર્થ સમજવા
- **English Reference:** *Understanding the meaning of unusual words*

#### Item 18: Newspaper articles
- **Target Script:** સામયિકો અથવા અખબારના લેખો સમજવા
- **English Reference:** *Understanding magazine or newspaper articles*

#### Item 19: Following a story | **Short Form**
- **Target Script:** પુસ્તકમાં અથવા ટીવી પર આવતી વાર્તાનો ક્રમ સમજી શકવો
- **English Reference:** *Following a story in a book or on TV*

#### Item 20: Writing letters
- **Target Script:** મિત્રોને અથવા વ્યવસાયિક હેતુ માટે પત્ર લખવો
- **English Reference:** *Composing a letter to friends or for business purposes*

---

### Decisions and money (items 22, 23, 24, 25, 26)

#### Item 22: Everyday decisions | **Short Form**
- **Target Script:** રોજિંદા બાબતોમાં નિર્ણય લેવા
- **English Reference:** *Making decisions on everyday matters*

#### Item 23: Shopping money | **Short Form**
- **Target Script:** ખરીદી માટે પૈસાનો ઉપયોગ અને હિસાબ રાખવો
- **English Reference:** *Handling money for shopping*

#### Item 24: Financial matters | **Short Form**
- **Target Script:** નાણાકીય બાબતો સંભાળવી, જેમ કે પેન્શન અથવા બેંકના કામકાજ
- **English Reference:** *Handling financial matters, e.g. the pension, dealing with the bank*

#### Item 25: Everyday arithmetic | **Short Form**
- **Target Script:** રોજિંદા જીવનની અન્ય ગણિતીય સમસ્યાઓ ઉકેલવી, જેમ કે કેટલું ખોરાક ખરીદવું અથવા પરિવાર અને મિત્રોની મુલાકાતો વચ્ચે કેટલો સમય થયો છે તે જાણવું
- **English Reference:** *Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends*

#### Item 26: Reasoning | **Short Form**
- **Target Script:** શું ચાલી રહ્યું છે તે સમજવા અને તેના વિશે વિચારવા માટે પોતાની બુદ્ધિનો ઉપયોગ કરવો
- **English Reference:** *Using his/her intelligence to understand what's going on and to reason things through*

---

## Short Form (16 items)

The Short Form administers the following full-form item numbers, in this order.

| SF # | Full-form # | Short Label | Target Script | English Reference |
|:---|:---|:---|:---|:---|
| 1 | 3 | Facts about people | પરિવારના સભ્યો અને મિત્રો વિશેની માહિતી યાદ રાખવી, જેમ કે વ્યવસાય, જન્મદિવસ અને સરનામા | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| 2 | 4 | Recent events | તાજેતરમાં બનેલી ઘટનાઓ યાદ રાખવી | Remembering things that have happened recently |
| 3 | 5 | Conversations | થોડા દિવસો પછી થયેલી વાતચીત યાદ કરવી | Recalling conversations a few days later |
| 4 | 7 | Address and phone | પોતાનું સરનામું અને ટેલિફોન નંબર યાદ રાખવો | Remembering his/her address and telephone number |
| 5 | 8 | Day and month | આજે કયો દિવસ અને કયો મહિનો છે તે યાદ રાખવું | Remembering what day and month it is |
| 6 | 9 | Where things are kept | વસ્તુઓ સામાન્ય રીતે ક્યાં રાખવામાં આવે છે તે યાદ રાખવું | Remembering where things are usually kept |
| 7 | 10 | Things moved | જે વસ્તુઓ સામાન્ય જગ્યાથી બીજી જગ્યાએ રાખવામાં આવી હોય તે ક્યાં છે તે યાદ રાખવું | Remembering where to find things which have been put in a different place from usual |
| 8 | 12 | Familiar machines | ઘરમાં ઉપયોગમાં લેવાતી પરિચિત મશીનો ચલાવવી આવડવી | Knowing how to work familiar machines around the house |
| 9 | 13 | New gadgets | ઘરમાં નવી મશીન અથવા સાધનનો ઉપયોગ શીખવો | Learning to use a new gadget or machine around the house |
| 10 | 14 | Learning in general | સામાન્ય રીતે નવી વસ્તુઓ શીખવી | Learning new things in general |
| 11 | 19 | Following a story | પુસ્તકમાં અથવા ટીવી પર આવતી વાર્તાનો ક્રમ સમજી શકવો | Following a story in a book or on TV |
| 12 | 22 | Everyday decisions | રોજિંદા બાબતોમાં નિર્ણય લેવા | Making decisions on everyday matters |
| 13 | 23 | Shopping money | ખરીદી માટે પૈસાનો ઉપયોગ અને હિસાબ રાખવો | Handling money for shopping |
| 14 | 24 | Financial matters | નાણાકીય બાબતો સંભાળવી, જેમ કે પેન્શન અથવા બેંકના કામકાજ | Handling financial matters, e.g. the pension, dealing with the bank |
| 15 | 25 | Everyday arithmetic | રોજિંદા જીવનની અન્ય ગણિતીય સમસ્યાઓ ઉકેલવી, જેમ કે કેટલું ખોરાક ખરીદવું અથવા પરિવાર અને મિત્રોની મુલાકાતો વચ્ચે કેટલો સમય થયો છે તે જાણવું | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| 16 | 26 | Reasoning | શું ચાલી રહ્યું છે તે સમજવા અને તેના વિશે વિચારવા માટે પોતાની બુદ્ધિનો ઉપયોગ કરવો | Using his/her intelligence to understand what's going on and to reason things through |

---

## Clinical Administration & Scoring Guidelines

These rules are reproduced from the instructions drawer and result screen in the HTML. They are clinician-facing and are presented in English only — they are never read to the informant.

### Administration Rules:
- **`rule-verbatim`**
  - **English Guideline:** *Read each item exactly as written, with the stem “Compared with 10 years ago, how is this person at…”. Do not reword it.*
- **`rule-no-prompt`**
  - **English Guideline:** *Do not prompt toward an answer. If needed, repeat the item and the five bands once, in order.*
- **`rule-cant-rate`**
  - **English Guideline:** *Accept “can’t rate” rather than a guess. It is excluded from the score — at most 3 items on the full form, 2 on the Short Form.*
- **`rule-notes`**
  - **English Guideline:** *Record verbatim remarks in the note field. They qualify the answer and appear on the result.*
- **`rule-comparison`**
  - **English Guideline:** *The comparison is with the same person 10 years ago — never with other people of the same age.*
- **`rule-cutoff-meaning`**
  - **English Guideline:** *A score at or above a cut-off indicates suspicion of cognitive decline only. Interpret it alongside the full clinical picture.*
- **`rule-informant-effect`**
  - **English Guideline:** *IQCODE scores are affected by the informant as well as the patient. Informant anxiety, depression and carer burden are all associated with higher scores; a reluctance to “mark down” a relative is associated with lower ones. Weigh the score accordingly.*
- **`rule-reference-period`**
  - **English Guideline:** *A five-year reference period is a recorded departure from protocol. The published cut-offs are validated against ten years.*

### Scoring:
- **Item score:** 1 (Much improved) to 5 (Much worse).
- **IQCODE score:** the arithmetic **mean** of the rated items, to two decimals. Items marked *can’t rate* are excluded and the score is prorated over the items actually answered.
- **Unrateable limit:** more than 3 excluded items (Full Form) or 2 (Short Form) makes the assessment unscoreable.
- **Reference period:** 10 years by default. A five-year period is recorded as a departure from protocol, because the published cut-offs are validated against ten years.

### Published Cut-offs — Full Form (26 items):

| Cut-off | Sensitivity | Specificity | Validation Sample |
|:---|:---|:---|:---|
| **3.30** or above | 79% | 83% | 684 community residents aged 70+ — Jorm et al. 1994 |
| **3.31** or above | 83% | 83% | 160 rural community — Morales et al. 1997 |
| **3.40** or above | 89% | 88% | 399 community + 61 dementia patients — Fuh et al. 1995 |
| **3.60** or above | 80% | 82% | 69 geriatric patients, mean age 80 — Jorm et al. 1991 |
| **3.90** or above | 74% | 71% | 299 memory clinic patients — Flicker et al. 1997 |
| **4.00** or above | — | — | 577 memory clinic patients, AUC 0.82 — Stratford et al. 2003 |

### Published Cut-offs — Short Form (16 items):

| Cut-off | Sensitivity | Specificity | Validation Sample |
|:---|:---|:---|:---|
| **3.38** or above | 79% | 82% | 684 community residents aged 70+ — Jorm 1994 |
| **3.44** or above | 100% | 86% | 177 medical inpatients aged 65+ — Harwood et al. 1997 |

> A score at or above a cut-off indicates **suspicion of cognitive decline only**. Interpret it alongside the full clinical picture.

---

## Appendix: Complete Translation Dictionary

The complete Gujarati content pack (`LANGS.gu`) in source order, paired with the English reference line.

| String Key | Target Script Translation | English Reference Gloss |
|:---|:---|:---|
| `stem` | 10 વર્ષ પહેલાંની સરખામણીમાં આ વ્યક્તિ નીચેની બાબતોમાં કેવી છે? | Compared with 10 years ago, how is this person at… |
| `bands[0]` | ઘણો સુધારો થયો છે | Much improved |
| `bands[1]` | થોડો સુધારો થયો છે | A bit improved |
| `bands[2]` | ખાસ ફેરફાર નથી | Not much change |
| `bands[3]` | થોડું ખરાબ થયું છે | A bit worse |
| `bands[4]` | ઘણું ખરાબ થયું છે | Much worse |
| `preamble[0]` | હવે અમે ઇચ્છીએ છીએ કે તમે યાદ કરો કે તમારા મિત્ર અથવા સગા 10 વર્ષ પહેલાં કેવી સ્થિતિમાં હતા અને તેની તુલના તેમની હાલની સ્થિતિ સાથે કરો. 10 વર્ષ પહેલાં 19__ વર્ષ હતું. | Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}. |
| `preamble[1]` | નીચે કેટલીક પરિસ્થિતિઓ આપવામાં આવી છે જેમાં આ વ્યક્તિએ પોતાની યાદશક્તિ અથવા બુદ્ધિનો ઉપયોગ કરવો પડે છે. અમે ઇચ્છીએ છીએ કે તમે જણાવો કે છેલ્લા 10 વર્ષોમાં આ બાબતોમાં તેમની કાર્યક્ષમતા સુધરી છે, એ જ રહી છે કે ખરાબ થઈ છે. કૃપા કરીને તેમની હાલની કામગીરીની 10 વર્ષ પહેલાંની કામગીરી સાથે તુલના કરવાનું મહત્વ ધ્યાનમાં રાખો. | Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago. |
| `preamble[2]` | તેથી જો 10 વર્ષ પહેલાં પણ આ વ્યક્તિ વારંવાર ભૂલી જતી હતી કે વસ્તુઓ ક્યાં મૂકી છે અને આજે પણ એવું જ કરે છે, તો તેને 'ખાસ ફેરફાર નથી' તરીકે ગણવામાં આવશે. કૃપા કરીને તમે જોયેલા ફેરફારો અનુસાર યોગ્ય જવાબ પર ગોળ કરો. | So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best. |
| `items[0]` | પરિવારના સભ્યો અને મિત્રોનો ચહેરો ઓળખવો | Recognizing the faces of family and friends |
| `items[1]` | પરિવારના સભ્યો અને મિત્રોના નામ યાદ રાખવા | Remembering the names of family and friends |
| `items[2]` | પરિવારના સભ્યો અને મિત્રો વિશેની માહિતી યાદ રાખવી, જેમ કે વ્યવસાય, જન્મદિવસ અને સરનામા | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| `items[3]` | તાજેતરમાં બનેલી ઘટનાઓ યાદ રાખવી | Remembering things that have happened recently |
| `items[4]` | થોડા દિવસો પછી થયેલી વાતચીત યાદ કરવી | Recalling conversations a few days later |
| `items[5]` | વાતચીત દરમિયાન શું કહેવું હતું તે ભૂલી જવું | Forgetting what he/she wanted to say in the middle of a conversation |
| `items[6]` | પોતાનું સરનામું અને ટેલિફોન નંબર યાદ રાખવો | Remembering his/her address and telephone number |
| `items[7]` | આજે કયો દિવસ અને કયો મહિનો છે તે યાદ રાખવું | Remembering what day and month it is |
| `items[8]` | વસ્તુઓ સામાન્ય રીતે ક્યાં રાખવામાં આવે છે તે યાદ રાખવું | Remembering where things are usually kept |
| `items[9]` | જે વસ્તુઓ સામાન્ય જગ્યાથી બીજી જગ્યાએ રાખવામાં આવી હોય તે ક્યાં છે તે યાદ રાખવું | Remembering where to find things which have been put in a different place from usual |
| `items[10]` | રોજિંદા જીવનના નિયમિત કાર્યક્રમમાં થતા ફેરફારોને અનુરૂપ થવું | Adjusting to any change in his/her day-to-day routine |
| `items[11]` | ઘરમાં ઉપયોગમાં લેવાતી પરિચિત મશીનો ચલાવવી આવડવી | Knowing how to work familiar machines around the house |
| `items[12]` | ઘરમાં નવી મશીન અથવા સાધનનો ઉપયોગ શીખવો | Learning to use a new gadget or machine around the house |
| `items[13]` | સામાન્ય રીતે નવી વસ્તુઓ શીખવી | Learning new things in general |
| `items[14]` | બાળપણ અથવા યુવાનીમાં બનેલી ઘટનાઓ યાદ રાખવી | Remembering things that happened to him/her when he/she was young |
| `items[15]` | બાળપણ અથવા યુવાનીમાં શીખેલી બાબતો યાદ રાખવી | Remembering things he/she learned when he/she was young |
| `items[16]` | અસામાન્ય અથવા ઓછા વપરાતા શબ્દોના અર્થ સમજવા | Understanding the meaning of unusual words |
| `items[17]` | સામયિકો અથવા અખબારના લેખો સમજવા | Understanding magazine or newspaper articles |
| `items[18]` | પુસ્તકમાં અથવા ટીવી પર આવતી વાર્તાનો ક્રમ સમજી શકવો | Following a story in a book or on TV |
| `items[19]` | મિત્રોને અથવા વ્યવસાયિક હેતુ માટે પત્ર લખવો | Composing a letter to friends or for business purposes |
| `items[20]` | ભૂતકાળની મહત્વપૂર્ણ ઐતિહાસિક ઘટનાઓ વિશે જાણવું | Knowing about important historical events of the past |
| `items[21]` | રોજિંદા બાબતોમાં નિર્ણય લેવા | Making decisions on everyday matters |
| `items[22]` | ખરીદી માટે પૈસાનો ઉપયોગ અને હિસાબ રાખવો | Handling money for shopping |
| `items[23]` | નાણાકીય બાબતો સંભાળવી, જેમ કે પેન્શન અથવા બેંકના કામકાજ | Handling financial matters, e.g. the pension, dealing with the bank |
| `items[24]` | રોજિંદા જીવનની અન્ય ગણિતીય સમસ્યાઓ ઉકેલવી, જેમ કે કેટલું ખોરાક ખરીદવું અથવા પરિવાર અને મિત્રોની મુલાકાતો વચ્ચે કેટલો સમય થયો છે તે જાણવું | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| `items[25]` | શું ચાલી રહ્યું છે તે સમજવા અને તેના વિશે વિચારવા માટે પોતાની બુદ્ધિનો ઉપયોગ કરવો | Using his/her intelligence to understand what's going on and to reason things through |

---

*Generated from `Assessments/IQCODE Assessment (2) (1).html` — all 35 content strings (1 stem + 5 bands + 3 preamble paragraphs + 26 items) are translated into Gujarati.*
