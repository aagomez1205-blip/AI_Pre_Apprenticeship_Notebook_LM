# AI_Pre_Apprenticeship_Notebook_LM
# Meet SiteReady: My AI Civil Engineering Internship Coach
## 1. Project Overview
SiteReady is an AI career coach designed to help **civil engineering students** prepare for their **first internship interview** at a consulting engineering firm. I built it around a real opportunity: an in-person interview for a **Civil Engineering Intern** role at Kimley-Horn.

**Career pathway:** Civil Engineering (consulting / site civil and water resources)

**Built with:** Google NotebookLM

## 2. The Problem I'm Solving
Civil engineering students often have strong school and club projects but struggle to connect them to what a consulting firm actually needs. Our coursework uses tools like Onshape and hand calculations, while firms work in AutoCAD, Civil 3D, GIS, and municipal plan sets. It's hard to know which experiences to highlight, how to talk about gaps honestly, and what to do in the first weeks of an internship.

SiteReady helps a student:
- Map their real experiences to the skills in a specific job posting
- Practice behavioral interview questions with structured feedback
- Plan a strong internship so they can earn a return offer

## 3. How My AI Career Coach Works
I curated these sources in NotebookLM:
- **Target job description:** Kimley-Horn Civil Engineering Intern posting
- **Company resource:** Kimley-Horn's culture, core values, and careers pages
- **Interview preparation resource:** Reported Kimley-Horn interview questions and process (Glassdoor)
- **My background:** A redacted summary of my experience (kept in a private notebook, never published)

I used NotebookLM's **Configure Chat → Custom** setting to give the coach a role (a Kimley-Horn hiring manager), so its answers stayed grounded in the uploaded sources instead of generic career advice.

Prompting techniques I used:
- **Role prompting:** "Act as a Kimley-Horn Civil Engineering hiring manager…"
- **Few-shot prompting:** gave the AI an example question → answer → feedback pattern for the mock interview
- **Chain-of-thought prompting:** "Think step by step…" for the 30/60/90-day plan
- **Output formatting:** asked for a table (skills analysis) and bullet points (action plan)

## 4. My AI Career Coach in Action

### Example 1: Career Guidance

**What the AI helped me understand:**
The coach identified five priorities for the role: civil/technical software, pre-construction design and analysis, multidisciplinary collaboration, regulatory and code compliance, and quality control. It matched each to my experience, such as my Engineers Without Borders drainage and irrigation project and my ADA-compliant design work. It also named honest gaps, like no direct Civil 3D experience and no exposure to formal plan redlines, and suggested I present my 3D modeling background as proof that I learn software quickly.

![Career guidance example](screenshots/2026-11-05 162935.png)

### Example 2: Mock Interview
**What I learned:**
My first answer ("people-first culture and entrepreneurial model") was accurate but generic. Any candidate could say it. The feedback showed me I needed a personal action (what I did to learn about the firm or the local projects) and a clear result (what value I would bring to the team). I now answer "Why Kimley-Horn?" with a specific reason connected to my own experience.

![Mock interview example](screenshots/2026-11-05 163040.png)

### Example 3: Career Action Plan
**My next steps:**
The plan showed me that the first month of an internship is about learning the firm's standards: AutoCAD/Civil 3D conventions, QC and redline procedures, and local public works standards. Its most practical advice was to aim for "zero repeat redlines" and to hold a short weekly check-in with my mentor. I'm starting a Civil 3D tutorial now so I arrive with a head start.

![Career plan example](screenshots/2026-11-05 163134.png)

## 5. Testing and Improving My Assistant
**Original prompt:**
> Think step by step. Based on the job description, build a 30/60/90-day plan for a new Kimley-Horn analyst. For each phase, list the goals, the software and skills to learn, and how I would show progress to my manager. Use bullet points.

**Improved prompt:**
> Think step by step. I'm starting a summer civil engineering internship at Kimley-Horn. Build a 30/60/90-day plan: what to learn first (software like AutoCAD/Civil 3D, plan sets, how projects run), how to add value by mid-summer, and how to finish strong so I get a return offer. Use bullet points.

**What changed and why:**
The original prompt said "analyst," which is Kimley-Horn's full-time entry-level title, so the AI blended full-time and intern expectations ("analyst/intern"). The improved prompt states the real situation (a summer internship), names the software to focus on, and defines the goal (a return offer). A summer internship is about 10–12 weeks, so a 30/60/90 structure fits it almost exactly. Being specific about role, timeline, and goal produced a plan I could actually follow.

## 6. Responsible AI
**How I checked the AI's output:**
- **Checked claims against the sources.** The AI said Kimley-Horn trains interns in Civil 3D and GIS and mentioned permitting topics like MS4/NPDES and CEQA. I confirmed these against the actual job posting before using them in my interview answers, rather than trusting the AI's summary.
- **Caught a role mismatch.** In the 30/60/90 plan the AI mixed "analyst" and "intern" because of my wording. I fixed the prompt instead of accepting a plan written for the wrong job.
- **Watched for overconfidence.** The AI's feedback is a coaching tool, not a hiring decision. I used it to improve my answers, not to predict the outcome.
- **Checked for bias.** The coach evaluated my experience by skills and evidence, not by school name or background. I would flag any feedback that relied on assumptions about a candidate.

**What should never be shared with this assistant (or published):**
- Full résumés with contact information, home address, or phone number
- Transcripts, student ID numbers, or financial information
- Names or contact details of recruiters and interviewers
- Confidential company or client project information
- Passwords or API keys

## 7. My 30/60/90-Day Career Plan
**30 days:** Learn Kimley-Horn's CAD standards, file structure, and QC/redline process. Complete onboarding training, start Civil 3D practice, and set up a weekly check-in with my mentor.

**60 days:** Take ownership of small, well-defined tasks on site civil or drainage plan sets. Apply local grading and drainage standards, and turn in redline revisions with zero repeat comments.

**90 days:** Contribute to a deliverable from start to finish, present what I worked on to my team, and ask my mentor for feedback on what it would take to earn a return offer.

## 8. Reflection
1. **What was the most useful thing my AI coach did?**
   The skills-gap table. It turned a long job posting into five clear priorities and showed me exactly which of my projects to talk about for each one.
2. **What was one limitation or mistake I discovered?**
   The AI followed my wording too literally. When I wrote "analyst," it planned for a full-time role. It also stated some details with confidence that I had to verify against the job posting myself.
3. **How could this assistant help someone in a real job?**
   A new intern or engineer could load their firm's standards and a project scope, then use it to prepare for meetings, explain technical work to non-technical clients, and plan their first weeks on a project.
4. **What would I improve in a future version?**
   I would add the firm's actual CAD standards and local municipal design manuals as sources. I would also add a prompt that rewrites my technical project descriptions for a non-technical client, since consulting engineers explain their work to clients every day.

## 9. Skills Demonstrated
- Prompt engineering (role, few-shot, chain-of-thought, output formatting)
- AI output evaluation
- Research and source curation
- Responsible AI practices
- GitHub documentation
- Career readiness
