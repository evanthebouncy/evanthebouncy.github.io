---
layout: about
permalink: /
profile:
  align: right
  image: profile.png
published: true
---

I develop program synthesis algorithms that ground human instructions as codes[^1], in a way a programmer would. A programmer does much more than generating Python from comments. Given an instruction (stated in language, test cases, or drawings), a human programmer can infer latent goals, generate code appropriate for the current situation, and interact to repair misunderstandings and overcome implementation difficulties.

My work studies **natural programs** — instructions given to a person to carry out a task on a computer (e.g. modifying a 3D scene or coding). I curate datasets of natural programs, and build program synthesis systems inspired by cognitive science that grounds them as executable code, in a way a human would. I work on neuro-symbolic methods, computational pragmatics, and grounded semantics of natural language. 
<!-- For more information, the following papers are good starting points. -->
<!-- I collaborate with researchers from cogsci, nlp, pl, grahpics, and hci. -->

[^1]: Code in a general sense, as any interactions (programming, manipulating UI, acting in a simulation) with the computer.

### representative works
<span style="font-size:0.8em;"> For full list see my [google scholar](https://scholar.google.com/citations?user=LJnNKXMAAAAJ&hl=en), I use "Yewen Pu" as name in my publications. </span>

#### programming by informative examples (PBiE)
<span style="font-size:0.8em;">  [Program Synthesis with Pragmatic Communication](https://arxiv.org/abs/2007.05060) (NeurIPS 2020). </span>

<span style="font-size:0.8em;"> [Generating Pragmatic Examples to Train Neural Program Synthesizers](https://arxiv.org/abs/2311.05740) (ICLR 2024). </span> 

#### grounding natural language as search problems
<span style="font-size:0.8em;"> [Communicating Natural Programs to Humans and Machines](https://arxiv.org/abs/2106.07824) (NeurIPS 2022). </span>

### collaboration
I believe quality research is a consequence of a good "party" -- in a sense of a good team 👥, and a good time 🎉. I collaborate broadly as code generation is applicable to various disciplines.
 <!-- I rely heavily on [my collaborators](/collaborators/) for their expertise, guidance, and encouragement.  -->
Here is my [mentoring statement](/mentoring-statement/).

### news

* <span style="font-size:0.8em;"> 2024-01-16: Two papers accepted to ICLR. [Hypothesis Search](https://arxiv.org/abs/2309.05660) deals with programming by examples (PBE) in a challenging (ARC) domain, where LLM performing the inductive step from examples to programs. [Generating Pragmatic Examples to Train Neural Program Synthesizers](https://arxiv.org/abs/2311.05740) is a general method that allows any PBE system to take account of user's informativity in generating examples, scalable to combinatorically complex space of programs. </span>

* <span style="font-size:0.8em;"> 2023-12-01: Two papers accepted to NeurIPS, [ANPL](https://arxiv.org/abs/2305.18498) and [DiffVL](https://neurips.cc/virtual/2023/poster/70947). The overall theme of both paper is grounding natural language as **search problems**, providing an alternative to the conventional approach of grounding natural language directly into executable code. </span>

* <span style="font-size:0.8em;"> 2022-10-13: The first installment to my minimalistic guide to program synthesis [is live!](https://evanthebouncy.github.io/program-synthesis-minimal/). It took me two months to write, get feedbacks, and edit. Hope you find it useful!! </span>