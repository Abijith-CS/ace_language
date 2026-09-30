# RUDAS Assessment — Urdu

> **Source:** Extracted directly from [RUDAS Assessment -Aether- V3 - standalone.html](./RUDAS%20Assessment%20-Aether-%20V3%20-%20standalone.html).
> **Language Code:** `ur` | **Native Name:** اردو
> **Script Direction:** `rtl` | **Font Family:** `Noto Nastaliq Urdu` | **Style Class:** `.nastaliq`
> **Speech Recognition / Voice:** `ur-PK`
> **Instrument Total:** 30 points across 6 cognitive domains

---

## Overview & Provenance

This document contains the complete clinical text, spoken administration scripts, guidance notes, scored questions and stimulus word list for the **RUDAS Urdu Edition** as implemented in the RUDAS HTML assessment. It is typeset in **Noto Nastaliq Urdu** and is the only right-to-left pack in the instrument: the target line is mirrored beneath the English lead, and Latin digits inside the target text are isolated with `<bdi>` so numerals such as 5 and 10 read correctly inside the right-to-left run.

Every target-language line below is reproduced **verbatim** from the `STR.ur` content pack inside the HTML, paired with the `STR.en` English line it sits beside on screen. The assessment renders each spoken script bilingually: the English lead for the clinician, the Urdu line beneath it with a read-aloud control that speaks it using the `ur-PK` voice.

### Domain Totals

| Domain | Task(s) | Max Score |
|:---|:---|:---|
| Memory | `mem-register + mem-recall` | 8 |
| Body Orientation | `vis-body` | 5 |
| Praxis | `prax-hands` | 2 |
| Visuoconstructional drawing | `draw-cube` | 3 |
| Judgement | `judg-road` | 4 |
| Language | `lang-animals` | 8 |
| **Total** | | **30** |

---

## Cognitive Domains & Task Protocols

### Task 1: Shopping list — registration (`mem-register`)
- **Domain:** MEMORY | **Max Score:** 0 | *Not scored — the four items are recalled and scored later at Task 6*
- **Sheet Item Number:** 1 | **Rail Label:** Memory

#### Spoken Administration Script:
- **[reg-script]**
  - **Target Script:** میں چاہتا ہوں کہ آپ تصور کریں کہ ہم خریداری کے لیے جا رہے ہیں۔ یہ خریداری کی چیزوں کی ایک فہرست ہے۔ میں چاہتا ہوں کہ آپ ان چیزوں کو یاد رکھیں جو ہمیں دکان سے خریدنی ہیں۔ تقریباً 5 منٹ بعد جب ہم دکان پہنچیں گے تو میں آپ سے پوچھوں گا کہ ہمیں کیا خریدنا ہے۔ آپ کو یہ فہرست یاد رکھنی ہے۔
  - **English Reference:** *I want you to imagine that we are going shopping. Here is a list of grocery items. I would like you to remember the following items which we need to get from the shop. When we get to the shop in about 5 mins. time I will ask you what it is that we have to buy. You must remember the list for me.*
- **[reg-repeat]**
  - **Target Script:** براہِ کرم یہ فہرست میرے لیے دہرائیں۔
  - **English Reference:** *Please repeat this list for me.*

#### Instructions & Guidance Notes:
- **[reg-sub1]**
  - **Target Script:** (شخص سے فہرست 3 مرتبہ دہرانے کو کہیں۔)
  - **English Reference:** *(Ask person to repeat the list 3 times.)*
- **[reg-sub2]**
  - **Target Script:** اگر شخص چاروں الفاظ نہ دہرا سکے تو فہرست دوبارہ سنائیں، یہاں تک کہ وہ انہیں یاد کر لے اور دہرا سکے، یا زیادہ سے زیادہ پانچ مرتبہ تک۔
  - **English Reference:** *(If person did not repeat all four words, repeat the list until the person has learned them and can repeat them, or, up to a maximum of five times.)*

#### Shopping List Stimuli (4 Items):

| Item | String Key | Target Word | English Reference |
|:---|:---|:---|:---|
| Word 1 | `w-tea` | **چائے** | Tea |
| Word 2 | `w-oil` | **کھانا پکانے کا تیل** | Cooking Oil |
| Word 3 | `w-eggs` | **انڈے** | Eggs |
| Word 4 | `w-soap` | **صابن** | Soap |

#### Trials Recorded:
- **Presentations needed to learn all four:** 1 · 2 · 3 · 4 · 5 *(recorded, not scored)*

#### How to Administer:
1. Read the list aloud, then ask the person to repeat it. Ask for the list three times.
2. If the person did not repeat all four words, repeat the list until the person has learned them and can repeat them, or up to a maximum of five times.
3. Record how many presentations were needed. The list is recalled at item 1 (Recall), after the judgment task.

#### Scoring:
- Not scored. Recall of the four items is scored later, 2 points each, to a maximum of 8.

---

### Task 2: Body parts (`vis-body`)
- **Domain:** VISUOSPATIAL | **Max Score:** 5
- **Sheet Item Number:** 2 | **Rail Label:** Body Orientation

#### Spoken Administration Script:
- **[body-script]**
  - **Target Script:** میں آپ سے جسم کے مختلف حصوں کی پہچان کرنے کے لیے کہوں گا اور انہیں دکھانے کے لیے بھی کہوں گا۔
  - **English Reference:** *I am going to ask you to identify/show me different parts of the body.*

#### Instructions & Guidance Notes:
- **[body-sub]**
  - **Target Script:** — *(English only — no target-language string in the content pack)*
  - **English Reference:** *(Correct = 1). Once the person correctly answers 5 parts of this question, do not continue as the maximum score is 5.*

#### Specific Questions / Prompts:
- **[body-1]**
  - **Target Script:** اپنا دایاں پاؤں دکھائیں۔
  - **English Reference:** *Show me your right foot.*
- **[body-2]**
  - **Target Script:** اپنا بایاں ہاتھ دکھائیں۔
  - **English Reference:** *Show me your left hand.*
- **[body-3]**
  - **Target Script:** اپنے دائیں ہاتھ سے اپنے بائیں کندھے کو چھوئیں۔
  - **English Reference:** *With your right hand touch your left shoulder.*
- **[body-4]**
  - **Target Script:** اپنے بائیں ہاتھ سے اپنے دائیں کان کو چھوئیں۔
  - **English Reference:** *With your left hand touch your right ear.*
- **[body-5]**
  - **Target Script:** میرا بایاں گھٹنا کون سا ہے؟
  - **English Reference:** *Which is my left knee?*
- **[body-6]**
  - **Target Script:** میری دائیں کہنی کون سی ہے؟
  - **English Reference:** *Which is my right elbow?*
- **[body-7]**
  - **Target Script:** اپنے دائیں ہاتھ سے میری بائیں آنکھ کی طرف اشارہ کریں۔
  - **English Reference:** *With your right hand indicate/point to my left eye.*
- **[body-8]**
  - **Target Script:** اپنے بائیں ہاتھ سے میرے بائیں پاؤں کی طرف اشارہ کریں۔
  - **English Reference:** *With your left hand indicate/point to my left foot.*

#### How to Administer:
1. Ask each part in turn and mark it. Correct = 1.
2. Once the person correctly answers 5 parts, do not continue — the maximum score is 5.

#### Scoring:
- One point per correct part, capped at 5. Parts left unmarked after the cap is reached are recorded as not administered.

#### Scoring Options (Normal view symbols):

| Value | Verdict | Normal-view Symbol |
|:---|:---|:---|
| 1 | Correct | Circle |
| 0 | Incorrect | Square |
| — | Did not attempt | Triangle |

> Normal view shows these shapes in place of the verdict words, so nothing on screen reads as right or wrong to the patient. Scoring view shows the words.

---

### Task 3: Alternating hand movements (`prax-hands`)
- **Domain:** PRAXIS | **Max Score:** 2
- **Sheet Item Number:** 3 | **Rail Label:** Praxis

#### Spoken Administration Script:
- **[praxis-script]**
  - **Target Script:** میں آپ کو اپنے ہاتھوں سے ایک حرکت/مشق دکھاؤں گا۔ میں چاہتا ہوں کہ آپ مجھے غور سے دیکھیں اور وہی کریں جو میں کرتا ہوں۔ جب میں یہ حرکت کروں تو آپ بھی ویسا ہی کریں۔ (ایک ہاتھ مٹھی میں رکھیں اور دوسرا ہاتھ میز پر ہتھیلی کے بل رکھیں، پھر دونوں کی حالت باری باری ایک ساتھ تبدیل کریں۔) اب میرے ساتھ کریں۔ اب میں چاہتا ہوں کہ آپ یہی حرکت اسی رفتار سے کرتے رہیں جب تک میں آپ کو رکنے کے لیے نہ کہوں، تقریباً 10 سیکنڈ تک۔ (درمیانی رفتار سے چلنے کی رفتار کے مطابق مظاہرہ کریں۔)
  - **English Reference:** *I am going to show you an action/exercise with my hands. I want you to watch me and copy what I do. Copy me when I do this . . . (One hand in fist, the other palm down on table - alternate simultaneously.) Now do it with me. Now I would like you to keep doing this action at this pace until I tell you to stop - approximately 10 seconds. (Demonstrate at moderate walking pace).*

#### Scoring Rubric (Max 2):

| Points | Band | Criteria |
|:---|:---|:---|
| **2** | Normal | Very few if any errors; self-corrected, progressively better; good maintenance; only very slight lack of synchrony between hands |
| **1** | Partially adequate | Noticeable errors with some attempt to self-correct; some attempt at maintenance; poor synchrony |
| **0** | Failed | Cannot do the task; no maintenance; no attempt whatsoever |

#### How to Administer:
1. Demonstrate: one hand in a fist, the other palm down on the table — alternate simultaneously.
2. Then have the person do it with you, then keep going at the same pace for about 10 seconds. Demonstrate at a moderate walking pace.

#### Scoring:
- Normal = 2 (very few if any errors; self-corrected, progressively better; good maintenance; only very slight lack of synchrony between hands). Partially adequate = 1 (noticeable errors with some attempt to self-correct; some attempt at maintenance; poor synchrony). Failed = 0 (cannot do the task; no maintenance; no attempt whatsoever).

---

### Task 4: Cube copy (`draw-cube`)
- **Domain:** DRAWING | **Max Score:** 3
- **Sheet Item Number:** 4 | **Rail Label:** Visuoconstructional drawing

#### Spoken Administration Script:
- **[cube-script]**
  - **Target Script:** آپ سے گزارش ہے کہ اس تصویر کو بالکل ویسا ہی بنائیں جیسی یہ آپ کو نظر آ رہی ہے۔
  - **English Reference:** *Please draw this picture exactly as it looks to you.*

#### Instructions & Guidance Notes:
- **[cube-sub]**
  - **Target Script:** — *(English only — no target-language string in the content pack)*
  - **English Reference:** *(Show cube on back of page). (Yes = 1)*

#### Specific Questions / Prompts:
- **[cube-1]**
  - **Target Script:** کیا مریض نے مربع کی بنیاد پر شکل بنائی ہے؟
  - **English Reference:** *Has person drawn a picture based on a square?*
- **[cube-2]**
  - **Target Script:** کیا شخص کی بنائی ہوئی شکل میں تمام اندرونی لکیریں موجود ہیں؟
  - **English Reference:** *Do all internal lines appear in person’s drawing?*
- **[cube-3]**
  - **Target Script:** کیا شخص کی بنائی ہوئی شکل میں تمام بیرونی لکیریں موجود ہیں؟
  - **English Reference:** *Do all external lines appear in person’s drawing?*

#### Stimulus:
- **Cube image:** presented on the back of the sheet, or full screen with the **Show patient** control (`P`). The patient surface shows the cube only — never a score, mark or identifier.
- **Capture:** *Use Camera* / *QR Capture* record the patient’s drawing against the encounter.

#### How to Administer:
1. Show the cube (on the back of the sheet, or with Show patient) and ask the person to draw it exactly as it looks to them.
2. Photograph or scan the drawing for the record.

#### Scoring:
- Yes = 1 for each: a picture based on a square; all internal lines present; all external lines present. Maximum 3.

#### Scoring Options (Normal view symbols):

| Value | Verdict | Normal-view Symbol |
|:---|:---|:---|
| 1 | Yes | Circle |
| 0 | No | Square |
| — | Did not attempt | Triangle |

> Normal view shows these shapes in place of the verdict words, so nothing on screen reads as right or wrong to the patient. Scoring view shows the words.

---

### Task 5: Crossing the road (`judg-road`)
- **Domain:** JUDGMENT | **Max Score:** 4
- **Sheet Item Number:** 5 | **Rail Label:** Judgement

#### Spoken Administration Script:
- **[judg-script]**
  - **Target Script:** آپ ایک مصروف سڑک کے کنارے کھڑے ہیں۔ وہاں نہ پیدل چلنے والوں کے لیے کراسنگ ہے اور نہ ٹریفک لائٹ۔ مجھے بتائیں کہ آپ سڑک کے دوسری طرف محفوظ طریقے سے جانے کے لیے کیا کریں گے۔
  - **English Reference:** *You are standing on the side of a busy street. There is no pedestrian crossing and no traffic lights. Tell me what you would do to get across to the other side of the road safely.*

#### Instructions & Guidance Notes:
- **[judg-sub1]**
  - **Target Script:** اگر مریض کا جواب نامکمل ہو اور سوال کے دونوں حصوں کا جواب نہ دیتا ہو تو پوچھیں: "کیا آپ اور کچھ کریں گے؟"
  - **English Reference:** *If person gives incomplete response that does not address both parts of answer, use prompt: “Is there anything else you would do?”*
- **[judg-sub2]**
  - **Target Script:** شخص جو کچھ کہے اسے لفظ بہ لفظ لکھیں۔
  - **English Reference:** *Record exactly what patient says and circle all parts of response which were prompted.*

#### Specific Questions / Prompts:
- **[judg-1]**
  - **Target Script:** کیا شخص نے بتایا کہ وہ ٹریفک کو دیکھے گا؟
  - **English Reference:** *Did person indicate that they would look for traffic?*
- **[judg-2]**
  - **Target Script:** کیا شخص نے حفاظت کے لیے کوئی اور طریقہ یا احتیاط بتائی؟
  - **English Reference:** *Did person make any additional safety proposals?*

#### How to Administer:
1. Read the scenario. If the person gives an incomplete response that does not address both parts of the answer, use the prompt: “Is there anything else you would do?”
2. Record exactly what the person says, and mark which parts of the response were prompted.

#### Scoring:
- Each question: Yes = 2; Yes, prompted = 1; No = 0. Maximum 4.

#### Scoring Options (Normal view symbols):

| Value | Verdict | Normal-view Symbol |
|:---|:---|:---|
| 2 | Yes | Circle |
| 1 | Yes, prompted | Diamond |
| 0 | No | Square |
| — | Did not attempt | Triangle |

> Normal view shows these shapes in place of the verdict words, so nothing on screen reads as right or wrong to the patient. Scoring view shows the words.

---

### Task 6: Shopping list — recall (`mem-recall`)
- **Domain:** MEMORY | **Max Score:** 8
- **Sheet Item Number:** 1 | **Rail Label:** Memory

#### Spoken Administration Script:
- **[recall-script]**
  - **Target Script:** اب ہم دکان پر پہنچ گئے ہیں۔ کیا آپ کو یاد ہے کہ ہمیں کون سی چیزیں خریدنی تھیں؟
  - **English Reference:** *We have just arrived at the shop. Can you remember the list of groceries we need to buy?*

#### Instructions & Guidance Notes:
- **[recall-sub]**
  - **Target Script:** اگر شخص فہرست میں سے کوئی چیز یاد نہ کر سکے تو کہیں: "پہلی چیز چائے تھی"
  - **English Reference:** *Prompt: If person cannot recall any of the list, say “The first one was ‘tea’.” (Score 2 points each for any item recalled which was not prompted – use only ‘tea’ as a prompt.)*

#### Recalled Items (2 points each — Max 8):

| # | String Key | Target Word | English Reference | Prompt Allowed |
|:---|:---|:---|:---|:---|
| 1 | `w-tea` | **چائے** | Tea | Yes — “The first one was ‘tea’.” |
| 2 | `w-oil` | **کھانا پکانے کا تیل** | Cooking Oil | No |
| 3 | `w-eggs` | **انڈے** | Eggs | No |
| 4 | `w-soap` | **صابن** | Soap | No |

> In **Normal view** the four labels are concealed and read `Item 1`–`Item 4`, so the recall stays uncued for the patient. **Scoring view** names them in English and Urdu.

#### How to Administer:
1. Ask for the shopping list. If the person cannot recall any of the list, say “The first one was ‘tea’.” Use only ‘tea’ as a prompt.

#### Scoring:
- 2 points for each item recalled that was not prompted. Tea scores 0 once prompted. Maximum 8.

#### Scoring Options (Normal view symbols):

| Value | Verdict | Normal-view Symbol |
|:---|:---|:---|
| 2 | Recalled | Circle |
| 0 | Recalled after prompt (first item only) | Diamond |
| 0 | Not recalled | Square |
| — | Did not attempt | Triangle |

> Normal view shows these shapes in place of the verdict words, so nothing on screen reads as right or wrong to the patient. Scoring view shows the words.

---

### Task 7: Animal naming (`lang-animals`)
- **Domain:** LANGUAGE | **Max Score:** 8
- **Sheet Item Number:** 6 | **Rail Label:** Language

#### Spoken Administration Script:
- **[anim-script]**
  - **Target Script:** میں آپ کو ایک منٹ کا وقت دوں گا۔ اس ایک منٹ میں، آپ جتنے مختلف جانوروں کے نام بتا سکتے ہیں، بتائیں۔ دیکھتے ہیں کہ آپ ایک منٹ میں کتنے مختلف جانوروں کے نام بتا سکتے ہیں۔
  - **English Reference:** *I am going to time you for one minute. In that one minute, I would like you to tell me the names of as many different animals as you can. We’ll see how many different animals you can name in one minute.*

#### Instructions & Guidance Notes:
- **[anim-sub1]**
  - **Target Script:** (ضرورت پڑنے پر ہدایات دوبارہ دہرائیں۔)
  - **English Reference:** *(Repeat instructions if necessary.)*
- **[anim-sub2]**
  - **Target Script:** اس حصے کا زیادہ سے زیادہ اسکور 8 ہے۔ اگر شخص ایک منٹ سے کم وقت میں 8 مختلف جانوروں کے نام بتا دے تو مزید جاری رکھنے کی ضرورت نہیں۔
  - **English Reference:** *Maximum score for this item is 8. If person names 8 new animals in less than one minute there is no need to continue.*

#### Timing & Entry:
- **Time limit:** 60 seconds. The timer starts on the first word entered.
- **Entry:** each animal is typed and committed with space or Enter; the target-language keyboard is accepted and each chip is rendered in `.nastaliq` with right-to-left isolation.
- **Exclusions:** click a word to drop it from the count (repetitions, non-animals). Only valid words count, to a maximum of 8.

#### How to Administer:
1. Time one minute. Type each animal and press space or Enter — the timer starts on the first word. Repeat the instructions if necessary.
2. Click a word to exclude it from the count (repeats, non-animals).

#### Scoring:
- One point per different animal, to a maximum of 8. If the person names 8 new animals in less than one minute there is no need to continue.

---

## Clinical Administration & Scoring Guidelines

These guidelines are reproduced from `TASK_GUIDANCE` in the HTML and specify exact administration rules and clinical scoring criteria. They are clinician-facing and are presented in English only — they are never read to the patient.

### `mem-register` — Shopping list — registration
- **How to administer:**
  - *Read the list aloud, then ask the person to repeat it. Ask for the list three times.*
  - *If the person did not repeat all four words, repeat the list until the person has learned them and can repeat them, or up to a maximum of five times.*
  - *Record how many presentations were needed. The list is recalled at item 1 (Recall), after the judgment task.*
- **Scoring:**
  - *Not scored. Recall of the four items is scored later, 2 points each, to a maximum of 8.*

### `vis-body` — Body parts
- **How to administer:**
  - *Ask each part in turn and mark it. Correct = 1.*
  - *Once the person correctly answers 5 parts, do not continue — the maximum score is 5.*
- **Scoring:**
  - *One point per correct part, capped at 5. Parts left unmarked after the cap is reached are recorded as not administered.*

### `prax-hands` — Alternating hand movements
- **How to administer:**
  - *Demonstrate: one hand in a fist, the other palm down on the table — alternate simultaneously.*
  - *Then have the person do it with you, then keep going at the same pace for about 10 seconds. Demonstrate at a moderate walking pace.*
- **Scoring:**
  - *Normal = 2 (very few if any errors; self-corrected, progressively better; good maintenance; only very slight lack of synchrony between hands). Partially adequate = 1 (noticeable errors with some attempt to self-correct; some attempt at maintenance; poor synchrony). Failed = 0 (cannot do the task; no maintenance; no attempt whatsoever).*

### `draw-cube` — Cube copy
- **How to administer:**
  - *Show the cube (on the back of the sheet, or with Show patient) and ask the person to draw it exactly as it looks to them.*
  - *Photograph or scan the drawing for the record.*
- **Scoring:**
  - *Yes = 1 for each: a picture based on a square; all internal lines present; all external lines present. Maximum 3.*

### `judg-road` — Crossing the road
- **How to administer:**
  - *Read the scenario. If the person gives an incomplete response that does not address both parts of the answer, use the prompt: “Is there anything else you would do?”*
  - *Record exactly what the person says, and mark which parts of the response were prompted.*
- **Scoring:**
  - *Each question: Yes = 2; Yes, prompted = 1; No = 0. Maximum 4.*

### `mem-recall` — Shopping list — recall
- **How to administer:**
  - *Ask for the shopping list. If the person cannot recall any of the list, say “The first one was ‘tea’.” Use only ‘tea’ as a prompt.*
- **Scoring:**
  - *2 points for each item recalled that was not prompted. Tea scores 0 once prompted. Maximum 8.*

### `lang-animals` — Animal naming
- **How to administer:**
  - *Time one minute. Type each animal and press space or Enter — the timer starts on the first word. Repeat the instructions if necessary.*
  - *Click a word to exclude it from the count (repeats, non-animals).*
- **Scoring:**
  - *One point per different animal, to a maximum of 8. If the person names 8 new animals in less than one minute there is no need to continue.*

### Instrument-wide Rules:
- **`rule-body-cap`**
  - **English Guideline:** *Once the person correctly answers 5 parts of the body question, do not continue — the maximum score is 5. Remaining parts are recorded as not administered.*
- **`rule-recall-prompt`**
  - **English Guideline:** *Use only ‘tea’ as a prompt. An item recalled after prompting scores 0; items recalled unprompted score 2 each.*
- **`rule-animals-cap`**
  - **English Guideline:** *Maximum score for animal naming is 8. If the person names 8 new animals in less than one minute there is no need to continue.*
- **`rule-judgment-prompt`**
  - **English Guideline:** *If the response is incomplete and does not address both parts of the answer, prompt once with “Is there anything else you would do?” and mark which parts were prompted.*
- **`rule-record-verbatim`**
  - **English Guideline:** *Record exactly what the patient says for the road-crossing item, including the parts that were prompted.*
- **`rule-patient-surface`**
  - **English Guideline:** *The patient screen presents the cube only. It never shows scores, marks or identity. Exit with Esc or the corner control.*

---

## Appendix: Complete Translation Dictionary

Below is the complete dictionary of string keys defined for **Urdu (`ur`)** in the RUDAS HTML content pack, in source order, paired with the English reference line.

| String Key | Target Script Translation | English Reference Gloss |
|:---|:---|:---|
| `reg-script` | میں چاہتا ہوں کہ آپ تصور کریں کہ ہم خریداری کے لیے جا رہے ہیں۔ یہ خریداری کی چیزوں کی ایک فہرست ہے۔ میں چاہتا ہوں کہ آپ ان چیزوں کو یاد رکھیں جو ہمیں دکان سے خریدنی ہیں۔ تقریباً 5 منٹ بعد جب ہم دکان پہنچیں گے تو میں آپ سے پوچھوں گا کہ ہمیں کیا خریدنا ہے۔ آپ کو یہ فہرست یاد رکھنی ہے۔ | I want you to imagine that we are going shopping. Here is a list of grocery items. I would like you to remember the following items which we need to get from the shop. When we get to the shop in about 5 mins. time I will ask you what it is that we have to buy. You must remember the list for me. |
| `reg-repeat` | براہِ کرم یہ فہرست میرے لیے دہرائیں۔ | Please repeat this list for me. |
| `reg-sub1` | (شخص سے فہرست 3 مرتبہ دہرانے کو کہیں۔) | (Ask person to repeat the list 3 times.) |
| `reg-sub2` | اگر شخص چاروں الفاظ نہ دہرا سکے تو فہرست دوبارہ سنائیں، یہاں تک کہ وہ انہیں یاد کر لے اور دہرا سکے، یا زیادہ سے زیادہ پانچ مرتبہ تک۔ | (If person did not repeat all four words, repeat the list until the person has learned them and can repeat them, or, up to a maximum of five times.) |
| `body-script` | میں آپ سے جسم کے مختلف حصوں کی پہچان کرنے کے لیے کہوں گا اور انہیں دکھانے کے لیے بھی کہوں گا۔ | I am going to ask you to identify/show me different parts of the body. |
| `body-sub` | — | (Correct = 1). Once the person correctly answers 5 parts of this question, do not continue as the maximum score is 5. |
| `body-1` | اپنا دایاں پاؤں دکھائیں۔ | Show me your right foot. |
| `body-2` | اپنا بایاں ہاتھ دکھائیں۔ | Show me your left hand. |
| `body-3` | اپنے دائیں ہاتھ سے اپنے بائیں کندھے کو چھوئیں۔ | With your right hand touch your left shoulder. |
| `body-4` | اپنے بائیں ہاتھ سے اپنے دائیں کان کو چھوئیں۔ | With your left hand touch your right ear. |
| `body-5` | میرا بایاں گھٹنا کون سا ہے؟ | Which is my left knee? |
| `body-6` | میری دائیں کہنی کون سی ہے؟ | Which is my right elbow? |
| `body-7` | اپنے دائیں ہاتھ سے میری بائیں آنکھ کی طرف اشارہ کریں۔ | With your right hand indicate/point to my left eye. |
| `body-8` | اپنے بائیں ہاتھ سے میرے بائیں پاؤں کی طرف اشارہ کریں۔ | With your left hand indicate/point to my left foot. |
| `praxis-script` | میں آپ کو اپنے ہاتھوں سے ایک حرکت/مشق دکھاؤں گا۔ میں چاہتا ہوں کہ آپ مجھے غور سے دیکھیں اور وہی کریں جو میں کرتا ہوں۔ جب میں یہ حرکت کروں تو آپ بھی ویسا ہی کریں۔ (ایک ہاتھ مٹھی میں رکھیں اور دوسرا ہاتھ میز پر ہتھیلی کے بل رکھیں، پھر دونوں کی حالت باری باری ایک ساتھ تبدیل کریں۔) اب میرے ساتھ کریں۔ اب میں چاہتا ہوں کہ آپ یہی حرکت اسی رفتار سے کرتے رہیں جب تک میں آپ کو رکنے کے لیے نہ کہوں، تقریباً 10 سیکنڈ تک۔ (درمیانی رفتار سے چلنے کی رفتار کے مطابق مظاہرہ کریں۔) | I am going to show you an action/exercise with my hands. I want you to watch me and copy what I do. Copy me when I do this . . . (One hand in fist, the other palm down on table - alternate simultaneously.) Now do it with me. Now I would like you to keep doing this action at this pace until I tell you to stop - approximately 10 seconds. (Demonstrate at moderate walking pace). |
| `cube-script` | آپ سے گزارش ہے کہ اس تصویر کو بالکل ویسا ہی بنائیں جیسی یہ آپ کو نظر آ رہی ہے۔ | Please draw this picture exactly as it looks to you. |
| `cube-sub` | — | (Show cube on back of page). (Yes = 1) |
| `cube-1` | کیا مریض نے مربع کی بنیاد پر شکل بنائی ہے؟ | Has person drawn a picture based on a square? |
| `cube-2` | کیا شخص کی بنائی ہوئی شکل میں تمام اندرونی لکیریں موجود ہیں؟ | Do all internal lines appear in person’s drawing? |
| `cube-3` | کیا شخص کی بنائی ہوئی شکل میں تمام بیرونی لکیریں موجود ہیں؟ | Do all external lines appear in person’s drawing? |
| `judg-script` | آپ ایک مصروف سڑک کے کنارے کھڑے ہیں۔ وہاں نہ پیدل چلنے والوں کے لیے کراسنگ ہے اور نہ ٹریفک لائٹ۔ مجھے بتائیں کہ آپ سڑک کے دوسری طرف محفوظ طریقے سے جانے کے لیے کیا کریں گے۔ | You are standing on the side of a busy street. There is no pedestrian crossing and no traffic lights. Tell me what you would do to get across to the other side of the road safely. |
| `judg-sub1` | اگر مریض کا جواب نامکمل ہو اور سوال کے دونوں حصوں کا جواب نہ دیتا ہو تو پوچھیں: "کیا آپ اور کچھ کریں گے؟" | If person gives incomplete response that does not address both parts of answer, use prompt: “Is there anything else you would do?” |
| `judg-sub2` | شخص جو کچھ کہے اسے لفظ بہ لفظ لکھیں۔ | Record exactly what patient says and circle all parts of response which were prompted. |
| `judg-1` | کیا شخص نے بتایا کہ وہ ٹریفک کو دیکھے گا؟ | Did person indicate that they would look for traffic? |
| `judg-2` | کیا شخص نے حفاظت کے لیے کوئی اور طریقہ یا احتیاط بتائی؟ | Did person make any additional safety proposals? |
| `recall-script` | اب ہم دکان پر پہنچ گئے ہیں۔ کیا آپ کو یاد ہے کہ ہمیں کون سی چیزیں خریدنی تھیں؟ | We have just arrived at the shop. Can you remember the list of groceries we need to buy? |
| `recall-sub` | اگر شخص فہرست میں سے کوئی چیز یاد نہ کر سکے تو کہیں: "پہلی چیز چائے تھی" | Prompt: If person cannot recall any of the list, say “The first one was ‘tea’.” (Score 2 points each for any item recalled which was not prompted – use only ‘tea’ as a prompt.) |
| `anim-script` | میں آپ کو ایک منٹ کا وقت دوں گا۔ اس ایک منٹ میں، آپ جتنے مختلف جانوروں کے نام بتا سکتے ہیں، بتائیں۔ دیکھتے ہیں کہ آپ ایک منٹ میں کتنے مختلف جانوروں کے نام بتا سکتے ہیں۔ | I am going to time you for one minute. In that one minute, I would like you to tell me the names of as many different animals as you can. We’ll see how many different animals you can name in one minute. |
| `anim-sub1` | (ضرورت پڑنے پر ہدایات دوبارہ دہرائیں۔) | (Repeat instructions if necessary.) |
| `anim-sub2` | اس حصے کا زیادہ سے زیادہ اسکور 8 ہے۔ اگر شخص ایک منٹ سے کم وقت میں 8 مختلف جانوروں کے نام بتا دے تو مزید جاری رکھنے کی ضرورت نہیں۔ | Maximum score for this item is 8. If person names 8 new animals in less than one minute there is no need to continue. |
| `w-tea` | چائے | Tea |
| `w-oil` | کھانا پکانے کا تیل | Cooking Oil |
| `w-eggs` | انڈے | Eggs |
| `w-soap` | صابن | Soap |

### Keys Without a Urdu Translation

These keys are defined in `STR.en` only; the assessment renders the English line alone where they appear.

- `body-sub` — *(Correct = 1). Once the person correctly answers 5 parts of this question, do not continue as the maximum score is 5.*
- `cube-sub` — *(Show cube on back of page). (Yes = 1)*

---

*Generated from `Assessments/RUDAS Assessment -Aether- V3 - standalone.html` — 32 of 34 content strings are translated into Urdu.*
