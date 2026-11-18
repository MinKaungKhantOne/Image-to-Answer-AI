# Image-to-Answer AI System

An AI-powered image-based information retrieval system that extracts text from images using Microsoft's TrOCR, searches for relevant information on the internet using Exa Search, and generates answers or summaries using Qwen LLM.

## Overview

This project integrates Optical Character Recognition (OCR), Large Language Models (LLMs), and web search tools into a single AI-powered pipeline.

The system takes an image containing text as input, extracts the text using Microsoft's pretrained TrOCR model, and passes the extracted text to Qwen LLM. Qwen generates relevant search queries and uses the Exa Search tool to retrieve information from the internet. It then analyzes the collected search results and generates a final answer or summary based on the retrieved information.

## How It Works

The system follows an automated pipeline:

1. **Image Input:** Takes an image containing text as input.
2. **Text Extraction:** Uses Microsoft's TrOCR model to recognize and extract text from the image.
3. **Query Generation:** Qwen LLM analyzes the extracted text and generates relevant search queries.
4. **Web Search:** Uses the Exa Search tool to search the internet and collect relevant information.
5. **Information Analysis:** Qwen processes and analyzes the retrieved search results.
6. **Answer Generation:** Generates a relevant answer or summarizes the collected information.
7. **Final Output:** Displays the extracted text and the generated answer to the user.
