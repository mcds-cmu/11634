---
layout: s25
title: Syllabus
nav_order: 2
has_children: false
has_toc: false
---

# 11-634: Capstone Planning Seminar - Syllabus

## Course Description

{% include syllabus/course_learning_outcomes.md %}

## Time & Location

TR 08:00 AM	- 09:20AM TEP 1403

## Course Format

At the beginning of the course, students will submit their information and resume/CV. In the subsequent weeks, students will have access to both live presentations and recorded videos for each of the candidate's projects. Students will then be asked to submit a list of project preferences. The faculty and MCDS Administration will assign teams to projects by matching the project sponsor's and student's preferences. 

Note: If you have proposed a self-identified project (i.e., have spoken to a faculty member, identified a topic, submitted a proposal, and formed a team / will work individually), please contact course staff within the first week. Each team will begin to work on their assigned project and commence weekly meetings with their project mentor. The course then provides several milestones throughout the semester where each team is required to submit a report and, in some cases, present and discuss their and others' work progress.

## Course Assessments

- ### Weekly Report

    Starting week 5, each week, your team will deliver a 5 to 10-minute presentation summarizing your project’s progress from the past week. The presentation must use the quad chart template provided on Canvas and should focus on detailed progress updates rather than an extended introduction. The aim is to clearly communicate your work and facilitate productive discussions.

    To accommodate the large number of teams, these reports will alternate biweekly between meetings with the instructor and meetings with a designated TA. These meetings will not occur during regular class times:
        •	Instructor Meetings: Held Tuesday to Thursday, 1:00–5:00 PM in GHC 5419.
        •	TA Meetings: Teams and TAs will coordinate the time and location, with the option to meet on Zoom.

    Each report will be graded, and attendance is mandatory.


- ### Vision Document

    Document the motivation for the project - what problems does the proposed project attempt to solve, and for what data set(s)? What is novel or unique about the proposed approach? How will success be measured? What is the expected impact (business or research value) if the project is successful? The Vision Document should clearly state Research Questions, General Hypotheses, and Specific (Testable) Hypotheses, along with an indication of how technical performance and/or business value will be measured.

- ### Requirements Document

    Document specific use cases (workflows and/or data flows) for the proposed solution. Analyze the data set(s) and provide a domain analysis that identifies the salient characteristics of the data domain and likely challenges (missing data, noise, skewed distributions, magnitude, drift, etc.). Identify (from a systems perspective) what computations will be required to clean, pre-process, prepare, and train models on the data set(s); what software modules must be designed and implemented, either from scratch or using existing toolkits; what metrics and measurement routines must be implemented or deployed using existing toolkits; user/case studies that will be undertaken to demonstrate business value; etc.

- ### Design and Plan Document

    Document a specific architecture (modules and data flow) to represent the cleaning pre-processing, model training, solution deployment, and solution evaluation phases for the proposed project. Provide a mapping from each use case in the requirements document to the workflows and modules that will support that use case. Identify which elements will be designed and coded by hand, implemented via existing frameworks / toolkits, or reused from existing solutions. Create a work breakdown structure to indicate what development activities will be undertaken and, at what times, by which team members. It should be clear from the plan how and when each element will be completed, how it will be evaluated, and how error analysis and refinement will be undertaken for each module, as well as the entire end-to-end solution. Teams are strongly encouraged to complete a preliminary end-to-end implementation of each workflow in the solution, along with a corresponding error analysis, before the end of the semester. Preliminary results by mid-semester will be expected for any team that wishes to publish results at the end of the Spring semester.


- ### Draft Report

    Document all of the updates made to the vision / requirements / design and plan documents, with a focus on any remaining issues to be addressed in the Fall semester. Be sure to revisit the work breakdown structure in order to provide the most realistic plan possible for the remaining work. Summarize all experimental results achieved so far (with appropriate calculations of statistical significance), along with a discussion of performance gains versus the prior state of the art, an analysis of known remaining error types, and suggestions for how to address known gaps in performance or specific error categories.

- ### Spring Final Presentation

    Present your vision, requirements, design, and plan in a short presentation, along with a summary of results so far and work remaining to be completed. The presentations will take place in a public venue; all members of the SCS community (as well as MCDS alumni) and the project mentors will be invited to attend.

- ### Final Presentation Peer Review

    Each student is required to attend at least one Spring final presentation of another team and submit a brief review of this team's presentation. Students will have the chance to submit their preference for the team to review according to their schedule suitability.

- ### End-of-Semester Internal Evaluation

    To facilitate a fair distribution of work among team members, our assessment process includes a peer review component, conducted exclusively at the end of the semester. This peer review is an individual assignment, integral to the final assessment, focusing on three key aspects:

    **Your Contribution to the Project:** Detailing the roles and responsibilities you undertook and your direct impact on the project's progress.

    **Peers’ Contribution to the Project:** Providing insights into each team member's contributions. Despite the potential challenge in larger teams, it’s vital to acknowledge and reflect on every member’s involvement.

    **Contribution to Peer Learning:** Assessing how you and your peers have facilitated each other's learning throughout the project.

    To ensure a meaningful review, you are required to provide substantive, reflective answers to each question. Your responses should include specific examples and constructive criticism aimed at problem-solving and improvement.

    The quality of your feedback is a significant component of your grade. Effective feedback benefits both the giver and the receiver, fostering a deeper understanding and improvement. As such, thoughtful and considerate responses are encouraged.

    Your review, which will be shared with all team members, should be constructive, respectful, and considerate.

    Furthermore, anonymized data from these peer reviews will be made available to all students. This initiative aims to provide insights into team dynamics and encourage discussions on collaborative improvement.

    Participation in this peer review is mandatory, and it will substantially influence your individual grade. This policy underscores our commitment to fostering a collaborative learning environment where every member's contribution is valued and assessed fairly.

- ### Personal Learning Objectives

    Each student is required to define and communicate their personal learning objectives, which they aim to achieve throughout the capstone experience. Additionally, they are to compose a short report that demonstrates their reflective thinking and ongoing efforts towards self-improvement and skill enhancement. This concise report should detail how their experiences in the capstone project have contributed to meeting these learning goals.

- ### Individual Check-In Survey:

    Periodically, you will be asked to complete a survey to provide insights into your individual progress, any struggles you may be facing, issues with your team or teammates, and general feedback. These surveys are an essential part of the course and are required to ensure your success.

- ### Final Report

    Submit an update to your Draft Report, which incorporates: a) feedback received on your Draft Report submission and b) feedback received during your Spring Final Presentation.

## Course Schedule

See the [Course Calendar]({{ site.baseurl }}{{ page.subpath }}{% link s25/schedule.md %}) for the tentative schedule. Specific deadlines are posted on Canvas.

## Grading

Grading will consist of:

- Biweekly Report with Instructor: 10%
- Biweekly Report with TA: 10%
- Vision Document: 10%
- Requirements Document: 10%
- Design Document: 5%
- Plan Document: 5%
- Draft Report: 5%
- Final Report: 15%
- Spring Final Presentation: 15%
- Personal Learning Objectives: 5%
- Individual Check-in Surveys: 5%
- Participation: 5% 

Deliverables will be assigned a team grade, and it is essential that all members of a team make efforts to collaborate effectively. Above or below-average individual work may put individual grades ahead or below the group grade only by a small margin. We expect everyone not to isolate themselves and make a good faith effort on a regular basis to coordinate/engage with their teammates, share their insights, and make sure everyone can contribute. Individuals will be assigned project grades based on the team grade and peer evaluations.

## Grade Policy

**Individual Grade Adjustments**

In our team-based academic settings, it is recognized that uniform grading may not always reflect individual contributions. Hence, instructors have the discretion to modify a student's grade relative to the team's collective grade. This adjustment is grounded in a thorough evaluation of various factors such as the student's effort, active participation in course work, professionalism, ability to work collaboratively, and demonstration of a growth mindset.

**Grading Methodology**

Our grading process begins with the normalization of scores using statistical techniques to calculate the mean and variance. Individual grades are determined based on the standard deviations from the mean.

**Exceptional Performance Recognition**

We reserve the highest accolade, the 'A+' grade, for students who not only secure top marks but also demonstrate significant research impact. This decision is made collectively by course instructors and mentors, ensuring a fair and comprehensive assessment of each student's academic prowess.

**Regrading Policy**

All grading disputes and regrading requests must be made within 7 days after the grade is released. No requests will be accepted after this deadline.

## Attendance Policy

Attendance is a critical component of your participation score, contributing 5% of your overall grade. It is mandatory to attend all class meetings, weekly reports, and presentations. Past experience from previous cohorts shows that regular attendance is essential for team success and individual growth. Therefore, all students are expected to attend every session as scheduled.

Since the course meets only a few times during the regular class schedule, attendance at all these sessions is required. Additionally, students must be present:
	•	During their team’s biweekly report presentations to the instructor and TA.
	•	For their final presentation and any other presentations they are assigned to review.

Failure to attend any of these will result in a zero score for that specific assignment for the individual student.

In recognition of the unpredictable nature of circumstances, each student will be allowed **one** absence per semester. This absence is permissible only for sessions where the student's team is not scheduled to present. It should be noted that interview appointments or similar commitments are not considered valid reasons for additional absences beyond this single allowance.

## Academic Integrity

For all team presentations and the final report, it's imperative that students present their work in a manner that distinctly outlines their contributions and differentiates them from existing work. This includes clearly indicating parts of the project that have been influenced by, derived from, or adapted from prior works. It is crucial that these external influences are not only acknowledged but also properly cited in both the report and presentation slides.

Appropriate citation must cover a wide range of materials, including but not limited to:

- Academic writings (including those published by collaborators of the project)
- Diagrams and visual aids
- Datasets utilized in the project
- Reports from previous Capstone projects
- Video tutorials and scientific blog posts
- Technical components such as algorithms, software libraries, and similar tools
- When incorporating these materials into your work, two key principles must be followed:

**Paraphrasing**: When the text from a source is paraphrased (i.e., rewritten in your own words), it is essential to cite the original source to acknowledge its influence on your work.

**Direct Quotation**: If a piece of text is used verbatim (exactly as it appears in the source), it must be placed within quotation marks and accompanied by a specific reference to its origin.

Ensuring the integrity of your work through proper citations is not only a scholarly requirement but also a mark of respect for the intellectual property of others. This practice is central to upholding academic honesty and fostering a culture of responsibility and ethical scholarship in our academic community.

## Assignment Submission Confidentiality and Use for Course Improvement

All assignment submissions for this course will be utilized for course analytics and to enhance future course offerings. These submissions will remain confidential and will not be made publicly available, unless express written consent is provided by the authors of the submitted work.
