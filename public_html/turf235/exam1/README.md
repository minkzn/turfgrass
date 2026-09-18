# TURF 235 Exam 1 Study Site

## Contents
- `study-guide.html` — searchable/printable study guide
- `quiz.html` — 580-question quiz, 10 at a time
- `questions.json` — the question bank; the union of all nine module banks (M1-M9)
- `styles.css`

## Question distribution
Each module's questions carry over 1:1 from its own module bank (`../M#/questions.json`), so the distribution naturally reflects how much well-formed material each module supports — nothing here is padded to a fixed count.

- M1: 75
- M2: 76
- M3: 70
- M4: 66
- M5: 67
- M6: 58
- M7: 73
- M8: 45
- M9: 50

## Accuracy / source rules
- Each question is modeled on the real Canvas quiz style for its module (verified against the instructor's actual M1-M5 and M7 quizzes) and sourced from that module's own course PDFs, with a curated slice of textbook enrichment on the same topics where it adds real depth.
- Every question reveals its source after submission.
- M6's Overview cites a 9th-edition textbook page range not included in the source material; M6 questions use only the uploaded M6 course PDFs, with no textbook enrichment.

## Quiz behavior
- 10 questions per batch
- correct answers retire
- missed answers cycle to the back
- progress saved per module filter in localStorage
