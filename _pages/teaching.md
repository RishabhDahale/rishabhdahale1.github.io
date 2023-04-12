---
layout: page
permalink: /projects/
title: Projects
description: A collection of my projects. Some are not included now as I need to take permission from my guide before making them public.
nav: true
---

<h4> Research Projects </h4>

* <strong>Automatic Music Accompaniment Generation</strong><br>
This is a part of my Master's thesis in which I aim to develop a computationally creative model for the automatic generating of good quality music conditioned on existing available information. Creating a complex work of art like music necessitates profound creativity. With recent advancements in deep learning and powerful models such as transformers, there has been huge progress in automatic music generation. In an accompaniment generation context, creating a coherent drum pattern with apposite fills and improvisations at proper locations in a song is a challenging task even for an experienced drummer. Drum beats tend to follow a repetitive pattern through stanzas with fills or improvisation at section boundaries. In this work, we tackle the task of drum pattern generation conditioned on the accompanying music played by four melodic instruments: Piano, Guitar, Bass, and Strings. We use the transformer sequence to sequence model to generate a basic drum pattern conditioned on the melodic accompaniment to find that improvisation is largely absent, attributed possibly to its expectedly relatively low representation in the training data. We propose a novelty function to capture the extent of improvisation in a bar relative to its neighbors. We train a model to predict improvisation locations from the melodic accompaniment tracks. Finally, we use a novel BERT-inspired in-filling architecture, to learn the structure of both the drums and melody to in-fill elements of improvised music.
<br>
[Thesis](/assets/pdf/DDP_Stage_2_Report.pdf) || [ISMIR 2022 Paper](https://arxiv.org/abs/2209.00291) || [ISMIR LBD 2021 Paper](https://arxiv.org/abs/2209.00291)
<!-- This is not the first work on music generation with machine learning methods, but here I'm focusing on generating accompanying drum beats for any given melody. The pattern and rhythm of drums plays a crutial role in perception of a song. Moreover drums are expected to maintain a tempo and keep the song (band) together by playing fills and improvising in an online fashion with other instruments. Due to such characterstics, generating coherent drum patterns is a difficult task. As work is still in progress, I cannot share the report or code, but if you are interested in knowing the progress you can check the paper accepted to ISMIR LBD 2021.<br>
[ISMIR LBD 2021 Paper](https://archives.ismir.net/ismir2021/latebreaking/000015.pdf) -->

* <strong>Monte Carlo Exploration Starts for POMDP</strong><br>
We study Monte-Carlo Exploring Starts for POMDP’s (MCESP), a memory-less, model-free reinforcement learning algorithm that integrates the Monte Carlo exploring starts into a local search of deterministic policy space to perform control tasks in partially observable Markov decision processes (POMDP’s). The novelty in this approach is the introduction of a new action-value function which ensures that the algorithm is theoretically sound and guarantees the convergence to locally optimal policies in some special cases. We implement the algorithm on multiple standard partially observable domains to demonstrate the convergence properties. We then go on to modify the algorithm so that the policy search now works in the space of stochastic policies. We verify the dominance of this modified version empirically over the deterministic version and other stochastic learning algorithms in partially observable domains.<br>
[Blog Post](https://rishabhdahale.github.io/blog/2022/aila-project/)


* <strong>Automatic Music Transcription</strong> <br>
This study is an attempt to solve a problem in Automatic Music Transcription (AMT) - namely, the problem of chord detection (a subset of which is, of course, note detection). <br>
[Report](/assets/pdf/AMT_Manual.pdf)


* <strong>Multiple Image Co-segmentation</strong><br>
In this work we develop methods for simultaneous segmentation of common foregound object from multiple (>= 2) images.


<h4> Course Projects </h4>

* <strong>Hear me if you can! (Audio Steganography)</strong><br>
Audio steganography is a technique for concealing the existence of information by embedding it within non-secret audio, called the carrier audio signal. There is a trade-off between the amount of information encoded and the imperceptibility of the change in the encoded audio. In this work, we implement a deep-learning based audio steganography technique. PESQ score is used as the evaluation metric to quantify the amount of degradation. We also study the time required for encoding the text as a function of it’s length, nature and PESQ. Lastly, we study the effect of a Gaussian Noise channel on our encoding technique.
<br>
[Report](/assets/pdf/audio_stego.pdf) ||  [Presentation](https://github.com/methi1999/stego-audio/blob/master/final_presentation.pptx) || [Code](https://github.com/methi1999/stego-audio)


* <strong>Two-Factor Challenge Response based Authentication</strong><br>
As the world progresses in the fields of science and technology, traditional security methods shall soon be phased out. Although the idea of voice-activated security has been around since the Arabian Night’s Alibaba and the forty thieves, its real world applications have been limited to bank vaults in movies. Conventional login password methods have been replaced by more inventive methods which take into account the uniqueness of certain parameters. Fingerprint and Retinal-scanner based identification systems have been installed in many places. However, we can agree that just speaking out the password is generally more convenient than positioning the eyeball for a retinal scan or placing a greased finger over the scanner. It is due to this reason that more and more applications are being fitted with voice controls. We aim to implement a voice-activated unlocking system which will verify the user-uttered password as well as the authenticity of the visitor.
<br>
[Report](/assets/pdf/voice_authentication.pdf)

* <strong>Game Theory based Human Pose Estimation and Tracking</strong><br>
A review of the paper [Atriculated Human Pose Tracking using Game Theory](https://ieeexplore.ieee.org/document/6738526) as a project for SC 631 Game Theory course at IIT Bombay.
<br>
[Presentation](/assets/pdf/SC_631_Course_Project.pdf)

* <strong>Phase Based Fingerprint Matching</strong><br>
A major approach for fingerprint recognition is to extract minute details from high-quality fingerprint images using algorithms like Harris Corner Detection, and then matching these stored minute details to those of a probe image. However, such an approach depends heavily on fingerprint surface condition (for instance, dirt on the fingerprint sensor glass, rough fingertips and so on). This makes realistic recognition systems unreliable. Using phase components of 2D discrete Fourier Transforms[1] makes it possible to achieve robust recognition with good accuracy even for low-quality fingerprint images, captured in unfavourable conditions.
<br>
[Report](/assets/pdf/CS663_Project_Report.pdf)

* <strong>Pipelined RISC Processor</strong><br>
A Reduced Instruction Set Computer implemented in VHDL as part of EE224 at IIT Bombay
<br>
[Report](/assets/pdf/risc_report.pdf) || [Specifications](/assets/pdf/risc_specs.pdf) || [Code](https://github.com/RishabhDahale/risc)

* <strong>Online Learning - Survey of Dueling Bandits</strong><br>
Conventional online learning settings require absolute feedback for each action (in the form of a reward or loss). However, in some cases, such feedback is not possible. E.g. search engine suggestions and their click-through-rate only tell us which action was preferred over the other. There is no absolute measure (such as how strongly was the clicked suggestion preferred over the ignored one). The Dueling Bandits framework solves this problem by assuming only the presence of feedback about the relative quality of each pair of actions. The aim of this project is a survey of various algorithms used in the Dueling Bandit setting.
<br>
[Report](/assets/pdf/bandit_report.pdf) || [Code](https://github.com/RishabhDahale/dueling-bandits)

* <strong>Case Study on Future of 4K Televisions</strong><br>
A case studey on the future of 4K televisions done as a part of EE 786 Developments, Trends and Economic Frontiers course at IIT Bombay
<br>
[Report](/assets/pdf/Case_Study.pdf)


<!-- <h2> Other Projects </h2> -->




<!-- <div class="projects">
  {% if site.enable_project_categories and page.display_categories %}
    {% for category in page.display_categories %}
      <h2 class="category">{{ category }}</h2>
      {% assign categorized_projects = site.projects | where: "category", category %}
      {% assign sorted_projects = categorized_projects | sort: "importance" %}
      {% if page.horizontal %}
        <div class="container">
          <div class="row row-cols-2">
          {% for project in sorted_projects %}
            {% include projects_horizontal.html %}
          {% endfor %}
          </div>
        </div>
      {% else %}
        <div class="grid">
          {% for project in sorted_projects %}
            {% include projects.html %}
          {% endfor %}
        </div>
      {% endif %}
    {% endfor %}

  {% else %}
  {% assign sorted_projects = site.projects | sort: "importance" %}
    {% if page.horizontal %}
      <div class="container">
        <div class="row row-cols-2">
        {% for project in sorted_projects %}
          {% include projects_horizontal.html %}
        {% endfor %}
        </div>
      </div>
    {% else %}
      <div class="grid">
        {% for project in sorted_projects %}
          {% include projects.html %}
        {% endfor %}
      </div>
    {% endif %}

  {% endif %}

</div> -->

