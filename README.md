# RespiCore — Singapore Respiratory Care Mock Examination

**Live website:** https://tripsplitsupport-design.github.io/respicore-mock-exam/

Responsive practice site for respiratory care exam preparation, using original single-best-answer questions based on NUS/NUH teaching materials, Egan’s *Fundamentals of Respiratory Care*, the Intensive Care Foundation handbook, and Singapore MOH respiratory care competencies (2022).

## Exam papers

| Paper | Questions | Difficulty | Time limit | Content |
| --- | ---: | --- | ---: | --- |
| Practise Exam 1 | 100 | Mixed | 120 minutes | Original full-length mock examination |
| Practise Exam 2 | 100 | Mixed | 120 minutes | 100 additional original questions (30 easy, 35 intermediate, 35 hard) |
| Practise Exam 3 | 100 | Mixed | 120 minutes | 50 questions reused from Exam 1 and 50 from Exam 2; question/option order shuffled |
| Practise Exam 4 | 100 | Mixed | 120 minutes | The other 50 from Exam 1 and 50 from Exam 2; question/option order shuffled |
| Foundation | 50 | Easy | 60 minutes | Core knowledge |
| Clinical Application | 50 | Intermediate | 60 minutes | Clinical application |
| Advanced Reasoning | 50 | Hard | 60 minutes | Calculations and higher-order reasoning |

350 distinct original questions; 550 practice question appearances across all papers, with 84 unique calculation questions. Exams 3 and 4 repeat the original question stems from Exams 1 and 2, with answer options reordered and the correct-answer index recalculated.

## Features

- 100-question timed exams (120 minutes), 50-question timed exams (60 minutes), and untimed practice
- Question navigator, mark-for-review, progress indicator and in-exam calculator
- Autosaved progress per device/browser using local storage
- Final scores and question-by-question answer reviews with explanations and source notes
- Topic breakdown, retake, print and CSV results export
- Works on iPhone, Android, iPad, Windows and Mac with modern browsers
- No login required

This is independent educational practice material, **not an official NUS exam**. Results are stored locally in the browser, not centrally collected. Clearing site data or changing devices may remove local progress.

## Source-based mock exams added on 18 November 2026

| Exam | Questions | Time limit | Source and handling |
|---|---:|---:|---|
| **Mock Exam 1** | 100 | **120 minutes** | Numbered first MCQ paper in `Mock exam preparation .pdf` (PDF pages 13 back to 1) |
| **Mock Exam 2** | 100 | **120 minutes** | 96 intact items from the second printed questionnaire in `Mock exam preparation .pdf`, plus four complete items from `vims question and answer.pdf` |

The printed question stems and answer choices were transcribed without changing their option order. The mock exams **enforce a 2-hour timer** and use the same scoring, answer review, calculation support, result export and mobile-friendly user interface as other papers.

Answer keys, PDF page numbers, any clinical caveats, the recorded basis for answer selection and topic tags are stored in [`mock-answer-audit.json`](./mock-answer-audit.json). Question text and answer options are stored in [`mock-exams.js`](./mock-exams.js). Twelve items have an explanatory source caveat. For Mock Exam 2, question 79, both A and D are scored as correct because the wording makes them essentially equivalent.

The accompanying `vims question and answer.pdf` includes many recollection notes with incomplete stems or missing options; these cannot be reproduced exactly as four-option MCQs without fabricating content, so they have not been invented as complete examination items.

**Current website total:** 9 exam papers; 200 source-transcribed Mock Exam questions plus 550 earlier practice-paper question appearances (750 question appearances overall). The earlier practice bank contains 350 original questions.

## Deployment

GitHub Pages deploys automatically on pushes to `main` using `.github/workflows/pages.yml`. `index.html` loads the additional question bank from `practice2.js`.
