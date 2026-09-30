# IQCODE Assessment — Hindi

> **Source:** Extracted directly from [IQCODE Assessment (2) (1).html](./IQCODE%20Assessment%20%282%29%20%281%29.html).
> **Language Code:** `hi` | **Native Name:** हिन्दी | **Pack Label:** `English and Hindi`
> **Script Direction:** `ltr` | **Font Family:** `Noto Sans Devanagari` | **Line Height:** `1.75` | **Style Class:** `(none — inherits the base class)`
> **Speech Recognition / Voice:** `hi-IN`
> **Instrument:** IQCODE — 26 items (Full Form) / 16 items (Short Form), each rated 1–5

---

## Overview & Provenance

This document contains the complete informant-facing text for the **IQCODE Hindi Edition** as implemented in the IQCODE HTML assessment: the spoken preamble, the question stem, the five response bands, and all 26 questionnaire items. Hindi is left-to-right, so the Devanagari line sits directly beneath the English lead on the same edge rather than mirrored.

Every target-language line below is reproduced **verbatim** from the `LANGS.hi` content pack inside the HTML, paired with the English line it sits beside on screen. The IQCODE is administered **bilingually**: the clinician reads the English lead, and the Hindi line is shown to the informant with a read-aloud control that speaks it using the `hi-IN` voice.

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
  - **Target Script:** अब हम चाहते हैं कि आप याद करें कि आपका मित्र या रिश्तेदार 10 वर्ष पहले कैसा था और उसकी तुलना उसकी वर्तमान स्थिति से करें। 10 वर्ष पहले वर्ष 19__ था।
  - **English Reference:** *Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}.*
- **[preamble-2]**
  - **Target Script:** नीचे कुछ ऐसी परिस्थितियाँ दी गई हैं जिनमें इस व्यक्ति को अपनी याददाश्त या बुद्धि का उपयोग करना पड़ता है। हम चाहते हैं कि आप बताएं कि पिछले 10 वर्षों में इन स्थितियों में उसकी क्षमता में सुधार हुआ है, वैसी ही बनी हुई है, या खराब हुई है। कृपया उसकी वर्तमान क्षमता की तुलना 10 वर्ष पहले की क्षमता से करें।
  - **English Reference:** *Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago.*
- **[preamble-3]**
  - **Target Script:** यदि 10 वर्ष पहले भी यह व्यक्ति अक्सर भूल जाता था कि उसने चीजें कहाँ रखी हैं और आज भी ऐसा ही करता है, तो इसे ”ज्यादा बदलाव नहीं हुआ“ माना जाएगा। कृपया अपने द्वारा देखे गए बदलावों के अनुसार उचित उत्तर पर गोला लगाएँ।
  - **English Reference:** *So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best.*

### Question Stem — repeated above every item

- **[stem]**
  - **Target Script:** 10 वर्ष पहले की तुलना में यह व्यक्ति निम्नलिखित कार्यों में कैसा है?
  - **English Reference:** *Compared with 10 years ago, how is this person at…*

---

## Response Bands (5-point scale)

Each item is rated on the same five bands. The numeric value is the score contributed by that item; the IQCODE result is the **mean** of the rated items, reported to two decimals.

| Value | Target Script | English Reference | Keyboard |
|:---|:---|:---|:---|
| **1** | बहुत सुधार हुआ है | Much improved | `1` |
| **2** | थोड़ा सुधार हुआ है | A bit improved | `2` |
| **3** | ज्यादा बदलाव नहीं हुआ है | Not much change | `3` |
| **4** | थोड़ा खराब हुआ है | A bit worse | `4` |
| **5** | बहुत खराब हुआ है | Much worse | `5` |

- **Can’t rate:** an item the informant genuinely cannot judge is marked *can’t rate* rather than guessed. It is **excluded from the mean**, and at most **3** items (Full Form) or **2** items (Short Form) may be excluded before the assessment is unscoreable.
- In **Normal view** the band numbers are hidden and only the words are shown, so nothing on screen reads as a score to the informant. **Scoring view** shows the numbers.

---

## Questionnaire Items (26)

Items are grouped below by the clinical clusters used in the assessment’s navigation rail. **SF** marks the 16 items that make up the **Short Form**.

### People and names (items 1, 2, 3)

#### Item 1: Faces
- **Target Script:** परिवार के सदस्यों और मित्रों के चेहरों को पहचानना
- **English Reference:** *Recognizing the faces of family and friends*

#### Item 2: Names
- **Target Script:** परिवार के सदस्यों और मित्रों के नाम याद रखना
- **English Reference:** *Remembering the names of family and friends*

#### Item 3: Facts about people | **Short Form**
- **Target Script:** परिवार और मित्रों के बारे में बातें याद रखना, जैसे उनका काम, जन्मदिन और पता
- **English Reference:** *Remembering things about family and friends e.g. occupations, birthdays, addresses*

---

### Recent memory (items 4, 5, 6)

#### Item 4: Recent events | **Short Form**
- **Target Script:** हाल ही में हुई घटनाओं को याद रखना
- **English Reference:** *Remembering things that have happened recently*

#### Item 5: Conversations | **Short Form**
- **Target Script:** कुछ दिनों बाद हुई बातचीत को याद करना
- **English Reference:** *Recalling conversations a few days later*

#### Item 6: Losing the thread
- **Target Script:** बातचीत के बीच में यह भूल जाना कि क्या कहना था
- **English Reference:** *Forgetting what he/she wanted to say in the middle of a conversation*

---

### Everyday memory (items 7, 8, 9, 10, 11)

#### Item 7: Address and phone | **Short Form**
- **Target Script:** अपना पता और टेलीफोन नंबर याद रखना
- **English Reference:** *Remembering his/her address and telephone number*

#### Item 8: Day and month | **Short Form**
- **Target Script:** यह याद रखना कि आज कौन-सा दिन और कौन-सा महीना है
- **English Reference:** *Remembering what day and month it is*

#### Item 9: Where things are kept | **Short Form**
- **Target Script:** यह याद रखना कि चीजें आमतौर पर कहाँ रखी जाती हैं
- **English Reference:** *Remembering where things are usually kept*

#### Item 10: Things moved | **Short Form**
- **Target Script:** यह याद रखना कि वे चीजें कहाँ रखी हैं जिन्हें उनकी सामान्य जगह से हटाकर कहीं और रखा गया है
- **English Reference:** *Remembering where to find things which have been put in a different place from usual*

#### Item 11: Routine changes
- **Target Script:** रोज़मर्रा की दिनचर्या में होने वाले बदलावों के अनुसार खुद को ढालना
- **English Reference:** *Adjusting to any change in his/her day-to-day routine*

---

### Machines and learning (items 12, 13, 14)

#### Item 12: Familiar machines | **Short Form**
- **Target Script:** घर में उपयोग होने वाली परिचित मशीनों को चलाना जानना
- **English Reference:** *Knowing how to work familiar machines around the house*

#### Item 13: New gadgets | **Short Form**
- **Target Script:** घर में किसी नई मशीन या उपकरण का उपयोग करना सीखना
- **English Reference:** *Learning to use a new gadget or machine around the house*

#### Item 14: Learning in general | **Short Form**
- **Target Script:** सामान्य रूप से नई चीजें सीखना
- **English Reference:** *Learning new things in general*

---

### Memory from long ago (items 15, 16, 21)

#### Item 15: Early-life events
- **Target Script:** बचपन या युवावस्था की घटनाओं को याद रखना
- **English Reference:** *Remembering things that happened to him/her when he/she was young*

#### Item 16: Early-life learning
- **Target Script:** बचपन या युवावस्था में सीखी हुई बातें याद रखना
- **English Reference:** *Remembering things he/she learned when he/she was young*

#### Item 21: Historical events
- **Target Script:** अतीत की महत्वपूर्ण ऐतिहासिक घटनाओं के बारे में जानकारी रखना
- **English Reference:** *Knowing about important historical events of the past*

---

### Words and reading (items 17, 18, 19, 20)

#### Item 17: Unusual words
- **Target Script:** अपरिचित या कम उपयोग होने वाले शब्दों का अर्थ समझना
- **English Reference:** *Understanding the meaning of unusual words*

#### Item 18: Newspaper articles
- **Target Script:** पत्रिका या समाचार पत्र के लेखों को समझना
- **English Reference:** *Understanding magazine or newspaper articles*

#### Item 19: Following a story | **Short Form**
- **Target Script:** किताब या टीवी पर चल रही कहानी को समझते हुए उसका क्रम बनाए रखना
- **English Reference:** *Following a story in a book or on TV*

#### Item 20: Writing letters
- **Target Script:** मित्रों को या व्यावसायिक उद्देश्य के लिए पत्र लिखना
- **English Reference:** *Composing a letter to friends or for business purposes*

---

### Decisions and money (items 22, 23, 24, 25, 26)

#### Item 22: Everyday decisions | **Short Form**
- **Target Script:** रोज़मर्रा के मामलों में निर्णय लेना
- **English Reference:** *Making decisions on everyday matters*

#### Item 23: Shopping money | **Short Form**
- **Target Script:** खरीदारी के लिए पैसों का उपयोग और हिसाब रखना
- **English Reference:** *Handling money for shopping*

#### Item 24: Financial matters | **Short Form**
- **Target Script:** वित्तीय मामलों को संभालना, जैसे पेंशन या बैंक से संबंधित कार्य
- **English Reference:** *Handling financial matters, e.g. the pension, dealing with the bank*

#### Item 25: Everyday arithmetic | **Short Form**
- **Target Script:** रोज़मर्रा की अन्य गणितीय समस्याओं को संभालना, जैसे कितना खाना खरीदना है या परिवार और मित्रों की मुलाकातों के बीच कितना समय हुआ है यह जानना
- **English Reference:** *Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends*

#### Item 26: Reasoning | **Short Form**
- **Target Script:** क्या हो रहा है यह समझने और उस पर विचार करने के लिए अपनी बुद्धि का उपयोग करना
- **English Reference:** *Using his/her intelligence to understand what's going on and to reason things through*

---

## Short Form (16 items)

The Short Form administers the following full-form item numbers, in this order.

| SF # | Full-form # | Short Label | Target Script | English Reference |
|:---|:---|:---|:---|:---|
| 1 | 3 | Facts about people | परिवार और मित्रों के बारे में बातें याद रखना, जैसे उनका काम, जन्मदिन और पता | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| 2 | 4 | Recent events | हाल ही में हुई घटनाओं को याद रखना | Remembering things that have happened recently |
| 3 | 5 | Conversations | कुछ दिनों बाद हुई बातचीत को याद करना | Recalling conversations a few days later |
| 4 | 7 | Address and phone | अपना पता और टेलीफोन नंबर याद रखना | Remembering his/her address and telephone number |
| 5 | 8 | Day and month | यह याद रखना कि आज कौन-सा दिन और कौन-सा महीना है | Remembering what day and month it is |
| 6 | 9 | Where things are kept | यह याद रखना कि चीजें आमतौर पर कहाँ रखी जाती हैं | Remembering where things are usually kept |
| 7 | 10 | Things moved | यह याद रखना कि वे चीजें कहाँ रखी हैं जिन्हें उनकी सामान्य जगह से हटाकर कहीं और रखा गया है | Remembering where to find things which have been put in a different place from usual |
| 8 | 12 | Familiar machines | घर में उपयोग होने वाली परिचित मशीनों को चलाना जानना | Knowing how to work familiar machines around the house |
| 9 | 13 | New gadgets | घर में किसी नई मशीन या उपकरण का उपयोग करना सीखना | Learning to use a new gadget or machine around the house |
| 10 | 14 | Learning in general | सामान्य रूप से नई चीजें सीखना | Learning new things in general |
| 11 | 19 | Following a story | किताब या टीवी पर चल रही कहानी को समझते हुए उसका क्रम बनाए रखना | Following a story in a book or on TV |
| 12 | 22 | Everyday decisions | रोज़मर्रा के मामलों में निर्णय लेना | Making decisions on everyday matters |
| 13 | 23 | Shopping money | खरीदारी के लिए पैसों का उपयोग और हिसाब रखना | Handling money for shopping |
| 14 | 24 | Financial matters | वित्तीय मामलों को संभालना, जैसे पेंशन या बैंक से संबंधित कार्य | Handling financial matters, e.g. the pension, dealing with the bank |
| 15 | 25 | Everyday arithmetic | रोज़मर्रा की अन्य गणितीय समस्याओं को संभालना, जैसे कितना खाना खरीदना है या परिवार और मित्रों की मुलाकातों के बीच कितना समय हुआ है यह जानना | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| 16 | 26 | Reasoning | क्या हो रहा है यह समझने और उस पर विचार करने के लिए अपनी बुद्धि का उपयोग करना | Using his/her intelligence to understand what's going on and to reason things through |

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

The complete Hindi content pack (`LANGS.hi`) in source order, paired with the English reference line.

| String Key | Target Script Translation | English Reference Gloss |
|:---|:---|:---|
| `stem` | 10 वर्ष पहले की तुलना में यह व्यक्ति निम्नलिखित कार्यों में कैसा है? | Compared with 10 years ago, how is this person at… |
| `bands[0]` | बहुत सुधार हुआ है | Much improved |
| `bands[1]` | थोड़ा सुधार हुआ है | A bit improved |
| `bands[2]` | ज्यादा बदलाव नहीं हुआ है | Not much change |
| `bands[3]` | थोड़ा खराब हुआ है | A bit worse |
| `bands[4]` | बहुत खराब हुआ है | Much worse |
| `preamble[0]` | अब हम चाहते हैं कि आप याद करें कि आपका मित्र या रिश्तेदार 10 वर्ष पहले कैसा था और उसकी तुलना उसकी वर्तमान स्थिति से करें। 10 वर्ष पहले वर्ष 19__ था। | Now we want you to remember what your friend or relative was like 10 years ago and to compare it with what he/she is like now. 10 years ago was in {refYear}. |
| `preamble[1]` | नीचे कुछ ऐसी परिस्थितियाँ दी गई हैं जिनमें इस व्यक्ति को अपनी याददाश्त या बुद्धि का उपयोग करना पड़ता है। हम चाहते हैं कि आप बताएं कि पिछले 10 वर्षों में इन स्थितियों में उसकी क्षमता में सुधार हुआ है, वैसी ही बनी हुई है, या खराब हुई है। कृपया उसकी वर्तमान क्षमता की तुलना 10 वर्ष पहले की क्षमता से करें। | Below are situations where this person has to use his/her memory or intelligence and we want you to indicate whether this has improved, stayed the same, or got worse in that situation over the past 10 years. Note the importance of comparing his/her present performance with 10 years ago. |
| `preamble[2]` | यदि 10 वर्ष पहले भी यह व्यक्ति अक्सर भूल जाता था कि उसने चीजें कहाँ रखी हैं और आज भी ऐसा ही करता है, तो इसे ”ज्यादा बदलाव नहीं हुआ“ माना जाएगा। कृपया अपने द्वारा देखे गए बदलावों के अनुसार उचित उत्तर पर गोला लगाएँ। | So if 10 years ago this person always forgot where he/she had left things, and he/she still does, then this would be considered “Not much change”. Please indicate the changes you have observed by choosing the answer that fits best. |
| `items[0]` | परिवार के सदस्यों और मित्रों के चेहरों को पहचानना | Recognizing the faces of family and friends |
| `items[1]` | परिवार के सदस्यों और मित्रों के नाम याद रखना | Remembering the names of family and friends |
| `items[2]` | परिवार और मित्रों के बारे में बातें याद रखना, जैसे उनका काम, जन्मदिन और पता | Remembering things about family and friends e.g. occupations, birthdays, addresses |
| `items[3]` | हाल ही में हुई घटनाओं को याद रखना | Remembering things that have happened recently |
| `items[4]` | कुछ दिनों बाद हुई बातचीत को याद करना | Recalling conversations a few days later |
| `items[5]` | बातचीत के बीच में यह भूल जाना कि क्या कहना था | Forgetting what he/she wanted to say in the middle of a conversation |
| `items[6]` | अपना पता और टेलीफोन नंबर याद रखना | Remembering his/her address and telephone number |
| `items[7]` | यह याद रखना कि आज कौन-सा दिन और कौन-सा महीना है | Remembering what day and month it is |
| `items[8]` | यह याद रखना कि चीजें आमतौर पर कहाँ रखी जाती हैं | Remembering where things are usually kept |
| `items[9]` | यह याद रखना कि वे चीजें कहाँ रखी हैं जिन्हें उनकी सामान्य जगह से हटाकर कहीं और रखा गया है | Remembering where to find things which have been put in a different place from usual |
| `items[10]` | रोज़मर्रा की दिनचर्या में होने वाले बदलावों के अनुसार खुद को ढालना | Adjusting to any change in his/her day-to-day routine |
| `items[11]` | घर में उपयोग होने वाली परिचित मशीनों को चलाना जानना | Knowing how to work familiar machines around the house |
| `items[12]` | घर में किसी नई मशीन या उपकरण का उपयोग करना सीखना | Learning to use a new gadget or machine around the house |
| `items[13]` | सामान्य रूप से नई चीजें सीखना | Learning new things in general |
| `items[14]` | बचपन या युवावस्था की घटनाओं को याद रखना | Remembering things that happened to him/her when he/she was young |
| `items[15]` | बचपन या युवावस्था में सीखी हुई बातें याद रखना | Remembering things he/she learned when he/she was young |
| `items[16]` | अपरिचित या कम उपयोग होने वाले शब्दों का अर्थ समझना | Understanding the meaning of unusual words |
| `items[17]` | पत्रिका या समाचार पत्र के लेखों को समझना | Understanding magazine or newspaper articles |
| `items[18]` | किताब या टीवी पर चल रही कहानी को समझते हुए उसका क्रम बनाए रखना | Following a story in a book or on TV |
| `items[19]` | मित्रों को या व्यावसायिक उद्देश्य के लिए पत्र लिखना | Composing a letter to friends or for business purposes |
| `items[20]` | अतीत की महत्वपूर्ण ऐतिहासिक घटनाओं के बारे में जानकारी रखना | Knowing about important historical events of the past |
| `items[21]` | रोज़मर्रा के मामलों में निर्णय लेना | Making decisions on everyday matters |
| `items[22]` | खरीदारी के लिए पैसों का उपयोग और हिसाब रखना | Handling money for shopping |
| `items[23]` | वित्तीय मामलों को संभालना, जैसे पेंशन या बैंक से संबंधित कार्य | Handling financial matters, e.g. the pension, dealing with the bank |
| `items[24]` | रोज़मर्रा की अन्य गणितीय समस्याओं को संभालना, जैसे कितना खाना खरीदना है या परिवार और मित्रों की मुलाकातों के बीच कितना समय हुआ है यह जानना | Handling other everyday arithmetic problems, e.g. knowing how much food to buy, knowing how long between visits from family or friends |
| `items[25]` | क्या हो रहा है यह समझने और उस पर विचार करने के लिए अपनी बुद्धि का उपयोग करना | Using his/her intelligence to understand what's going on and to reason things through |

---

*Generated from `Assessments/IQCODE Assessment (2) (1).html` — all 35 content strings (1 stem + 5 bands + 3 preamble paragraphs + 26 items) are translated into Hindi.*
