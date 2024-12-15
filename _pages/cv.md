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

  **Research Intern**

* China Regional Commercialization, ByteDance, Beijing, China, May 2022 ———— Sept. 2022

  **Big data development Intern**

Projects
======

* LLM Agent Framework Construction and Related Researches
  
  **Main Contributor**,       Jul. 2024 ———— Present
  
  * Researching the system for LLM agents, especially the context (including agent ”memory”, tool results, and external knowledge) cache and position-independent KV cache system.

* Optimization of LLM Inference Framework(Based on vLLM)
  
  **Contributor**,               Jan. 2024 ———— Jun. 2024
  
  - Built a prefix tree to cache KV during inference, accelerating multi-round chat, shared knowledge chat (RAG), and multi-user chat, resulting in a 22.8% reduction in inference TTFT compared to vLLM.
  - Disaggregated the prefill and decode stages, distributing them across different GPUs for cross-cluster deployment, which
improved overall throughput by 25% compared to vLLM.

* High-bandwidth Multi-stream  Parallel Data Swap System in Memory Pool
  
  **Main Contributor**,           Sept. 2023 ———— Feb. 2024
  
  - Designed and implemented a service-aware memory offloading mechanism with a multi-queue structure for the memory pool in cloud computing, based on the memory access patterns of different services.
  - Implemented a data swap subsystem with stream-level and path-level parallelism to enhance data offloading performance, achieving a 50% memory reduction with less than 3% time overhead when integrated with the existing far memory system.

* Application-Aware Multi-Path Far Memory Management System 
  
  **Main Contributor**,           Jun. 2022 ———— Apr. 2023
  
  - Designed and implemented a memory system that leverages the VM kernel isolation mechanism to achieve application transparency and awareness, isolating swap paths between different applications to enable parallel swaps.
  - Designed and implemented an optimization system for backend selection and swap path parameter adjustment, achieving up
to 3.9x faster data swap performance and a 5.1x improvement in data center task throughput compared to SOTA systems.

Skills
======

**Programming Language**: C/C++, Python, SQL, Latex

**Soft Skills**: Linux; Linux kernel (memory part); RDMA; Pytorch; ML; LLM; Big data.

**Language**: English (TOEFL 109: R:29, L:30, S:22, W:28)

<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->
