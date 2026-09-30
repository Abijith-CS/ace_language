# IQCODE Assessment — Urdu

> **Source:** Extracted directly from [IQCODE Assessment (2) (1).html](./IQCODE%20Assessment%20%282%29%20%281%29.html).
> **Language Code:** `ur` | **Native Name:** اردو | **Pack Label:** `English and Urdu`
> **Script Direction:** `rtl` | **Font Family:** `Noto Nastaliq Urdu` | **Line Height:** `2.2` | **Style Class:** `.nastaliq`
> **Speech Recognition / Voice:** `ur-PK`
> **Instrument:** IQCODE — 26 items (Full Form) / 16 items (Short Form), each rated 1–5

---

## Overview & Provenance

This document contains the complete informant-facing text for the **IQCODE Urdu Edition** as implemented in the IQCODE HTML assessment: the spoken preamble, the question stem, the five response bands, and all 26 questionnaire items. This is the only right-to-left pack in the instrument. The Urdu line is mirrored beside the English lead, set on a 2.2 line-height so the Nastaliq descenders are not clipped, and Latin digits inside the target text (10, 19__) stay in logical order within the right-to-left run.

Every target-language line below is reproduced **verbatim** from the `LANGS.ur` content pack inside the HTML, paired with the English line it sits beside on screen. The IQCODE is administered **bilingually**: the clinician reads the English lead, and the Urdu line is shown to the informant with a read-aloud control that speaks it using the `ur-PK` voice.

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
  - **Target Script:** اب ہم چاہتے ہیں کہ آپ یاد کریں کہ آپ کا دوست یا رشتہ دار 10 سال پہلے کیسا تھا اور اس کا موازنہ اس کی موجودہ حالت سے کریں۔ 10 سال پہلے سن 19__ تھا۔
  - **English Reference:** *Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}.*
- **[preamble-2]**
  - **Target Script:** نیچے کچھ ایسی صورتِ حال دی گئی ہیں جن میں اس شخص کو اپنی یادداشت یا ذہانت استعمال کرنی پڑتی ہے۔ ہم چاہتے ہیں کہ آپ بتائیں کہ پچھلے 10 سالوں میں ان کاموں کو کرنے کی اس کی صلاحیت بہتر ہوئی ہے، ویسی ہی رہی ہے یا کم ہوئی ہے۔ خاص طور پر یہ دیکھیں کہ وہ آج یہ کام کتنی اچھی طرح کر سکتا ہے، اور 10 سال پہلے یہ کام کتنی اچھی طرح کر سکتا تھا
  - **English Reference:** *Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago.*
- **[preamble-3]**
  - **Target Script:** اگر 10 سال پہلے بھی یہ شخص اکثر بھول جاتا تھا کہ اس نے چیزیں کہاں رکھی ہیں اور اب بھی ایسا ہی کرتا ہے، تو اسے ”زیادہ تبدیلی نہیں آئی“ سمجھا جائے گا۔ براہِ کرم جو تبدیلیاں آپ نے دیکھی ہیں ان کے مطابق مناسب جواب پر دائرہ لگائیں۔
  - **English Reference:** *So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best.*

### Question Stem — repeated above every item

- **[stem]**
  - **Target Script:** 10 سال پہلے کے مقابلے میں، یہ شخص نیچے دیے گئے کام اب کتنی اچھی طرح کر سکتا ہے؟
  - **English Reference:** *Compared with 10 years ago, how is this person at…*

---

## Response Bands (5-point scale)

Each item is rated on the same five bands. The numeric value is the score contributed by that item; the IQCODE result is the **mean** of the rated items, reported to two decimals.

| Value | Target Script | English Reference | Keyboard |
|:---|:---|:---|:---|
| **1** | بہت بہتر | Much improved | `1` |
| **2** | کچھ بہتر | A bit improved | `2` |
| **3** | زیادہ تبدیلی نہیں آئی | Not much change | `3` |
| **4** | کچھ خراب | A bit worse | `4` |
| **5** | بہت خراب | Much worse | `5` |

- **Can’t rate:** an item the informant genuinely cannot judge is marked *can’t rate* rather than guessed. It is **excluded from the mean**, and at most **3** items (Full Form) or **2** items (Short Form) may be excluded before the assessment is unscoreable.
- In **Normal view** the band numbers are hidden and only the words are shown, so nothing on screen reads as a score to the informant. **Scoring view** shows the numbers.

---

## Questionnaire Items (26)

Items are grouped below by the clinical clusters used in the assessment’s navigation rail. **SF** marks the 16 items that make up the **Short Form**.

### People and names (items 1, 2, 3)

#### Item 1: Faces
- **Target Script:** خاندان کے افراد اور دوستوں کے چہروں کو پہچاننا
- **English Reference:** *Recognizing the faces of family and friends*

#### Item 2: Names
- **Target Script:** خاندان کے افراد اور دوستوں کے نام یاد رکھنا
- **English Reference:** *Remembering the names of family and friends*

#### Item 3: Facts about people | **Short Form**
- **Target Script:** خاندان اور دوستوں کے بارے میں معلومات یاد رکھنا، مثلاً پیشہ، سالگرہ اور پتے
- **English Reference:** *Remembering things about family and friends e.g. occupations, birthdays, addresses*

---

### Recent memory (items 4, 5, 6)

#### Item 4: Recent events | **Short Form**
- **Target Script:** حال ہی میں ہونے والے واقعات یاد رکھنا
- **English Reference:** *Remembering things that have happened recently*

#### Item 5: Conversations | **Short Form**
- **Target Script:** چند دن بعد ہونے والی گفتگو یاد کرنا
- **English Reference:** *Recalling conversations a few days later*

#### Item 6: Losing the thread
- **Target Script:** گفتگو کے دوران یہ بھول جانا کہ کیا کہنا تھا
- **English Reference:** *Forgetting what he/she wanted to say in the middle of a conversation*

---

### Everyday memory (items 7, 8, 9, 10, 11)

#### Item 7: Address and phone | **Short Form**
- **Target Script:** اپنا پتہ اور ٹیلیفون نمبر یاد رکھنا
- **English Reference:** *Remembering his/her address and telephone number*

#### Item 8: Day and month | **Short Form**
- **Target Script:** یہ یاد رکھنا کہ آج کون سا دن اور کون سا مہینہ ہے
- **English Reference:** *Remembering what day and month it is*

#### Item 9: Where things are kept | **Short Form**
- **Target Script:** یہ یاد رکھنا کہ چیزیں عام طور پر کہاں رکھی جاتی ہیں
- **English Reference:** *Remembering where things are usually kept*

#### Item 10: Things moved | **Short Form**
- **Target Script:** یہ یاد رکھنا کہ وہ چیزیں کہاں ہیں جو معمول کی جگہ سے ہٹا کر کہیں اور رکھی گئی ہوں
- **English Reference:** *Remembering where to find things which have been put in a different place from usual*

#### Item 11: Routine changes
- **Target Script:** روزمرہ کے معمولات میں ہونے والی تبدیلی کے مطابق خود کو ڈھالنا
- **English Reference:** *Adjusting to any change in his/her day-to-day routine*

---

### Machines and learning (items 12, 13, 14)

#### Item 12: Familiar machines | **Short Form**
- **Target Script:** گھر میں استعمال ہونے والی عام مشینیں چلانا
- **English Reference:** *Knowing how to work familiar machines around the house*

#### Item 13: New gadgets | **Short Form**
- **Target Script:** گھر میں کسی نئی مشین یا آلے کو استعمال کرنا سیکھنا
- **English Reference:** *Learning to use a new gadget or machine around the house*

#### Item 14: Learning in general | **Short Form**
- **Target Script:** عام طور پر نئی چیزیں سیکھنا
- **English Reference:** *Learning new things in general*

---

### Memory from long ago (items 15, 16, 21)

#### Item 15: Early-life events
- **Target Script:** اپنی جوانی یا بچپن کے واقعات یاد رکھنا
- **English Reference:** *Remembering things that happened to him/her when he/she was young*

#### Item 16: Early-life learning
- **Target Script:** وہ باتیں یاد رکھنا جو اس نے جوانی یا بچپن میں سیکھی تھیں
- **English Reference:** *Remembering things he/she learned when he/she was young*

#### Item 21: Historical events
- **Target Script:** ماضی کے اہم تاریخی واقعات کے بارے میں معلومات رکھنا
- **English Reference:** *Knowing about important historical events of the past*

---

### Words and reading (items 17, 18, 19, 20)

#### Item 17: Unusual words
- **Target Script:** غیر معمولی یا کم استعمال ہونے والے الفاظ کے معنی سمجھنا
- **English Reference:** *Understanding the meaning of unusual words*

#### Item 18: Newspaper articles
- **Target Script:** رسالوں یا اخبارات کے مضامین سمجھنا
- **English Reference:** *Understanding magazine or newspaper articles*

#### Item 19: Following a story | **Short Form**
- **Target Script:** کتاب یا ٹی وی پر چلنے والی کہانی کو سمجھتے ہوئے اس کا تسلسل برقرار رکھنا
- **English Reference:** *Following a story in a book or on TV*

#### Item 20: Writing letters
- **Target Script:** دوستوں کو یا کاروباری مقصد کے لیے خط لکھنا
- **English Reference:** *Composing a letter to friends or for business purposes*

---

### Decisions and money (items 22, 23, 24, 25, 26)

#### Item 22: Everyday decisions | **Short Form**
- **Target Script:** روزمرہ کے معاملات میں فیصلے کرنا
- **English Reference:** *Making decisions on everyday matters*

#### Item 23: Shopping money | **Short Form**
- **Target Script:** خریداری کے لیے پیسوں کا حساب رکھنا اور استعمال کرنا
- **English Reference:** *Handling money for shopping*

#### Item 24: Financial matters | **Short Form**
- **Target Script:** مالی معاملات سنبھالنا، مثلاً پنشن یا بینک کے معاملات
- **English Reference:** *Handling financial matters, e.g. the pension, dealing with the bank*

#### Item 25: Everyday arithmetic | **Short Form**
- **Target Script:** روزمرہ کے دیگر حسابی مسائل حل کرنا، مثلاً کتنا کھانا خریدنا ہے یا خاندان اور دوستوں کی ملاقاتوں کے درمیان کتنا وقت گزرا ہے
- **English Reference:** *Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends*

#### Item 26: Reasoning | **Short Form**
- **Target Script:** اپنی سمجھ بوجھ اور ذہانت استعمال کرکے حالات کو سمجھنا اور ان پر غور و فکر کرنا
- **English Reference:** *Using his/her intelligence to understand what's going on and to reason things through*

---

## Short Form (16 items)

The Short Form administers the following full-form item numbers, in this order.

| SF # | Full-form # | Short Label | Target Script | English Reference |
|:---|:---|:---|:---|:---|
| 1 | 3 | Facts about people | خاندان اور دوستوں کے بارے میں معلومات یاد رکھنا، مثلاً پیشہ، سالگرہ اور پتے | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| 2 | 4 | Recent events | حال ہی میں ہونے والے واقعات یاد رکھنا | Remembering things that have happened recently |
| 3 | 5 | Conversations | چند دن بعد ہونے والی گفتگو یاد کرنا | Recalling conversations a few days later |
| 4 | 7 | Address and phone | اپنا پتہ اور ٹیلیفون نمبر یاد رکھنا | Remembering his/her address and telephone number |
| 5 | 8 | Day and month | یہ یاد رکھنا کہ آج کون سا دن اور کون سا مہینہ ہے | Remembering what day and month it is |
| 6 | 9 | Where things are kept | یہ یاد رکھنا کہ چیزیں عام طور پر کہاں رکھی جاتی ہیں | Remembering where things are usually kept |
| 7 | 10 | Things moved | یہ یاد رکھنا کہ وہ چیزیں کہاں ہیں جو معمول کی جگہ سے ہٹا کر کہیں اور رکھی گئی ہوں | Remembering where to find things which have been put in a different place from usual |
| 8 | 12 | Familiar machines | گھر میں استعمال ہونے والی عام مشینیں چلانا | Knowing how to work familiar machines around the house |
| 9 | 13 | New gadgets | گھر میں کسی نئی مشین یا آلے کو استعمال کرنا سیکھنا | Learning to use a new gadget or machine around the house |
| 10 | 14 | Learning in general | عام طور پر نئی چیزیں سیکھنا | Learning new things in general |
| 11 | 19 | Following a story | کتاب یا ٹی وی پر چلنے والی کہانی کو سمجھتے ہوئے اس کا تسلسل برقرار رکھنا | Following a story in a book or on TV |
| 12 | 22 | Everyday decisions | روزمرہ کے معاملات میں فیصلے کرنا | Making decisions on everyday matters |
| 13 | 23 | Shopping money | خریداری کے لیے پیسوں کا حساب رکھنا اور استعمال کرنا | Handling money for shopping |
| 14 | 24 | Financial matters | مالی معاملات سنبھالنا، مثلاً پنشن یا بینک کے معاملات | Handling financial matters, e.g. the pension, dealing with the bank |
| 15 | 25 | Everyday arithmetic | روزمرہ کے دیگر حسابی مسائل حل کرنا، مثلاً کتنا کھانا خریدنا ہے یا خاندان اور دوستوں کی ملاقاتوں کے درمیان کتنا وقت گزرا ہے | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| 16 | 26 | Reasoning | اپنی سمجھ بوجھ اور ذہانت استعمال کرکے حالات کو سمجھنا اور ان پر غور و فکر کرنا | Using his/her intelligence to understand what's going on and to reason things through |

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

The complete Urdu content pack (`LANGS.ur`) in source order, paired with the English reference line.

| String Key | Target Script Translation | English Reference Gloss |
|:---|:---|:---|
| `stem` | 10 سال پہلے کے مقابلے میں، یہ شخص نیچے دیے گئے کام اب کتنی اچھی طرح کر سکتا ہے؟ | Compared with 10 years ago, how is this person at… |
| `bands[0]` | بہت بہتر | Much improved |
| `bands[1]` | کچھ بہتر | A bit improved |
| `bands[2]` | زیادہ تبدیلی نہیں آئی | Not much change |
| `bands[3]` | کچھ خراب | A bit worse |
| `bands[4]` | بہت خراب | Much worse |
| `preamble[0]` | اب ہم چاہتے ہیں کہ آپ یاد کریں کہ آپ کا دوست یا رشتہ دار 10 سال پہلے کیسا تھا اور اس کا موازنہ اس کی موجودہ حالت سے کریں۔ 10 سال پہلے سن 19__ تھا۔ | Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}. |
| `preamble[1]` | نیچے کچھ ایسی صورتِ حال دی گئی ہیں جن میں اس شخص کو اپنی یادداشت یا ذہانت استعمال کرنی پڑتی ہے۔ ہم چاہتے ہیں کہ آپ بتائیں کہ پچھلے 10 سالوں میں ان کاموں کو کرنے کی اس کی صلاحیت بہتر ہوئی ہے، ویسی ہی رہی ہے یا کم ہوئی ہے۔ خاص طور پر یہ دیکھیں کہ وہ آج یہ کام کتنی اچھی طرح کر سکتا ہے، اور 10 سال پہلے یہ کام کتنی اچھی طرح کر سکتا تھا | Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago. |
| `preamble[2]` | اگر 10 سال پہلے بھی یہ شخص اکثر بھول جاتا تھا کہ اس نے چیزیں کہاں رکھی ہیں اور اب بھی ایسا ہی کرتا ہے، تو اسے ”زیادہ تبدیلی نہیں آئی“ سمجھا جائے گا۔ براہِ کرم جو تبدیلیاں آپ نے دیکھی ہیں ان کے مطابق مناسب جواب پر دائرہ لگائیں۔ | So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best. |
| `items[0]` | خاندان کے افراد اور دوستوں کے چہروں کو پہچاننا | Recognizing the faces of family and friends |
| `items[1]` | خاندان کے افراد اور دوستوں کے نام یاد رکھنا | Remembering the names of family and friends |
| `items[2]` | خاندان اور دوستوں کے بارے میں معلومات یاد رکھنا، مثلاً پیشہ، سالگرہ اور پتے | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| `items[3]` | حال ہی میں ہونے والے واقعات یاد رکھنا | Remembering things that have happened recently |
| `items[4]` | چند دن بعد ہونے والی گفتگو یاد کرنا | Recalling conversations a few days later |
| `items[5]` | گفتگو کے دوران یہ بھول جانا کہ کیا کہنا تھا | Forgetting what he/she wanted to say in the middle of a conversation |
| `items[6]` | اپنا پتہ اور ٹیلیفون نمبر یاد رکھنا | Remembering his/her address and telephone number |
| `items[7]` | یہ یاد رکھنا کہ آج کون سا دن اور کون سا مہینہ ہے | Remembering what day and month it is |
| `items[8]` | یہ یاد رکھنا کہ چیزیں عام طور پر کہاں رکھی جاتی ہیں | Remembering where things are usually kept |
| `items[9]` | یہ یاد رکھنا کہ وہ چیزیں کہاں ہیں جو معمول کی جگہ سے ہٹا کر کہیں اور رکھی گئی ہوں | Remembering where to find things which have been put in a different place from usual |
| `items[10]` | روزمرہ کے معمولات میں ہونے والی تبدیلی کے مطابق خود کو ڈھالنا | Adjusting to any change in his/her day-to-day routine |
| `items[11]` | گھر میں استعمال ہونے والی عام مشینیں چلانا | Knowing how to work familiar machines around the house |
| `items[12]` | گھر میں کسی نئی مشین یا آلے کو استعمال کرنا سیکھنا | Learning to use a new gadget or machine around the house |
| `items[13]` | عام طور پر نئی چیزیں سیکھنا | Learning new things in general |
| `items[14]` | اپنی جوانی یا بچپن کے واقعات یاد رکھنا | Remembering things that happened to him/her when he/she was young |
| `items[15]` | وہ باتیں یاد رکھنا جو اس نے جوانی یا بچپن میں سیکھی تھیں | Remembering things he/she learned when he/she was young |
| `items[16]` | غیر معمولی یا کم استعمال ہونے والے الفاظ کے معنی سمجھنا | Understanding the meaning of unusual words |
| `items[17]` | رسالوں یا اخبارات کے مضامین سمجھنا | Understanding magazine or newspaper articles |
| `items[18]` | کتاب یا ٹی وی پر چلنے والی کہانی کو سمجھتے ہوئے اس کا تسلسل برقرار رکھنا | Following a story in a book or on TV |
| `items[19]` | دوستوں کو یا کاروباری مقصد کے لیے خط لکھنا | Composing a letter to friends or for business purposes |
| `items[20]` | ماضی کے اہم تاریخی واقعات کے بارے میں معلومات رکھنا | Knowing about important historical events of the past |
| `items[21]` | روزمرہ کے معاملات میں فیصلے کرنا | Making decisions on everyday matters |
| `items[22]` | خریداری کے لیے پیسوں کا حساب رکھنا اور استعمال کرنا | Handling money for shopping |
| `items[23]` | مالی معاملات سنبھالنا، مثلاً پنشن یا بینک کے معاملات | Handling financial matters, e.g. the pension, dealing with the bank |
| `items[24]` | روزمرہ کے دیگر حسابی مسائل حل کرنا، مثلاً کتنا کھانا خریدنا ہے یا خاندان اور دوستوں کی ملاقاتوں کے درمیان کتنا وقت گزرا ہے | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| `items[25]` | اپنی سمجھ بوجھ اور ذہانت استعمال کرکے حالات کو سمجھنا اور ان پر غور و فکر کرنا | Using his/her intelligence to understand what's going on and to reason things through |

---

*Generated from `Assessments/IQCODE Assessment (2) (1).html` — all 35 content strings (1 stem + 5 bands + 3 preamble paragraphs + 26 items) are translated into Urdu.*
