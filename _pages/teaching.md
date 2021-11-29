---
layout: page
permalink: /projects/
title: Projects
description: A collection of my projects. Some of them are not included now as I need to take permissions from my guide before making them public.
nav: true
---

* <strong>Automatic Music Transcription</strong> <br> This study is an attempt to solve a problem in Automatic Music Transcription (AMT) - namely,
the problem of chord detection (a subset of which is, of course, note detection). <br>
[Report](/assets/pdf/AMT_Manual.pdf)

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
[Presentation](/assets/pdf/CS663_Project_Report.pdf)

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

