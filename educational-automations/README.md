# AI Grading Agent — Case Study
### Overview

This n8n AI Agent workflow automates the assignment submission, grading, and feedback process for students in schools.




### Instead of manual grading, this workflow handles:

. Assignment submission via Google Form

. Automatic extraction and validation of student data

. OCR processing of submitted PDF assignments

. AI-based grading, feedback generation, and improvement suggestions

. Storing results in Google Sheets

. Sending detailed results back to students via email

All of this happens within seconds, ensuring fast, accurate, and standardized grading.

# Workflow Steps

### 1. Student Submission

. Student fills a Google Form with:

. Name

. Email 

. Class

. Assignment link

### 2. Google Sheets Trigger

. Upon submission, n8n workflow is triggered automatically.

. Workflow fetches all submission details.

. Link Validation & Standardization

. Checks if the assignment link is valid and accessible

.Converts it to proper format to avoid unopened/invalid submissions

### 3. OCR Processing

. Extracts text/data from PDF assignments

. Ensures AI agent can read student work accurately

### 4. AI Grading Agent

. Receives assignment content + student info

. Uses pre-configured system + user prompts to:

. Check correctness

. Provide marks

. Suggest improvements

. Generate detailed feedback

### 5. Store & Notify

Stores all results in Google Sheets

Sends a full result email to the student automatically


# Benefits

. Fully automated grading in seconds

. Reduces human error and grading time

. Standardized feedback for all students

. Keeps detailed records in Google Sheets

. Easy to scale for large classes or multiple assignments
