---
layout: default
title: "CV"
permalink: /CV/
---
# Curriculum Vitae 
I am a graduating PhD student in Health Data Science at the University of Oxford specialising in machine learning for medical sensor data. My research aims to improve cardiovascular risk prediction through the discovery of novel digital biomarkers. 

Below is a summary of my academic background, research experience, and technical skills. A downloadable PDF version of my CV is available [here](/assets/files/CV.pdf).

<hr>


<h2>Technical Summary</h2>

<h4>🧑‍💻 Programming Languages</h4>
<div class="row text-center mb-4 cv-tech-summary">
  <div class="col-md-3"><strong>Python, R, SQL</strong><br/><small>5+ years</small></div>
  <div class="col-md-3"><strong>C / C++ / Java / Haskell</strong><br/><small>2–3 years</small></div>
</div>

<h4>⚙️ Tech stack</h4>
<div class="row text-center cv-tech-summary">
  <div class="col-md-3"><strong>ML / DL</strong><br/><small>PyTorch, TensorFlow, scikit-learn, SHAP</small></div>
  <div class="col-md-3"><strong>Data</strong><br/><small>Pandas, NumPy, Spark</small></div>
  <div class="col-md-3"><strong>MLOps</strong><br/><small>Docker, Git, ClearML</small></div>
  <div class="col-md-3"><strong>Other</strong><br/><small>AWS, Palantir Foundry, Jupyter, Anaconda, RMarkdown, LaTeX</small></div>
</div>



<hr>

<!-- ✅ Bootstrap Accordion -->
<style>
/* 🔽 Arrow chevron right-aligned and animated */
.accordion-header {
  position: relative;
}

.accordion-button .chevron {
  position: absolute;
  right: 1.25rem;
  top: 50%;
  transform: translateY(-50%);
  transition: transform 0.2s ease;
}

.accordion-button .chevron::after {
  content: "▼";
  font-size: 0.9rem;
  display: inline-block;
  transition: transform 0.2s ease;
}

.accordion-button:not(.collapsed) .chevron::after {
  transform: rotate(180deg);
}
</style>

{% raw %}
<div class="accordion" id="cvAccordion">

<!-- 💼 Professional Experience -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingExp">
    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseExp" aria-expanded="true" aria-controls="collapseExp">
      💼 Professional Experience
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapseExp" class="accordion-collapse collapse show">
    <div class="accordion-body">
      <p><strong>PhD Researcher in Health Data Science</strong> – <em>University of Oxford, Oct 2020 – May 2025</em></p>
      <ul>
        <li>Built  scalable deep learning pipelines for medical device data such as ECG to future disese incident disease</li>
        <li>Achieved up to 17% improvement in identifying eligible patients for treatment over the current NHS risk tools</li>
        <li>Presented at top international conferences such as ESC, BSC, ICAMPAM</li>
      </ul>

      <p><strong> Life & Health R&D Analyst – Swiss Re</strong> – <em>Internship:  Jun–Aug 2024</em></p>
      <ul>
        <li>Conducted mortality forecasting across 6 million surveyed individuals using LSTM and ARIMA models to support pricing strategies</li>
        <li>Used causal methods such as G-computation to assess difference in mortality between insured and uninsured
populations</li>
        <li>Authored scientific reports on emerging medical innovations shaping life and health insurance, published for internal and external stakeholders</li>
      </ul>

      <p><strong>Software Engineer – Intel Corporation</strong> – <em>Jul 2018 – Aug 2019</em></p>
      <ul>
        <li>Provided software consultation to major accounting firms to address </li>
        <li>Optimised financial algorithms (Black-Scholes, Monte Carlo)</li>
        <li>Managed and maintained high-performance computing (HPC) resources, including cluster infrastructure, and performance monitoring.</li>
      </ul>
    </div>
  </div>
</div>

<!-- 🎓 Education -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingEdu">
    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseEdu" aria-expanded="true" aria-controls="collapseEdu">
      🎓 Education
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapseEdu" class="accordion-collapse collapse show">
    <div class="accordion-body">
      <p><strong>PhD, Health Data Science (EPSRC CDT)</strong> – <em>University of Oxford</em></p>
      <ul>
        <li>Full EPSRC scholarship and enhanced stipend (~£100,000 over four years)</li>
      </ul>

      <p><strong>BSc (Hons), Computer Science</strong> – <em>University of Nottingham</em></p>
      <ul>
        <li>First Class Honours, 85% (Ranked 1st out of 180, awarded the School of Computer Science Top Student Award).</li>
      </ul>
    </div>
  </div>
</div>


<!-- 📚 Publications -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingPubs">
    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapsePubs">
      📚 Publications
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapsePubs" class="accordion-collapse collapse">
    <div class="accordion-body">

      <p><strong>First-author manuscripts</strong></p>
      <ul>
        <li><strong>Sturge</strong>, Harper et al. <a href="https://doi.org/10.1101/2025.04.03.25325101">Predictive performance of wearable sensors for mortality risk in older adults: a model development and validation study</a>. <em>medRxiv</em>, 2025.</li>
      </ul>

      <p><strong>Working Manuscripts (in preparation to submit)</strong></p>
      <ul>
        <li><strong>Sturge AD</strong>, et al. <em>Development and validation of an ECG-based 10-year risk prediction model for Major Adverse Cardio/Cerebrovascular Events in UK Biobank</em>. 2025.</li>
        <li><strong>Sturge, AD</strong> et al. <em>The added value of the objectively measured physical activity to the prediction of incident Major Adverse Cardio/Cerebrovascular Events</em>. 2025.</li>
        <li>Acquah A, <strong>Sturge, AD</strong> et al. <em>The added value of objectively measured gait to the prediction of Parkinson’s disease</em>. 2025.</li>
      </ul>

     <p><strong>Industry Reports</strong></p>
      <ul>
        <li><em>Swiss Re</em>. <a href="https://www.swissre.com/reinsurance/insights/alzheimers-disease-growing-development.html">Alzheimer’s Disease a growing risk with promising developments 
 Risk</a></li>
      </ul>

    </div>
  </div>
</div>

<!-- 🎤 Invited Talks -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingTalks">
    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTalks">
      🎤 Invited Talks
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapseTalks" class="accordion-collapse collapse">
    <div class="accordion-body">
      <ul>
        <li>European Society of Cardiology | August 2024</li>
        <li>
          British Cardiovascular Society | June 2024
          <ul>
            <li>Received “Best of the Best” awards for two oral presentations</li>
          </ul>
        </li>
        <li>International Society for the Measurement of Physical Activity | June 2024</li>
        <li>British Heart Foundation Centre for Research Excellence Symposium | November 2023</li>
      </ul>
    </div>
  </div>
</div>

<!-- 🏆 Awards -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingAwards">
    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseAwards">
      🏆 Awards
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapseAwards" class="accordion-collapse collapse">
    <div class="accordion-body">
      <ul>
        <li><strong>EPSRC Health Data Science CDT Studentship</strong> – Full funding, 2020–2024</li>
        <li>
          <strong>University of Nottingham School of Computer Science Top Student Award</strong>, 2020
          <ul>
            <li>Awarded for graduating at the top of my BSc (Hons) cohort</li>
          </ul>
        </li>
        <li>
          <strong>Undergraduate Exceptional Achievement Award</strong> – 2017 & 2018
          <ul>
            <li>Awarded for completing the academic year within the top 5 of the cohort for overall percentage grade</li>
          </ul>
        </li>
      </ul>
    </div>
  </div>
</div>



<!-- 🤝 Outreach -->
<div class="accordion-item mb-5 cv-section">
  <h2 class="accordion-header" id="headingOutreach">
    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOutreach">
      🤝 Charity & Outreach 
      <span class="chevron"></span>
    </button>
  </h2>
  <div id="collapseOutreach" class="accordion-collapse collapse">
    <div class="accordion-body">
      <p><strong>Treasurer, Austrian Society</strong> – <em>University Of Oxford (2022–2024)</em></p>
      <ul>
        <li>Managed budget and cultural programming</li>
      </ul>

      <p><strong>Technical Lead, Intel Inspire/STEM committee</strong> – <em>Intel (2018–2019)</em></p>
      <ul>
        <li>Delivered AI/STEM workshops to 1,000+ students</li>
      </ul>
    </div>
  </div>
</div>

</div> <!-- End Accordion -->
{% endraw %}
<div class="mt-5"></div>

<hr>

## 📄 Download

- [Download CV (PDF)](/assets/files/CV.pdf)