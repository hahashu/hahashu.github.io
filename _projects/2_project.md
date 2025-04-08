---
layout: page
title: TextileBot 🗣️♻️
description: LLM-Mediated Domain-Specific Voice Agents
img: assets/img/botopen.png
importance: 2
category: PhD work
related_publications: true
---

TextileBot is a domain-specific voice agent focused on the sustainability topic of textile circularity🧶. IIt is built into a smart device, a Raspberry Pi encased in 3D-printed housing, and was introduced in February 2023.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/ca.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Traditional vs LLM-based conversational agents with voice inputs and outputs method.
</div>

#### From task-agnostic to domain-specific

- We proposed use Taxonomy-Based Knowledge Structure Chain to embed Textiles into the agent, enabling continuous multi-turn conversations.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/taxprompt0.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Taxonomy-Based Knowledge Structure Chain. 
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm">
        {% include figure.liquid path="assets/img/botopen.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm">
        {% include figure.liquid path="assets/img/bot.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>

</div>
<div class="caption">
    TextileBot - The physical agent interface is composed of a 3D printed box (6), a speaker (5), a microphone (4), and a button (3), all integrated into the Google AIY board (2) mounted on the Raspberry Pi 3 Model B (1) presented in (a). Right: A participant interacting with the TextileBot used across all three voice-based agents (b).
</div>

- We developed 2 variation of TextileBot: Assistant & Expert

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/tbot_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From task-agnostic to domain-specific: on the topic of lunch (Vanilla GPT-3.5 model, TextileBot Expert, TextileBot Assistant)
</div>

For more information about TextileBot {% cite zhong2025llm %}, check our [paper](https://doi.org/10.1080/0144929X.2025.2456667).
