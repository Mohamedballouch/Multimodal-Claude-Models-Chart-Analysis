# Multimodal Claude Models Chart Analysis

## Overview

We compare the following multimodal Large Language Models (LLMs):

- claude-3-5-sonnet
- claude-3-opus
- claude-3-sonnet

The project uses the Anthropic API to interact with these models and analyze their performance in extracting and interpreting data from financial charts.

## Requirements

- Python 3.x
- Libraries: anthropic, boto3, Pillow, matplotlib

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/multimodal-claude-analysis.git
   ```
2. Install the required packages:
   ```
   pip install anthropic boto3 Pillow matplotlib
   ```

## Usage

1. Set up your Anthropic API credentials.
2. Prepare your financial chart images.
3. Run the Jupyter notebook or Python script to perform the analysis.

## Key Findings

- Claude 3.5 Sonnet demonstrated superior accuracy in extracting exact values from complicated charts.
- Claude 3 Opus and Claude 3 Sonnet showed some inaccuracies in data extraction.
- The models' performances varied based on the complexity of the questions and charts.

