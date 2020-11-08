---
title: "A-Level Note Taking System"
date: "2020-08-08 12:24"
---

### Core Values
* Notes should not cover lessons, but concepts as a whole
* Notes should be organised in multiple ways:
	* Their relation to the syllabus
	* The links between different concepts
	* Which lesson they occured in
* Notes should embed flashcards which are reviewed daily
	* See [[Writing Good Flashcards]]
* Rewriting notes should be prevented as much as possible
* Notes should be concise

### Notes should cover concepts
This is how notes should be organised:

```
subject/
	topics/
		concept1/
		concept2/
		concept3/
	lessons/
	syllabus/
```

* `subject` is the subject being studied.
* `topics` contain the different topics/concepts.
	* Concepts should be atomic, and describe one thing well instead of describing multiple things.
	* Each concept entry should contain attached worksheets and references to the relevant pages of the textbook.
	* If a topic has many sub-topics, it can be broken down into its own entry, named something like `Complex Numbers - Moivre's Theorem`.
* `lessons/`
	* Contains a record of what was taught in each lesson, as a link to the concept that was being discussed.
* `syllabus/`
	* Contains a breakdown of the entire course.
	* Every topic in the syllabus should hypothetically have a corresponding `topic` entry.

In order to achieve this, there are three €ý,€ý,entry templates:

- `topic.tmpl`
- `lessons.tmpl`
- `syllabus.tmpl`

### Rewriting notes should be prevented
The main way of review should be via Anki flashcards. The only reason notes should be rewritten is to add detail or make them more concise.

In the context of [[Elevate - Effective Note Taking]], the Learn step is writing the notes and reviewing the flashcards. Not rewriting the flashcards saves time for applying the knowledge learnt in past papers and the like.

### Daily Routine
The above can be thought of as a series of Albatross commands that I need to run every day:

```
albatross update school/a-level/subject/lessons
albatross update school/a-level/subject/topics/concept-covered
```
