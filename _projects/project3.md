---
title: "Distributed Heterogeneous Training for Large Language Models using Ray and DeepSpeed"
collection: projects
type: "Projects"
permalink: /projects/project3
venue: "Course Project (Columbia University), Fall 2023 "
location: "High Performance Machine Learning"
---

Conducted ablation studies for exploring efficient heterogeneous (CPU + GPU) distributed training for language models such as BeRT and RoBeRTa over different factors such as batch size, number of CPU/GPU parallel workers etc. Ray was used for parallelizing CPU processes and Deepspeed’s ZeRO optimization was used for data parallelism along with mixed precision training for sentiment analysis.