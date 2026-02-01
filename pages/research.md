---
layout: default
title: Scholarship
---

---
<!-- My research focuses on software engineering and computer science education, exploring effective pedagogical approaches that integrate real-world, industry-aligned practices into the classroom. In particular, I investigate how automated and AI-driven tools, such as CI-based code assessment, static analysis, NLP, and large language models, can support formative feedback, improve code quality, and enhance learning outcomes for novice programmers. I am also interested in memory architecture design and the development of innovative data management techniques to improve application performance. -->
<!-- My current research focuses on software engineering education, exploring effective pedagogical and industry methods that integrate real-world software engineering practices and experiences into the classroom. The goal is to enrich the learning experience and help bridge the gap between academia and the software industry. I am also interested in memory architecture design and the development of innovative data management techniques that enhance application performance. -->

## Projects

---
My research focuses on software engineering and computer science education, exploring effective pedagogical approaches that integrate real-world, industry-aligned practices into the classroom. In particular, I investigate how automated and AI-driven tools, such as CI-based code assessment, static analysis, NLP, and large language models, can support formative feedback, improve code quality, and enhance learning outcomes for novice programmers. I am also interested in memory architecture design and the development of innovative data management techniques to improve application performance.

You can visit the SEPO Lab’s page for more info about my current research projects.
<!-- ### From Submission to Feedback: A CI-Driven Automated Solution for Code Assessment -->
<!-- ### From Submission to Feedback: A CI-Driven Automated Assessment for Student Code Submissions -->
### From Submission to Feedback: A LLM-Powered CI-Driven Automated Code Assessment

<!-- <img src="/assets/img/codinspct.png" alt="Example image" width="650" height="400"> -->

![Alt text](/assets/img/codinspct.pdf "CodeInspector architectural design.")

Timely, formative feedback is essential in academia, helping students reinforce learning and develop the skills needed for subsequent assignments and advanced topics. However, manually assessing code submissions is time-consuming and often results in delayed feedback. This project investigates state-of-the-art automated code assessment techniques and proposes CodeInspector—a CI-driven, semi-automated solution that leverages industry-standard tools to assess student code submissions and generate immediate feedback on quality and correctness, while supporting iterative learning and continuous improvement.

**Status:** Funded by the ENMU FRID Grant Program (2023-2025); Amount: $8471; Role: Principal Investigator.

<!-- #### Related Publications

- Essa Imhmed, Edgar Ceh-Varela, Ludwig Scherer, George Candal, and Ivan Sanjaya. WIP: CodeInspector: automated LLM-Supported CS1- Level code assessment. In 2025 IEEE Frontiers in Education Conference (FIE) (FIE 2025), page 4.98, Nashville, USA, November 2025.
- Ceh-Varela, E., Imhmed, E., Parten, C., & Scherer, L. (2025). Enhancing Code Assessment and Feedback Generation with GenAI Agents. In Innovative Educational Assessment with Generative AI: Opportunities, Challenges, and Practical Case Studies (pp. 275-297). Cham: Springer Nature Switzerland. -->

#### Students

- **Ludwig Scherer** (2025 - current) – Undergraduate Research Assistant on the CodeInspector project.
- **Scott Kilgore** (2023 - 2024) – Undergraduate Research Assistant on the CodeInspector project.

---

### AI-Driven Static Analysis and Feedback Generation

A common challenge among novice programmers is interpreting runtime error stack traces and manually detecting logic and style errors in their Java code, often leading to inefficient debugging and poor coding practices. This study aims to design an AI-driven static analysis and feedback-generation approach that leverages natural language processing (NLP) and machine learning clustering techniques to statically identify code errors.

**Status:** Funded by the ENMU FRID Grant Program (2025–2026); Amount: $2,046; Role: Principal Investigator.

#### Students

- **George Candal** (2025 - current) – Undergraduate Research Assistant on the project.
- **Ivan Sanjaya** (2025 - current) – Undergraduate Research Assistant on the project.

---

### Local Memory Store for Embedded Systems

![Alt text](/assets/img/LMStoreArchit.pdf "LMStore architecture.")
<!-- <p><a href="/assets/img/LMStoreArchit.pdf" target="_blank">Figure 1: LMStore Architecture (PDF)</a></p> -->

Local Memory Store (LMStore) is a novel scratchpad memory (SPM) design, featuring some hardware management of the SPM along with explicit access and interaction by the program. Rather than presenting the program with a flat, directly accessed address space, LMStore uses indirect references in the form of 2-tuples and 3-tuples to access data stored in its memory, allowing LMStore to manage its memory more effectively for better utilization. This project explores data management schemes specifically designed to maximize LMStore performance, with a focus on reducing power consumption and minimizing memory access latency in embedded programs.

<!-- #### Related Publications

- Imhmed, E., Ceh-Varela, E., Cook, J., & Parten, C. (2023, June). Evaluation of the performance impact of SPM allocation on a novel scratchpad memory. In 2023 IEEE 47th Annual Computers, Software, and Applications Conference (COMPSAC) (pp. 972-973). IEEE.
- Imhmed, E., Cook, J., & Badawy, A. H. (2022, September). Evaluation of a novel scratchpad memory through compiler supported simulation. In 2022 IEEE High Performance Extreme Computing Conference (HPEC) (pp. 1-7). IEEE. -->

**Status:** Completed; interested in more.

#### Students

- **Caleb Parten** (Spring 2023) – Undergraduate Research Assistant on the LMStore project.

---

## Selected Publications

1. **E. Imhmed**, E. Ceh-Varela and M. Elfituri, "Using Scrum to Improve Student Teamwork in a Project-Based Hybrid Learning Setting," 2025 IEEE Frontiers in Education Conference (FIE), Nashville, TN, USA, 2025, pp. 1-8, doi: 10.1109/FIE63693.2025.11328266.
2. **E. Imhmed**, E. Ceh-Varela, L. Scherer, G. Candal and I. Sanjaya, "WIP: CodeInspector: Automated LLM-Supported CS1-Level Code Assessment," 2025 IEEE Frontiers in Education Conference (FIE), Nashville, TN, USA, 2025, pp. 1-5, doi: 10.1109/FIE63693.2025.11328429.
3. Ceh-Varela, E., **Imhmed, E.**, Parten, C., & Scherer, L. (2025). Enhancing Code Assessment and Feedback Generation with GenAI Agents. In Innovative Educational Assessment with Generative AI: Opportunities, Challenges, and Practical Case Studies (pp. 275-297). Cham: Springer Nature Switzerland.
4. Ceh-Varela, E., & **Imhmed, E.** (2024, May). Investigating Freshmen Students’ Coding Standards Challenges Using NLP Techniques. In International Conference on Information, Communication and Computing Technology (pp. 3-15). Cham: Springer Nature Switzerland.
5. **Imhmed, E.**, Ceh-Varela, E., Abu-Gellban, H., & Kilgore, S. (2024). Fostering Code Quality Practices Among Undergraduate Novice Programmers. Journal of Computing Sciences in Colleges, 39(7), 21-32.
6. **Imhmed, E.**, Ceh-Varela, E., & Kilgore, S. (2023, December). Identifying code quality issues for undergraduate students using static analysis and NLP. In 2023 International Conference on Computational Science and Computational Intelligence (CSCI) (pp. 1527-1533). IEEE.
7. Abu-Gellban, H., & **Imhmed**, E. (2023, December). Efficient Crop Classification Using Optical and Radar Big Data: A Time and Cost Reduction Approach. In 2023 International Conference on Computational Science and Computational Intelligence (CSCI) (pp. 598-604). IEEE.
8. **Imhmed, E.**, Ceh-Varela, E., Cook, J., & Parten, C. (2023, June). Evaluation of the performance impact of SPM allocation on a novel scratchpad memory. In 2023 IEEE 47th Annual Computers, Software, and Applications Conference (COMPSAC) (pp. 972-973). IEEE.
9. **Imhmed, E.**, Cook, J., & Badawy, A. H. (2022, September). Evaluation of a novel scratchpad memory through compiler supported simulation. In 2022 IEEE High Performance Extreme Computing Conference (HPEC) (pp. 1-7). IEEE.

---
