---
layout: s23
title: Syllabus
nav_order: 2
has_children: false
has_toc: false
---

# 11-634: Capstone Planning Seminar - Syllabus

## Course Description

{% include syllabus/course_learning_outcomes.md %}

## Time & Location

Section A: MW 8 am - 09:20 am, POS 153

Section B: MW 11 am - 12:20 pm, GHC 4102

## Course Format

At the beginning of the course, students will submit their information and resume/CV. In the subsequent weeks, students will have access to both live presentations and recorded videos for each of the candidate's projects. Students will then be asked to submit a list of project preferences. The faculty and MCDS Administration will assign teams to projects by matching the project sponsor's and student's preferences. 

Note: If you have proposed a self-identified project (i.e., have spoken to a faculty member, identified a topic, submitted a proposal, and formed a team / will work individually), please contact course staff within the first week. Each team will begin to work on their assigned project and commence weekly meetings with their project mentor. The course then provides several milestones throughout the semester where each team is required to submit a report and, in some cases, present and discuss their and others' work progress.

## Course Milestones

- **Vision Document**. Document the motivation for the project - what problems does the proposed project attempt to solve, and for what data set(s)? What is novel or unique about the proposed approach? How will success be measured? What is the expected impact (business or research value) if the project is successful? The Vision Document should clearly state Research Questions, General Hypotheses, and Specific (Testable) Hypotheses, along with an indication of how technical performance and/or business value will be measured.

- **Requirements Document**. Document specific use cases (workflows and/or data flows) for the proposed solution. Analyze the data set(s) and provide a domain analysis that identifies the salient characteristics of the data domain and likely challenges (missing data, noise, skewed distributions, magnitude, drift, etc.). Identify (from a systems perspective) what computations will be required to clean, pre-process, prepare, and train models on the data set(s); what software modules must be designed and implemented, either from scratch or using existing toolkits; what metrics and measurement routines must be implemented or deployed using existing toolkits; user/case studies that will be undertaken to demonstrate business value; etc.

- **Design and Plan Document**. Document a specific architecture (modules and data flow) to represent the cleaning pre-processing, model training, solution deployment, and solution evaluation phases for the proposed project. Provide a mapping from each use case in the requirements document to the workflows and modules that will support that use case. Identify which elements will be designed and coded by hand, implemented via existing frameworks / toolkits, or reused from existing solutions. Create a work breakdown structure to indicate what development activities will be undertaken and, at what times, by which team members. It should be clear from the plan how and when each element will be completed, how it will be evaluated, and how error analysis and refinement will be undertaken for each module, as well as the entire end-to-end solution. Teams are strongly encouraged to complete a preliminary end-to-end implementation of each workflow in the solution, along with a corresponding error analysis, before the end of the semester. Preliminary results by mid-semester will be expected for any team that wishes to publish results at the end of the Spring semester.

- **Midterm Presentation**. Present the highlights of the vision, requirements, design, and plan, along with any preliminary results, in a recorded video.

- **Midterm Presentation Team Peer Review**. Watch at least one peer team's midterm presentation video and submit a brief review of the team(s) 's presentation on Persuall. 

- **Draft Report**. Document all of the updates made to the vision / requirements / design and plan documents, with a focus on any remaining issues to be addressed in the Fall semester. Be sure to revisit the work breakdown structure in order to provide the most realistic plan possible for the remaining work. Summarize all experimental results achieved so far (with appropriate calculations of statistical significance), along with a discussion of performance gains versus the prior state of the art, an analysis of known remaining error types, and suggestions for how to address known gaps in performance or specific error categories.

- **Draft Report Revision (Optional)**. After reviewing feedback for the draft, you will have the opportunity to revise the draft and submission a revision of the draft for regrading. This is optional, but we encourage you to take advantage of this opportunity to learn from the feedback and produce a better version of the draft.

 To be eligible for the revision draft submission, your initial draft report submission must receive at least a grade of 70%, AND your designated TA must recommend you. This means that the original draft you submit must be of substantial and authentic work and that the revised version would be a revised version of the draft report and not used as a time extension mechanism.

 If you submit the revision, your grade for the draft report will be the grade of the revised draft. If you choose not to submit a revision, your grade will be the original grade of the first draft report submission. We strive to give you feedback as quickly as possible to give you sufficient time to review and revise the draft.

- **Spring Final Presentation**. Present your vision, requirements, design, and plan in a short presentation, along with a summary of results so far and work remaining to be completed. The presentations will take place in a public venue; all members of the SCS community (as well as MCDS alumni) and the project mentors will be invited to attend.

- **Final Presentation Team Peer Review**. Each student is required to attend at least one Spring final presentation of another team and submit a brief review of this team's presentation. Students will have the chance to submit their preference for the team to review according to their schedule suitability.

- **Inner-team Peer Review**. Reflect on your contribution to your peer(s)' learning and the overall project, and evaluate peer(s)' contribution to the project. 

- **Final Report**. Submit an update to your Draft Report, which incorporates: a) feedback received on your Draft Report submission and b) feedback received during your Spring Final Presentation.

## Course Schedule

See the [Course Calendar]({{ site.baseurl }}{{ page.subpath }}{% link s23/schedule.md %}) for the tentative schedule. Specific deadlines are posted on Canvas.

## Grading
Grading will consist of:
- **Capstone Project Deliverables**
 - Vision Document (10%)
 - Requirements Document (10%)
 - Design Document (10%)
 - Plan Document (10%)
 - Midterm Presentation (10%)
 - Draft Report (10%)
 - Final Report (15%)
 - Spring Final Presentation (10%)
- **Peer Reviews**
 - Midterm Presentation Team Peer Review (5%)
 - Final Presentation Team Peer Review (5%)
 - Midterm Inner-team Peer Review (2.5%)
 - Final Inner-team Peer Review (2.5%)

Deliverables will be assigned a team grade, and it is essential that all members of a team make efforts to collaborate effectively. Above or below-average individual work may put individual grades ahead or below the group grade only by a small margin. We expect everyone not to isolate themselves and make a good faith effort on a regular basis to coordinate/engage with their teammates, share their insights, and make sure everyone can contribute. Individuals will be assigned project grades based on the team grade and peer evaluations.

## Attendance Policy
The course only meets as stated in the schedule to provide ample time for dedicated project work and weekly meetings with the project mentor. Each student is permitted **one** absence for the semester. It may only be taken for a session in which the student's team is not presenting. Interview appointments are not considered valid excuses for absences beyond this allowance.

## Inner-team Peer Review Assessment
To facilitate a fair distribution of work among team members, each midterm and final assessment includes a peer review. These reviews are individual assignments. The review asks for three main points, how you contributed to the project, how your peers contributed to the project, and how you contributed to your peer's learning. All questions are short-answer questions and require no numerical evaluation.

You must provide substantive answers to each question to receive marks for the answers. In particular, you must give concrete examples for each point and provide constructive feedback on fixing the problems.

You must provide feedback to all team members when answering questions about their contribution to the project. We understand this can be tedious for large teams. However, understanding and reflecting on others' contributions to the project are important regardless of the team size. 

You will be graded on the quality of the feedback. Giving feedback is as impactful for the reviewers as it is to the receivers, so we encourage you to take some time to reflect on the question prompts and write a meaningful review. Your review will be available to all team members, so be constructive but nice and mindful.

Data from the inner-team peer reviews (how your peers responded to each prompt) will be made available for all students. The personal information of the writers will be removed. We hope you find this data useful to discuss how to reflect on them and work collaboratively better.

Participation will be mandatory, and individual grades will be influenced by peer review outcomes.

## Academic Integrity
For all presentations and the final report, students share their work with their teammates. Both presentations and reports need to make clear at all times the students' contributions and those parts that have been influenced, taken, adapted, or otherwise derived from prior work. Any such additional material must be properly cited in the report and on the presentation slides. This citation material includes related academic writing (even if published by a collaborator of the project), diagrams, datasets, prior Capstone project reports, video tutorials, scientific blog posts, and technical components such as algorithms, libraries, and among others. When a source's text is paraphrased, it needs to be referenced. If it is reused verbatim, it must be quoted (i.e., put into quotation marks and annotated with a reference).