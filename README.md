# Security+ Practice Test Generator

A simple system for generating and taking **CompTIA Security+ SY0-701** practice tests. 

To use it properly, you should understand the test structure, so make sure you familiarize yourself with the 5-modules structure.

The prompt allows you to target specific test domains for focused practice or generate a full mixed set for comprehensive review.

The repository contains:

* `test-engine.html` — reusable browser-based test runner
* `SY0-701.md` — instructs an AI model to produce practice tests for CompTIA Security+ SY0-701 

## Usage

1. Copy the generation prompt an LLM of your choice.
2. Request a test:

```text
Scope: Objective 4.1
Questions: 20
```

3. Save the generated output as a `.json` file.
4. Open `test-engine.html` in your browser.
5. Upload the JSON file.
6. Complete the test and review your results.

No server or installation is required.

## Goal

The generation prompt is designed to create difficult questions through **realistic Security+ reasoning**, not obvious distractors or answer-pattern clues.

It includes checks for:

* strong competing answers
* ambiguous questions
* structural answer clues
* conjunction and punctuation clues
* technical correctness
* official SY0-701 scope

## Notes

This project is intended for self-study.

It generates original practice questions and is not intended to reproduce real CompTIA exam questions. 
