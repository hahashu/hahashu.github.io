---
layout: page
title: AI learns to touch 👋 🧣
description: Exploring Human-AI Perception Alignment in touch Experiences
img: assets/img/hai_tsne.png
importance: 3
category: PhD work
related_publications: true
---

We introduces **perceptual alignment** as a critical aspect of human-AI interaction, focusing on bridging the gap in tactile perception alignment between humans and AI.

Our research present the **first exploration** of this alignment through the "textile hand" task across two studies, examining how well LLMs align with human **touch experiences**  {% cite zhong2024feeling %} and {% cite zhong2024exploring %}.


### Study 1 
We assess how Multimodal LLMs interpret textile tactile qualities compared to human perception—a key challenge for online shopping environments.
In person study with 30 participants. 
We evaluate models from GenAI families: 
- OpenAI GPTs, 
- Google Geminis,
- Anthropic Claude 3. 

Check the paper
[Feeling Textiles through AI: An exploration into Multimodal Language Models and Human Perception Alignment
](https://dl.acm.org/doi/10.1145/3678957.3685756) 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hai_tsne.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Human descriptions (crosses), AI-generated descriptions from MLLM models (dots), and LLM models (triangles) visualised in 2D t-SNE.
</div>

### Study 2
- We introduce a novel interactive task probes LLMs' learned representations for human alignment.
- First study on alignment between human touch experiences and LLMs in embeddings.
- LLMs show perceptual biases, aligning better with certain textiles than others.


For details check our [video](https://youtu.be/XFD3E-U5Q8c) and [paper](https://arxiv.org/abs/2406.06587) 


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/aitouch_set-up.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/p_touch.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Overview of the user study setup: A participant handling textiles in a "``"Guess What Textile" task interact with custumised AI system.
</div>
