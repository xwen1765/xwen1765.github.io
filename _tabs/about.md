---
# the default layout is 'page'
layout: page
icon: fas fa-info-circle
order: 1
toc: false
---

<div class="row">
  <div class="col-md-8">
    <h2 id="about-xuan-wen">About Xuan Wen</h2>
    <p>I am a Ph.D. candidate in Neuroscience at Vanderbilt University, deeply fascinated by the intricate workings of the brain and devoted to investigating higher cognitive functions. My research spans reinforcement learning, cognitive mapping, and the neural basis of decision-making. With a strong background in both neuroscience and computer science, I leverage computational methods to unravel the complexities of cognition.</p>
    <p>In Dr. Thilo Womelsdorf's lab, my work focuses on understanding adaptive behavior and learning in primates. My research also involves developing innovative tools, such as a 3D stimuli generation toolbox, which I've made open-source for the scientific community. I'm also contributing to the development of a new software platform in Unity for animal cognition studies, pushing the boundaries of how we can study and understand animal behavior and cognition. My collaborations across disciplines allow me to delve into cutting-edge topics like Integrated Information Theory and collective intelligence. Driven by intellectual curiosity and a passion for interdisciplinary research, I aim to contribute meaningfully to our understanding of the brain's most sophisticated processes.</p>
  </div>
  <div class="col-md-4">
    <blockquote>
      <h2 id="education">Education</h2>
      <p><strong>Ph.D. in Neuroscience</strong><br>
      <em>Vanderbilt University, 2022 - Present</em></p>
      <p><strong>B.S. in Brain & Cognitive Science (Honors)</strong><br>
      <strong>B.S. in Computer Science</strong><br>
      <em>University of Rochester, Graduated 2022</em><br>
      Magna Cum Laude</p>
    </blockquote>
  </div>
</div>

---

<div class="row">
  <div class="col-md-6">
    <h2 id="awards-and-grants">Awards and Grants</h2>
    <ul>
      <li><strong>Vanderbilt Graduate School Travel Grant</strong>, <em>Fall 2024</em></li>
      <li><strong>Vanderbilt Brain Institute Scholar Award</strong>, <em>Fall 2023 - Fall 2024</em></li>
      <li><strong>Lacy-Fischer Interdisciplinary Research Grant</strong>, <em>Spring 2023</em></li>
    </ul>
  </div>
  <div class="col-md-6">
    <h2 id="teaching-experience">Teaching Experience</h2>
    <ul>
      <li><strong>Graduate Teaching Assistant</strong>, <em>Spring 2023</em><br>
      NSC-3630: Drugs & Behavior<br>
      Under Dr. Meredyth Wegener</li>
    </ul>
  </div>
</div>

---

<h2 id="conferences-and-publications">Conferences and Publications</h2>

{%- include tabs.html tabs_id="pub-tabs" -%}

{%- capture tab_presentations -%}
- **Society of Neuroscience, 2024**
  - Xuan Wen, Thilo Womelsdorf. "Gaze preferences predict fast learning of new attentional targets and slow disengagement from distractors during adaptive behavior"

- **Computational Cognitive Neuroscience, 2024**
  - Ankani Chattoraj, Xuan Wen, Ralf Haefner. "Comparing primacy effects across different temporal scales to distinguish between theories of evidence integration"

- **Society of Neuroscience, 2023**
  - Xuan Wen, Seema Dhungana, Adam Neumann, Marcus Watson, Thilo Womelsdorf. "Learning of the Latent Structure of Object Relationships in Rhesus Monkeys"

- **Visual Science Society, 2022**
  - Xuan Wen, Ankani Chattoraj, Ralf Haefner. "Investigating limits and time scales of a perceptual confirmation bias"
{%- endcapture -%}

{%- capture tab_publications -%}
- Marcus R. Watson, Nathan Traczewski, Seema Dunghana, Kianoush Banaie Boroujeni, Adam Neumann, Xuan Wen, Thilo Womelsdorf. "A Multi-task Platform for Profiling Cognitive and Motivational Constructs in Humans and Nonhuman Primates." *bioRXiv*, 2023
{%- endcapture -%}

<div class="tab-content">
  <div class="tab-pane active" id="presentations" role="tabpanel">
    {{- tab_presentations | markdownify -}}
  </div>
  <div class="tab-pane" id="publications" role="tabpanel">
    {{- tab_publications | markdownify -}}
  </div>
</div>