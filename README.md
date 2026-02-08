## Question Format

The DevOps quiz questions are stored in `data/questions.json` as an array named `questions`.

Each question follows this structure:

- `id`: Unique identifier for the question (e.g., Q1)
- `topic`: DevOps topic (e.g., Continuous Integration, Infrastructure as Code)
- `question`: The question text
- `options`: A list of multiple-choice answers
- `answerIndex`: Index of the correct answer (0-based)
- `explanation`: Explanation shown after answering

This structure allows easy filtering by topic and clear feedback for users.