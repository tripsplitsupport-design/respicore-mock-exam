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

## Deployment

GitHub Pages deploys automatically on pushes to `main` using `.github/workflows/pages.yml`. `index.html` loads the additional question bank from `practice2.js`.
