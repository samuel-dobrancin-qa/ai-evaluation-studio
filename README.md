# AI Evaluation Studio

A structured evaluation tool for assessing AI-generated 
responses across five quality dimensions. Built for QA 
engineers and AI quality specialists who need a repeatable, 
documented methodology for evaluating AI products.

**Live:** https://ai-evaluation-studio.vercel.app

---

## What it does

Select the AI product you're testing, paste the question 
you asked and the response you got, and the tool 
automatically evaluates it across five dimensions using 
Claude as an independent judge.

You can override any score with your own judgment — the 
human-in-the-loop element is intentional. AI assists, 
you decide.

Run multiple evaluations in one session. When you're done, 
export a complete structured report ready for GitHub or 
a test report document.

---

## Evaluation dimensions

| Dimension | What it measures |
|---|---|
| Accuracy | Are factual claims correct and verifiable? |
| Hallucination | Does it invent unsupported details or citations? |
| Completeness | Does it cover the important angles? |
| Uncertainty Calibration | Does confidence match actual certainty? |
| Relevance | Does it actually address what was asked? |

Each dimension scored 0–3. Overall score drives a 
verdict from Reject through Reliable.

---

## AI products supported

Microsoft Copilot · Google Gemini · ChatGPT (GPT-4o) · 
Perplexity AI · Claude · Meta Llama · Mistral AI · Other

Each product loads specific evaluation context — 
Perplexity is evaluated differently than Copilot 
because they are different tools with different 
quality criteria.

---

## How to use

1. Enter your Anthropic API key (used only for evaluation, 
   never stored)
2. Select the AI product you tested
3. Paste your question and the AI's response
4. Click Run Evaluation
5. Review scores — override any with the sliders
6. Add more test cases to build a session
7. Export the full report when done

---

## Why this exists

Manual AI evaluation means copying responses between 
tabs, pasting into evaluation prompts, formatting 
findings by hand. This tool collapses that into one 
interface — paste once, evaluate instantly, export 
a structured report.

Built on the LLM-as-judge methodology used internally 
by AI labs to evaluate models at scale. Applied here 
as a practical tool for QA engineers doing manual 
AI product evaluation.

---

## Stack

HTML · CSS · Vanilla JS · Anthropic Claude API

---

## About

Samuel Dobrančin — Quality Engineer  
Building toward AI Quality Specialist roles.

[GitHub](https://github.com/samuel-dobrancin-qa) ·
[LinkedIn](https://linkedin.com/in/samuel-dobrancin-8a203a273) ·
[Live tool](https://ai-evaluation-studio.vercel.app)
