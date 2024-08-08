# Mental Health Analysis ChatBot

## Overview

The **Mental Health Analysis ChatBot** is a research project focused on developing a conversational AI tool designed to support mental well-being. Utilizing advanced AI and Natural Language Processing (NLP) technologies, this chatbot aims to make mental health resources more accessible, particularly in regions with limited infrastructure. This initiative is timely given the increasing mental health challenges exacerbated by the COVID-19 pandemic.

## Objective

The primary objectives of this project are to:
- Develop a chatbot that can engage in informal conversations to understand users' mental health challenges.
- Provide supportive suggestions and facilitate access to mental health resources.
- Operate continuously, offering 24/7 assistance as a complementary tool to traditional mental health interventions.

## Background and Motivation

Mental health issues are often stigmatized, creating barriers to seeking professional help. Traditional therapies are not always accessible, especially in underserved regions. Chatbots can bridge this gap by offering an initial layer of support, making mental health resources more available and reducing the stigma associated with seeking help.

## Dataset Description

The chatbot was trained using diverse datasets:
- **DR (Depression Recognition)**: Reddit posts focused on detecting depression.
- **Dreddit (Stress Detection)**: Reddit conversations for identifying stress.
- **SAD (Stress Cause Detection)**: SMS conversations for identifying stress triggers.
- **Irf (Interpersonal Risk Factors)**: Reddit discussions on interpersonal challenges.
- **MultiWD (Wellness Dimensions)**: Reddit conversations related to wellness.

These datasets were selected and evaluated by mental health experts to ensure relevance and authenticity.

## Methodology

The methodology includes:
1. **Data Collection and Preprocessing**: Gathering and merging datasets for training.
2. **Model Selection**: Using the Llama 2 7B model with a focus on Question Answering (QA).
3. **Fine-Tuning**: Employing QLoRA and bitsandbytes configurations to enhance model performance.
4. **Training and Evaluation**: Training the model and conducting rigorous evaluation for accuracy and efficiency.

## Evaluation

The evaluation phase involved:
- **Response Generation**: Testing the model’s ability to generate responses.
- **Correctness Evaluation**: Assessing classification accuracy and F1 scores.
- **Quality Evaluation**: Using metrics like ROUGE-L, BLEU, BERT Score, and BART Score.

**Results**:
- **Correctness Scores**: High performance in recognizing mental health issues.
- **Quality Scores**:
  - **ROUGE-L**: Indicated substantial content overlap with reference summaries.
  - **BLEU**: Showed n-gram overlap with scores ranging from 0.24 to 0.49.
  - **BERT Score**: Reflected significant semantic similarity with scores between 0.87 and 0.92.
  - **BART Score**: Provided relative benchmarks for summarization tasks.

## Conclusions

The chatbot demonstrated robust performance in both correctness and quality evaluations. It shows promise in providing effective mental health support through conversational interactions. The high accuracy and quality scores affirm its potential as a valuable tool in mental health care.

## Future Work

Future research should focus on:
- Expanding the chatbot’s capabilities with more complex intents and generative algorithms.
- Improving sentiment analysis by incorporating diverse thresholds and types.
- Enhancing adaptability to different cultural contexts and languages.
