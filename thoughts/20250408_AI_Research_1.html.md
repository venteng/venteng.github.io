---
layout: default
title: A Practical Guide to AI-Assisted Research
---

# Section 1 Writing

💬 *“AI is not replacing researchers — it’s empowering them to think deeper, move faster, and communicate better.”*

## AI Tools for Academic Research

- Soft AI (自然語言與生成型 AI)  
  ChatGPT, GROK, Claude, Gemini, Perplexity

- Hard AI（資料庫導向、學術支援型 AI）  
  參考 NYCU 圖書館的 AI 研究助理平台，包括 ALMA、WOS、Scite.AI  
  👉 [NYCU AI 工具入口網站](https://www.lib.nycu.edu.tw/?lang=zh-TW)

---

## Step 1

1. Start with a tentatitve title
2. Correct and identify authors in alphabetic orders at the moment. 


## Step 2: Introduction

Section 1 should include:

- (a) A literature review covering 3–5 relevant introductory topics  
- (b) A clear statement of the study's goals and its significance to society

The goal is to convince your readers why your research matters — not only in academia, but also in the real world.

Before proposing your research objectives, explore the broader context thoroughly with the help of both traditional methods and AI tools.

---

##  📌 Literature Review Workflow Step-by-Step Process

### 1. Identify Key Topics
Select 3 to 5 core themes relevant to your research area.

### 2. Use one AI for Discovery
For each topic:

- Ask your favorite AI (e.g., ChatGPT or Claude) to generate a list of relevant academic papers
- Request BibTeX citations from the AI
- Use Google Scholar or publisher sites to fact-check and validate each paper

### 3. Structure Findings in Slides

- Summarize findings in a clear table or matrix
- Structure the information into presentation-ready slides for communicating to a general audience

### 4. Manage Writing in Overleaf
- Compile sources into a BibTeX file
- Upload to Overleaf for easy reference management

### 5. Iterate with Other AI Tools
- Repeat the process using different AI tools, transit from Soft AI to Hard AI. 
- Refine until your review is comprehensive and well-structured

---

![AI-1](https://github.com/user-attachments/assets/a3a33e0f-2bad-4f31-bb19-05e8497d6cd6)


## Step 3: Building literature using bibtex format 


1. bibkeys have to be of a consistant format: firstauthor+yyyy+first word, all in lowercase.
2.  In 'title', use \textsc{xxx} to enforce words in uppper case.
3.  Don't cite a master thesis. (It is a hurt to cite a master thesis in your paper. No offense, but this is a fact.)
4.  Need to double check every information with google scholar. Add a note, ex: "% confirmed by Teng on 20250409" 

### A wrong example 
@mastersthesis{btcHeston,
  author    = {Chang, Yung-Chi},
  title     = {Pricing and Hedging Inverse BTC Options with Heston’s Stochastic Volatility Model},
  school    = {National Yang Ming Chiao Tung University},
  year      = {2022},
  note      = {Master's thesis}
}

### A corrected example 

% confirmed by Teng on 20250409
@article{chang2023stochastic,
	author = {Yung-Chi Chang and Huei-Wen Teng and Wolfgang H{\"{a}}rdle},
	title = {Stochastic volatility dynamic hedging of the inverse \textsc{BTC} option},
	volume = {16},
	number = {2},
	pages = {1--48},
	month = {August},
	year = {2023},
	journal = {Journal of Futures and Options},	
	note = {(TSSCI)},
	}
