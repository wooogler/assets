# Setting the Research Questions

- When formulating research questions (RQs), it is essential to ensure that they help readers anticipate the research contribution, the method, and the result. This includes understanding what new knowledge will be gained, predicting the methods that will be used to achieve the research goals, and comprehending the significance, purpose, or problem that the research addresses. This practice aids in setting clear expectations for the research outcomes and methodologies.
- It is crucial that RQs are purpose-driven and not solely centered around the use of tools or technology. The focus should be on the intended outcome or purpose of the technology, rather than the technology itself. For example, instead of asking how a new technology can be used, frame the question around how it can achieve a specific goal or facilitate a process.

# Best Practices for Writing Abstracts

An effective practice for writing abstracts for research papers involves an initial drafting process. This can be achieved by copying the first sentence of each chapter and pasting them together. This method serves as a starting point for the abstract, ensuring that it reflects the role of each chapter. It also means that the first sentence of each chapter should effectively summarize its content.

The following content explains what should be included in the abstract.

- **Context and Significance**: Begin with one or two sentences explaining the context and significance of the study.
- **Problem Statement**: Include one or two sentences detailing the problem being addressed or studied.
- **Study Goal**: Provide one or two sentences explaining the goal of the study, which may involve describing what was done (e.g., using technologies to solve a specific issue).
- **Methodology**: Describe the method in one or two sentences.
- **Results**: Summarize the (anticipated) results in one or two sentences. This should be the most interesting AND significant takeaway of your study result.
- **Implications/Contributions** (optional): It is desirable to include one or two sentences explaining the implications or contributions of the work to the world. (Now that we know what we found from this study, what does it mean to the world, i.e., people, researchers, future self).

# How to write an Introduction

- When writing the introduction for a paper, it should include a summarized version of the entire paper. This includes the motivation, goal, method, results, and learnings. The introduction should be comprehensive and transparent, avoiding surprises for the reader. The aim is to make the paper predictable and clear as early as possible. Readers should get a warm fuzzy feeling that they felt like they read the entire paper if they finish reading the introduction to the level so that they don't feel the need to read the rest of them.
- Additionally, ensure that the main points and important information are presented early in the document. Avoid saving key insights or valuable content for later sections, as readers may not continue if they do not find the initial paragraphs engaging or informative. This approach helps maintain reader engagement and comprehension, allowing readers to anticipate the progression of ideas and arguments.
- When formulating research questions, it is essential to ensure that they help readers anticipate the research contribution. This includes understanding what new knowledge will be gained, predicting the methods that will be used to achieve the research goals, and comprehending the significance, purpose, or problem that the research addresses. This practice aids in setting clear expectations for the research outcomes and methodologies.

# Writing Discussions for Research Papers

- Check out the following external resources for guidance on writing discussion sections for research papers, particularly in the context of Human-Computer Interaction (HCI) studies.- Lennart Nacke's guide on writing a strong discussion section for CHI papers.  https://lennartnacke.com/how-to-write-a-strong-discussion-section-for-your-chi-paper
- D. Buschek's Medium article on writing better discussions for HCI studies. https://dbuschek.medium.com/how-to-write-better-discussions-for-your-hci-study-be851092f351 This practice suggests that Echolab values leveraging external expert advice to enhance the quality of their research outputs.

# LLM-Based Generative AI Usage Guidelines for Proofreading

- It is acceptable to use a large language model like ChatGPT for proofreading. While it is recommended to proofread their papers thoroughly before submission, those who use generative AI should ensure that the use of GPT does not alter the meaning or nuance of the original expression or disrupt the consistency of terms used.
- If ChatGPT introduces unnecessary complexity or uses overly sophisticated language, the changes should be rejected. Making it easy to read and understand is more important than making it sound like you are intelligent.
- Proofreading should be done paragraph by paragraph rather than in large chunks. This is because you have to carefully review the amount of content after each revision.
- Generative AI should NOT be used for proofreading quotes from interviewees or open-ended responses from participants.
- Do NOT use ChatGPT to generate any portion of the entire initial draft. Write on your own first.

# Topic Sentence

- **Topic Sentence Practice**:- The first sentence of any paragraph should ideally be a topic sentence, clearly stating the main idea or focus of that paragraph.
- If not used as the first sentence, ensure there is a compelling reason (e.g., storytelling), and consider writing the topic sentence initially and removing it in the final draft.
- Use visual distinctions (e.g., bold, underlined, or highlighted) for topic sentences during drafting to enhance clarity and focus for easy skimming by collaborators.
- **Drafting Process**:- After creating a rough outline, write the topic sentences for each paragraph before developing the paragraph bodies.
- Topic sentences should be simple initially and can be refined later.
- Review topic sentences to ensure they convey the intended message, flow together, and cover all major details.
- **Iterative Writing and Review**:- Writing paragraph bodies may reveal missing elements, necessitating revisions to topic sentences.
- Use topic sentences as a basis for summaries or abstracts by compiling them to form an initial draft.
- **Feedback and Collaboration**:- Collaborators can quickly understand the document's content by reading bolded topic sentences, facilitating efficient feedback and collaboration.

# Latex Tips

## Latex In-line comments command

- To manage inline comments in your academic writing using LaTeX, you can utilize the following commands. This is useful to leave comments in the rendered PDF, it is easier to get attention than comments in Overleaf, which is difficult to keep track of.```
\newcommand{\out}[1]{#1} % allows you to display comments
%\newcommand{\out}[1]{} % Use comment out the line and uncomment this if you want to hide all the in-line comments.
\newcommand{\sang}[1]{\out{{\small\textcolor{blue}{\bf [*** Sang: #1]}}}}
```
- I recommend **writing one sentence per line in LaTeX files**. Given one line break in the LaTeX file does not translate to line breaks in the PDF, writing one sentence per line makes it easier to identify overly long sentences. It also aids in communication and locating LaTeX errors, such as referencing specific lines like line 194.
- It is important to use only the LaTeX packages specified on the ACM website to avoid issues when preparing the camera-ready version of a submission.  For checking approved LaTeX packages, visit: https://authors.acm.org/proceedings/production-information/accepted-latex-packages.