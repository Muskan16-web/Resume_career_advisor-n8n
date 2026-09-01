# Resume_career_advisor-n8n
AI Resume Career Advisor built with n8n — an automated workflow that analyzes a candidate's resume, extracts key skills and experience, evaluates career opportunities, and provides personalized career recommendations using AI. The workflow demonstrates AI-powered resume analysis, career guidance, automation, and structured data processing with n8n.

# 🤖 AI Resume Career Advisor — n8n Workflow

An AI-powered **Resume Career Advisor** built with **n8n** that analyzes a candidate's resume against a specific job description and provides a detailed, personalized career improvement report.

The workflow uses AI to evaluate the candidate's skills, experience, qualifications, and overall resume-job compatibility, then delivers the analysis directly to the candidate's email.

## 🚀 Features

* 📄 Resume analysis and information extraction
* 💼 Job Description analysis
* 🎯 Resume-to-Job Description matching
* 📊 **Resume compatibility score**
* 🧠 AI-powered skill and experience evaluation
* 🔍 Identification of matching and missing skills
* ⚠️ Identification of skill gaps
* 💡 Personalized career recommendations
* 📧 **Detailed career report delivered directly via email**
* 📈 Resume improvement suggestions
* 📚 **Personalized 3-month practice and learning plan**
* 🎓 Recommended topics and skills to practice
* ⚡ Fully automated workflow using n8n

## 📊 Resume Score & Job Matching

The workflow compares the candidate's resume with the provided **Job Description (JD)** and generates a score based on factors such as:

* Skills and technical requirements
* Relevant experience
* Educational qualifications
* Job-specific keywords
* Required technologies/tools
* Overall profile relevance

The result provides the candidate with a clear understanding of **how well their current resume matches the target job** and what areas need improvement.

## 📧 Detailed Email Report

After completing the analysis, the workflow automatically generates and sends a **detailed report to the candidate's email**.

The report can include:

* 📊 Overall Resume Match Score
* ✅ Matching Skills
* ❌ Missing Skills
* 💼 Job Role Compatibility
* 🔍 Resume Strengths
* ⚠️ Areas for Improvement
* 📝 Resume Improvement Suggestions
* 🎯 Recommended Career Direction
* 📚 Skills to Learn
* 📅 Personalized 3-Month Practice Plan

## 📅 3-Month Practice Plan

One of the key features of the workflow is its ability to create a **personalized 3-month practice plan** based on the candidate's skill gaps and target job description.

The plan is structured into progressive stages:

### Month 1 — Foundation

Focus on understanding and strengthening the fundamental concepts required for the target role.

### Month 2 — Skill Development

Practice job-relevant technical skills through exercises, projects, and hands-on implementation.

### Month 3 — Job Readiness

Focus on practical projects, interview preparation, resume improvements, and applying the acquired skills to real-world scenarios.

The plan is personalized according to the candidate's current skills and the requirements of the target job.

## 🔄 Workflow Overview

**Resume + Job Description + Candidate Email**

⬇️

**Resume Processing**

⬇️

**Job Description Analysis**

⬇️

**AI Resume & JD Comparison**

⬇️

**Skill & Experience Evaluation**

⬇️

**Resume Match Score**

⬇️

**Skill Gap Analysis**

⬇️

**Career Recommendations**

⬇️

**3-Month Personalized Practice Plan**

⬇️

**Generate Detailed Report**

⬇️

**Send Report via Email 📧**

## 🛠️ Technologies Used

* **n8n** — Workflow automation
* **AI / LLM** — Resume and job-description analysis
* **JSON** — Workflow configuration
* **Prompt Engineering** — Structured AI analysis
* **Email Integration** — Automated report delivery

## 📁 Repository Contents

```text
resume-career-advisor/
│
├── resume-career-advisor.json
└── README.md
```

The `resume-career-advisor.json` file contains the complete n8n workflow and can be imported into an n8n instance.

## ⚙️ How to Use

1. Download or clone this repository.
2. Open your n8n instance.
3. Import `resume-career-advisor.json`.
4. Configure the required AI/API credentials.
5. Configure the email service/credentials.
6. Provide the candidate's resume.
7. Provide the target Job Description.
8. Enter the candidate's email address.
9. Execute the workflow.
10. Receive the detailed AI-generated career report by email.

## 🎯 Project Objective

The objective of this project is to demonstrate how **AI and workflow automation can be combined to create an intelligent career-assistance system**.

Instead of simply analyzing a resume, the workflow evaluates the resume against a real job description, calculates a compatibility score, identifies skill gaps, recommends improvements, and creates a structured **3-month preparation plan** to help the candidate become more job-ready.

## 🔮 Future Improvements

* 🤝 Automatic job matching from job portals
* 📄 AI-powered ATS resume scoring
* 🔗 LinkedIn profile analysis
* 💼 Multiple job-description comparison
* 📚 Personalized course recommendations
* 🎤 AI interview preparation
* 🧪 Technical assessment generation
* 📈 Progress tracking during the 3-month plan
* 📊 Career dashboard for candidates

## 👩‍💻 Author

**Muskan**

Built as an AI automation project using **n8n**.
