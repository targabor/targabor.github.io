---
layout: post
title:  "My MSc Journey: Semester Two"
summary: "Join me as I dive into the exciting experiences of my second semester in the MSc in Data Science program."
author: rofa
date: '2024-06-13 18:30:00 +0100'
category: ['msc','university', 'data_science']
tags: msc
thumbnail: /assets/img/posts/msc-second/msc-2.jpg
keywords: masters, machine_learning, university, data science msc, data science, 
usemathjax: false
permalink: /blog/msc-second-semester/
---

## I. Introduction

After the "success" of my first post (okay, not really), I think it's time to share my experiences from my second semester in the Master's program at the University of Pannon. Riding high on the achievements of my first semester, I was confident that this one would be just as successful. That's usually when life gives you a big kick in the teeth. However, there's always a chance that the good streak will continue.

## II. Dive into the classes

This semester, I took on a slightly heavier load with 45 credits (lol). Initially, I was worried it might be too much, but fortunately, I managed to handle everything.

There were 3 mandatory subjects:
- Advanced database management systems
- Process modelling and process mining 
- Unsupervised machine learning

And 6 optional subjects:
- Cloud programming
- Combinatorial optimization
- Advanced data warehouse technologies
- Production intelligence and process information systems
- Cloud security
- Advanced image processing techniques (Recognized by my old studies)

In the following sections, I'll briefly discuss each subject and share my experiences.

### Advanced database management systems:

I had mixed feelings about this subject throughout the semester. It wasn't bad, but I'm not entirely sure of the value it added. Unfortunately, there are far fewer hours in part-time courses than in full-time courses, which may have contributed to that feeling.

The instructor seemed somewhat uncomfortable with the online learning environment, but that's perfectly understandable.

We covered topics such as triggers, loose coupling, jobs, data replication, graph databases, cloud databases (GCP), Firestore, Firestore transactions, and BigQuery.

For our project, we had to apply the topics we learned. I created a basic accommodation booking site, combining Postgres and Firestore for the backend.

<b>Final Grade: 5</b>

### Process modelling and process mining:

Honestly, this subject had the potential to be very good, but unfortunately, it fell short. The issue might be related to it being a part-time course, and I believe that having only two sessions wasn't sufficient to cover the material adequately.

The instructors were helpful throughout the course, and the requirements were clear and achievable. During the course, we were introduced to the basics of process modeling, created a BPMN diagram, and learned basic process mining algorithms. We used Python and the pm4py package for this.

For our final project, we had to create a BPMN diagram of a process, run process mining algorithms based on a custom data log, and compare the results.

<b>Final Grade: 5</b>

### Unsupervised learning:

This course served as a continuation of supervised learning from the previous semester. Throughout the term, we delved into dimension reduction methods, clustering algorithms, outlier analysis, and explored association rule mining, not to mention the intriguing realm of recommender systems.

Our instructor was well-prepared and adept at delivering the material, it was a pleasant experience throughout the semester.

As part of the course requirements, I had to submit a project applying the concepts learned. Additionally, there was an oral exam at the end of the semester.

<b>Final Grade: 5</b>

### Cloud programming:

As the course name suggests, we learned about various cloud technologies on GCP. To complete the course, we had to create a cloud-based project. For my project, I developed a Streamlit-based website where users could post comments. These comments were saved to cloud storage in JSON format. For every new post, a trigger activated a cloud function that parsed the user's comment using the NLP API and then stored it in a BigQuery table.

<b>Final Grade: 5</b>

### Combinatorial optimization:

This course can also be seen as a continuation of the advanced operations research from the previous semester. During the course, we studied advanced modeling techniques, such as TSP (Traveling Salesman Problem) modeling, scheduling problems, and either-or relation modeling. We also learned various solution techniques for these problems. Toward the end of the course, we explored advanced techniques like Branch and Bound (B&B), game theory, and scheduling theory.

Completion of the course required several homework assignments and the presentation of a topic at the end of the semester. My topic was the heuristics of the Traveling Salesman Problem.

Although this topic was not mandatory, I found it covered some very interesting areas. I believe subjects like this can develop our logical thinking and potentially be useful in the future.

<b>Final Grade: 5</b>

### Advanced data warehouse technologies:

The course name suggests that it is an advanced course, but this was not the case. Many students were being introduced to the concept of a data warehouse for the first time, so we started from the basics. Similar to the database course, there wasn't enough time to cover all the material, which required a significant individual time investment.

We also had to complete a project based on the course material. Unfortunately, I started working on it late, so the result did not meet my initial expectations.

<b>Final Grade: 4</b>

### Production intelligence and process information systems:

This course stood out from the others, as it felt more like a small foray into the industrial/manufacturing field. We had a presentation from an external vendor on intelligent maintenance, which was particularly insightful. I also learned about Lean 4.0 and attended a presentation on industrial digitalization.

There's huge potential on the data side in the industry, and I believe we are still very much at the beginning. I expect we will see many useful and smart solutions emerging in the future.

<b>Final Grade: 5</b>

### Cloud security:

The course included a Cloud Security Fundamentals module provided by Palo Alto Networks. It was useful to see things from a networking perspective, but overall, the course didn't leave a significant impression on me.

<b>Final Grade: 5</b>

## III. Lessons from this Semester:

This semester has left me with a completely different impression compared to the first. I found that the subjects fell into one of two extremes: some were very interesting and provided useful knowledge, while others had the potential to be interesting but unfortunately didn't meet expectations.

With two semesters left, I have completed most of my courses, so my focus will now shift to my thesis. I already have my topic, but I'll be sharing more about that in a separate series of posts later. 