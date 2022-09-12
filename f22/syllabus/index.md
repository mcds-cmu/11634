---
layout: f22
title: Syllabus
nav_order: 2
has_children: true
has_toc: false
---

# 11-632: Data Science Capstone - Syllabus

## Course Learning Outcomes

The main learning objectives of the course are for students to design, implement and evaluate a software system and machine learning model on real-world datasets at a real-world scale.
Formulate computational data science problems in different application domains and critique their state-of-the-art solutions. Organize, present, and report on, a real-world data science project in collaboration with other researchers/programmers.

{% assign staffers = site.staffers | where_exp: "staffer", "staffer.staff_for contains 'f22'" %}

## Instructor
{% assign instructors = staffers | where: 'role', 'Instructor' | sort:"list_order" %}
<div class="staffer-container">
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
</div>

## Course Developer
{% assign developers = staffers | where: 'role', 'Course Staff and Developers' | sort:"list_order" %}
<div class="staffer-container">
{% for staffer in developers %}
{{ staffer }}
{% endfor %}
</div>

## Teaching Assistants
{% assign tas = staffers | where: 'role', 'Teaching Assistants' | sort:"list_order" %}
<div class="staffer-container">
{% for staffer in tas %}
{{ staffer }}
{% endfor %}
</div>

## Time & Location

Section A: M/W 10:10 am – 11:30 am, TEP 1403

## Contents and Schedule

Student teams will work on their assigned Capstone projects under the supervision of the project advisor and, where applicable, in collaboration with other students/faculty. 

Class sessions are noted on the scheduled dates below. Professor Nyberg is available for office hours during class meeting time in the assigned classroom (TEP 1403). Teams are encouraged to come to class to work on their projects and/or ask questions. 

All deliverables are **bolded**. Students are expected to meet as project teams at least once a week, record, and submit a 5 to 10-minute weekly standup. There are three evaluation milestones, a draft, and final report, and a final presentation.

All _italicized_ text is for your notice.

<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Activity</th>
      <th><strong>Deliverable Due</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Aug 29</td>
      <td>Introduction/Overview</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Aug 31</td>
      <td>
        Tutorials:
        <ul>
            <li>Fall Plan</li>
            <li>How to do a Standup</li>
        </ul>
    </td>
      <td><strong>Fall Plan Due Sep 4</strong></td>
    </tr>
    <tr>
      <td>Sep 5</td>
      <td colspan="2" style="text-align: center;">Labor Day (No Class)</td>
    </tr>
    <tr>
      <td>Sep 7</td>
      <td colspan="2" style="text-align: center;">Fall Plan Feedback</td>
    </tr>
    <tr>
      <td>Sep 12</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Sep 14</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Sep 15</strong></td>
    </tr>
    <tr>
      <td>Sep 19</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Sep 21</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Sep 22</strong></td>
    </tr>
    <tr>
      <td>Sep 26</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Sep 28</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Sep 29</strong></td>
    </tr>
    <tr>
      <td>Oct 3</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Oct 5</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Oct 6</strong></td>
    </tr>
    <tr>
      <td>Oct 10</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Oct 12</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Oct 13</strong></td>
    </tr>
    <tr>
      <td>Oct 17</td>
      <td colspan="2" rowspan="2" style="text-align: center;">Fall Break (No Class)</td>
    </tr>
    <tr>
      <td>Oct 19</td>
    </tr>
    <tr>
      <td>Oct 24</td>
      <td rowspan="2"><strong>Midterm Check-in with Prof. Nyberg (in-person and Zoom)<br>Schedule TBD</strong></td>
      <td><i>Midterm Grades due to University Oct 24</i></td>
    </tr>
    <tr>
      <td>Oct 26</td>
      <td><strong>Midterm Inner-team Peer Review due Oct 27</strong></td>
    </tr>
    <tr>
      <td>Oct 31</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Nov 2</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Nov 3</strong></td>
    </tr>
    <tr>
      <td>Nov 7</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Nov 9</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Nov 10</strong></td>
    </tr>
    <tr>
      <td>Nov 14</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Nov 16</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Nov 17<br>Draft Report Due Nov 20</strong></td>
    </tr>
    <tr>
      <td>Nov 21</td>
      <td rowspan="2" colspan="2" style="text-align: center;">Thanksgiving Break (No Class)</td>
    </tr>
    <tr>
      <td>Nov 23</td>
    </tr>
    <tr>
      <td>Nov 28</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><i>Draft Report Feedback will be returned by Nov 28</i></td>
    </tr>
    <tr>
      <td>Nov 30</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td><strong>Weekly Standup Due Dec 1</strong></td>
    </tr>
    <tr>
      <td>Dec 5</td>
      <td>Work with Team and Mentor; Prof. Nyberg Office Hours (in-person, in the classroom during class time)</td>
      <td>&nbsp;</td>
    </tr>
    <tr>
      <td>Dec 7 - Dec 14</td>
      <td colspan="2" style="text-align: center;"><strong>MCDS Capstone Final Presentation</strong></td>
    </tr>
    <tr>
      <td>Dec 15</td>
      <td colspan="2" style="text-align: center;"><strong>Team Peer Review Due<br>Final Report Due<br>Final Inner-team Peer Review Due</strong></td>
    </tr>
    <tr>
      <td>Dec 21</td>
      <td colspan="2" style="text-align: center;"><i>Final Grades due to University</i></td>
    </tr>
  </tbody>
</table>