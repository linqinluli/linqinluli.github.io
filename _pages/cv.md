---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======

* M.S. in Computer Technology, Shanghai Jiao Tong University, 2022 ———— Present
* B.S. in Computer Science and Technology, Shanghai Jiao Tong University, 2022

Publications
======

<ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching experience
======

* CS3328 - Cloud Computing Technology, Shanhai Jiao Tong University, Sept. 2024 ———— Present
  * Teaching Assistant
  * Duties included: Design the course experiments and projects.

Working experience
======

* Cloud Storage Innovation Lab, Huawei Cloud, Chengdu, China, Sept. 2023 ———— Present
  
  * Research Intern
    
    <!-- * Duties includes: Updates and improvements to template -->
  * Supervisor: Jie Meng

* China Regional Commercialization, ByteDance, Beijing, China, May 2022 ———— Sept. 2022
  
  * Big data development
    
    <!-- * Duties included: Merging pull requests -->
  * Supervisor: None

Projects
======

* Memory System for Large Language Model Agents
  
  **Independent Research** Jul. 2024 ———— Present
  
  * Researching the memory system for LLM agents, especially the context(including agent ”memory”, agent tools’ results, and outer knowledge) cache system

* Optimization of LLM Inference Framework(Based on vLLM)
  
  **Contributor** >Jan. 2024 ———— Jun. 2024
  
  - Constructed an inference caching system based on prefix matching, dynamically managed the KV cache in the inference process, realized KV cache reuse in multi-round dialogs of the same user, and improved the inference performance.
  - Realized the disaggregation of Prefill and Decode phases in cluster scenarios to coordinate the differences in throughput between the two phases and improve the overall memory and computation utilization efficiency.

* High-bandwidth Multi-stream  Parallel Data Swap System in Memory Pool
  
  **Main Contributor** >Sept. 2023 ———— Feb. 2024
  
  - Designed and implemented a differentiated memory offloading mechanism for the memory pool in the data center based on the memory access patterns of different services. 
  - Implemented a memory swap system with stream-level and path-level parallelism to enhance swap performance.

* Application-Aware Multi-Path Far Memory Management System 
  
  **Main Contributor** >Jun. 2022 ———— Apr. 2023
  
  - Designed and implemented a memory system utilizing the VM kernel separation mechanism to achieve application transparency and awareness, isolating the swap paths between different applications to achieve parallel swaps.
  - Designed and implemented an optimization system for backend selection and parameter adjustment of swap path.

Skills
======

**Programming Language**: C/C++, Python, SQL, Latex
**Soft Skills**: Linux; Linux kernel (memory part); RDMA; Pytorch; ML basics; LLM basics; Big data basics
**Language**: English (TOEFL 107: R:30, L:29, S:21, W:27)

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
