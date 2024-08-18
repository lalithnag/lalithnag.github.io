---
layout: page
title: Research
permalink: /research/
order: 5
---

<p style="font-size: 14px;">
My current research lies at the intersection of computer vision, deep learning, and cardiac surgery. In particular, the focus of my PhD is to use the computational tools at hand, to tackle important challenges in minimally invasive mitral valve repair, a surgery of the mitral valve of the heart. My cumulative dissertation is titled <i> Deep learning based image analysis for endoscopic minimally invasive mitral valve repair </i>.
</p>
<div style="margin-bottom: 10px;"></div>
<p style="font-size: 14px;">
During this time, I have worked on various computer vision tasks: depth sensing and 3D reconstruction, landmark detection and tracking, unpaired image translation, instrument segmentation, and multi-modal image registration. In the following paragraphs, I explain why this is an important problem to solve, the broad objectives of this work, and the contributions that resulted from the work of my PhD. 
</p>

<details>
<summary> Why is this problem important? </summary>
<div style="margin-bottom: 12px;"></div>

<p style="font-size: 12px;"> 
Minimally invasive mitral valve repair, which is the gold standard to treat mitral regurigtation is a surgery that is routinely performed with endoscopic assistance. Owing to restrited surgical ports, high surgical complexity, and a lack of quantitative information; successful outcomes are impacted by intraoperative decision making. For example, choosing the right size of ring prosthesis and artificial chordae tendinae is of paramount importance to successfully restore the valve to its normal function. Endoscopic imaging presents a rich source of information that can be leveraged using computational tools, to assist in surgical decision making, and provide insights that help tackle the complexity of this surgery. 
</p>

<figure>
    <img src="/assets/mvr_evolution.png" alt="Alt text" width="600" height="auto" style="margin: 30px;">
    <figcaption style="font-size: 12px;"> The evolution of mitral valve repair leading up to a totally endoscopic approach, with a look into the enabling technologies, developments in surgical repair techniques, and decrease in the surgical port size over time. 
    <br>
    <small> The image is from my dissertation, and is provided with a CC-BY-NC-SA </small>
    <img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" alt="CC BY-NC-SA" width="44" height="16">
</figcaption>
</figure>

</details>
<div style="margin-bottom: 20px;"></div>

<details open>

<summary> Overview of the work done in my PhD </summary>

<div style="margin-bottom: 20px;"></div>
<p style="font-size: 12px;">
To tackle the challenges of endoscopic mitral valve repair, the work of my PhD had three broad objectives:
</p>

<figure>
    <img src="/assets/visual_abstact.png" alt="Alt text" style="margin: 30px;">
    <figcaption style="font-size: 12px;"> 
        <small> The image is from my dissertation, and is provided with a CC-BY-NC-SA </small>
        <img src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png" alt="CC BY-NC-SA" width="44" height="16">
    </figcaption>
</figure>

<ol style="font-size: 14px; color: #808080;">
<li> Extract <b> 3D information about valve morphology </b>, to obtain objective measurements of the valve dimensions, for example: the valve diameters, anterior leaflet area, leaflet lengths, and chordae indices; which are important parameters in surgical decision making. </li>
<div style="margin-bottom: 12px;"></div>

<ul style="font-size: 14px; list-style-type: disc; color: black;">
<li> Towards this obective, I worked on 3D reconstruction and depth estimation methods. In addition, a suitable close-range RGB-D camera was identified, to extract the 3D valve morphology in real-time for use in the patient-specific mitral valve repair simulator (Burger, and Sharan et al. 2023). The camera is chosen by a thorough evaluation of three shortlisted cameras, based on several parameters in scenarios mimicking mitral valve repair. </li>
<div style="margin-bottom: 14px;"></div>

<li> Based on the identified camera, smartMVR, an integrated real-time measurements and augmented reality application, was developed, which is to my best knowledge, the first of its kind for cardiac endoscopy, bringing together depth sensing, augmented reality, and deep learning based image analysis methods onto a single platform. </li>
<div style="margin-bottom: 12px;"></div>
</ul>

<li> Extract the <b> texture and appearance </b> of the intraoperative mitral valve, and translate it to patient-specific silicone valve replicas used in surgical simulators, to make the sil- icone replicas appear similar to intraoperative tissue using a form of augmented reality. </li>
<div style="margin-bottom: 12px;"></div>

<ul style="font-size: 14px; list-style-type: disc; color: black;">
<li> I worked on a novel deep learning method (Sharan et al. 2022) to extract the appearance of realistic valve tissue and translate it to silicone valve replica, while better preserving the suture point locations. This method produces a realistic appearance of the silicone valve replica, thereby generating ‘fake’ intraoperative data, which is further used to improve a suture point detection model (Sharan et al. 2021) through dataset fusion. </li>
<div style="margin-bottom: 12px;"></div>
</ul>

<li> Obtain peripheral information of the surgical scene, for example by <b> automatically detecting entry and exit points of annuloplasty sutures </b>, towards understanding underlying suture configurations, computing suture bite length, and potential use as augmented reality markers. </li>
<div style="margin-bottom: 12px;"></div>

<ul style="font-size: 14px; list-style-type: disc; color: black;">
<li> Here, I worked on a deep learning based method to detect the entry and exit points of annuloplasty sutures on the mitral valve, which was a hard problem as there could be variable number of points without semantic consistency of anatomical locations. In a follow-up work, a metric for the spatio-temporal tracking of the suture points across multiple views was proposed (Sharan et al. 2023), and a sample use-case for suture point detection in mitral valve repair demonstrated.</li>
<div style="margin-bottom: 12px;"></div>
</ul>

</ol>
</details>
<div style="margin-bottom: 12px;"></div>

<p style="font-size: 12px; color: #808080;">
    For the references and a full list, check my <a target="_blank" href="/pubs/">publications page</a> or my <a href="https://scholar.google.com/citations?hl=en&user=bdLgSAgAAAAJ" target="_blank">Google Scholar</a> page. My dissertation will be published once my defense takes place.
</p>

#### Contributions to open science

<ul style="font-size: 14px;">
<li> The code for the three journal publications that make up the chunk of my cumulative dissertation (Burger, and Sharan et al. 2023; Sharan et al. 2021, 2022), are all made publicly available (check my <a target="_blank" href="/pubs/">publications page</a> for Github links). The papers have also been published open access.</li>
<div style="margin-bottom: 12px;"></div>

<li> An in-house curated dataset used for suture point detection comprising 2,376 intraoperative images and 2,708 surgical simulator images, along with the corresponding suture labels with over 50,000 suture points was released to the community as part of a publicly organised challenge (<a target="_blank" href="https://adaptor2021.github.io">AdaptOR 2021</a>) at the 24th International Conference on Medical Image Computing and Computer Assisted Interventions (<a target="_blank" href="https://miccai2021.org/en/">MICCAI</a>) 2021. </li> 
<div style="margin-bottom: 12px;"></div>

<li> An extended clean stereo-endoscopic dataset from the intraoperative and surgical simulator domains was curated and publicly released to the community, for a novel view synthesis task as part of another publicly organised challenge (<a target="_blank" href="https://adaptor2022.github.io">AdaptOR 2022</a>) at <a target="_blank" href="https://conferences.miccai.org/2022/en/">MICCAI 2022</a>. The released dataset contains 1,366 stereo frames from 10 simulations and 5,395 stereo frames from 9 surgeries, with an average of 600 frames per surgery. </li>
<div style="margin-bottom: 12px;"></div>

<li> The work of my PhD was presented in four international and national conferences, and four symposia, and as a result garnered three best poster awards, and one third-best poster award. Lastly, I had a lot of fun conducting scientific outreach activities including over 10 poster presentations and scientific talks, and 7 <a target="_blank" href="/talks/">science slams</a> to a general audience of over 3,000. </li>
</ul>
<div style="margin-bottom: 20px;"></div>


