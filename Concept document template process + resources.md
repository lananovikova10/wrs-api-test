---
title: "[]{#_oh7thv8pn6m3 .anchor}Concept Document Process"
---

This document explains best practices for researching, writing, and
maintaining a concept document. It extends and structures the
information described in the template guide in a step-by-step way. As
you explore this process document, you\'ll gain insights into crafting
clear and consistent concept documents.

## Before writing a concept document

Before you begin working on your Concept Document, you may take the
following preparatory steps to ensure that you are well-equipped to
create a comprehensive and effective document:

-   Learn about your audience: Understand your target audience or
    audiences, their familiarity with the subject matter, roles,
    responsibilities, and specific needs or pain points. This knowledge
    will empower you to tailor the document\'s content and language
    effectively.

-   Map Out the Concept: Create an overview or map of the concept,
    including its connections to other concepts, its place within the
    broader system, and dependencies. This step helps your understanding
    and may later serve as a visual aid in your concept document (See
    the Visual aid section below).

-   Explore the Concept\'s Background: Gain insights into the
    prehistory, background, and any limitations that have shaped the
    concept. Engage with developers or project managers to grasp the
    broader context in which the concept operates.

-   Define Scope and Boundaries: Clearly outline what the concept
    encompasses and what it does not, research information within these
    boundaries.

-   Collect Common Questions and Concerns: Review internal chats,
    external support systems, or public discussions to gather common
    questions and concerns related to the concept. Look for inquiries
    such as \"What is it?\" \"Why do I need it?\" \"Why not use Y?\"
    \"When shouldn\'t I use it?\" to anticipate and address them in your
    document.

## A Guide to Naming Your Concept Document

There is a difference between the type of information and the actual
document titles. The type of information is usually called Concept (used
in GitLab and DITA frameworks) or Explanation (used by Diataxis
framework). Both terms refer to the same document type --- "a high-level
overview of a specific topic, concept, or feature; that helps a user to
understand complex ideas, and provide them context and background" and
we will consider them as synonyms in the scope of this template guide.

Within a documentation set, you have some flexibility in the title
naming convention. Common title options include:

-   Overview of {concept or subject}

-   Introduction to {concept or subject}

-   About {concept or subject}

-   Understanding {concept or subject}

-   Background

-   Name of the {concept or subject} as a noun, for example, Payments.
    GitLab in their contribution guideline recommended this option as
    main.

Less common options include:

-   Crash Course

-   {concept or subject 101}

-   {concept} Tour

We do not recommend using just Overview or Introduction without any
following words as this without pointing to a specific concept using a
noun makes a concept document less discoverable.

This is especially important from an SEO perspective. When readers or
search engines encounter a document titled \"Overview\" or
\"Introduction,\" it doesn\'t provide a clear indication of the
content\'s subject matter. This can lead to reduced discoverability and
a less effective user experience. For example, it will not be included
into snippets that are displayed on top of search results.

For SEO optimization, it\'s recommended to use descriptive and
keyword-rich titles that clearly convey the main topic or concept
covered in the document. This not only improves discoverability but also
helps search engines understand the content\'s relevance to specific
queries.

**Note:** *Do not confuse a Concept document which is a part of
technical documentation with two other types of documents that are also
referred to as 'Concept Documents'. One of them is a Proposal or a
Request For Comments (RFC). The other is a component of the Game Design
Document (GDD). Both are commonly known as concept documents.*

## Define an audience or audiences

Identifying and understanding your target audience is a fundamental step
in creating an effective concept document. You may often need to write
for multiple audiences, such as a primary and secondary audience with
varying levels of expertise and interests. Consider the following
strategies to tailor your document to the needs of your diverse
readership:

1.  Identify audience categories: Start by categorizing your potential
    audiences. Are they developers, managers, end users, support
    engineers, or other relevant roles? Clearly define the primary and
    secondary audiences who will be engaging with your concept document.
    A good example of defining personas is [[The Good Docs's
    one.]{.underline}](https://docs.google.com/document/d/1QqiOEr2W4iG_0HWP0-wcjLudIJIRsvbd9pxHF1LrLqo/edit#heading=h.hsi0enkkga6)

2.  Assess specific needs and goals: For each audience category, assess
    their unique needs, goals, and expectations. Understand what they
    seek to gain from the concept document and how it can address their
    specific concerns or challenges.

3.  Determine industry relevance: Recognize the industry to which each
    audience belongs. Different industries may require distinct
    perspectives or applications of the concept, and tailoring your
    document to these contexts can enhance its value.

4.  Audience\'s role and relationship to the concept: Determine the role
    and responsibility of each audience in relation to the concept. Are
    they decision-makers, implementers, presenters, or evaluators?
    Understanding their roles will help you address their needs
    effectively.

5.  Contextual understanding: Dive deeper into the work situations and
    problems that your audience faces. Consider whether they are
    evaluating the concept, seeking to understand how to utilize it in
    practical scenarios, or preparing presentations about it. This
    deeper contextual understanding allows you to frame the concept in a
    way that resonates with your audience\'s real-world concerns.

When you are tasked with writing for multiple audiences, consider the
following strategies:

\- Chunking: Divide your concept document into clearly defined sections
or chunks. Each section can cater to a specific audience or address a
particular aspect of the concept. This structure enables readers to
easily skim and locate the information most relevant to them.

\- Split into multiple documents: If the concept is complex and the
information for each audience significantly diverges, consider creating
separate documents for each audience. This approach ensures that each
group receives tailored, focused content that directly addresses their
needs.

## Write a concept document

The process is described in the [[\[Concept Template
Guide\]]{.underline}](https://docs.google.com/document/d/1dyTP-KAJvrz6xDRexvn0XENJaU1VYkBHsOnXG5a81mQ/edit).

## Create visual aids for a concept document

Visual aids play a crucial role in concept documents by making complex
information more accessible and engaging for the reader.

Visual aids encompass various elements, including diagrams (such as
decision trees, context diagrams, and flowcharts), small videos,
comparison tables, and images. These elements are strategically chosen
to complement the narrative and help the reader grasp the concept more
effectively.

If you go with a diagram option, regardless of the type it should
represent relationships between key components, providing a
comprehensive overview of the concept\'s structure and connections.

  -----------------------------------------------------------------------
  Diagram Type     Value                   When to Use
  ---------------- ----------------------- ------------------------------
  Context Diagram  Provides an overview of Use when illustrating how the
                   system components and   concept fits into a broader
                   their interactions.     framework or ecosystem.

  Flowchart        Represents step-by-step Ideal for explaining
                   processes and decision  sequential procedures or
                   points. For example,    illustrating decision-making
                   how the concept evolved within the concept.
                   or which decisions were 
                   made throughout the     
                   evolution.              

  Decision Tree    Depicts decision        Effective when presenting
                   scenarios and outcomes. choices and consequences
                                           related to the concept.

  Infographic      Utilizes visuals and    Suitable for providing a
                   icons to convey complex high-level overview of the
                   information.            concept, especially when
                                           visual appeal is crucial. Can
                                           be used to visualize numbers.
  -----------------------------------------------------------------------

Incorporating visual aids follows principles of multimedia learning,
notably [[Mayer\'s spatial contiguity
principle]{.underline}](#articles-and-books). This principle emphasizes
the importance of keeping text and related visuals close together and
aligned. By doing so, concept documents prevent overwhelming the reader
with disjointed information and promote a seamless understanding of the
material.

Videos can be useful when demonstrating dynamic processes, showcasing
real-world examples, or providing an illustration of the process (for
instance, if some concept developed over time).

However, it might be useful to use videos sparingly and ensure they add
value to the document without overwhelming the reader, because watching
the video takes time and your reader may lose context of an article.
Also videos are expensive to produce and maintain. But the good news is
that conceptual documentation is slower to become obsolete than
instructional documentation, because processes and interfaces change
more often than fundamental concepts and approaches.

Videos for concept docs should be concise and short. Consider including
a white-board styled drawing to enhance information presented. Also,
videos are hard to skim through which is a frequent scenario for the
concept document.

By incorporating these visual aids strategically, concept documents not
only convey information more effectively but also enhance the reader\'s
overall comprehension of the concept at hand.

## Maintain a Concept document

To ensure that your concept document remains a valuable and reliable
resource, it\'s essential to establish a maintenance plan. Consider the
following best practices for keeping your concept document up-to-date
and accurate:

1\. Version Control: Implement a version control system for your concept
document. Use tools like Git or similar version control systems to track
changes and reference previous versions.

2\. Regular Review: Set a schedule for periodically reviewing the
concept document, especially when there are updates to the underlying
concept or when new linked concepts become available. Regular reviews
help ensure the document\'s continued relevance.

3\. Communication with Stakeholders: Maintain open lines of
communication with relevant teams, such as developers, project managers,
and subject matter experts, to ensure that the document reflects the
most accurate and up-to-date information about the concept.

4\. User Feedback: Consider adopting user feedback as a valuable source
of improvement. Solicit input from readers, stakeholders, and users to
identify areas where the document can be enhanced or clarified. Things
to test and gather feedback carefully are definitions, analogies and
metaphors, and examples.

5\. Testing Updates: Whenever there are significant updates to the
concept, test them to confirm that they are effectively conveyed in the
document. Verify that any changes in the concept\'s context and
components are accurately reflected. Some techniques to test the user
comprehension are --- ask a reader to retell the concept in their own
words (Explain Like I\'m 5 may work in this case), present readers with
real-world scenarios related to the concept and ask how they would apply
the knowledge in those situations, give readers an opportunity to
provide feedback through surveys or feedback forms --- this can reveal
areas of confusion or misunderstanding.

6\. Visual Components: Ensure that visual aids, if used in the document,
are also updated when necessary. Diagrams, charts, and other visuals
should remain consistent with any changes to the concept they represent.
To make it easier to keep them up to date, use the diagrams-as-code
approach (it means you describe the diagram with a markup and the
tooling takes care of the visual rendering, so that you don't need to
store them as pictures and update each time. Read more in Quick
introduction to Diagram as Code) and write diagrams using any notation
of your choice or a notation that is understandable by your audience.

7\. Documentation of Changes: Display document version. This
documentation serves as a reference for understanding the document\'s
evolution and the reasoning behind specific updates.Update the document
to reflect any new insights or changes in the concept\'s context.

Typically it is sufficient to include a \"Last Updated: {Date}\" on a
page, which may be provided by your Content Management System.

Versioning documents can help a returning reader expect change. If
versioning, consider using a MAJOR.MINOR.PATCH semantic versioning
pattern.

It may look somewhat like this:

Version \| Date \| Description

2.0 \| 2023-06-01 \| Added a new limitation

1.1 \| 2023-02-01 \| Enhanced explanation of key concepts

1.0 \| 2023-01-01 \| Initial Concept Document
