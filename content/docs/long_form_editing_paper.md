---
title: "Research Progress: Evaluating Model Editing for Natural Language Generation"
date: 2023-09-23T15:30:03+00:00
tags: ["NLP", "Model Editing", "Natural Language Generation", "Research Update"]
author: "Yahya Kayani"
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "Starting on a new research journey to evaluate model editing in natural language generation."
canonicalURL: "https://canonical.url/to/page"
disableHLJS: true
disableShare: false
hideSummary: false
searchHidden: true
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
cover:
    image: "<image path/url>"
    alt: "<alt text>"
    caption: "<text>"
    relative: false
    hidden: true
editPost:
    URL: "https://github.com/domenicrosati/longform_edit_model_evals"
    Text: ""
    appendFilePath: true
---

## **September 23, 2023: Embarking on Model Editing Evaluation**

### **Research Leadership**

This research is spearheaded by [Domenic Rosati](https://github.com/domenicrosati). Domenic is pivotal in bringing this project to completion and bringing the team up to speed. Collaborating closely with him on this initiative are Yahya(Me), Melis, and Deepika.


### **Research Objective**

The primary aim of this project is to establish a framework for assessing paragraph-length generations from edited large language models. As the capabilities of large language models grow, so does the importance of understanding their behavior, especially when edited.

### **Collaborative Effort**

This research is a collaborative initiative involving:

- Domenic, Yahya, Deepika, Melis.
- Supervisors: Lizbeth Escobedo, Hassan Sajjad, Frank Rudzicz
- External Collaborators: Jason (from Counterfact+ dataset), Andrew

Relevant Resources:
- [Zotero Group](https://www.zotero.org/groups/5187924/long-form-model-edit-eval)
- [Overleaf Paper Draft](https://www.overleaf.com/4737549179znvrxghfcyqg)
- [Github Repository](https://github.com/domenicrosati/longform_edit_model_evals)

#### **Weekly Meeting Time**

Our team has set a weekly meeting every Wednesday from 10am to 11am AST to discuss progress, issues, and next steps.


### **Initial Steps**

Our first task was to design a 10-passage survey aimed at discerning various properties and values related to model editing. The design specifics and outcomes of this survey will be detailed in the next update.

### **Resources & Readings**

As we dive into this project, several readings and resources have been suggested by Domenic to lay a basic understanding of the subject matter:
- Basics: An understanding of neural networks, transformers, tokens, and more.
- Papers: From understanding the risks posed by language models to evaluating the ripple effects of knowledge editing.



## **October 7, 2023: Week 1 Milestones and Tasks**

### **This Week's Milestone: Introduction**

#### **Goals**

- Understand the overall project and its objectives.
- Familiarize ourselves with the background necessary for writing the introduction section.
- Frame an introduction for our paper.
- Pick a motivation paper to read for next week.
- Read and understand the editing survey we have designed.

#### **Slides**

- Slides for this week will focus on the above-mentioned goals.

#### **To-Do for Next Week**

##### **Pick Motivation Paper to Look At**

We have identified several papers that can serve as motivation for our work:

- Petroni, F., et al. (2019). "Language models as knowledge bases?".
- Jiang, Z., et al. (2020). "How can we know what language models know?".
- Elazar, Y., et al. (2021). "Measuring and improving consistency in pretrained language models".
- Lin, S., et al. (2021). "Truthfulqa: Measuring how models mimic human falsehoods".
- Gehman, S., et al. (2020). "Realtoxicityprompts: Evaluating neural toxic degeneration in language models".
- Bender, E. M., et al. (2021). "On the dangers of stochastic parrots: Can language models be too big?".
- Weidinger, L., et al. (2022). "Taxonomy of Risks posed by Language Models".

##### **All of Us Read**

- Yao, Y., et al. (2023). "Editing Large Language Models: Problems, Methods, and Opportunities".
- Visit the webpage: [Rome Lab](https://rome.baulab.info/)
- Read Appendix J and Counterfactual AI Writing Study in [Arxiv Paper](https://arxiv.org/pdf/2202.05262.pdf)



## **October 14, 2023: Week 2 Milestones and Tasks**

### **Last Week Recap**

#### **Questions and Feedback**

- Addressed questions about model editing.
- Discussed pre-test feedback, including issues with paragraph length and clarity of terminologies used for annotation.

### **This Week's Milestone: Related Works and Survey Deployment**

#### **Goals**

- Delve into related works, focusing on model editing and evaluation of model editing.
- Deploy the survey designed in Week 1.

#### **Slides**

- Slides for this week will center on the above goals.

### **To-Do for Next Week**

#### **Annotation Project**

- **Reading (All - Optional):**
  - Papers on annotation best practices and quality management.
  
- **Brainstorm by Freeform Annotating:**
  - Group 1 (Dom)
  - Group 2 (Deepika)
  - Group 3 (Yahya)
  - Group 4 (Melis)

- **Other Tasks:**
  - Develop a draft of Annotation Guidelines (Dom)
  - Select a Platform for Annotations (Dom)
  - Identify a Dataset for Annotation (Dom)

### **Annotation Session and Feedback**

#### **Session Overview**

- All team members participated in an annotation session.
- We followed the annotation guidelines to label pairs of sentences as consistent, inconsistent, or neutral.

#### **Issues and Feedback**

- The paragraphs for annotation were found to be too long, making the task cumbersome.
- Some terminologies used in the annotation guidelines were confusing.
  
#### **Action Items for Next Annotation Session**

- Shorten the paragraphs to be annotated.
- Clarify terminologies and guidelines for annotation.


### **Annotation Instructions**

#### **Task Description**

In this task, you will read pairs of sentences and label them as consistent, inconsistent, or neutral.

#### **Guidelines**

- **Consistent Sentence Pair**: A pair of sentences that agree with each other.
  - **Example**: The Eiffel Tower is in Rome. / Rome is home to the world famous Eiffel Tower.
- **Inconsistent Sentence Pair**: A pair of sentences that contradict each other.
  - **Example**: The Eiffel Tower is in Rome. / Paris is home to the world famous Eiffel Tower.
- **Neutral Sentence Pair**: A pair of sentences that is neither consistent nor inconsistent.
  - **Example**: The Eiffel Tower is in Rome. / Paris is a wonderful city to visit.

#### **Note**

The focus is not on the factual accuracy of the sentences but on their consistency or inconsistency with each other.

## **October 21, 2023: Week 3 Milestones and Tasks**

### **Last Week Recap**

- Deployed the survey designed in earlier weeks.
- Discussed related works.
- Conducted a pre-study on annotations.

### **This Week's Milestone: Methods for Data Collection and Annotation Guidelines**

#### **Goals**

- Finalize methods for data collection.
- Update Annotation Guidelines based on feedback and discussions.
- Pilot the new annotation guidelines.

#### **Slides**

- Slides for this week will encapsulate the above goals.

### **Updated Annotation Guidelines**

#### **Changes**

- **Video Tutorial**: A [video](https://www.loom.com/share/acb1231f2b774e60b8503e87654adfc5?sid=4959f30b-d350-4f2a-85b5-073b7d70f613) was made to explain the new guidelines.
  
- **Instructions**: The task now involves reading a passage of text and labeling a claim about that passage.
  
- **Classification**: The task has two parts:
  1. Classifying the passage as supporting, contradicting, or neutral towards the claim.
  2. Highlighting sentences that support or contradict the claim (if applicable).
  
- **Examples**: New examples were provided to illustrate what supporting, contradicting, and neutral passages look like.

### **To-Do for Next Week**

- Show [HyperMatrix Annotation Platform](https://hypermatrix.lighttag.io/label).
- Send reminders to those who haven't completed the survey.
- Provide feedback on the annotation proposal.
- Discuss the analysis plan for the survey.

#### **Round Table and Annotations Discussion**

- A round table discussion will be conducted to discuss the new annotation guidelines and the pilot study.

## **October 28, 2023: Week 4 Milestones and Tasks**

### **Last Week Recap**

- Conducted an annotation pretest.
- Krippendorff's Alpha was measured to be 0.54.

### **This Week's Milestone: Achieve Higher Agreement**

#### **Goals**

- Aim for higher agreement among annotators.
- Discuss discrepancies and plan for improvement.

#### **Slides**

- Slides will focus on achieving higher inter-rater reliability and discussing disagreements.

### **Round Table and Disagreement Discussion**

- A round table discussion will be held to openly discuss disagreements among annotations.
- Annotations will be reviewed on [Light Tag](https://lighttag.io/).
- Annotation guidelines will be revised and can be found [here](https://docs.google.com/document/d/1Ar1X7FZa5obS_vhL556VY9IJXq3cwoY_MwtBYufj8ww/edit).

### **To-Do for Next Week**

#### **Pretest and Annotation Strategies**

- Conduct another pretest.
- Based on the pretest results:
  - If Inter-Rater Reliability (IRR) is less than \( \alpha = 0.7 \), annotations will be split 2 ways.
  - If IRR is high, annotations will be split 4 ways.

#### **Handling Missing Context**

- Missing context in annotations was identified as a challenge.
- Two paths for addressing this:
  1. Provide the whole paragraph along with the sentence to be measured.
  2. Keep it at sentence pairs with a rule: if you don’t have enough information, label it as neutral.

#### **Other Tasks**

- Open the option for open text feedback.
- Complete 300 annotations.
- I (Yahya) will look into resources for training DeBERTa V3 on annotations, starting with [this course](https://huggingface.co/learn/nlp-course/chapter0/1?fw=pt).

## **Glossary and Context**

### **Inter-Rater Reliability (IRR)**

- **What it is**: Inter-Rater Reliability (IRR) is a metric used to measure the degree of agreement among multiple raters or annotators.
  
- **What it's for**: In the context of this project, IRR is important for ensuring that the annotations being made by different team members are consistent and reliable. This helps in the validation of the dataset being created.

### **Krippendorff's Alpha**

- **What it is**: Krippendorff's Alpha is a statistical measure used to determine the reliability of agreement among multiple coders. It is a more general form of the Cronbach's alpha and can be applied to any number of coders providing ordinal, interval, or ratio data.

- **What it's for**: In this project, Krippendorff's Alpha is used as a specific method to quantify IRR. It helps identify how much of the variation in the data can be attributed to the reliability of the annotators.

### **The Need for Higher Agreement**

- **Why it's important**: Achieving higher agreement among annotators is crucial for the validity and reliability of the data being generated. It ensures that the interpretations of the text are consistent, thereby making the conclusions drawn from the data more robust.

