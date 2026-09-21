<img width="1093" height="622" alt="21 09 2026_15 13 44_REC" src="https://github.com/user-attachments/assets/ea0c5e3b-e49b-459e-bd78-90764b67c140" />


# AI CV Screening & Recruitment Automation

An AI-powered recruitment workflow built with **n8n** that automatically screens incoming CVs, evaluates candidates against hiring criteria, organizes applications, and sends personalized email responses.

## Overview

This workflow automates the initial stages of the recruitment process by connecting **Google Drive, Google Gemini AI, Google Sheets, and Gmail**.

When a new CV is uploaded, the system extracts the candidate's information, analyzes their profile against predefined hiring requirements, calculates a match score, and automatically routes the candidate based on the result.

## Workflow

**Google Drive → Download CV → Extract Resume Data → Gemini AI Screening → Google Sheets → Match Score → Shortlisted / Rejected → Email**

### How It Works

1. Detects new CVs uploaded to Google Drive.
2. Downloads and extracts text from the resume.
3. Uses **Google Gemini AI** to analyze the candidate against hiring criteria.
4. Extracts candidate information such as name, email, phone, skills, experience, and education.
5. Stores candidate details and match score in Google Sheets.
6. Automatically classifies candidates based on their match score.
7. Moves shortlisted and rejected CVs into separate Google Drive folders.
8. Generates personalized email responses using AI.
9. Sends the appropriate email through Gmail.

## Key Features

* 🤖 AI-powered resume screening
* 📄 Automated CV data extraction
* 🧠 Candidate evaluation using Google Gemini AI
* 📊 Match score-based candidate classification
* 📁 Automatic CV organization
* ✉️ AI-generated personalized emails
* ⚡ End-to-end recruitment workflow automation
* 🔗 Google Drive, Sheets, and Gmail integration

## Tech Stack

* **n8n**
* **Google Drive**
* **Google Gemini AI**
* **Google Sheets**
* **Gmail**
* **Structured Output Parser**

## Use Case

This automation can help HR teams reduce repetitive manual work during the initial screening stage, keep candidate information organized, and provide timely responses to applicants.

## Project Goal

The goal of this project is to demonstrate how AI and workflow automation can be combined to streamline repetitive recruitment processes and create a more efficient candidate screening workflow.

---

**Built with n8n + Google Gemini AI + Google Workspace**
