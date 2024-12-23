# AI-spell-checker-project
This project focuses on creating an advanced Tamil Spell and Grammar Checker that integrates rule-based algorithms and machine learning techniques. It aims to improve writing accuracy by addressing common spelling and grammatical errors unique to the Tamil language

# Overview
This project implements a Tamil grammar checker that takes ungrammatical Tamil sentences as input and provides grammatically corrected sentences as output. It uses an LSTM-based Seq2Seq model with an attention mechanism for better accuracy in handling long sentences and complex structures.

# Project Components



# Usage
Data Preparation

Save your dataset in Excel format with the following columns:

1) Ungrammatical Statement: Ungrammatical Tamil sentences.

2) Standard Tamil: Correct grammatical Tamil sentences.

Place your dataset in the project directory and update the file path in the script.


# Model Architecture

The grammar checker uses a Seq2Seq architecture with:

Encoder: Converts input sequences into a fixed-length context vector.

Decoder: Generates corrected sentences from the context vector.

Embedding layers: Learn sentence representations.

LSTM units: Capture temporal dependencies.


# Dataset

* The dataset consists of Tamil sentences with grammatical errors and their corrected versions. Example:

Ungrammatical Statement: நான் நேற்று பாடம் படிக்கிறேன்.

Standard Tamil: நான் நேற்று பாடம் படித்தேன்.

Ensure your dataset has sufficient examples for effective training.

