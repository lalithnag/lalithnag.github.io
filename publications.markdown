---
layout: page
title: Publications
permalink: /pubs/
order: 7
---

<p style="font-size: 14px;"> Also find me on <a href="https://scholar.google.com/citations?hl=en&user=bdLgSAgAAAAJ" target="_blank"> Google Scholar  </a> </p>

<!-- Include the reusable CSS at the top -->
<style>
    /* Tooltip container */
    .image-tooltip-container {
        position: relative;
        display: inline-block;
        cursor: pointer;
    }

    /* Tooltip image */
    .image-tooltip {
        visibility: hidden;
        max-width: 600px; /* Set a max-width for the image */
        background-color: #fff;
        border: 1px solid #ccc;
        border-radius: 5px;
        padding: 5px;
        position: absolute;
        z-index: 1;
        bottom: 125%; /* Position above the text */
        left: 50%;
        transform: translateX(-50%); /* Center the tooltip horizontally */
        opacity: 0;
        transition: opacity 0.3s;
        overflow: hidden; /* Ensure image doesn't overflow the tooltip */
    }

    /* Tooltip visibility on hover */
    .image-tooltip-container:hover .image-tooltip {
        visibility: visible;
        opacity: 1;
    }

    /* Arrow below the tooltip */
    .image-tooltip::after {
        content: "";
        position: absolute;
        top: 100%; /* Arrow below the tooltip */
        left: 50%;
        margin-left: -5px;
        border-width: 5px;
        border-style: solid;
        border-color: #fff transparent transparent transparent;
    }

    /* Adjust tooltip for small screens */
    @media (max-width: 700px) {
        .image-tooltip {
            max-width: 80vw; /* Set a maximum width relative to viewport width */
            left: 0;
            transform: none; /* Remove centering transformation */
            margin: 0 auto; /* Center the tooltip horizontally */
            right: 0;
        }
    }
</style>

#### Journals

<ol style="font-size: 14px;">
  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Romano, G., Koehler, S., Kelm, H., Karck, M., De Simone, R., and Engelhardt, S. (2022). <span style="color: black;">Mutually Improved Endoscopic Image Synthesis and Landmark Detection in Unpaired Image-to-Image Translation.</span> IEEE Journal of Biomedical and Health Informatics 26(1), 127–138. ISSN: 2168-2208. DOI: 10.1109/JBHI.2021.3099858. (<a href="https://ieeexplore.ieee.org/document/9496194" target="_blank"> Paper </a>, <a href="https://github.com/Cardio-AI/detcyclegan_pytorch" target="_blank"> Code </a>) <span title="Unpaired image translation with conditioned on consistency of suture point locations. The generated data was further used for training in the OR domain." style="font-size: 10px"> TLDR </span>
    <div style="margin-bottom: 20px;"></div> 
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Romano, G., Brand, J., Kelm, H., Karck, M., De Simone, R., and Engelhardt, S. (2021). <span style="color: black;">Point detection through multi-instance deep heatmap regression for sutures in endoscopy.</span> International Journal of Computer Assisted Radiology and Surgery 16(12), 2107–2117. ISSN: 1861-6429. DOI: 10.1007/s11548-021-02523-w. (<a href="https://link.springer.com/article/10.1007/s11548-021-02523-w" target="_blank"> Paper </a>, <a href="https://github.com/Cardio-AI/suture-detection-pytorch" target="_blank"> Code </a>) <span title="Model to detect entry and exit points of sutures (variable in every frame) from endoscopic images captured in the OR and from a surgical simulator." style="font-size: 10px"> TLDR </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Burger, L.*, <span style="color: black; text-decoration: underline;">Sharan, L.*</span>, Karl, R., Wang, C., Karck, M., De Simone, R., Wolf, I., Romano, G., and Engelhardt, S. (2023). <span style="color: black;">Comparative evaluation of three commercially available markerless depth sensors for close-range use in surgical simulation.</span> International Journal of Computer Assisted Radiology and Surgery 18(6), 1109–1118. ISSN: 1861-6429. DOI: 10.1007/s11548-023-02887-1. (*Equal contribution) (<a href="https://link.springer.com/article/10.1007/s11548-023-02887-1" target="_blank"> Paper </a>, <a href="https://github.com/Cardio-AI/depth-sensor-evaluation" target="_blank"> Code </a>) <span title="Thorough evaluation and idenfitication of an RGB-D camera that can be used in the close-range in patient-speciic surgical simulators for the use case of mitral valve repair." style="font-size: 10px"> TLDR </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
  Engelhardt, S., Dar S.U.H., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, André, F., Nagel, E., and Thomas, S. (2024). <span style="color: black;"> Artificial intelligence in cardiovascular imaging and intervention. </span> Herz. DOI: 10.1007/s00059-024-05264-z. (<a href="https://link.springer.com/article/10.1007/s00059-024-05264-z" target="_blank"> Paper </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>
  
 <li style="color: #808080">
    Wang, C., Karl, R., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Grizelj, A., Fischer, S., Karck, M., De Simone, R., Romano, G., and Engelhardt, S. (2023). <span style="color: black;">Surgical Training of Minimally Invasive Mitral Valve Repair on a Patient-Specific Simulator Improves Surgical Skills.</span> European Journal of Cardio-Thoracic Surgery, ezad387. ISSN: 1873-734X. DOI:10.1093/ejcts/ezad387. (<a href="https://academic.oup.com/ejcts/article-abstract/65/3/ezad387/7439596?redirectedFrom=fulltext&login=false" target="_blank"> Paper </a>) 
    <div style="margin-bottom: 20px;"></div>
 </li>

<li style="color: #808080">
    Fischer, S., Romano, G., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Warnecke, G., Mereles, D., Karck, M., Simone, R. D., and Engelhardt, S. (2023). <span style="color: black;">Surgical Rehearsal for Mitral Valve Repair: Personalizing Surgical Simulation by 3D Printing.</span> The Annals of Thoracic Surgery 115(4), 1062–1067. ISSN: 0003-4975. DOI: 10.1016/j.athoracsur.2022.12.039. (<a href="https://www.sciencedirect.com/science/article/abs/pii/S0003497523000152" target="_blank"> Paper </a>) 
    <div style="margin-bottom: 20px;"></div>
 </li>

<li style="color: #808080">
    Kostiuchik, G., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Mayer, B., Wolf, I., Preim, B., and Engelhardt, S. (2024). <span style="color: black;">Surgical phase and instrument recognition: how to identify appropriate dataset splits.</span> International Journal of Computer Assisted Radiology and Surgery. ISSN: 1861-6429. DOI: 10.1007/s11548-024-03063-9. (<a href="https://link.springer.com/article/10.1007/s11548-024-03063-9" target="_blank"> Paper </a>) 
    <div style="margin-bottom: 20px;"></div>
 </li>
</ol>

#### Multi-institutional collaborative work

<ol style="font-size: 14px;">
  <li style="color: #808080">
    Reinke A., Tizabi M.D., ..., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, ..., Maier-Hein, L. (2023). <span style="color: black;"> Common limitations of image processing metrics: A picture story. </span> arXiv preprint arXiv:2104.05642 DOI: 10.48550/arXiv.2104.05642 (<a href="https://www.tandfonline.com/doi/full/10.1080/21681163.2022.2159535" target="_blank"> Pre-print </a>) <span title="Pitfalls in the use-case of suture point detection in particular, and more generally landmark/point detection." style="font-size: 10px"> Contribution </span>
    <div style="margin-bottom: 20px;"></div>
  </li>
</ol>

#### Conference proceedings

<ol style="font-size: 14px;">
  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Kelm, H., Romano, G., Karck, M., De Simone, R., and Engelhardt, S (2023). <span style="color: black;">mvHOTA: A multi-view higher order tracking accuracy metric to measure temporal and spatial associations in multi-point tracking.</span> Computer Methods in Biomechanics and Biomedical Engineering: Imaging & Visualization 11(4), 1281–1289. ISSN: 2168-1163, 2168-1171. DOI: 10.1080/21681163.2022.2159535. (<a href="https://www.tandfonline.com/doi/full/10.1080/21681163.2022.2159535" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/2206.09372" target="_blank"> Pre-print </a>, <a href="https://github.com/Cardio-AI/mvhota" target="_blank"> Code </a>) <span title="A metric that combines per-frame detection with temporal tracking (associations) and multi-view associations (correspondence), extending the popularly used HOTA metric, used for KITTI benchmarks." style="font-size: 10px"> TLDR </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Grizelj, A., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Karck, M., Simone, R. D., Romano, G., and Engelhardt, S. (2024). <span style="color: black;"> On-demand mitral valve morphometrics during surgical repair. </span> Current Directions in Biomedical Engineering (accepted). <span title="This paper presents features and a pilot study of our tool smartMVR" style="font-size: 10px"> TLDR </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Koehler, S., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Kuhm, J., Ghanaat, A., Gordejeva, J., Simon, N. K., Grell, N. M., André, F., and Engelhardt, S. (2022).  <span style="color: black;">Comparison of Evaluation Metrics for Landmark Detection in CMR Images.</span> In: Bildverarbeitung für die Medizin 2022. Ed. by Maier-Hein, K., Deserno, T. M., Handels, H., Maier, A., Palm, C., and Tolxdorff, T. Springer Fachmedien Wiesbaden, Wiesbaden, pp. 198–203. DOI: 10.1007/978-3-658-36932-3_43. (<a href="https://link.springer.com/chapter/10.1007/978-3-658-36932-3_43" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/2201.10410" target="_blank"> Pre-print </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Burger, L., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Fischer, S., Brand, J., Hehl, M., Romano, G., Karck, M., De Simone, R., Wolf, I., and Engelhardt, S. (2022).  <span style="color: black;">Comparison of Depth Estimation Setups from Stereo Endoscopy and Optical Tracking for Point Measurements. </span> In: Bildverarbeitung für die Medizin 2022. Ed. by Maier-Hein, K., Deserno, T. M., Handels, H., Maier, A., Palm, C., and Tolxdorff, T. Springer Fachmedien Wiesbaden, Wiesbaden, pp. 160–165. DOI: 10.1007/978-3-658-36932-3_35. (<a href="https://link.springer.com/chapter/10.1007/978-3-658-36932-3_35" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/2201.10848" target="_blank"> Pre-print </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Stern, A., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Romano, G., Koehler, S., Karck, M., De Simone, R., Wolf, I., and Engelhardt, S. (2021). <span style="color: black;">Heatmap-based 2D Landmark Detection with a Varying Number of Landmarks. </span> In: Bildverarbeitung für die Medizin 2021. Ed. by Palm, C., Deserno, T. M., Handels, H., Maier, A., Maier-Hein, K., and Tolxdorff, T., Springer Fachmedien, Wiesbaden, pp. 22–27. DOI: 10.1007/978-3-658-33198-6_7. (<a href="https://link.springer.com/chapter/10.1007/978-3-658-33198-6_7" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/2101.02737" target="_blank"> Pre-print </a>)
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Kostiuchik, G., Wolf, I., Karck, M., Simone, R. D., and Engelhardt, S. (2020). <span style="color: black;">Domain gap in adapting self-supervised depth estimation methods for stereo-endoscopy. </span> Current Directions in Biomedical Engineering 6(1). ISSN: 2364-5504. DOI: 10.1080/21681163.2022.2159535. (<a href="https://www.degruyter.com/document/doi/10.1515/cdbme-2020-0004/html?lang=en" target="_blank"> Paper </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Engelhardt, S., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Karck, M., Simone, R. D., and Wolf, I. (2019). <span style="color: black;">Cross-Domain Conditional Generative Adversarial Networks for Stereoscopic Hyperrealism in Surgical Training. </span> In: Medical Image Computing and Computer Assisted Intervention – MICCAI 2019. Ed. by Shen, D., Liu, T., Peters, T. M., Staib, L. H., Essert, C., Zhou, S., Yap, P.-T., and Khan, A., Springer International Publishing, Cham, pp. 155–163. DOI: 10.1007/978-3-030-32254-0_18. (<a href="https://link.springer.com/chapter/10.1007/978-3-030-32254-0_18" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/1906.10011" target="_blank"> Pre-print </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Preetha, C. J., Kloss, J., Wehrtmann, F. S., <span style="color: black; text-decoration: underline;">Sharan, L.</span>, Fan, C., Müller-Stich, B. P., Nickel, F., and Engelhardt, S. (2020). <span style="color: black;">Towards augmented reality-based suturing in monocular laparoscopic training. </span> In: Medical Imaging 2020: Image-Guided Procedures, Robotic Interventions, and Modeling. SPIE, pp. 232–238. DOI: 10.1117/12.2550830. (<a href="https://www.spiedigitallibrary.org/conference-proceedings-of-spie/11315/113150X/Towards-augmented-reality-based-suturing-in-monocular-laparoscopic-training/10.1117/12.2550830.short" target="_blank"> Paper </a>, <a href="https://arxiv.org/abs/2001.06894" target="_blank"> Pre-print </a>) 
    <div style="margin-bottom: 20px;"></div>
  </li>
</ol>

#### Posters and abstracts

<ol style="font-size: 14px;">
  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR support for minimally invasive Mitral Valve Repair.</span> Poster and talk at Informatics for Life annual meeting in Heidelberg, Germany, 2022.
    <span class="image-tooltip-container">
      <span style="color: black; text-decoration: underline;"> Winner, Best Poster Award</span>
        <span class="image-tooltip">
            <img src="/assets/IFL2022_2.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR based computational support for minimally invasive Mitral Valve Repair.</span> Talk at Informatics for Life annual meeting in 
    <span class="image-tooltip-container">
      <span> Heidelberg, Germany, 2023. </span>
        <span class="image-tooltip">
            <img src="/assets/IFL2023.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Lukas Burger, Christina Wang, Andela Grizelj, Roger Karl, Jimmy Chen, Samantha Fischer, Julian Brandt, Josephin Marx, Gabriele Romano, Matthias Karck, Raffaele De Simone, Sandy Engelhardt. <span style="color: black;">AI and AR assisted minimally invasive mitral valve repair.</span> 
    <span class="image-tooltip-container">
      <span> AI4MED-BW Retreat  </span>
        <span class="image-tooltip">
            <img src="/assets/AI4MED_BW.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Kapusta, M., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">AI and AR based computational support for minimally invasive Mitral Valve Repair.</span> Talk at 26th International Conference on Medical Image Computing and Computer Assisted Intervention,
    <span class="image-tooltip-container">
      Vancouver, Canada 2023.
        <span class="image-tooltip">
            <img src="/assets/MICCAI2023.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Burger, L., Wang, C., Grizelj, A., Kapusta, M., Karl, R., Chen, J., Fischer, S., Brand, J., Marx, J., Romano, G., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">Quantitative endoscopic image analysis.</span> Talk at MIDL Doctoral Symposium, Germany, 2021.
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Wang, C., Karl, R., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Grizelj, A., Fischer, S., Karck, M., De Simone, R., Romano, G., and Engelhardt, S. <span style="color: black;">Quantification of the learning progress in minimally invasive mitral valve repair on a patient-specific simulator. </span> Poster at the Deutsche Gesellschaft für Kardiologie – Herz- und Kreislaufforschung e.V. (DGK) annual meeting in Mannheim, Germany, 2023.
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Chen, J., Romano, G., Mayer, B., Kelm, H., Marx, J., Kostiuchik G., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Preim, B., Karck, M., De Simone, R., Engelhardt, S. <span style="color: black;">The unmet potential of digital workflow analysis for interventional cardiology and cardiac surgery. </span> Poster at the Deutsche Gesellschaft für Kardiologie – Herz- und Kreislaufforschung e.V. (DGK) annual meeting in Mannheim, Germany, 2023.
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    Engelhardt, S., <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Karck, M., De Simone, R., & Wolf, I. (2020). <span style="color: black;"> Abstract: Generative Adversarial Networks for Stereoscopic Hyperrealism in Surgical Training. </span> In T. Tolxdorff, T. M. Deserno, H. Handels, A. Maier, K. H. Maier-Hein, & C. Palm (Eds.), Bildverarbeitung für die Medizin 2020 (pp. 341–341). Springer Fachmedien. DOI: 10.1007/978-3-658-29267-6_75
    <div style="margin-bottom: 20px;"></div>
  </li>

  <li style="color: #808080">
    <span style="color: black; text-decoration: underline;">Sharan, L.</span>,  Karl, R.*, Fischer, S., Marx, J., Brand, J., Romano, G., De Simone, R., Engelhardt, S. <span style="color: black;"> Patient-specific Mitral Valve Simulation to Support Therapy.</span> Poster at Informatics for Life annual meeting in Heidelberg, Germany, 2021. (*Equal contribution) 
    <span class="image-tooltip-container">
        <span style="color: black; text-decoration: underline;"> Winner, Best Poster Award </span>
        <span class="image-tooltip">
            <img src="/assets/IFL2021.jpeg">
        </span>
    </span>
    <div style="margin-bottom: 20px;"></div>
  </li>
</ol>  