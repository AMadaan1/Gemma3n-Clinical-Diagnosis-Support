# Gemma 3n: Clinical Diagnosis Support

## Problem Statement and Importance
According to BMJ Quality & Safety (from British Medical Journal, also stated on reports from Johns Hopkins Medicine) approximately ****795,000**** people die or are permanently disabled due to misdiagnosis a year in America alone. Current medicine focuses on *****aggregates and averages*****, and often neglects rarer diseases. 

The disease mentioned here is ****Immune Thrombocytopenic Purpura**** (ITP), and it is a rare disease according to Johns Hopkins Medicine. This may also be referred to as *****Thrombocytopenia with Immune Thrombocytopenic Purpura*****, as thrombocytopenia is simply having a low platelet count. Another one of the most common names used is ****Idiopathic Thrombocytopenic Purpura****. A quick description of ITP is that it is a disease where the body kills its own platelets.

ITP specifically was picked because of my own personal experience with misdiagnosis being able to cause serious damage. A member in my own family had ITP and consistently had ****trouble getting treatment and had been misdiagnosed****. This became ****near-fatal**** to my family member when he broke his arm and had to undergo surgery, with his condition causing surprise complications.

However, Gemma 3n, as can be demonstrated ****can diagnose a rare disease****, and one that has made nearly every injury amplified to the extremes. 

This project tries to make sure that other families like mine won't deal with the same situation and that more families can plan and be more informed regarding their diseases. This could help family members keep themselves and their loved ones safe, and not have to be sprung with problems in a life or death scenario.

Additionally, human doctors can have ****human problems****, meaning that they can be fatigued, be overloaded from work, and be under stress. All of these factors can ****make humans perform worse****.

Generative ****AI doesn't have these problems****. Furthermore, using GenAI is *****cheaper, easier, and faster***** than manually going to a doctor, scheduling an appointment, and paying hefty prices or waiting in long lines.

## Step by Step Solution
1. Takes patient file as a string (or inputted in the textbox on the Gradio interface).
2. Uses ****few-shot prompting**** by giving examples in order to return a structured version of the patient file as a JSON.
3. With the structured data, Gemma 3n analyzes everything under a ****persona prompt**** by roleplaying as a medical professional to come up with ****personalized diagnoses****.
4. Given the fact that this is Generative AI, it is not ethically sound to simply output diagnoses in full confidence. That is why Gemma is specifically told to ****give a *disclaimer***** about its limitations and how a real professional should be consulted.

## Framework
As discussed earlier, this project first ****parses then analyzes**** a patient file to make diagnoses.

This is done because this project does not only hold the potential to save lives through prediction, but it also solves a problem that plagues many applications of technology in healthcare, which is ****unstructured data****. By ****structuring the data**** so that it is very easy to understand and in a standardized format, ****it is more easy to use and implement****.

### The Use of Structured Data
According to the National Institutes of Health, ****80 percent**** of medical data is ****unstructured****. If we need to use data to create more products used in medicine, ****especially diagnosis prediction****, it needs to be in a *****standard, recognized, and understandable***** format. Currently, some data can be written in barely spoken languages, may never be translated, and be very hard for professionals across the globe to use in products that can change lives.

This project ****helps to solve that.**** It ****parses the file into a JSON****, outputting *****structured* data****, that AI can then diagnose.
