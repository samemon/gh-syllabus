---
title: Policies and Resources
layout: page
menuItem: Policies and Resources
menuPosition: 3
---
{% if site.docsUrl != "" %}
You can download all required reading in the [Study materials]({{ site.docsUrl }}) at the faculty website.
{% endif %}

# Policies

## Late Policy

Each student will be granted 5 late days to use over the duration of the semester. You can use these late days for any assignment. Using late days will not affect your grade. However, once the late days are used up, submissions will be penalized by 20% for each late day taken. 

## Academic Integrity

You are expected to comply with the [University Policy on Academic Integrity and Plagiarism](https://www.cmu.edu/policies/). You are allowed to talk with and work with other students on homework assignments. You can share ideas but not code. You should submit your own code. 

Your course instructor reserves the right to determine an appropriate penalty based on the violation of academic dishonesty that occurs. Violations of the university policy can result in severe penalties including failing this course and possible expulsion from Carnegie Mellon University. If you have any questions about this policy and any work you are doing in the course, please feel free to contact your instructor for help.


## Attendance

Attendance in this course is mandatory, except for excused absences for illness, conference travel, religious obligations, etc. Students with more than four unexcused absences will be docked one letter grade.

# Resources

## Take Care of Yourself!

As a student, you may experience a range of challenges that can interfere with learning, such as strained relationships, increased anxiety, substance use, feeling down, difficulty concentrating and/or lack of motivation. All of us benefit from support during times of struggle. There are many helpful resources available on campus and an important part of having a healthy life is learning how to ask for help. Asking for support sooner rather than later is almost always helpful. CMU services are available, and treatment does work. You can learn more about confidential mental health services available on campus at: http://www.cmu.edu/counseling/. Support is always available (24/7) from Counseling and Psychological Services: 412-268-2922.

## Accommodations for Students with Disabilities:

If you have a disability and have an accommodations letter from the Disability Resources office, I encourage you to discuss your accommodations and needs with me as early in the semester as possible. I will work with you to ensure that accommodations are provided as appropriate. If you suspect that you may have a disability and would benefit from accommodations but are not yet registered with the Office of Disability Resources, I encourage you to contact them at access@andrew.cmu.edu.

<!--<ol>
{% assign syllabus = (site.syllabus | sort: "week") %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a> 
  	{% for tag in week.tags %}
  		<b>#{{ tag }}</b>
  	{% endfor %}
  	({{ week.day }})</li>
{% endfor %}
</ol>-->
