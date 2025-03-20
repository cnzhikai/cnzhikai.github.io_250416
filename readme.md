

## About

I am a Ph.D. student in the Integrated Devices, Electronics, and Systems (IDEAS) group at ETH Zurich, dedicated to advancing human health through innovative biomedical technologies. My research spans device design using scalable microfabrication techniques compatible with CMOS and MEMS platforms, circuit development for interfacing with the physical world through seamless integration and optimization, and system-level enhancement by incorporating advanced features like machine learning for broader applications.

Feel free to contact me at zhhuang@ethz.ch for any inquiries.

## Gallery

**Tick to enlarge*
<style>
    .gallery {
        display: flex;
        flex-wrap: wrap;
        justify-content: flex-start;
        gap: 10px;
    }
    .gallery img {
        width: 100px;
        height: 100px;
        object-fit: cover;
        border-radius: 10px;
        cursor: pointer;
        transition: transform 0.2s;
    }
    .gallery img:hover {
        transform: scale(1.1);
    }
    .gallery-item {
        text-align: left;
    }
    .caption {
        font-size: 10px;
        color: gray;
        text-align: center;
    }

    /* Fullscreen overlay */
    .lightbox {
        display: none;
        position: fixed;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: rgba(0, 0, 0, 0.8);
        flex-direction: column;
        justify-content: center;
        align-items: center;
        text-align: center;
        padding: 20px;
    }
    .lightbox img {
        max-width: 90%;
        max-height: 80%;
        border-radius: 10px;
    }
    .lightbox .lightbox-caption {
        margin-top: 10px;
        color: white;
        font-size: 20px;
    }
</style>

<div class="gallery">
    <div class="gallery-item">
        <a href="javascript:void(0)" onclick="openLightbox('https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/microcage_array.jpg?raw=true', 'SEM Image of a Microcage Array')">
            <img src="https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/microcage_array.jpg?raw=true">
        </a>
    </div>
    <div class="gallery-item">
        <a href="javascript:void(0)" onclick="openLightbox('https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/250314_SEM_AMicrocage.jpg?raw=true', 'SEM Image of a Actuatable Microcage Before Release from Substrate, IEEE BioCAS 2024')">
            <img src="https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/250314_SEM_AMicrocage.jpg?raw=true">
        </a>
    </div>
    <div class="gallery-item">
        <a href="javascript:void(0)" onclick="openLightbox('https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/250314_SEM_MUE.png?raw=true', 'SEM Image of Multi-Use-Electrode Before Post-Processing, IEEE VLSI 2024')">
            <img src="https://github.com/cnzhikai/cnzhikai.github.io/blob/main/images/250314_SEM_MUE.png?raw=true">
        </a>
    </div>
</div>

<!-- Lightbox -->
<div class="lightbox" id="lightbox" onclick="closeLightbox()">
    <img id="lightbox-img" src="">
    <div class="lightbox-caption" id="lightbox-caption"></div>
</div>

<script>
    function openLightbox(src, caption) {
        document.getElementById("lightbox-img").src = src;
        document.getElementById("lightbox-caption").innerText = caption;
        document.getElementById("lightbox").style.display = "flex";
    }

    function closeLightbox() {
        document.getElementById("lightbox").style.display = "none";
    }
</script>


## Teaching

- 2024 Fall. Teaching Assistant, Electronic Circuits, ETH Zurich


## Services

- Reviewer for IEEE Conferences
    -  ISCAS (2025)

## Publications

<style>
    .small-text {
        font-size: 0.9em;
    }
</style>

<div class="small-text">
 <u>J</u>ournal, <u>C</u>onference, <u>T</u>hesis, <u>R</u>eports
 <br><br>
<p>
 [C8] Marco Saif, Fuze Jiang, Shao-Wei Lo, Adam Y Wang, <u>Zhikai Huang</u>, Jiachen Wang, Hangxing Liu, Chih-Jen Shih, Thomas Burger, Hua Wang; MEMS-Free 4096-Pixel CMOS E-Nose Gas Sensor Array with Molecular-Selective Metal-Organic-Framework Sensing and In-Pixel Thermodynamic Modulation for Fast Sensor Regeneration; IEEE International Solid-State Circuits Conference (ISSCC 2025)
</p>

<p>
 [C7] <u>Zhikai Huang</u>, Fuze Jiang, Hangxing Liu, Ying Kong, Yuguo Sheng, Adam Wang, Dongwon Lee, Marco Saif, Hua Wang; A CMOS-Compatible and Actuatable 3D-Microcage Array with Shape-Memory for On-Chip Dynamic Cell Interfacing; 2024 IEEE Biomedical Circuits and Systems Conference (BioCAS)
</p>

<p>
 [C6] Marco Saif, Fuze Jiang, Hangxing Liu, Adam Wang, <u>Zhikai Huang</u>, Yuguo Sheng, Dongwon Lee, Thomas Burger, Hua Wang; A CMOS Molecular Sensor for Personalized Diagnostics Featuring Enzyme-Free Reading and Encoding of Viral Variants at Single-Nucleotide Resolution; 2024 IEEE European Solid-State Electronics Research Conference (ESSERC)
</p>

<p>
 [C5] Hangxing Liu, Fuze Jiang, Adam Wang, <u>Zhikai Huang</u>, Ying Kong, Marco Saif, Dongwon Lee, Thomas Burger, Jing Wang, Hua Wang; Highly Sensitive Multimodal CMOS Antifouling Sensor Array with Multi-Use Electrodes for Single-Cell-Level Profiling of Biophysical and Biochemical Parameters; 2024 IEEE Symposium on VLSI Technology and Circuits (VLSI Technology and Circuits)
</p>

<p>
 [C4] Hangxing Liu, Fuze Jiang, Ying Kong, Dongwon Lee, Yuguo Sheng, Adam Wang, <u>Zhikai Huang</u>, Marco Saif, Thomas Burger, Jing Wang, Hua Wang; A Subcellular-Resolution Multimodal CMOS Biosensor Array with 16K Ion-Selective Pixels for Real-Time Monitoring Potassium Dynamics; 2024 IEEE Symposium on VLSI Technology and Circuits (VLSI Technology and Circuits)
</p>

<p>
 [C3] Dongwon Lee, Kyung-Sik Choi, Fuze Jiang, Hangxing Liu, Doohwan Jung, Ying Kong, Marco Saif, <u>Zhikai Huang</u>, Jing Wang, Hua Wang; 17.6 Fully Integrated CMOS Ferrofluidic Biomolecular Processing Platform with On-Chip Droplet-Based Manipulation, Multiplexing and Sensing; 2024 IEEE International Solid-State Circuits Conference (ISSCC)
</p>

<p>
 [C2] Hangxing Liu, Fuze Jiang, Dongwon Lee, Yuguo Sheng, Adam Wang, Marco Saif, Ying Kong, <u>Zhikai Huang</u>, Thomas Burger, Jing Wang, Hua Wang; A 256-channel in-pixel electrochemical platform in CMOS for rapid isothermal genetic amplification and screening; ESSCIRC 2023-IEEE 49th European Solid State Circuits Conference (ESSCIRC)
</p>

<p>
 [C1] Alfio Di Mauro, Arpan Suravi Prasad, <u>Zhikai Huang</u>, Matteo Spallanzani, Francesco Conti, Luca Benini; SNE: an energy-proportional digital accelerator for sparse event-based convolutions; 2022 Design, Automation & Test in Europe Conference & Exhibition (DATE)
</p>

<p>
 [T1] <u>Zhikai Huang</u>; A Continuous-Time Input Pipelined SAR ADC with Loop-Embedded Predictive Offset Generation; 2022 ETH Zürich Master Thesis
</p>
</div>




---
Last update Feb. 21, 2025;
<br><a href="https://info.flagcounter.com/7Kt5"><img src="https://s11.flagcounter.com/count2/7Kt5/bg_FFFFFF/txt_000000/border_CCCCCC/columns_4/maxflags_12/viewers_0/labels_0/pageviews_0/flags_0/percent_0/" alt="Flag Counter" border="0"></a>
