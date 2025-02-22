# AI Image Generator

## Overview
This software infers text into AI prompts to create images. It supports options to use ChatGPT and DeepSeek, processes `.srt` and `.txt` files, and automatically splits each text sentence into individual lines for AI inference. The output is an image file with random motion effects, which can be automatically imported into JianyingPro Drafts. Additional features include one-click translation, batch AI inference, image zoom, HD conversion, saving records, and image synthesis and cutting.

## Features
- Text Processing from `.srt` and `.txt` files
- AI Inference using ChatGPT and DeepSeek
- Random Image Motion Effects
- Automatic Import into JianyingPro Drafts
- One-Click Translation of Raw Images
- Batch AI Inference
- Image Zoom and HD Conversion
- Save Current Record
- Image Synthesis and Cutting
- Package as Executable

## Requirements
- Python 3.8+
- OpenAI API
- DeepSeek API
- JianyingPro API

## Installation
1. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
2. Run the application:
    ```bash
    python main.py
    ```

## Usage
- Place your `.srt` or `.txt` file in the `input` directory.
- Run the application and follow the prompts.
- Output images will be saved in the `output` directory and imported into JianyingPro Drafts.

## License
MIT License