---
title: "Intraoperative Absolute Depth Estimation in MVD Surgery"
collection: publications
category: manuscripts
permalink: /publication/paper-title-number-1-Intraoperative Absolute Depth Estimation in MVD Surgery
excerpt: 'This paper is about the number 1. The number 2 is left for future work.'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://www.computer.org/csdl/proceedings-article/cbms/2025/261000a341/284Kgjo3aQU'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Lee, J., Lee, H., Park, J. J., Htun, E., Xu, B. C., Cho, S. H., ... & Buch, V. P. (2025, June). Intraoperative Absolute Depth Estimation in MVD Surgery. In 2025 IEEE 38th International Symposium on Computer-Based Medical Systems (CBMS) (pp. 341-342). IEEE Computer Society.'
---



<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <meta name="description"
        content="Skin Trouble Progression Simulation">
  <meta name="keywords" content="Diffusion Models, GANs">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Skin Trouble Progression Simulation</title>

  <!-- Global site tag (gtag.js) - Google Analytics -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-PYVRSFMDRL"></script>
  <script>
    window.dataLayer = window.dataLayer || [];

    function gtag() {
      dataLayer.push(arguments);
    }

    gtag('js', new Date());

    gtag('config', 'G-PYVRSFMDRL');
  </script>

  <link href="https://fonts.googleapis.com/css?family=Google+Sans|Noto+Sans|Castoro"
        rel="stylesheet">

  <link rel="stylesheet" href="./static/css/bulma.min.css">
  <link rel="stylesheet" href="./static/css/bulma-carousel.min.css">
  <link rel="stylesheet" href="./static/css/bulma-slider.min.css">
  <link rel="stylesheet" href="./static/css/fontawesome.all.min.css">
  <link rel="stylesheet"
        href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">
  <link rel="stylesheet" href="./static/css/index.css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script defer src="./static/js/fontawesome.all.min.js"></script>
  <script src="./static/js/bulma-carousel.min.js"></script>
  <script src="./static/js/bulma-slider.min.js"></script>
  <script src="./static/js/index.js"></script>
</head>
<body>

<section class="hero">
  <div class="hero-body">
    <div class="container is-max-desktop">
      <div class="columns is-centered">
        <div class="column has-text-centered">
          <!-- <h1 class="title is-1 publication-title">Skin Trouble Progression Simulation</h1> -->
          <!-- <div class="is-size-5 publication-authors">
            <span class="author-block">
              Jinhee Lee</a><sup>1</sup>,</span>           
            <span class="author-block">
              Chanhyuk Lee</a><sup>1</sup>,</span>
            <span class="author-block">
              Huisu Yoon</a><sup>2</sup>,
            </span>
            <span class="author-block">
              Semin Kim</a><sup>3</sup>,
            </span>
            <span class="author-block">
              Jongha Lee</a><sup>1</sup>,
            </span>            
          </div>

          <div class="is-size-5 publication-authors">
            <span class="author-block"><sup>1</sup>lululab Inc.</span>
            <span class="author-block"><sup>2</sup>University of Ulsan</span>
            <span class="author-block"><sup>3</sup>Andong National University</span>
          </div> -->

          <!-- <div class="column has-text-centered">
            <div class="publication-links">             
              <span class="link-block">
                <a href="https://arxiv.org/pdf/"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fas fa-file-pdf"></i>
                  </span>
                  <span>Paper</span>
                </a>
              </span>            
              
              <span class="link-block">
                <a href="https://github.com/"
                   class="external-link button is-normal is-rounded is-dark">
                  <span class="icon">
                      <i class="fab fa-github"></i>
                  </span>
                  <span>Code</span>
                  </a>
              </span>          
            </div>
          </div> -->
        </div>
      </div>
    </div>
  </div>
</section>

<section class="hero teaser">
  <div class="container is-max-desktop">
    <div class="hero-body">
      <img id="teaser" src="/images/SkinTroubleProgressionSimulation/teaser.png" alt="Teaser Image" style="width:100%; height:auto;">
      <!-- <h2 class="subtitle has-text-centered">
        <span class="dnerf">Skin trouble progression.
      </h2> -->
    </div>
  </div>
</section>


<section class="section">
  <div class="container is-max-desktop">    
    <!-- About This Work. -->
    <div class="columns">
      <div class="column is-full">
        <h2 class="title is-3 has-text-centered">About This Work</h2>
        <p>
          This project aims to create a pipeline for simulating the progression of skin troubles by leveraging existing generative models.
          There has been a limited number of skin trouble images available to represent continuously evolving skin conditions while maintaining consistent facial features.
          To address this limitation, we generated multi-paired skin trouble images by fine-tuning the Stable Diffusion XL model, creating a comprehensive and diverse dataset.
          Since diffusion models require long sampling times, it is challenging to observe real-time skin trouble progression.
          To address this, we further trained a GAN using our dataset to simulate severity transitions.
          By leveraging this approach, our model successfully generates photorealistic images that depict skin trouble progression with precise control over severity levels.         
        </p>
        <img src="/images/SkinTroubleProgressionSimulation/results.png" alt="Result Image" style="max-width:100%; height:auto; display:block; margin-top: 20px; margin:0 auto;">
      </div>
    </div>
    <!--/ About This Work. -->
  </div>
</section>


<section class="section">
  <div class="container is-max-desktop">

    <div class="columns is-centered">

      <!-- Visual Effects. -->
      <div class="column">
        <div class="content">
          <h2 class="title is-3 has-text-centered">Qualitative Results</h2>
          <p>
            We present skin trouble progression across different severity levels, demonstrating natural transitions in appearance.
          </p>
          <img src="/images/SkinTroubleProgressionSimulation/zoom image.png" alt="Zoom Image" style="max-width:100%; height:auto; display:block; margin-top: 20px; margin:0 auto;">
        </div>
      </div>
      <!--/ Visual Effects. -->
    </div>

    <section class="section">
      <div class="container is-max-desktop">    
        <div class="columns is-centered">
          <!-- Overview. -->
          <div class="columns">
            <div class="content">
              <h2 class="title is-3 has-text-centered">Pipeline Overview</h2>
              <p>
                Our pipeline consists of two main stages: (1) dataset generation and (2) GAN-based severity transition modeling.
                First, we fine-tune the Stable Diffusion XL model to create a diverse, multi-paired skin trouble dataset while maintaining consistent facial features.
                The training dataset includes 55k facial images with severity scores assigned using a pre-trained trouble score estimation model. 
                We generate text prompts by combining BLIP captions with severity scores, enabling the diffusion model to produce a structured dataset across 10 severity levels.
                Using the multi-paired skin trouble dataset generated from the diffusion model, we then train a GAN to simulate severity transitions with precise control over progression levels.             
              </p>
              <img src="/images/SkinTroubleProgressionSimulation/overview.png" alt="Overview Image" style="max-width:100%; height:auto; display:block; margin-top: 20px; margin:0 auto;">
            </div>
          </div>
        </div>
        <!--/ Overview. -->
      </div>
    </section>


    <!-- Concurrent Work. -->
    <div class="columns is-centered">
      <div class="column is-full-width">
        <h2 class="title is-3">Related Links</h2>

        <div class="content has-text-justified">
          <p>
            Here are some excellent works that inspired and contributed to our approach.
          </p>
          <p>
            <a href="https://github.com/kohya-ss/sd-scripts">Stable Diffusion XL</a> provides recent diffusion-based pipelines for general applications.
          </p>
          <p>
            We utilized <a href="https://github.com/ry-lu/pytorch-face-reaging-network">FRAN</a> for GAN training.
          </p>          
        </div>
    </div>
    <!--/ Concurrent Work. -->

  </div>
</section>


<section class="section" id="BibTeX">
  <div class="container is-max-desktop content">
    <h2 class="title">BibTeX</h2>
    <pre><code>@article{,
  author    = {Jinhee Lee},
  title     = {REALISTIC SKIN TROUBLE SIMULATION VIA IMAGE GENERATION MODELS},
  journal   = {},
  year      = {2025},
}</code></pre>
  </div>
</section>


<footer class="footer">
  <div class="container">    
    <div class="columns is-centered">
      <div class="column is-8">
        <div class="content">
          <p>
            This website is licensed under a <a rel="license"
                                                href="http://creativecommons.org/licenses/by-sa/4.0/">Creative
            Commons Attribution-ShareAlike 4.0 International License</a>.
          </p>
          <p>
            Website taken from <a
              href="https://github.com/nerfies/nerfies.github.io">here</a>.
          </p>
        </div>
      </div>
    </div>
  </div>
</footer>

</body>
</html>
