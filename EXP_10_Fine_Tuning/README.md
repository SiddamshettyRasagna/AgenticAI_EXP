# EXP10 - Fine-Tuning for Domain Adaptation

## Objective

This experiment demonstrates domain adaptation of a language model using a domain-specific dataset.

## Domain

College and Student Information.

## Technologies

- Python
- Ollama
- Llama 3.2
- JSONL Dataset

## Workflow

Dataset → Model Adaptation → Specialized Model → Evaluation

## Description

A small domain-specific dataset is created containing college and student-related information. The model is adapted using these examples and evaluated using new questions from the same domain.

## Files

- `dataset.jsonl` - Contains domain-specific training examples.
- `fine_tuning.py` - Python program for the experiment.
- `README.md` - Documentation of the experiment.

## Expected Result

The adapted model should provide more domain-specific responses compared with a general model.
