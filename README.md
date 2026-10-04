# 📚 15-Day Student Engagement Segmentation & LLM Course Guidance Project

## 📌 Project Overview

This project was developed progressively over a period of **15 days**, with a specific task assigned for each day. The overall objective was to build an intelligent **personalized course-guidance system** that combines **student video-lecture engagement analysis, student segmentation, lecture transcripts, course information, and Large Language Models (LLMs)**.

The project begins by analyzing student engagement with video lectures and grouping students into meaningful engagement segments. It then progressively builds a transcript-based course knowledge system and connects the identified student segments with personalized course guidance.

By the end of the 15-day development process, the project evolves into an **LLM-powered course assistant** capable of understanding student context, retrieving relevant course information from lecture transcripts, generating personalized learning recommendations, and providing an interface through which students can interact with the system.

---

# 🗓️ Day-by-Day Task Description

## 🔹 Day 1 – Student Engagement Segmentation & LLM Course Guide

**Assigned Task:**
Segment students based on video lecture engagement metrics, and deploy an LLM course guide that dynamically answers student questions using lecture transcripts.

The first day established the foundation of the project. Student engagement data from video lectures was considered using metrics such as viewing behaviour and engagement-related information. The objective was to identify different types of learners based on their engagement patterns.

Students were grouped into meaningful segments so that the system could later provide guidance according to their individual learning behaviour.

Alongside segmentation, the initial concept of an **LLM-based course guide** was established. Lecture transcripts were considered as the source of course knowledge, allowing students to ask questions and receive answers based on the available lecture content.

**Main outcome:**

* Student engagement analysis
* Student segmentation
* Introduction of transcript-based question answering
* Initial LLM course-guide concept

---

## 🔹 Day 2 – Student Segmentation & Transcript-Based Course-Guide Workflow

**Assigned Task:**
Develop student segmentation and define the transcript-based course-guide workflow.

The second day focused on strengthening the two major components introduced on Day 1: **student segmentation** and the **transcript-based course guide**.

The segmentation process was developed to identify different student profiles from engagement behaviour. At the same time, the workflow for the course guide was defined.

The transcript-based workflow describes how lecture information can be processed and used when a student asks a question. Instead of relying only on general LLM knowledge, the system uses lecture-transcript information as the basis for course-related responses.

**Main outcome:**

* Defined student segmentation workflow
* Defined transcript-processing workflow
* Established the relationship between student information and course guidance
* Created the foundation for retrieval-based course answering

---

## 🔹 Day 3 – Connecting Student Segments with Course Information

**Assigned Task:**
Connect student segments with transcript and course information.

On Day 3, the project moved from independent components toward an integrated personalized-guidance approach.

The student segments created during the earlier stages were connected with the available lecture transcripts and course information. This allows the system to consider not only **what the student is asking**, but also **what type of learner the student is**.

For example, different engagement levels can require different forms of guidance. A highly engaged student may benefit from deeper or advanced recommendations, while a less engaged student may require simpler explanations and additional learning support.

**Main outcome:**

* Student segments connected to course information
* Transcript information linked with learner context
* Beginning of personalized course guidance

---

## 🔹 Day 4 – Building the Course-Information Knowledge Base

**Assigned Task:**
Build the course-information knowledge base.

Day 4 focused on organizing course information into a structured knowledge base that can be used by the course assistant.

Lecture transcripts and course-related information were processed and organized into usable pieces of information. This provides the foundation for retrieving relevant course content when a student asks a question.

The knowledge-base approach helps the system locate information related to a particular course topic instead of treating the entire transcript as one large block of text.

**Main outcome:**

* Course information organized into a knowledge base
* Lecture transcript content prepared for retrieval
* Foundation created for transcript-based question answering

---

## 🔹 Day 5 – Designing Prompts for Personalized Course Guidance

**Assigned Task:**
Design prompts for personalized course guidance.

Day 5 introduced the prompt-design component of the system.

Prompts were designed to provide the LLM with the appropriate information about the student's context and the relevant course material. The goal was to make the generated response more personalized instead of producing the same generic answer for every student.

The prompt structure considers the relationship between:

* Student profile
* Student engagement segment
* Student question
* Retrieved course information
* Desired guidance

This creates a controlled communication layer between the student information, course knowledge and the LLM.

**Main outcome:**

* Personalized prompt structure
* Student-context integration
* Course-context integration
* Improved LLM guidance strategy

---

## 🔹 Day 6 – Developing the Course-Guidance Assistant

**Assigned Task:**
Develop the course-guidance assistant.

On Day 6, the individual components were brought together to form the initial **course-guidance assistant**.

The assistant is designed to receive a student's course-related question, identify the relevant context, retrieve useful course information, and generate an appropriate response.

The system moves beyond simple question answering by incorporating student context into the guidance process.

**Main outcome:**

* Initial course-guidance assistant
* Student-aware question answering
* Transcript-based course responses
* Personalized guidance workflow

---

## 🔹 Day 7 – Testing Course Queries for Different Student Profiles

**Assigned Task:**
Test course queries for different student profiles.

Day 7 focused on testing the behaviour of the course assistant using different student profiles.

Different student segments were used to examine whether the assistant could adapt its responses according to the learner's characteristics.

The same or similar course questions could therefore be tested across different student profiles to observe whether the generated guidance changes appropriately.

**Main outcome:**

* Multiple student profiles tested
* Course queries tested across segments
* Personalized response behaviour examined
* Initial system behaviour validated

---

## 🔹 Day 8 – Evaluating Personalization and Recommendation Relevance

**Assigned Task:**
Evaluate personalization and recommendation relevance.

Day 8 focused on evaluating whether the system was actually providing useful personalized guidance.

The generated responses were examined based on two important aspects:

### Personalization

Whether the response appropriately considers the student's profile and engagement segment.

### Recommendation Relevance

Whether the recommended course material or learning guidance is relevant to the student's question and available course information.

This evaluation helps identify areas where the assistant performs well and areas where improvements are required.

**Main outcome:**

* Personalized responses evaluated
* Recommendation relevance evaluated
* Weaknesses in the guidance process identified

---

## 🔹 Day 9 – Identifying Unsuitable Course Recommendations

**Assigned Task:**
Identify unsuitable course recommendations.

Day 9 focused on identifying cases where the system may generate recommendations that are not suitable for a particular student.

A personalized system should not only provide recommendations but should also avoid recommendations that do not match the student's current context or learning requirements.

The testing process therefore considered inappropriate or unsuitable recommendations and examined how the system responds to such situations.

**Main outcome:**

* Unsuitable recommendations identified
* Recommendation quality examined
* Problems in personalization detected
* Basis established for improving the prompting strategy

---

## 🔹 Day 10 – Improving Student-Context Prompts

**Assigned Task:**
Improve student-context prompts.

Based on the observations from earlier testing and evaluation, Day 10 focused on improving how student information is provided to the LLM.

The prompt structure was refined so that the assistant receives clearer student-context information before generating a response.

The objective was to improve the connection between:
**Student Profile → Engagement Segment → Course Context → Student Question → Personalized Response**

This refinement helps the LLM produce responses that are more aligned with the individual learner.

**Main outcome:**

* Improved student-context prompts
* Better personalization instructions
* More structured LLM input
* Improved course-guidance behaviour

---

## 🔹 Day 11 – Personalized Learning-Path Generation

**Assigned Task:**
Add personalized learning-path generation.

Day 11 expanded the system beyond answering individual questions.

The course assistant was extended toward generating **personalized learning paths** based on the student's context and course requirements.

Instead of simply answering:

> “What is this topic?”

the system can move toward providing guidance such as:

* What the student should learn first
* Which course topics should be reviewed
* What topics can be studied next
* What learning direction is appropriate for the student's current level

This transforms the project from a simple course Q&A system into a more personalized learning-support system.

**Main outcome:**

* Personalized learning-path concept
* Sequential learning recommendations
* Student-specific course guidance

---

## 🔹 Day 12 – Developing the Course-Guide Interface

**Assigned Task:**
Develop the course-guide interface.

Day 12 focused on making the course assistant accessible through an interactive interface.

An interface allows students to interact with the course assistant rather than executing individual code cells manually.

The interface provides a more practical way for a student to:

1. Enter or provide their context.
2. Ask a course-related question.
3. Submit the query.
4. Receive personalized course guidance.

This stage moves the project closer to an application-level implementation.

**Main outcome:**

* Interactive course-guide interface
* Student-query interaction
* LLM response display
* More user-friendly system

---

## 🔹 Day 13 – Integrating Segmentation, Transcripts and LLM

**Assigned Task:**
Integrate segmentation, transcripts and LLM.

Day 13 focused on integrating the major components developed throughout the previous days.

The complete workflow connects:

**Student Engagement Data**
↓
**Student Segmentation**
↓
**Student Profile**
↓
**Lecture Transcripts / Course Knowledge Base**
↓
**Relevant Course Information Retrieval**
↓
**Personalized Prompt**
↓
**LLM**
↓
**Course Guidance / Recommendation**

This integration represents the central architecture of the project.

Instead of treating segmentation, course information and LLM responses as separate components, they work together as one personalized course-guidance pipeline.

**Main outcome:**

* Segmentation integrated
* Transcript knowledge integrated
* LLM integrated
* End-to-end personalized guidance workflow established

---

## 🔹 Day 14 – Validating Different Student Profiles

**Assigned Task:**
Validate different student profiles.

Day 14 focused on validating the integrated system using different student profiles.

The purpose was to ensure that the system behaves appropriately for different types of students and does not produce identical guidance regardless of learner context.

Different profiles and course-related questions were used to verify whether:

* The correct student context is considered.
* Relevant course information is retrieved.
* The LLM receives the appropriate context.
* The generated guidance matches the learner profile.

**Main outcome:**

* Different student profiles validated
* Integrated system behaviour checked
* Personalization consistency examined
* Final issues identified before demonstration

---

## 🔹 Day 15 – Demonstrating the Course Assistant

**Assigned Task:**
Demonstrate the course assistant.

Day 15 represents the final stage of the 15-day development process.

The complete course assistant was demonstrated as an integrated system combining student engagement segmentation, transcript-based course knowledge, personalized prompting, LLM-based responses, and the course-guide interface.

The final demonstration shows how a student's profile and course question can move through the system to produce personalized course guidance.

The project therefore progresses from **raw engagement information** to a complete **AI-powered personalized learning assistant**.

**Main outcome:**

* Complete course assistant demonstrated
* End-to-end workflow presented
* Student segmentation and personalization demonstrated
* Transcript-based LLM guidance demonstrated
* Final project workflow completed

---

# 🔄 Overall 15-Day Development Journey

The 15-day work can be summarized as the following progression:

```text
Student Engagement Data
        ↓
Student Segmentation
        ↓
Student Profiles
        ↓
Lecture Transcripts
        ↓
Course Knowledge Base
        ↓
Information Retrieval
        ↓
Personalized Prompt Design
        ↓
LLM Course Assistant
        ↓
Profile-Based Testing
        ↓
Personalization Evaluation
        ↓
Recommendation Improvement
        ↓
Personalized Learning Paths
        ↓
Interactive Interface
        ↓
Full System Integration
        ↓
Profile Validation
        ↓
Final Course Assistant Demonstration
```

## 🎯 Final Project Outcome

At the end of the 15-day development process, the project establishes a personalized **LLM-based course-guidance system** that combines student engagement analysis with course knowledge derived from lecture transcripts.

The system is designed to understand different student profiles, retrieve relevant course information, incorporate student context into prompts, and generate personalized guidance and learning recommendations.

The project demonstrates how **student analytics + transcript-based knowledge + retrieval + prompt engineering + LLMs + user interaction** can be combined to create an intelligent learning-support system.

---

## 🧩 Key Components Developed

| Component                     | Purpose                                           |
| ----------------------------- | ------------------------------------------------- |
| Student Engagement Analysis   | Understand student learning behaviour             |
| Student Segmentation          | Group students based on engagement                |
| Lecture Transcript Processing | Convert lecture content into usable knowledge     |
| Course Knowledge Base         | Organize course information                       |
| Information Retrieval         | Find relevant course content                      |
| Prompt Engineering            | Provide student and course context to the LLM     |
| LLM Course Assistant          | Generate course-related responses                 |
| Personalization               | Adapt guidance to different students              |
| Recommendation Evaluation     | Check relevance of recommendations                |
| Learning Path Generation      | Suggest personalized learning progression         |
| Interactive Interface         | Allow students to interact with the assistant     |
| System Integration            | Combine all components into one workflow          |
| Validation                    | Test the system across different student profiles |

## 🏁 Conclusion

This 15-day project follows a progressive development approach, beginning with **student engagement segmentation** and gradually developing into an **interactive personalized LLM course assistant**.

Each day's task contributes a specific component to the final system. The progression demonstrates the complete journey from analyzing learner behaviour and organizing educational content to integrating an LLM capable of providing context-aware course guidance.

The final system provides a foundation for personalized learning by connecting **who the student is, how they engage with learning content, what they are asking, and what information is available in the course material**.
