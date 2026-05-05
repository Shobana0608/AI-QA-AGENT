# 🤖 Local AI QA Agent

> Free • Local • Private — No API keys needed!

## Built With
- Langflow
- Ollama  
- qwen2.5:latest

## Setup in 4 Steps

### 1. Install Ollama
Download from ollama.com
```bash
ollama pull qwen2.5
ollama pull nomic-embed-text
```

### 2. Install Langflow
```bash
conda create -n qaagent python=3.11 -y
conda activate qaagent
pip install langflow
python -m langflow run
```

### 3. Import Flow
- Open localhost:7860
- Click "Import" → upload `qa-agent-flow.json`

### 4. Start Testing!
Open Playground and ask:
- Generate test cases for a login page
- Triage this bug: ...
- Analyze this user story: ...

## What It Can Do
- ✅ Test Case Generation
- ✅ Requirements Gap Analysis
- ✅ User Story Elaboration
- ✅ Bug Severity Triage
- ✅ Automation Strategy
- ✅ Security Testing (OWASP)
- ✅ API & Integration Testing

## Cost
$0.00 forever 🎉
