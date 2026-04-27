---
title: Research
summary: Research interests
date: "2022-12-29T00:00:00Z"
show_date: false
reading_time: false  # Show estimated reading time?
share: false  # Show social sharing links?
profile: true  # Show author profile?
comments: false  # Show comments?

type: landing

design:
  # Choose a view for the listings:
  view: compact
  columns: '3'


page_type: publication

---



<h2> Early warning signals for bifurcations </h2>
<!-- <br> -->
<!-- {{< figure src="uploads/images/fig_critical_transition.png" width="80%" >}} -->
<img src="/uploads/images/fig_critical_transition.png" alt="Critical transition figure" style="width:100%;">

<!-- My research explores sudden qualitative changes in dynamical systems, also known as tipping points or bifurcations. These occur in many contexts, from epidemics and cardiac arrhythmias to ecological collapse.

When a system approaches a bifurcation, it exhibits universal properties. One example is critical slowing down, where the recovery rate decreases near the transition (shown above).

I develop computational tools combining dynamical systems theory and machine learning to help predict and understand these transitions, with applications across biology and ecology.
 -->

<div style="font-size: 18px; line-height: 1.5;">

A bifurcation marks a sudden qualitative change in a dynamical system as a parameter crosses a threshold--also referred to as a tipping point or a critical transition. They correspond to phenomena such as the onset of an epidemic, a cardiac arrhythmia, and the collapse of an ecosystem. 

When a system is near to a bifurcation, there are universal properties of bifurcations that can emerge when sufficient data is collected. One example is critical slowing down (shown above), where the recovery rate decreases close to the bifurcation. 

We develop computational tools based on the theory of dynamical systems and machine learning to help predict the onset of a bifurcation in various natural systems.

</div>
<br>

<b>Relevant work:</b>

<div style="font-size: 16px; line-height: 1.5;">

- Sadria, M., & **Bury, T. M.** (2024). <a href="https://academic.oup.com/bioinformatics/article/40/9/btae525/7739702?login=true" target="_blank">FateNet: an integration of dynamical systems and deep learning for cell fate prediction.</a> *Bioinformatics*, 40(9), btae525.

-   **Bury, T. M.**, Dylewsky, D., Bauch, C. T., Anand, M., Glass, L., Shrier, A., & Bub, G. (2023). <a href="https://www.nature.com/articles/s41467-023-42020-z" target="_blank">Predicting discrete-time bifurcations with deep learning.</a> *Nature Communications*, 14(1), 6331.

- **Bury, T. M.**, Sujith, R. I., Pavithran, I., Scheffer, M., Lenton, T. M., Anand, M., & Bauch, C. T. (2021). <a href="https://www.pnas.org/doi/10.1073/pnas.2106140118" target="_blank">Deep learning for early warning signals of tipping points.</a> *Proceedings of the National Academy of Sciences*, 118(39), e2106140118.

- **Bury, T. M.**, Bauch, C. T., & Anand, M. (2020). <a href="https://www.pnas.org/doi/10.1073/pnas.2106140118" target="_blank">Detecting and distinguishing tipping points using spectral early warning signals.</a> *Journal of the Royal Society Interface*, 17(170), 20200482.

</div>

<!-- <b>Research questions:</b>
- Can we develop early warning signals that distinguish subcritical (abrupt) from supercritical (smooth) bifurcations?
- To what extent can deep learning methods generalize to bifurcations in spatial systems?
- What features of time series are deep learning methods using to provide early warning signals?
- How do early warning signals behave in the vicinity of multiple bifurcations? -->


<br><br>




<h2> Nonlinear dynamics of cardiac arrhythmia </h2>
<!-- <br> -->
<!-- {{< figure src="uploads/images/fig_ecg_physionet.png" width="80%" >}} -->
<!-- ![ECG figure](/uploads/images/fig_ecg_physionet.png){ width=80% } -->
<img src="/uploads/images/fig_ecg_physionet.png" alt="ECG figure" style="width:100;">

The human heart beats around 100,000 times a day. A healthy heartbeat is the result of electrical propagation that travels through the heart, resulting in contraction of the cardiac tissue and pumping of blood to the body. A cardiac arrhythmia occurs when this propagation is disrupted in some way. Wearable device technology has reached the point where we can monitor the electrical activity of our hearts for extended periods of time, amassing a wealth of data. We use mathematical models and machine learning to better understand and predict the dynamics of the hearts in patients who have cardiac arrhythmia, in collaboration with cardiologists at the University of British Columbia and Weill Cornell Medicine and experimental physiologists at McGill University.

<b>Relevant work:</b>

<div style="font-size: 16px; line-height: 1.5;">

- **Bury, T. M.**, Diagne, K., Olshan, D., Glass, L., Shrier, A., Lerman, B. B., & Bub, G. (2023). <a href="https://pubs.aip.org/aip/cha/article-abstract/33/12/123130/2931573/The-inverse-problem-for-cardiac-arrhythmias?redirectedFrom=fulltext" target="_blank">The inverse problem for cardiac arrhythmias.</a> *Chaos: An Interdisciplinary Journal of Nonlinear Science*, 33(12).

- Diagne, K., **Bury, T. M.**, Deyell, M. W., Laksman, Z., Shrier, A., Bub, G., & Glass, L. (2023). <a href="https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.130.028401" target="_blank">Rhythms from two competing periodic sources embedded in an excitable medium.</a> *Physical Review Letters*, 130(2), 028401.

- **Bury, T. M.**, Lerma, C., Bub, G., Laksman, Z., Deyell, M. W., & Glass, L. (2020). <a href="https://pubs.aip.org/aip/cha/article-abstract/30/11/113127/1077361/Long-ECGs-reveal-rich-and-robust-dynamical-regimes?redirectedFrom=fulltext" target="_blank">Long ECGs reveal rich and robust dynamical regimes in patients with frequent ectopy.</a> *Chaos: An Interdisciplinary Journal of Nonlinear Science*, 30(11).
</div>
<!-- 
Current research questions:
- xxx -->

<br><br>


<h2> Onset of spiral waves in excitable systems </h2>
<div class="figure-row">
  <figure>
    <img src="/uploads/images/monolayer_regular.gif" alt="Monolayer 1">
  </figure>
  <figure>
    <img src="/uploads/images/monolayer_spiral.gif" alt="Monolayer 2">
  </figure>
</div>

Excitable systems exhibit various types of dynamics. They can be at rest, propagate planar waves following a stimulus (left), propagate self-sustaining spiral waves (right), or show more complicated spatio-temporal behaviour. Spiral waves in the human heart are responsible for ventricular tachycardia---a dangerous cardiac arrhythmia. We study how excitable systems can transition into spiral wave dynamics, combining mathematical models with reinforcement learning---a branch of machine learning designed to discover sequential actions that achieve a pre-defined task. 

This work is in collaboration with physiologists in the <a href="https://gil-bub.lab.mcgill.ca/">Bub lab</a>, who are conducting experiments with spiral waves in real cardiac tissue. Videos show motion transients from thin sheets of mouse cardiac tissue.


