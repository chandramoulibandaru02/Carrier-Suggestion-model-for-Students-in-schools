Student Subject Score Calculator
Project Overview

This project is designed to help educators or students evaluate performance across multiple subjects using manual input of answers for a set of multiple-choice questions (MCQs). The system calculates scaled scores out of 100 for each subject and tracks wrongly answered questions for revision purposes.

This can be used for 10th-grade student assessments or any other exam scenario where subject-wise performance analysis is required.

Features

Supports multiple subjects (e.g., Maths, Physics, Chemistry, Biology, English, History, Geography).

Each subject has 5 questions by default, with each question carrying 5 marks.

Scales the score for each subject to 100.

Tracks wrong answers for each subject for revision.

Assigns each subject score to unique variables (d, e, f, g, h, i, j) for easy reference in further calculations or analytics.

How the Code Works

The program stores MCQs for each subject in a dictionary: questions = { "Subject": [(Question, Options, CorrectAnswer), ...] }.

The program loops through each subject and displays its questions one by one.

Users enter their answer manually by typing a number corresponding to their choice.

The program calculates the score for each subject, scales it to 100, and stores it in a variable (d for Maths, e for Physics, etc.).

Wrong answers are stored and displayed at the end for revision.
