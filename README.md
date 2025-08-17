---
title: Data Analyst Agent
emoji: 📊
colorFrom: blue
colorTo: green
sdk: docker
pinned: false
app_port: 7860
---

# TDS Data Analyst Agent

A powerful AI-driven data analysis API that processes various data formats, generates visualizations, and answers analytical questions using LLMs.

## Features
- Multi-format data support (CSV, Excel, JSON, etc.)
- Web scraping capabilities
- Automatic visualization generation
- LLM-powered analysis with Gemini API
- RESTful API interface

## Usage
Send POST requests to `/api` with your questions and data files.

## API Endpoints
- `POST /api` - Main analysis endpoint
- `GET /api` - Health check
- `GET /summary` - System diagnostics
