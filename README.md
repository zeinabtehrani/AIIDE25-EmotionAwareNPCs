# AIIDE25-EmotionAwareNPCs

This repository contains the source code for the AIIDE-25 paper:

"Emotion-Aware Non-Player Characters for Multilingual Mental Health Games" 
 Author: Zeinab Tehrani  
 Submitted to: [AIIDE-25 Conference](https://aiide.org)
 Status: Paper submitted

## Overview

We present a multilingual, emotion-aware AI system designed to enhance narrative-driven mental health games through supportive NPC dialogue. The system detects user emotion in Persian, Arabic, French, and English, and responds with rule-based supportive dialogue tailored to NPC "personalities."

## Features

- Emotion classification using HuggingFace Transformers
- Language translation using `deep-translator`
- Rule-based, personality-driven NPC replies
- Multilingual text input (including right-to-left scripts)
- Designed for educational and therapeutic games

## File Structure

| File | Description |
|------|-------------|
| `AIIDE25.ipynb` | Full Colab notebook with step-by-step development |
| `aiide25.py` | Script version of the system for better readability |
| `requirements.txt` | Required Python libraries |
| `LICENSE` | MIT license for open usage (add this next if not done) |


##  Setup

Clone this repo and install dependencies:

```bash
git clone https://github.com/zeinabtehrani/AIIDE25-EmotionAwareNPCs.git
cd AIIDE25-EmotionAwareNPCs
pip install -r requirements.txt


##  Technologies
Python 3.10
HuggingFace transformers
deep-translator 
pandas, matplotlib, torch


