# LLM-Based Automation Agent  

## Overview  
This project is an automation agent that processes diverse operational and business tasks using an LLM (GPT-4o-Mini). The agent accepts plain-English instructions, executes multi-step operations, and produces verifiable outputs. It is designed to integrate into a Continuous Integration (CI) pipeline to streamline processes at DataWorks Solutions.  

## Features  
- Task execution powered by GPT-4o-Mini  
- Secure and controlled file operations  
- API-based task execution and verification  
- Multi-step automation for logs, reports, and code artifacts  
- Compliance with security constraints (no file deletions or external data access)  

## Pre-requisites
- Docker
- AI Proxy Token

## Installation & running


1. Clone the repository:
```sh
git clone https://github.com/kethu-seshu/TDS_pro1.git
cd TDS_pro1
```
2. Install dependencies:
```sh
pip install -r requirements.txt
```

3. Setup Environment Variables

Create a .env file in the project root with 
>AIPROXY_TOKEN=your_token_here

4. Run
```sh
python run.py
```

