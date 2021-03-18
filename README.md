# ItsLasagne
Question Generation and Answering, being a challenging task, has gained considerable attention in the past years. Even though significant milestones are achieved, when used in a real-time system, it needs indispensable optimization. This paper proposes an approach to developing an online platform that facilitates traditional processes by introducing a virtual assistant to support the educational programs by asking questions in natural language and getting an answer without reading the internal documents relevant to the problem. The system put forward is a cloud-based solution that automatically generates questions and provides sample answers from a given document(s). The entire architecture integrated into the WhatsApp interface with Twilio API's help offers a user-friendly experience.


## Overview

Querying a given document or understanding a considerable record is always a tedious task. Whether it be a research paper based on any topic or a textbook in pdf format, most of the content is becoming online, which opens up a huge opportunity to use the online content for better understanding and easily accessible information. Assume we have a 10-page pdf, and we need to refer to it to answer a specific question, but we do not know which part of the pdf the answer exists, here we can leverage Deep Learning and N.L.P. techniques. Question answering is becoming an exciting part of the N.L.P. due to the advancements in deep learning models such as transformers, neural networks, Etc.; question answering is getting increasingly popular. 

Open-domain question answering (Q.A.) is a task in natural language understanding that can be immensely useful for the users to understand better and find answers to their queries as soon as possible.

Another emerging topic in this field is question generation. Assume that a teacher wants to set a question paper for the students, he/she sets the questions from a particular domain, but for this, he/she needs to refer to the whole topic first and then frame questions out of it. Here, question generation using deep learning techniques can reduce the time spent reading the content and completes the task faster and efficiently.

Question generation is a task that takes the context text and an answer phase and then accordingly generates the question from these inputs. This field has become tremendously popular in the academic as well as industrial sectors.

We aim to combine both Question answering and question generation techniques in one place, which would help the user easily upload the content they need for processing, and based on the models present in the system, it will give the respective output to the user.

A user interface plays a vital role for the user. For easy accessibility of the system, the whole system is based on "WhatsApp" to be used through a chat-based system that is easy to understand and easy to use.

We propose a system capable of interacting with the user via whats app as a chat application and, based on the user's inputs, providing tasks such as question generation and question answering using the proposed models.
