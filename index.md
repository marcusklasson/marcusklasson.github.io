---
#
# By default, content added below the "---" mark will appear in the home page
# between the top bar and the list of recent posts.
# To change the home page layout, edit the _layouts/home.html file.
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
#
layout: home
title: #Welcome
---


<div class="profile">
  <img src="images/marcusklasson_2024.jpg" alt="Marcus Klasson" class="profile-image">
  <div class="profile-text">
    <p class="profile-name">Marcus Klasson</p>
    <p class="profile-bio"> I work as a researcher at <a href="https://www.ericsson.com/en" target="_blank">Ericsson</a>  in the Sensing and Perception team led by <a href="http://www.josearaujo.org/" target="_blank">José Araújo</a>. <br><br>
	  I obtained my PhD from <a href="https://www.kth.se/en" target="_blank">KTH</a>, where I was supervised by <a href="https://www.kth.se/profile/hedvig" target="_blank">Hedvig Kjellström</a> and <a href="https://cheng-zhang.org/" target="_blank">Cheng Zhang</a>. 
    After the PhD, I was a postdoc at <a href="https://www.aalto.fi/en" target="_blank">Aalto University</a> working with <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a> and <a href="https://users.aalto.fi/~kannalj1/" target="_blank">Juho Kannala</a> on uncertainty-aware methods for computer vision topics such as NeRF/Gaussian Splatting and Vision Language Models. 
    </p>
    <div class="profile-links">
      <a href="https://marcusklasson.github.io/files/cv_march2024.pdf" target="_blank">CV</a> /
      <a href="https://scholar.google.com/citations?user=H9VHxP4AAAAJ&h" target="_blank">Scholar</a> /
      <a href="https://github.com/marcusklasson" target="_blank">GitHub</a> /
      <a href="https://bsky.app/profile/marcusklasson.bsky.social" target="_blank">Bluesky</a> /
      <a href="mailto:marcusklasson@hotmail.com" target="_blank">Email</a>
    </div>
  </div>
</div>

<style>
.profile {
  display: flex;
  align-items: center;
  gap: 20px;
  margin-bottom: 20px;
}

.profile-image {
  width: 186px;
  height: 186px;
  border-radius: 50%;
  border: 5px solid white;
}

.profile-text {
  max-width: 600px;
}

.profile-name {
  font-size: 28px;
  font-weight: normal;
  margin: 0;
}

.profile-bio {
  font-size: 13px;
  margin: 5px 0;
}

.profile-links a {
  margin-right: 0px;
  text-decoration: none;
  font-size: 12px;
}
</style>


## Research

I am interested in computer vision, deep learning, various approaches to uncertainty estimation, and their real-world applications where methods must adapt fast under limited supervision and resources. 

Here is a list of my research publications: 

<div class="publications">

  <div class="publication">
    <img src="images/publications/bayesvlm.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Post-hoc Probabilistic Vision-Language Models</strong><br>
       <a href="https://scholar.google.de/citations?user=4CEGXaYAAAAJ" target="_blank">Anton Baumann</a>, <a href="https://ruili-pml.github.io/" target="_blank">Rui Li</a>, <strong>Marcus Klasson</strong>, <a href="https://scholar.google.com/citations?user=35fWh2oAAAAJ" target="_blank">Santeri Mentu</a>, <a href="https://sgk98.github.io/" target="_blank">Shyamgopal Karthik</a>, <a href="https://www.helmholtz-munich.de/en/chc/eml/pi/zeynep-akata" target="_blank">Zeynep Akata</a>, <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a>, <a href="https://trappmartin.github.io/website/" target="_blank">Martin Trapp</a> <br>
      <em>preprint </em> <br>
      <div class="publication-links">
      <a href="https://aaltoml.github.io/BayesVLM/" target="_blank">project page</a> /
        <a href="https://arxiv.org/abs/2412.06014" target="_blank">arXiv</a> /
        <a href="https://github.com/AaltoML/BayesVLM" target="_blank">code</a> 
      </div>
      The Laplace approximation on top of VLMs enables analytic uncertainty propagation without additional training useful for downstream tasks and in active learning. 
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/desplat.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>DeSplat: Decomposed Gaussian Splatting for Distractor-Free Rendering</strong><br>
       <a href="https://johanna0626.github.io/" target="_blank">Yihao Wang</a>, <strong>Marcus Klasson</strong>, <a href="https://maturk.github.io/" target="_blank">Matias Turkulainen</a>, <a href="https://ffrivera0.github.io/" target="_blank">Shuzhe Wang</a>, <a href="https://users.aalto.fi/~kannalj1/" target="_blank">Juho Kannala</a>, <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a> <br>
      <em>CVPR, 2025 </em> <br>
      <div class="publication-links">
      <a href="https://aaltoml.github.io/desplat/" target="_blank">project page</a> /
        <a href="https://arxiv.org/abs/2411.19756" target="_blank">arXiv</a> /
        <a href="https://github.com/AaltoML/desplat/" target="_blank">code</a> 
      </div>
      Reconstructing distractors and multi-view inconsistencies with view-specific Gaussians enables explicit separation of occluders and the underlying static 3D scene.
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/streamlined.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Streamlining Prediction in Bayesian Deep Learning</strong><br>
       <a href="https://ruili-pml.github.io/" target="_blank">Rui Li</a>, <strong>Marcus Klasson</strong>, <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a>, <a href="https://trappmartin.github.io/website/" target="_blank">Martin Trapp</a> <br>
      <em>ICLR, 2025 </em> <br>
      <div class="publication-links">
        <a href="https://arxiv.org/abs/2411.18425" target="_blank">arXiv</a> /
        <a href="https://github.com/AaltoML/SUQ" target="_blank">code</a> 
      </div>
      Local linearization of activation functions and local Gaussian approximations at linear layers bring accurate and fast predictive uncertainties scalable to ViT and GPT-2. 
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/flatness-small.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Flatness Improves Backbone Generalisation in Few-shot Classification</strong><br>
       <a href="https://ruili-pml.github.io/" target="_blank">Rui Li</a>, <a href="https://trappmartin.github.io/website/" target="_blank">Martin Trapp</a>, <strong>Marcus Klasson</strong>, <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a> <br>
      <em>WACV, 2025 <strong>(Oral Presentation)</strong> </em> <br>
      <div class="publication-links">
        <a href="https://arxiv.org/abs/2404.07696" target="_blank">arXiv</a> /
        <a href="https://github.com/AaltoML/FlatFSL" target="_blank">code</a> 
      </div>
      We show that backbone training and selection utilizing flatness-aware training and fine-tuning can outperform previous SotA methods in multi-domain few-show classification. 
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/sources.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Sources of Uncertainty in 3D Scene Reconstruction</strong><br>
      <strong>Marcus Klasson</strong>, <a href="https://scholar.google.com/citations?user=UVziXI0AAAAJ" target="_blank">Riccardo Mereu</a>, <a href="https://users.aalto.fi/~kannalj1/" target="_blank">Juho Kannala</a>, <a href="https://users.aalto.fi/~asolin/" target="_blank">Arno Solin</a> <br>
      <em>ECCV Workshop on Uncertainty for Computer Vision, 2024</em><br>
      <div class="publication-links">
      	<a href="https://aaltoml.github.io/uncertainty-nerf-gs/" target="_blank">project page</a> /
        <a href="https://arxiv.org/abs/2409.06407" target="_blank">arXiv</a> /
        <a href="https://github.com/AaltoML/uncertainty-nerf-gs" target="_blank">code</a> 
      </div>
      We categorized sources of uncertainties in 3D scene reconstruction using NeRF/Gaussian Splatting and proposed experimental setups for evaluating their impact. 
    </div>
  </div>


  <div class="publication">
    <img src="images/publications/replayschedule_tree.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Learn the Time to Learn: Replay Scheduling in Continual Learning</strong><br>
      <strong>Marcus Klasson</strong>, <a href="https://www.kth.se/profile/hedvig" target="_blank">Hedvig Kjellström</a>, <a href="https://cheng-zhang.org/" target="_blank">Cheng Zhang</a> <br>
      <em>TMLR, 2023</em><br>
      <div class="publication-links">
      	<a href="https://openreview.net/forum?id=Q4aAITDgdP" target="_blank">openreview</a> /
        <a href="https://arxiv.org/abs/2209.08660" target="_blank">arXiv</a> / 
        <a href="https://github.com/marcusklasson/replay_scheduling" target="_blank">code</a> / 
        <a href="https://www.youtube.com/watch?v=huCX46HqMl4" target="_blank">video</a> 
      </div>
      Learning schedules over which tasks to replay at different times in continual learning can outperform replaying all tasks equally or using heuristic scheduling rules.  
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/patterns-pipeline.png" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>Using Variational Multi-view Learning for Classification of Grocery Items</strong><br>
      <strong>Marcus Klasson</strong>, <a href="https://cheng-zhang.org/" target="_blank">Cheng Zhang</a>, <a href="https://www.kth.se/profile/hedvig" target="_blank">Hedvig Kjellström</a> <br>
      <em>Patterns, 2020</em><br>
      <div class="publication-links">
        <a href="https://www.cell.com/patterns/fulltext/S2666-3899(20)30191-4" target="_blank">paper</a> /  
        <a href="https://github.com/marcusklasson/vcca_grocerystore" target="_blank">code</a> 
      </div>
      Using a VAE for fusing natural images with web-scraped images and text descriptions of groceries yields more accurate classifiers compared to training with natural images only. 
    </div>
  </div>

  <div class="publication">
    <img src="images/publications/wacv_intro.jpg" alt="Paper 2 Image" class="publication-image">
    <div class="publication-text">
      <strong>A Hierarchical Grocery Store Image Dataset with Visual and Semantic Labels</strong><br>
      <strong>Marcus Klasson</strong>, <a href="https://cheng-zhang.org/" target="_blank">Cheng Zhang</a>, <a href="https://www.kth.se/profile/hedvig" target="_blank">Hedvig Kjellström</a> <br>
      <em>WACV, 2019</em><br>
      <div class="publication-links">
        <a href="https://github.com/marcusklasson/GroceryStoreDataset" target="_blank">dataset</a> /
        <a href="https://arxiv.org/abs/1901.00711" target="_blank">arXiv</a> /  
        <a href="https://youtu.be/aTCK0OWil-A" target="_blank">video</a> 
      </div>
      Dataset for grocery item classification with natural images from grocery stores organized with hierarchical labels, where each class has a corresponding web-scraped text and iconic image.   
    </div>
  </div>

</div>

<style>
.publications {
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.publication {
  display: flex;
  align-items: center;
}

.publication-image {
  width: 224px;
  height: auto; 
  margin-right: 15px;
  border-radius: 5px;
  object-fit: scale-down; /* Crop the image to fit the container, maintaining aspect ratio */
}

.publication-image-square {
  width: 160px;
  height: auto; 
  margin-right: 15px;
  border-radius: 5px;
}

.publication-text {
  max-width: 600px;
  font-size: 12px;
}

.publication-links a {
  margin-right: 0px;
  text-decoration: none;
}
</style>



<!-- 
I am a postdoctoral researcher at the Computer Science department of Aalto University in Finland, 
where I am supervised by Prof. [Arno Solin](https://users.aalto.fi/~asolin/) and Prof. [Juho Kannala](https://users.aalto.fi/~kannalj1/). 
My research project is on Uncertainty Quantification in Deep Vision Models and is funded by [FCAI](https://fcai.fi/). 

Before joining Aalto, I obtained my PhD at the [divison of Robotics, Perception, and Learning (RPL)](https://www.kth.se/is/rpl/) 
at KTH Royal Institute of Technology in Stockholm, Sweden, 
where I was supervised by Prof. [Hedvig Kjellström](https://www.kth.se/profile/hedvig) and Dr. [Cheng Zhang](https://cheng-zhang.org/). 
-->

<!--
<br clear="left"/>

I am a postdoctoral researcher at the Computer Science department in Aalto University, working mainly with [Arno Solin](https://users.aalto.fi/~asolin/) and [Juho Kannala](https://users.aalto.fi/~kannalj1/). 
My research project is focused on developing uncertainty-aware methods for computer vision applications and is funded by [FCAI](https://fcai.fi/). 
I am interested in 3D computer vision, deep learning, probabilistic methods for uncertainty estimation, and their real-world applications where the developed method must adapt fast under limited supervision and resources.  



I obtained my PhD from KTH Royal Institute of Technology in Sweden, 
where I was supervised by [Hedvig Kjellström](https://www.kth.se/profile/hedvig) and [Cheng Zhang](https://cheng-zhang.org/). 
My thesis was motivated from assisting visually impaired people using computer vision, where I focused on image classification of groceries and continual learning.
My PhD experience taught me to aim for formulating research questions based on real-world needs to recognize what challenges should be tackled to reach certain goals. 
-->



<!-- 
## **News**

* **2024-10-31**: Three workshop papers accepted at Neurips that are from fun projects that I am involved in: 
    * [Probabilistic Active Few-Shot Learning in Vision-Language Models](https://openreview.net/forum?id=sSX9wLMSJT&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2024%2FWorkshop%2FBDU%2FAuthors%23your-submissions))
    * [Posterior Inferred, Now What? Streamlining Prediction in Bayesian Deep Learning](https://openreview.net/forum?id=cx9TXPTzt9&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2024%2FWorkshop%2FBDU%2FAuthors%23your-submissions))
    * [Differentially Private Continual Learning using Pre-Trained Models](https://openreview.net/forum?id=8Xdu4IyTSP&referrer=%5BAuthor%20Console%5D(%2Fgroup%3Fid%3DNeurIPS.cc%2F2024%2FWorkshop%2FContinual_FoMo%2FAuthors%23your-submissions))


#### **News**

* **2023-02-01.** I have relocated to Helsinki in Finland and started working as a postdoc at Aalto University supervised by 
Prof. [Arno Solin](https://users.aalto.fi/~asolin/) and 
Prof. [Juho Kannala](https://users.aalto.fi/~kannalj1/).  

* **2022-11-08.** I have passed my thesis defense and obtained my PhD degree! Special thanks to my opponent Prof. Davide Bacciu; my grading committee members Prof. Serge Belongie, Prof. Per-Erik Forssén, and Prof. Nataša Sladoje; my chairperson Danica Kragic and my supervisors Prof. Hedvig Kjellström and Dr. Cheng Zhang. 
[PDF Link to thesis](https://marcusklasson.github.io/files/phdthesis_MarcusKlasson.pdf), [Slides](https://marcusklasson.github.io/files/phdthesis_slides.pdf)
-->

<!--
* **2022-10-24.** I will defend my thesis on November 8. 
The defense starts at 9.00 (Swedish time) in Room F3 at KTH Campus and will also be on [Zoom](https://kth-se.zoom.us/j/61189313070).<br> 
[PDF Link to thesis](https://marcusklasson.github.io/files/phdthesis_MarcusKlasson.pdf),
[Info about event at kth.se](https://www.kth.se/en/om/mot/kalender/fine-grained-and-continual-visual-recognition-for-assisting-visually-impaired-people-1.1199637?date=2022-11-08&orgdate=2022-11-08&length=1&orglength=1).
-->

<!--
**Summary of PhD research:**
*My PhD research has been on developing computer vision methods for assisting people with visual impairment. 
Early on, my research focused on the study of image classification for visual assistance when grocery shopping using a mobile phone. 
Here, we applied a variational autoencoder for fusing mobile phone images together with web-scraped images and text descriptions of groceries to train more accurate classifiers, compared to training with mobile phone images only. 
More recently, I have worked with replay-based continual learning motivated by mitigating catastrophic forgetting of image classifiers in user personalization scenarios. 
Our focus has been on showing the benefits of scheduling which tasks to replay at different time intervals, which is necessary in scenarios where the number of tasks exceeds the replay memory size. 
Currently, we are aiming to use reinforcement learning for learning replay scheduling policies that can generalize better than replaying all seen tasks equally.*
-->
