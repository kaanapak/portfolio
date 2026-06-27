---
layout: page
title: home
permalink: /
nav: false
description: Personal academic website for Kaan APAK.
---

<link rel="stylesheet" href="{{ '/assets/css/personal.css' | relative_url }}">

<main class="ka-home" data-ka-theme="dark" data-ka-lang="en">
  <nav class="ka-floating-nav" aria-label="Homepage sections">
    <a href="#home" data-i18n="nav.home">Home</a>
    <a href="#experience" data-i18n="nav.experience">Experience</a>
    <a href="#projects" data-i18n="nav.projects">Projects</a>
    <a href="#contact" data-i18n="nav.contact">Contact</a>
    <div class="ka-lang-toggle" aria-label="Language">
      <button class="ka-lang-button" type="button" data-lang-option="en" aria-label="English" aria-pressed="true">🇬🇧</button>
      <button class="ka-lang-button" type="button" data-lang-option="tr" aria-label="Türkçe" aria-pressed="false">🇹🇷</button>
    </div>
    <button class="ka-theme-toggle" type="button" aria-label="Switch to light theme" aria-pressed="false">
      <svg class="ka-theme-toggle__sun" aria-hidden="true" viewBox="0 0 24 24">
        <path d="M12 5.5a6.5 6.5 0 1 1 0 13 6.5 6.5 0 0 1 0-13Zm0-4v2.2m0 16.6v2.2M4.57 4.57l1.56 1.56m11.74 11.74 1.56 1.56M1.5 12h2.2m16.6 0h2.2M4.57 19.43l1.56-1.56M17.87 6.13l1.56-1.56" />
      </svg>
      <svg class="ka-theme-toggle__moon" aria-hidden="true" viewBox="0 0 24 24">
        <path d="M20.2 15.55A8.3 8.3 0 0 1 8.45 3.8 8.7 8.7 0 1 0 20.2 15.55Z" />
      </svg>
    </button>
  </nav>

  <div class="ka-shell">
    <section class="ka-hero" id="home" aria-labelledby="ka-hero-title">
      <div class="ka-hero__copy">
        <p class="ka-hero__role" data-i18n="hero.role">Optimization, machine learning, and decision analytics</p>
        <h1 id="ka-hero-title">Kaan <span class="ka-gradient-text">APAK</span></h1>
        <p class="ka-hero__lead" data-i18n="hero.lead">
          I develop optimization and machine learning models that power pricing, operations research, interpretable AI, and decision systems.
        </p>
        <p class="ka-hero__lead ka-hero__lead--secondary" data-i18n="hero.secondary">
          I will pursue a PhD in Management Science at the University of Waterloo under the supervision of Sibel A. Alumur and Recep Bekci.
        </p>
        <div class="ka-hero-actions">
          <a class="ka-button ka-button--primary" href="{{ '/assets/pdf/kaan-apak-cv.pdf' | relative_url }}" download>
            <svg aria-hidden="true" viewBox="0 0 24 24">
              <path d="M12 3v11m0 0 4-4m-4 4-4-4M5 20h14" />
            </svg>
            <span data-i18n="hero.downloadCv">Download my CV</span>
          </a>
          <a class="ka-button ka-button--icon" href="https://www.linkedin.com/in/kaan-apak-13307716a" rel="noopener noreferrer" target="_blank" aria-label="LinkedIn" data-i18n-attr="aria-label:hero.linkedinLabel">
            <svg aria-hidden="true" viewBox="0 0 24 24">
              <path d="M6.94 8.76H3.66v10.58h3.28V8.76ZM5.3 3.5a1.9 1.9 0 1 0 0 3.8 1.9 1.9 0 0 0 0-3.8ZM20.34 13.43c0-3.08-1.64-4.51-3.83-4.51a3.3 3.3 0 0 0-2.97 1.63h-.04V8.76h-3.15v10.58h3.28v-5.23c0-1.38.26-2.72 1.98-2.72 1.69 0 1.71 1.58 1.71 2.81v5.14h3.28v-5.91h-.26Z" />
            </svg>
          </a>
        </div>
      </div>

      <div class="ka-hero-visual" aria-label="Portrait and decision analytics preview" data-i18n-attr="aria-label:hero.visualLabel">
        <figure class="ka-portrait">
          <img src="{{ '/assets/img/kaan/profile.jpeg' | relative_url }}" alt="Portrait of Kaan APAK" data-i18n-attr="alt:hero.portraitAlt" loading="eager">
        </figure>
        <div class="ka-visual-panel">
          <span data-i18n="hero.panelLabel">Decision support</span>
          <strong data-i18n="hero.panelText">Turning complex data and operational constraints into usable tools.</strong>
          <div class="ka-mini-bars" aria-hidden="true"><i></i><i></i><i></i></div>
        </div>
      </div>
    </section>

    <section class="ka-section" id="experience" aria-labelledby="ka-experience-title">
      <div class="ka-section__heading">
        <h2 id="ka-experience-title" data-i18n="experience.heading">Experience</h2>
        <p data-i18n="experience.subheading">Research, analytics, teaching, and decision-support work across university and industry settings.</p>
      </div>

      <div class="ka-experience-track" aria-label="Experience cards" data-i18n-attr="aria-label:experience.trackLabel">
        <article class="ka-experience-card">
          <div class="ka-logo-frame">
            <img src="{{ '/assets/img/kaan/logo-waterloo.png' | relative_url }}" alt="University of Waterloo logo" loading="lazy">
          </div>
          <h3 data-i18n="experience.waterloo.title">PhD Student in Management Science</h3>
          <p class="ka-card__meta" data-i18n="experience.waterloo.org">University of Waterloo</p>
          <p data-i18n="experience.waterloo.preview">
            Starting in Fall 2026, I will pursue my PhD in Management Science at the University of Waterloo under the supervision of Professor Sibel A. Alumur and Assistant Professor Recep Bekci.
          </p>
          <details class="ka-card-details">
            <summary data-i18n="common.readMore">Read more</summary>
            <p data-i18n="experience.waterloo.more">As part of my doctoral studies, I will also serve as both a Research Assistant and Teaching Assistant.</p>
          </details>
        </article>

        <article class="ka-experience-card ka-experience-card--borusan">
          <div class="ka-logo-frame ka-logo-frame--wide">
            <img src="{{ '/assets/img/kaan/logo-borusan-cat.jpg' | relative_url }}" alt="Borusan CAT logo" loading="lazy">
          </div>
          <h3 data-i18n="experience.borusan.title">Data Analytics &amp; Business Intelligence Specialist</h3>
          <p class="ka-card__meta" data-i18n="experience.borusan.org">Borusan CAT</p>
          <p data-i18n="experience.borusan.preview">I develop data-driven solutions that support pricing, sales, customer, and operational decision making.</p>
          <details class="ka-card-details">
            <summary data-i18n="common.readMore">Read more</summary>
            <div class="ka-detail-prose">
              <p data-i18n="experience.borusan.more1">My work combines analytics, automation, and business intelligence to transform complex data into practical tools for decision makers.</p>
              <p data-i18n="experience.borusan.more2">I have designed Power BI dashboards for sales and customer analytics, developed pricing simulation tools that support pricing analysts in determining list prices, and automated numerous reporting and analytical processes using Python, VBA, and Power Automate. I also coordinated data warehouse planning initiatives, contributed to data governance by defining data quality metrics, and worked closely with IT teams to improve enterprise data infrastructure. In addition, I initiated an AI-powered dashboard assistant concept and collaborated with IT teams on its implementation and organization-wide adoption.</p>
            </div>
          </details>
        </article>

        <article class="ka-experience-card">
          <div class="ka-logo-frame ka-logo-frame--wide">
            <img
              src="{{ '/assets/img/kaan/logo-sustainability-platform.png' | relative_url }}"
              data-lang-src-en="{{ '/assets/img/kaan/logo-sustainability-platform.png' | relative_url }}"
              data-lang-src-tr="{{ '/assets/img/kaan/logo-sustainability-platform.png' | relative_url }}"
              alt="Ozyegin University Sustainability Platform logo"
              data-i18n-attr="alt:experience.sustainability.logoAlt"
              loading="lazy"
            >
          </div>
          <h3 data-i18n="experience.sustainability.title">Data Analyst</h3>
          <p class="ka-card__meta" data-i18n="experience.sustainability.org">Ozyegin University Sustainability Platform</p>
          <p data-i18n="experience.sustainability.preview">
            I developed analytical tools that measure and visualize the university's contributions to the United Nations Sustainable Development Goals.
          </p>
          <details class="ka-card-details">
            <summary data-i18n="common.readMore">Read more</summary>
            <p data-i18n="experience.sustainability.more">
              I collaborated with researchers, librarians, and IT teams to integrate research and educational data into interactive dashboards and built Python-based tools to classify academic activities automatically.
            </p>
          </details>
        </article>

        <article class="ka-experience-card">
          <div class="ka-logo-frame ka-logo-frame--wide">
            <img src="{{ '/assets/img/kaan/logo-ozyegin-university.png' | relative_url }}" alt="Ozyegin University logo" loading="lazy">
          </div>
          <h3 data-i18n="experience.ozyegin.title">Teaching &amp; Research Assistant</h3>
          <p class="ka-card__meta" data-i18n="experience.ozyegin.org">Ozyegin University</p>
          <p data-i18n="experience.ozyegin.preview">
            I supported Simulation Modelling, Probability, Mathematical Modelling, and Heuristic Algorithms through recitations, office hours, and mentoring.
          </p>
          <details class="ka-card-details">
            <summary data-i18n="common.readMore">Read more</summary>
            <p data-i18n="experience.ozyegin.more">
              Alongside my teaching responsibilities, I contributed to research projects in optimization and healthcare operations under the supervision of Professor Burcu Balcik, working on decision support systems and heuristic algorithms for post-disaster healthcare planning.
            </p>
          </details>
        </article>
      </div>
    </section>

    <section class="ka-section ka-projects" id="projects" aria-labelledby="ka-projects-title">
      <div class="ka-section__heading">
        <h2 id="ka-projects-title" data-i18n="projects.heading">Projects</h2>
        <p data-i18n="projects.subheading">Research projects that translate optimization and machine learning methods into practical decision support.</p>
      </div>

      <div class="ka-project-grid">
        <article class="ka-project-card">
          <div class="ka-project-card__image">
            <img src="{{ '/assets/img/kaan/disaster-planning.png' | relative_url }}" alt="Renal disaster coordination system interface" data-i18n-attr="alt:projects.disaster.imageAlt" loading="lazy">
          </div>
          <div class="ka-project-card__content">
            <h3 data-i18n="projects.disaster.title">Disaster Planning for Hemodialysis Patients</h3>
            <p data-i18n="projects.disaster.preview">
              This project develops optimization-based decision support tools for coordinating hemodialysis treatments following large-scale disasters, where healthcare capacity is severely constrained.
            </p>
            <a class="ka-publication-chip" href="https://www.sciencedirect.com/science/article/abs/pii/S0305048326000538" rel="noopener noreferrer" target="_blank">
              <span class="ka-publication-chip__cover" aria-hidden="true">
                <img src="{{ '/assets/img/kaan/omega.jpg' | relative_url }}" alt="" loading="lazy">
              </span>
              <span>
                <strong data-i18n="projects.disaster.publicationTitle">Chronic care management in times of capacity shortages: An integrated patient assignment and treatment scheduling problem for post-disaster hemodialysis planning</strong>
                <em data-i18n="projects.disaster.publicationAction">Omega - The International Journal of Management Science · sciencedirect.com</em>
              </span>
            </a>
            <details class="ka-card-details">
              <summary data-i18n="common.viewDescription">View description</summary>
              <p data-i18n="projects.disaster.more1">
                Conducted in collaboration with the Turkish Society of Nephrology's Renal Disaster Relief Task Force, the research focuses on improving patient access to life-sustaining treatment under emergency conditions.
              </p>
              <p data-i18n="projects.disaster.more2">
                My primary contributions focused on the development of a prototype decision support system that translates optimization models into a practical tool for disaster coordinators, and on the design of the <strong>Iterative Constructive Heuristic (ICH)</strong>, a scalable solution algorithm that rapidly produces high-quality treatment plans for large real-world instances.
              </p>
            </details>
          </div>
        </article>

        <article class="ka-project-card">
          <div class="ka-project-card__image">
            <img src="{{ '/assets/img/kaan/b2b-pricing.jpg' | relative_url }}" alt="Industrial aftermarket parts used for quotation-based pricing research" data-i18n-attr="alt:projects.pricing.imageAlt" loading="lazy">
          </div>
          <div class="ka-project-card__content">
            <h3 data-i18n="projects.pricing.title">Optimizing Quotation-Based B2B Pricing</h3>
            <p data-i18n="projects.pricing.preview">
              This research addresses quotation-based pricing in B2B aftermarket sales, where firms must determine profitable yet competitive prices for individual quotations.
            </p>
            <details class="ka-card-details">
              <summary data-i18n="common.viewDescription">View description</summary>
              <p data-i18n="projects.pricing.more1">
                The project introduces a novel regression clustering framework that simultaneously identifies customer price sensitivities and estimates pricing models directly from historical quotation data.
              </p>
              <p data-i18n="projects.pricing.more2">
                The core contribution of the research is the development of the Iterative Refit Classifier (IRC), a heuristic regression clustering algorithm designed to solve large-scale pricing problems efficiently while maintaining high predictive performance.
              </p>
              <p data-i18n="projects.pricing.more3">
                To further improve accuracy without sacrificing interpretability, I also proposed a teacher-student framework that distills complex machine learning models into an explainable pricing methodology. Together, these methods enable pricing analysts to identify heterogeneous price elasticities across quotation groups and support more informed, data-driven pricing decisions in industrial B2B environments.
              </p>
            </details>
          </div>
        </article>
      </div>
    </section>

    <section class="ka-section ka-contact" id="contact" aria-labelledby="ka-contact-title">
      <div class="ka-section__heading">
        <h2 id="ka-contact-title" data-i18n="contact.heading">Let's connect</h2>
        <p data-i18n="contact.subheading">For research conversations, collaboration, and future consulting inquiries.</p>
      </div>

      <div class="ka-contact-grid">
        <a class="ka-contact-link" href="mailto:kaanapak@outlook.com">
          <span class="ka-contact-link__icon" aria-hidden="true">
            <svg viewBox="0 0 24 24">
              <path d="M4 6.5h16v11H4z" />
              <path d="m4.7 7.2 7.3 5.5 7.3-5.5" />
            </svg>
          </span>
          <span class="ka-contact-link__copy">
            <span data-i18n="contact.emailLabel">Email</span>
            <strong>kaanapak@outlook.com</strong>
          </span>
        </a>
        <a class="ka-contact-link" href="https://www.linkedin.com/in/kaan-apak-13307716a" rel="noopener noreferrer" target="_blank">
          <span class="ka-contact-link__icon ka-contact-link__icon--linkedin" aria-hidden="true">
            <svg viewBox="0 0 24 24">
              <path d="M6.94 8.76H3.66v10.58h3.28V8.76ZM5.3 3.5a1.9 1.9 0 1 0 0 3.8 1.9 1.9 0 0 0 0-3.8ZM20.34 13.43c0-3.08-1.64-4.51-3.83-4.51a3.3 3.3 0 0 0-2.97 1.63h-.04V8.76h-3.15v10.58h3.28v-5.23c0-1.38.26-2.72 1.98-2.72 1.69 0 1.71 1.58 1.71 2.81v5.14h3.28v-5.91h-.26Z" />
            </svg>
          </span>
          <span class="ka-contact-link__copy">
            <span>LinkedIn</span>
            <strong>linkedin.com/in/kaan-apak-13307716a</strong>
          </span>
        </a>
      </div>
    </section>

    <footer class="ka-footer">
      <p>© 2026 Kaan Apak</p>
    </footer>
  </div>
</main>

<script>
  (function () {
    var home = document.querySelector(".ka-home");
    var themeToggle = document.querySelector(".ka-theme-toggle");
    var langButtons = document.querySelectorAll("[data-lang-option]");
    if (!home || !themeToggle) return;

    var dictionary = {
      en: {
        "nav.home": "Home",
        "nav.experience": "Experience",
        "nav.projects": "Projects",
        "nav.contact": "Contact",
        "common.readMore": "Read more",
        "common.viewDescription": "View description",
        "hero.role": "Optimization, machine learning, and decision analytics",
        "hero.lead": "I develop optimization and machine learning models that power pricing, operations research, interpretable AI, and decision systems.",
        "hero.secondary": "I will pursue a PhD in Management Science at the University of Waterloo under the supervision of Sibel A. Alumur and Recep Bekci.",
        "hero.visualLabel": "Portrait and decision analytics preview",
        "hero.portraitAlt": "Portrait of Kaan APAK",
        "hero.downloadCv": "Download my CV",
        "hero.linkedinLabel": "LinkedIn profile",
        "hero.panelLabel": "Decision support",
        "hero.panelText": "Turning complex data and operational constraints into usable tools.",
        "experience.heading": "Experience",
        "experience.subheading": "Research, analytics, teaching, and decision-support work across university and industry settings.",
        "experience.trackLabel": "Experience cards",
        "experience.waterloo.title": "PhD Student in Management Science",
        "experience.waterloo.org": "University of Waterloo",
        "experience.waterloo.preview": "Starting in Fall 2026, I will pursue my PhD in Management Science at the University of Waterloo under the supervision of Professor Sibel A. Alumur and Assistant Professor Recep Bekci.",
        "experience.waterloo.more": "As part of my doctoral studies, I will also serve as both a Research Assistant and Teaching Assistant.",
        "experience.borusan.title": "Data Analytics & Business Intelligence Specialist",
        "experience.borusan.org": "Borusan CAT",
        "experience.borusan.preview": "I develop data-driven solutions that support pricing, sales, customer, and operational decision making.",
        "experience.borusan.more1": "My work combines analytics, automation, and business intelligence to transform complex data into practical tools for decision makers.",
        "experience.borusan.more2": "I have designed Power BI dashboards for sales and customer analytics, developed pricing simulation tools that support pricing analysts in determining list prices, and automated numerous reporting and analytical processes using Python, VBA, and Power Automate. I also coordinated data warehouse planning initiatives, contributed to data governance by defining data quality metrics, and worked closely with IT teams to improve enterprise data infrastructure. In addition, I initiated an AI-powered dashboard assistant concept and collaborated with IT teams on its implementation and organization-wide adoption.",
        "experience.sustainability.title": "Data Analyst",
        "experience.sustainability.org": "Ozyegin University Sustainability Platform",
        "experience.sustainability.logoAlt": "Ozyegin University Sustainability Platform logo",
        "experience.sustainability.preview": "I developed analytical tools that measure and visualize the university's contributions to the United Nations Sustainable Development Goals.",
        "experience.sustainability.more": "I collaborated with researchers, librarians, and IT teams to integrate research and educational data into interactive dashboards and built Python-based tools to classify academic activities automatically.",
        "experience.ozyegin.title": "Teaching & Research Assistant",
        "experience.ozyegin.org": "Ozyegin University",
        "experience.ozyegin.preview": "I supported Simulation Modelling, Probability, Mathematical Modelling, and Heuristic Algorithms through recitations, office hours, and mentoring.",
        "experience.ozyegin.more": "Alongside my teaching responsibilities, I contributed to research projects in optimization and healthcare operations under the supervision of Professor Burcu Balcik, working on decision support systems and heuristic algorithms for post-disaster healthcare planning.",
        "projects.heading": "Projects",
        "projects.subheading": "Research projects that translate optimization and machine learning methods into practical decision support.",
        "projects.disaster.title": "Disaster Planning for Hemodialysis Patients",
        "projects.disaster.preview": "This project develops optimization-based decision support tools for coordinating hemodialysis treatments following large-scale disasters, where healthcare capacity is severely constrained.",
        "projects.disaster.imageAlt": "Renal disaster coordination system interface",
        "projects.disaster.publicationTitle": "Chronic care management in times of capacity shortages: An integrated patient assignment and treatment scheduling problem for post-disaster hemodialysis planning",
        "projects.disaster.publicationAction": "Omega - The International Journal of Management Science · sciencedirect.com",
        "projects.disaster.more1": "Conducted in collaboration with the Turkish Society of Nephrology's Renal Disaster Relief Task Force, the research focuses on improving patient access to life-sustaining treatment under emergency conditions.",
        "projects.disaster.more2": "My primary contributions focused on the development of a prototype decision support system that translates optimization models into a practical tool for disaster coordinators, and on the design of the <strong>Iterative Constructive Heuristic (ICH)</strong>, a scalable solution algorithm that rapidly produces high-quality treatment plans for large real-world instances.",
        "projects.pricing.title": "Optimizing Quotation-Based B2B Pricing",
        "projects.pricing.preview": "This research addresses quotation-based pricing in B2B aftermarket sales, where firms must determine profitable yet competitive prices for individual quotations.",
        "projects.pricing.imageAlt": "Industrial aftermarket parts used for quotation-based pricing research",
        "projects.pricing.more1": "The project introduces a novel regression clustering framework that simultaneously identifies customer price sensitivities and estimates pricing models directly from historical quotation data.",
        "projects.pricing.more2": "The core contribution of the research is the development of the Iterative Refit Classifier (IRC), a heuristic regression clustering algorithm designed to solve large-scale pricing problems efficiently while maintaining high predictive performance.",
        "projects.pricing.more3": "To further improve accuracy without sacrificing interpretability, I also proposed a teacher-student framework that distills complex machine learning models into an explainable pricing methodology. Together, these methods enable pricing analysts to identify heterogeneous price elasticities across quotation groups and support more informed, data-driven pricing decisions in industrial B2B environments.",
        "contact.heading": "Let's connect",
        "contact.subheading": "For research conversations, collaboration, and future consulting inquiries.",
        "contact.emailLabel": "Email"
      },
      tr: {
        "nav.home": "Ana Sayfa",
        "nav.experience": "Deneyim",
        "nav.projects": "Projeler",
        "nav.contact": "İletişim",
        "common.readMore": "Devamını oku",
        "common.viewDescription": "Açıklamayı görüntüle",
        "hero.role": "Optimizasyon, makine öğrenmesi ve karar analitiği",
        "hero.lead": "Gerçek karar problemlerini çözmek amacıyla optimizasyon ve makine öğrenmesi yöntemleri geliştiriyorum. Araştırmalarım fiyatlandırma, yöneylem araştırması, açıklanabilir yapay zekâ ve veri odaklı karar verme alanlarına odaklanmaktadır.",
        "hero.secondary": "2026 Güz döneminden itibaren, Waterloo Üniversitesi'nde Prof. Dr. Sibel A. Alumur ve Dr. Recep Bekçi danışmanlığında Yönetim Bilimleri alanında doktora eğitimime başlayacağım.",
        "hero.visualLabel": "Portre ve karar analitiği önizlemesi",
        "hero.portraitAlt": "Kaan APAK portresi",
        "hero.downloadCv": "CV'yi indir",
        "hero.linkedinLabel": "LinkedIn profili",
        "hero.panelLabel": "Karar destek sistemleri",
        "hero.panelText": "Karmaşık verileri ve operasyonel kısıtları uygulanabilir araçlara dönüştürmek.",
        "experience.heading": "Deneyim",
        "experience.subheading": "Üniversite ve endüstri ortamlarında araştırma, analitik, öğretim ve karar destek çalışmaları.",
        "experience.trackLabel": "Deneyim kartları",
        "experience.waterloo.title": "Yönetim Bilimleri Doktora Öğrencisi",
        "experience.waterloo.org": "Waterloo Üniversitesi",
        "experience.waterloo.preview": "2026 Güz döneminden itibaren Waterloo Üniversitesi'nde Prof. Dr. Sibel A. Alumur ve Dr. Recep Bekçi danışmanlığında Yönetim Bilimleri alanında doktora eğitimime başlayacağım.",
        "experience.waterloo.more": "Doktora çalışmalarım kapsamında aynı zamanda Araştırma Görevlisi ve Öğretim Asistanı olarak görev yapacağım.",
        "experience.borusan.title": "Veri Analitiği ve İş Zekâsı Uzmanı",
        "experience.borusan.org": "Borusan CAT",
        "experience.borusan.preview": "Borusan CAT'de fiyatlandırma, satış, müşteri ve operasyonel karar süreçlerini destekleyen veri odaklı çözümler geliştiriyorum.",
        "experience.borusan.more1": "Çalışmalarım; analitik, otomasyon ve iş zekâsını bir araya getirerek karmaşık verileri karar vericiler için uygulanabilir araçlara dönüştürmeye odaklanmaktadır.",
        "experience.borusan.more2": "Bu kapsamda satış ve müşteri analitiğine yönelik Power BI panoları tasarladım, fiyatlandırma analistlerinin liste fiyatlarını belirlemelerini destekleyen fiyat simülasyon araçları geliştirdim ve Python, VBA ile Power Automate kullanarak çok sayıda raporlama ve analiz sürecini otomatikleştirdim. Ayrıca veri ambarı planlama çalışmalarını koordine ettim, veri kalitesi metriklerinin tanımlanmasına katkı sağlayarak veri yönetimi süreçlerinde görev aldım ve kurumsal veri altyapısının geliştirilmesi için BT ekipleriyle yakın iş birliği içinde çalıştım. Bunun yanında yapay zekâ destekli bir gösterge paneli asistanı fikrini ortaya koyarak, uygulanması ve kurum genelinde yaygınlaştırılması sürecinde rol aldım.",
        "experience.sustainability.title": "Veri Analisti",
        "experience.sustainability.org": "Özyeğin Üniversitesi Sürdürülebilirlik Platformu",
        "experience.sustainability.logoAlt": "Özyeğin Üniversitesi Sürdürülebilirlik Platformu logosu",
        "experience.sustainability.preview": "Üniversitenin Birleşmiş Milletler Sürdürülebilir Kalkınma Amaçları'na katkılarını ölçen ve görselleştiren analitik araçlar geliştirdim.",
        "experience.sustainability.more": "Araştırmacılar, kütüphaneciler ve BT ekipleriyle iş birliği yaparak araştırma ve eğitim verilerini etkileşimli gösterge panolarına entegre ettim ve akademik faaliyetleri otomatik olarak sınıflandıran Python tabanlı araçlar geliştirdim.",
        "experience.ozyegin.title": "Öğretim ve Araştırma Asistanı",
        "experience.ozyegin.org": "Özyeğin Üniversitesi",
        "experience.ozyegin.preview": "Simülasyon Modellemesi, Olasılık, Matematiksel Modelleme ve Sezgisel Algoritmalar derslerini uygulama oturumları, ofis saatleri ve öğrenci danışmanlığı yoluyla destekledim.",
        "experience.ozyegin.more": "Öğretim sorumluluklarımın yanı sıra, Prof. Dr. Burcu Balcık danışmanlığında yürütülen optimizasyon ve sağlık operasyonları araştırmalarında görev aldım. Bu kapsamda afet sonrası sağlık hizmetlerinin planlanmasına yönelik karar destek sistemleri ve sezgisel algoritmalar üzerine çalıştım.",
        "projects.heading": "Projeler",
        "projects.subheading": "Optimizasyon ve makine öğrenmesi yöntemlerini uygulanabilir karar desteğine dönüştüren araştırma projeleri.",
        "projects.disaster.title": "Hemodiyaliz Hastaları İçin Afet Planlaması",
        "projects.disaster.preview": "Bu proje, sağlık hizmeti kapasitesinin ciddi şekilde kısıtlandığı büyük ölçekli afetlerin ardından hemodiyaliz tedavilerinin koordinasyonunu destekleyen optimizasyon tabanlı karar destek araçları geliştirmektedir.",
        "projects.disaster.imageAlt": "Böbrek afet koordinasyon sistemi arayüzü",
        "projects.disaster.publicationTitle": "Chronic care management in times of capacity shortages: An integrated patient assignment and treatment scheduling problem for post-disaster hemodialysis planning",
        "projects.disaster.publicationAction": "Omega - The International Journal of Management Science · sciencedirect.com",
        "projects.disaster.more1": "Türk Nefroloji Derneği Böbrek Afet Destek Görev Gücü ile iş birliği içinde yürütülen bu çalışma, acil durumlarda hastaların yaşam kurtarıcı tedavilere erişimini iyileştirmeyi amaçlamaktadır.",
        "projects.disaster.more2": "Bu projedeki temel katkılarım; optimizasyon modellerini afet koordinatörlerinin kullanabileceği pratik bir karar destek sistemine dönüştüren prototip bir yazılımın geliştirilmesi ve büyük ölçekli gerçek yaşam problemleri için kısa sürede yüksek kaliteli tedavi planları üreten ölçeklenebilir <strong>ICH algoritmasının</strong> tasarlanması olmuştur.",
        "projects.pricing.title": "Teklif Bazlı B2B Fiyatlandırmanın Optimizasyonu",
        "projects.pricing.preview": "Bu araştırma, firmaların her teklif için hem kârlılığı hem de rekabetçiliği dengelemesi gereken B2B satış sonrası pazarındaki teklif bazlı fiyatlandırma problemini ele almaktadır.",
        "projects.pricing.imageAlt": "Teklif bazlı fiyatlandırma araştırmasında kullanılan endüstriyel yedek parça görseli",
        "projects.pricing.more1": "Çalışmada, müşteri fiyat hassasiyetlerini belirleyen ve fiyatlandırma modellerini doğrudan geçmiş teklif verileri üzerinden eş zamanlı olarak tahmin eden yeni bir regresyon kümeleme yöntemi önerilmektedir.",
        "projects.pricing.more2": "Araştırmanın temel katkısı, büyük ölçekli fiyatlandırma problemlerini yüksek tahmin başarısını koruyarak verimli biçimde çözmek amacıyla geliştirilen IRC adlı sezgisel regresyon kümeleme algoritmasıdır.",
        "projects.pricing.more3": "Ayrıca doğruluğu artırırken yorumlanabilirlikten ödün vermemek amacıyla, karmaşık makine öğrenmesi modellerinin bilgisini açıklanabilir fiyatlandırma modellerine aktaran bir <strong>öğretmen-öğrenci model</strong> yaklaşımı önerdim. Bu yöntemler sayesinde fiyatlandırma analistleri, farklı teklif grupları arasındaki fiyat esnekliklerini daha doğru şekilde belirleyebilmekte ve endüstriyel B2B ortamlarında daha bilinçli, veri odaklı fiyatlandırma kararları alabilmektedir.",
        "contact.heading": "İletişim",
        "contact.subheading": "Araştırma görüşmeleri, iş birlikleri ve gelecekteki danışmanlık talepleri için.",
        "contact.emailLabel": "E-posta"
      }
    };

    function applyTheme(nextTheme) {
      home.dataset.kaTheme = nextTheme;
      themeToggle.setAttribute("aria-pressed", nextTheme === "light" ? "true" : "false");
      themeToggle.setAttribute("aria-label", nextTheme === "light" ? "Switch to dark theme" : "Switch to light theme");
      window.localStorage.setItem("ka-theme-v2", nextTheme);
    }

    function applyLanguage(nextLanguage) {
      var copy = dictionary[nextLanguage] || dictionary.en;
      home.dataset.kaLang = nextLanguage;
      document.documentElement.lang = nextLanguage;

      document.querySelectorAll("[data-i18n]").forEach(function (node) {
        var key = node.getAttribute("data-i18n");
        if (copy[key]) node.innerHTML = copy[key];
      });

      document.querySelectorAll("[data-i18n-attr]").forEach(function (node) {
        node.getAttribute("data-i18n-attr").split(";").forEach(function (pair) {
          var parts = pair.split(":");
          var attr = parts[0];
          var key = parts[1];
          if (attr && key && copy[key]) node.setAttribute(attr, copy[key]);
        });
      });

      document.querySelectorAll("[data-lang-src-en][data-lang-src-tr]").forEach(function (node) {
        var src = node.getAttribute("data-lang-src-" + nextLanguage);
        if (src) node.setAttribute("src", src);
      });

      langButtons.forEach(function (button) {
        button.setAttribute("aria-pressed", button.getAttribute("data-lang-option") === nextLanguage ? "true" : "false");
      });

      window.localStorage.setItem("ka-language-v1", nextLanguage);
    }

    var savedTheme = window.localStorage.getItem("ka-theme-v2") || "dark";
    var savedLanguage = window.localStorage.getItem("ka-language-v1") || "en";

    applyTheme(savedTheme === "light" ? "light" : "dark");
    applyLanguage(savedLanguage === "tr" ? "tr" : "en");

    themeToggle.addEventListener("click", function () {
      applyTheme(home.dataset.kaTheme === "light" ? "dark" : "light");
    });

    langButtons.forEach(function (button) {
      button.addEventListener("click", function () {
        applyLanguage(button.getAttribute("data-lang-option"));
      });
    });
  })();
</script>
