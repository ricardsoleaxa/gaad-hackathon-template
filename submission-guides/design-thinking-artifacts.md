# Design Thinking Guide

The instructions herein provide guidance on how a participating hackathon team can get started on the delivery of the requirements for their selected event track. 

>NOTE: These instructions are applicable to both event tracks.

## Prerequisite Education

### Plenary Sessions

The following plenary sessions are recommended before beginning the hackathon. Please refer to the [Participants Guide][1] for the schedule of sessions. 

**Highly Recommended for Design Thinking track:**
* Design Thinking Experience 
    * Design Thinking 101: What, why, where Design Thinking is used
* Design Thinking Recipe Overview for Atomic Accessibility Design Challenge
    * Overview of a Design Thinking recipe (set of exercises) to help create user-centered use cases
* Atomic Accessibility Design Theme Builder Workshop
    * Overview of the Theme Builder tool, how to use it, example use cases
* [Mural 101](mural.co)
    * Overview of the collaboration tool, Mural. (Hint: you will be utilizing Mural for the Design Thinking recipe)

**Additional Sessions that might be beneficial:**
* Atomic Accessibility Design Theme Builder for Designers workshop
    * Overview of how Designers can best utilize the theme builder tool to create accessible solutions
* Atomic Accessibility Design Theme Builder for Developers workshop
    * Overview of how Developers can best utilize the theme builder tool to create accessbile solutions
### Getting Access to Mural
You will need access to Mural to participate in Design Thinking activites. Refere to the links below to get started:
* [Getting Access to Mural & Using the Template](/submission-guides/mural/mural-instructions.md)
* [Mural FAQ](/submission-guides/mural/mural-faq.md)

### Developing Sequence Diagrams

Familiarity with UML sequence diagrams is suggested:

* [What is a Sequence Diagram?](https://en.wikipedia.org/wiki/Sequence_diagram)
* [Why use UML Sequence Diagrams?](https://www.lucidchart.com/pages/uml-sequence-diagram)
* [PlantUML Tutorial](https://plantuml.com/sequence-diagram)

### Developing User Stories

It is **highly recommended** that participating teams leverage the [sample use case story template](./../designs/story-template.md) to quickly and succinctly develop a story telling artifact that will meet the expectations of the judges.

## Sample Material
The following resources provide a bootstrap for participating hackers.

>ToDO: Sample Board templates
| Template | Description |
| --- | --- |
| Design Thinking Mural Board Template - I **Have** an Idea | [I Have an Idea - Innovation Accelerator TruCreds Workshop Template]() |
| Design Thinking Mural Board Template - I **Need** an Idea | [I Need an Idea - Innovation Accelerator TruCreds Workshop Template]() |
| Use Case Story | [Story template](../designs/story-template.md) |
| Design Thinking Playback Template | [PowerPoint Template Download](https://discoverfinancial.sharepoint.com/:p:/s/TCI-Innovation/EfcdhWb8qxRGlSNyRQjt2sEBqrwKtnnUpef5Ja4pKY4Atg?e=qUrfOR)

## Exit Criteria
Upon successful completion of this guide, the following hackathon checklist requirements will be produced:

| Artifact | Description |
| --- | --- |
| Design Thinking Mural Board | URL to whiteboard used for team brainstorming. |
| Use Case Story | Markdown file describing the use case with support by UML diagrams. 
| Design Thinking Playback Brief | PowerPoint Presentation used to convey results of Design Thinking activities. This presentation *should* be used for the creation of the 2-min Concept Video. |

## Instructions
### Design Thinking Day

The Design Thinking day is for you and your team to take time ***before*** the Hackathon to use Design Thinking templates that are being provided to help you during the hackathon, as well as to help you prepare the presentation for your project.

**Use our Design Thinking Mural templates to help you:**
* Brainstorm a **new** idea or jump start an **existing** idea
* Empathize with your users
* Gain a better understanding of the problem your trying to solve
* Identify and document your use case story
* Understand where you should focus your time
* Fast track your presentation

### Design Thinking Day Assets
>Note: You will need FREE access to Mural. See [instructions](./submission-guides/mural/mural/mural-instructions.md) for how to get set up.
 
**Use the Mural templates listed below that best fits your needs:**
* [I Have an Idea](**TODO**)
* [I Need a Idea](**TODO**)

**If you need help understanding any of the exercises, please refer to any of the follow:**
* [Video of a team going through all the exercises](https://web.microsoftstream.com/video/deb6f4ce-1b36-4450-8b7a-5d87b95c4c79)
```Note: At the beginning of each exercise a facilitator describes the method. There are also time codes in the video details that let you skip to sections with the specific methods.```  
* [Example of a completed Design Thinking Mural Template
]()  
* [Design Thinking Mentor Slack Channel](https://join.slack.com/t/slack-ebi5711/shared_invite/zt-1rm7f1p0i-qHl_638lkDgi~1obuYXLcw)
    
April 24th - May 5th is designated as Plenary week. We will have a Design Thinking Day that your team should plan to attend to best prepare for the event. Design Thinking mentors will be available between 8:00AM-4:00PM Central on [Slack](https://join.slack.com/t/slack-ebi5711/shared_invite/zt-1rm7f1p0i-qHl_638lkDgi~1obuYXLcw)
 

### Use Case Story

The objective here is to develop a human readable use case that can be easily consumed by business and technical readers. 

#### Develop UML

1. Pick a UML design tool (LucidCarts, PlantUML, other). Refer to [suggested tools](../submission-guides/tools.md).
2. Create a sequence diagram image and store it in the `./designs/images/uml` folder. Since diagram are often modified/altered, it is advised that you store the source files used to produce the diagram in the `./designs/src` folder.
3. Sometimes, a single diagram is too busy and would benefit from segmenting the steps into multiple diagrams. If multiple diagram are required, repeat `Step 2` for each required diagram. 
#### Develop Story

1. Make a copy of the provided story template file by replacing USECASE_NAME with the name of the team's use case.
   
   ```
   $ cp ./designs/story-template.md ./designs/USECASE_NAME.md 
   ```
2. Edit the story using the provided outline as a guide. Follow the provided inline template instructions. Feel free to augment the outline as needed. Leverage the `./designs/images` resources as directed. 

### Playback Brief

To help you streamline creating a presentation for your hackathon project, we have created a Google Slides template for you to use. The outline of this template follows exercises found in the Design Thinking Mural Templates, so make sure to take advantage of those!

[Google Slides Template](https://docs.google.com/presentation/d/1rZGvHs2P7DAQhsuU2DDylQQgRlUjdXpD9EbKw3yxOpc/edit#slide=id.p)


<!--- Reusable Resources --->
[1]: https://www.notion.so/tribegroup/Discover-GAAD-Hackathon-Participants-Guide-a7e0e146877645ea9b52981079ded691?pvs=4




