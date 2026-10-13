# EXP-6
# Role-Based and Negative Prompting Experiment

## Aim
To demonstrate how role-based prompting and negative prompting influence large language model outputs.

## Problem Statement
Generate responses to the question "Explain the importance of exercise" under three conditions:
1. Baseline prompting
2. Role-based prompting
3. Role-based prompting with negative constraints

## Technologies Used
- Python
- Google Gemini API
- Google Gen AI SDK
- python-dotenv

## Methodology
1. Define the same core question for all prompts.
2. Create baseline, role-based, and role-plus-negative prompts.
3. Send all prompts to the same model using the same temperature.
4. Collect and print the generated responses.
5. Compare tone, vocabulary, and adherence to negative constraints.

## Expected Results
The role-based prompt may produce a more motivational tone. The negative prompt should avoid medical jargon and references to weight loss. Actual responses must be inspected to verify constraint adherence.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Configure the Gemini API key securely.
3. Run: `python experiment.py`

## Note
A valid API key, an available model, and sufficient API quota are required. Temporary server errors may require retrying later.
