# Contributing to Cpp Learn

Thanks for helping make C++ easier to learn. Contributions can be lessons, exercises, small projects, corrections, or clearer explanations.

## Before you start

- Check existing issues and pull requests to avoid duplicate work.
- For a substantial new topic or a change to the repository structure, open an issue first and describe your idea.
- Small fixes, such as typos or corrections to an example, can go straight to a pull request.
- Please follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## What to contribute

- Beginner-friendly explanations with a short, runnable example.
- Exercises with clear instructions and, where useful, a separate sample solution.
- Corrections to code, terminology, formatting, or broken commands.
- Small command-line projects that demonstrate concepts from the learning roadmap.

Do not include copyrighted material you do not have permission to share, secrets, or personal data.

## Writing and code guidelines

1. Use plain language and define new terms when they first appear.
2. Keep each lesson focused on one topic. Explain *why* an example works, not only what it prints.
3. Prefer standard C++17 unless a lesson explicitly teaches a newer standard. State the required version when applicable.
4. Keep examples self-contained and use descriptive names. Avoid platform-specific dependencies unless they are the subject of the lesson.
5. Show how to compile and run new examples. For GCC or Clang, a useful starting command is:

   ```bash
   g++ -std=c++17 -Wall -Wextra -pedantic example.cpp -o example
   ./example
   ```

6. Check the example with the stated compiler and include expected output when it helps the learner. If output varies by system, explain that variation.
7. Do not add generated executables, build directories, or temporary files.

The README suggests `lessons/`, `exercises/`, and `projects/` for future content. If a directory does not exist yet, create the relevant one as part of your contribution.

## Submit a pull request

1. Fork the repository and create a branch for your change.
2. Add or update the content and any links needed to find it from the README.
3. Compile and run any changed C++ examples; review the Markdown preview.
4. Open a pull request explaining what changed, who it helps, and how you checked it.
5. Respond to review comments and keep discussion respectful.

There is no required pull request template or automated test suite yet. A clear description and a working example are enough to get started.

## Questions

Open a GitHub issue for questions about lessons or contribution ideas. For conduct concerns, use the private reporting instructions in [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) instead of a public issue.
