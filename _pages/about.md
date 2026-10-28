---
layout: about
title: About
permalink: /
subtitle:

profile:
  align: right
  image: photo.jpg
  more_info: >
    <div class="profile-links">
    <a href="/assets/pdf/cv.pdf" title="CV"><i class="ai ai-cv"></i></a>
    <a href="mailto:joaomavc@gmail.com" title="Email"><i class="fa-solid fa-envelope"></i></a>
    <a href="https://scholar.google.com/citations?user=66CKQAsAAAAJ" title="Google Scholar" rel="external nofollow noopener" target="_blank"><i class="ai ai-google-scholar"></i></a>
    <a href="https://github.com/JMVCoelho" title="GitHub" rel="external nofollow noopener" target="_blank"><i class="fa-brands fa-github"></i></a>
    <a href="https://www.linkedin.com/in/jmvcoelho" title="LinkedIn" rel="external nofollow noopener" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
    </div>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: false # social icons are shown under the photo instead (profile.more_info)
---

My research interests lie in the areas of Machine Learning, Natural Language Processing, and Information Retrieval.

Currently a PhD Candidate at <a href='https://deec.tecnico.ulisboa.pt/'>IST (DEEC)</a> and <a href='https://www.lti.cs.cmu.edu/'>CMU (LTI)</a>, under the dual degree CMU-Portugal program, supervised by <a href='http://web.ist.utl.pt/bruno.g.martins/'>Bruno Martins</a>, <a href='http://ctp.di.fct.unl.pt/~jmag/'>João Magalhães</a>, and <a href='http://www.cs.cmu.edu/~cx/'>Chenyan Xiong</a>. 

My current research focuses on dense retrieval and deep search systems, including training LLM search agents with reinforcement learning, and building infrastructure for deep research. During summer 2025, I worked with the <a href='https://aws.amazon.com/products/connect/'>AWS Connect</a> team at Amazon on agentic search for contact centers.

<div class="publications recent-work">
  <h2>Recent Work</h2>
  <ol class="bibliography">
    <li>
      <div class="row">
        <div class="col col-sm-2 abbr"><span class="recent-date">Oct 2026</span></div>
        <div class="col-sm-8">
          <div class="title"><a href="https://arxiv.org/abs/2610.10955">Learning Multi-Step Query Rewriting via Corpus Feedback for Conversational Search</a></div>
          <div class="periodical">A conversational query rewriting agent that iteratively refines its queries based on the documents it retrieves, trained with reinforcement learning using retrieval quality as the only reward, without human rewrite annotations.</div>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col col-sm-2 abbr"><span class="recent-date">Jun 2026</span></div>
        <div class="col-sm-8">
          <div class="title"><a href="https://arxiv.org/abs/2606.10709">Effective Reinforcement Learning for Agentic Search by Recycling Zero-Variance Queries During Training</a></div>
          <div class="periodical">Returning zero-variance queries to the training pool for later resampling makes GRPO training of search agents more effective, with a 1.7B agent matching prior systems of up to 7B parameters.</div>
        </div>
      </div>
    </li>
    <li>
      <div class="row">
        <div class="col col-sm-2 abbr"><span class="recent-date">Jun 2026</span></div>
        <div class="col-sm-8">
          <div class="title"><a href="https://arxiv.org/abs/2606.17209">Beyond Parallel Sampling: Diverse Query Initialization for Agentic Search</a></div>
          <div class="periodical">DivInit is a training-free method that picks diverse first-turn queries for parallel search trajectories, reducing the redundancy that limits standard parallel sampling.</div>
        </div>
      </div>
    </li>
  </ol>
</div>
