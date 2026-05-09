---
title:
date: 2026-05-05
type: landing

sections:
  - block: markdown
    content:
      title:
      text: |
        <section class="shen-home-hero">
          <p class="shen-eyebrow">Engineering Channel Materials</p>
          <h1>Shen Research Group</h1>
          <p>For energy, environment, and healthcare.</p>
        </section>
    design:
      columns: "1"
      background:
        gradient_start: "#f3fbfa"
        gradient_end: "#ffffff"

  - block: markdown
    content:
      title: Featured research
      text: |
        <div id="shenFeaturedResearch" class="carousel slide shen-feature-carousel" data-ride="carousel" data-interval="6000">
          <ol class="carousel-indicators">
            <li data-target="#shenFeaturedResearch" data-slide-to="0" class="active"></li>
            <li data-target="#shenFeaturedResearch" data-slide-to="1"></li>
            <li data-target="#shenFeaturedResearch" data-slide-to="2"></li>
            <li data-target="#shenFeaturedResearch" data-slide-to="3"></li>
            <li data-target="#shenFeaturedResearch" data-slide-to="4"></li>
          </ol>
          <div class="carousel-inner">
            <article class="carousel-item active">
              <div class="shen-feature-slide">
                <div>
                  <p class="shen-eyebrow">Science, 387 (2025) 776-782</p>
                  <h2>Engineering grain boundaries in monolayer molybdenum disulfide for efficient water-ion separation</h2>
                  <p>A key challenge for advancing membrane separation is the formation of uniform nanopores over large areas on robust 2D materials. Here, we show the engineering of atomically precise molecular channels in monolayer 2D films by using chemical vapor deposition. A high density of eight-membered rings is harnessed for fast single-file water transport while blocking ions.</p>
                  <p>A fascinating philosophy here: sometimes, "defects" make things "perfect"!</p>
                  <p><a class="btn btn-primary btn-lg" href="https://www-science-org.remotexs.ntu.edu.sg/doi/abs/10.1126/science.ado7489">Read More</a></p>
                </div>
                <img src="/media/science-sj.jpg" alt="Science feature image for MoS2 water-ion separation">
              </div>
            </article>
            <article class="carousel-item">
              <div class="shen-feature-slide">
                <div>
                  <p class="shen-eyebrow">Nature Materials, 2022</p>
                  <h2>Fast water transport and molecular sieving through conjugated-polymer-framework membranes</h2>
                  <p>Carbon nanomaterials such as graphene show intriguing molecular transport properties, but achieving regular channels over a large area requires perfect sheet alignment. This work fabricated a large-area two-dimensional conjugated-polymer-framework with regular pore distribution by a surface-confined CVD method, enabling fast water transport and greater than 99.5% salt rejection driven by osmotic pressure.</p>
                  <p><a class="btn btn-primary btn-lg" href="https://www.nature.com/articles/s41563-022-01325-y">Read More</a></p>
                </div>
                <img src="/media/featured-nat-mater-conjugated-polymer-framework.jpg" alt="Nature Materials feature image for conjugated-polymer-framework membranes">
              </div>
            </article>
            <article class="carousel-item">
              <div class="shen-feature-slide">
                <div>
                  <p class="shen-eyebrow">Nature Reviews Materials, 2021</p>
                  <h2>Artificial channels for confined mass transport at the sub-nanometre scale</h2>
                  <p>Artificial channels that selectively transport small molecules at the sub-nanometre scale are used in molecular separation. This review discusses channel design, nanostructure, fabrication, mass-transport mechanisms, promising applications, and future challenges.</p>
                  <p><a class="btn btn-primary btn-lg" href="https://www.nature.com/articles/s41578-020-00268-7">Read More</a></p>
                </div>
                <img src="/media/featured-nat-rev-materials-artificial-channels.jpg" alt="Nature Reviews Materials feature image for artificial channels">
              </div>
            </article>
            <article class="carousel-item">
              <div class="shen-feature-slide">
                <div>
                  <p class="shen-eyebrow">Nature, 550 (2017) 380-383</p>
                  <h2>Cationic control of membrane pore size</h2>
                  <p>Graphene oxide membranes have been explored as ion-sieving devices for water purification and related applications. This work demonstrated control of interlayer spacing using ions themselves, enabling ionic sieving as smaller interlayer spacings prevent larger cations from penetrating the membrane.</p>
                  <p><a class="btn btn-primary btn-lg" href="https://www.nature.com/articles/nature24044">Read More</a></p>
                </div>
                <img src="/media/featured-nature-ion-sieving.jpg" alt="Nature feature image for ion sieving in graphene oxide membranes">
              </div>
            </article>
            <article class="carousel-item">
              <div class="shen-feature-slide">
                <div>
                  <p class="shen-eyebrow">Science Advances, 6 (2020) eabb5367</p>
                  <h2>Electronic skin has a strong future stretching ahead</h2>
                  <p>A durable electronic skin was created using a hydrogel reinforced with silica nanoparticles as a strong and stretchy substrate and two-dimensional titanium carbide MXene as the sensing layer. The multidimensional configuration enables a broad working range, fast response, resilience, linearity, and reproducibility.</p>
                  <p><a class="btn btn-primary btn-lg" href="https://www.science.org/doi/10.1126/sciadv.abb5367">Read More</a></p>
                </div>
                <img src="/media/featured-sci-adv-e-skin.jpg" alt="Science Advances feature image for stretchable electronic skin">
              </div>
            </article>
          </div>
          <a class="carousel-control-prev" href="#shenFeaturedResearch" role="button" data-slide="prev">
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a class="carousel-control-next" href="#shenFeaturedResearch" role="button" data-slide="next">
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
    design:
      columns: "1"

  - block: collection
    content:
      title: News
      count: 5
      filters:
        folders:
          - post
      order: desc
    design:
      view: compact
      columns: "1"

  - block: markdown
    content:
      title: Contact
      text: |
        <div class="shen-contact-strip">
          <a href="mailto:jie.shen@ntu.edu.sg">Email</a>
          <a href="https://scholar.google.com/citations?hl=zh-CN&amp;user=lTyNfBsAAAAJ">Google Scholar</a>
          <a href="https://www.linkedin.com/in/jie-shen-871536b8/">LinkedIn</a>
          <a href="https://www.ntu.edu.sg/mse/about-us/our-people/faculty-staff/jieshen">Academic Profile</a>
        </div>
    design:
      columns: "1"
      background:
        color: "#f7faf9"
---
