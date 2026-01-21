---
layout: default
title: Oluwafemi (Femi) James
---

<div class="hero-box" style="text-align: center;">
  <h1 style="margin-bottom: 25px;">I engineer AI digital operating systems that turn manual industries into AI-driven markets.</h1>
   
  <p style="font-size: 1.25rem; margin-bottom: 35px; color: #e2e8f0;">
    I use <strong>Full-Stack Engineering</strong> to bridge the critical gap between <strong>Customer Demand</strong> and <strong>Operational Execution.</strong> I do it with governance, scalability, and ethics built in.
  </p>

  <div style="display: inline-block; text-align: left; max-width: 750px; background: rgba(255,255,255,0.05); padding: 25px; border-radius: 10px; border: 1px solid rgba(255,255,255,0.1);">
    <ul style="margin: 0; padding-left: 20px; list-style-type: none;">
       
      <li style="margin-bottom: 15px; display: flex; align-items: flex-start;">
        <span style="margin-right: 12px; font-size: 1.2rem;"></span>
        <span>
          <strong>The Infrastructure:</strong> I architect <strong>multi-tenant, asset-light systems</strong> that scale without overhead.
        </span>
      </li>

      <li style="margin-bottom: 15px; display: flex; align-items: flex-start;">
        <span style="margin-right: 12px; font-size: 1.2rem;"></span>
        <span>
          <strong>The Connective Tissue:</strong> I deploy <strong>NLP, Computer Vision, and Predictive Models</strong> (Regression, Classification, Time-Series) to automate decisions.
        </span>
      </li>

      <li style="margin-bottom: 0; display: flex; align-items: flex-start;">
        <span style="margin-right: 12px; font-size: 1.2rem;"></span>
        <span>
          <strong>The Outcome:</strong> I build platforms that autonomously orchestrate logistics, secure revenue streams, and <strong>dominate markets</strong>.
        </span>
      </li>

    </ul>
  </div>
</div>

<style>
  /* Accordion Container Styling */
  details.project-accordion {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    margin-top: 30px;
    box-shadow: 0 1px 3px rgba(0,0,0,0.05);
    overflow: hidden;
    transition: all 0.3s ease;
  }

  /* The Clickable Header */
  summary.project-summary {
    cursor: pointer;
    padding: 25px;
    list-style: none; /* Remove default triangle */
    position: relative;
    background-color: #fff;
    display: flex;
    flex-direction: column;
    align-items: center;
    transition: background-color 0.2s ease;
  }

  summary.project-summary:hover {
    background-color: #fcfcfc;
  }

  /* Remove default marker in Webkit */
  summary.project-summary::-webkit-details-marker {
    display: none;
  }

  /* Custom Arrow Indicator */
  summary.project-summary::after {
    content: "👇 Click to Expand Case Study";
    font-size: 0.85rem;
    color: #0366d6;
    margin-top: 15px;
    font-weight: 600;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }

  details[open] summary.project-summary::after {
    content: "❌ Close Case Study";
    color: #cb2431;
  }

  /* Inner Content Padding */
  .accordion-content {
    padding: 0 25px 25px 25px;
    border-top: 1px solid #eaecef;
    background: #fff;
  }
</style>

<details class="project-accordion" style="border-top: 4px solid #159957;">
  <summary class="project-summary">
    <div style="text-align: center;">
      <h2 style="margin-bottom: 5px; color: #24292e;">Flagship Platform: MESS Tracker</h2>
      <p style="color: #586069; font-size: 1.1rem; margin-top: 0; margin-bottom: 0;">The Asset-Light Operating System for Waste Management</p>
    </div>
  </summary>

  <div class="accordion-content">
    
    <p style="margin-top: 25px;">
      MESS Tracker is a <strong>multi-tenant SaaS marketplace</strong> that digitizes the entire waste service lifecycle. It serves as a centralized operating system, replacing fragmented, manual workflows with an intelligent, data-driven platform that connects demand, dispatch, and execution.
    </p>

    <h3 style="border-bottom: 1px solid #eaecef; padding-bottom: 10px; margin-top: 40px;">System Architecture: The "Three-Gate" Model</h3>
     
    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 20px; margin-top: 20px;">
       
      <div style="background: #f6f8fa; padding: 20px; border-radius: 6px; border: 1px solid #e1e4e8;">
        <h4 style="margin-top: 0; color: #24292e;">🔐 Zero-Trust Security</h4>
        <p style="font-size: 0.9rem; margin-bottom: 0;">
          Implemented a <strong>Three-Gate Architecture</strong>  to strictly isolate:
          <br>• <strong>Public Users</strong> (Magic Link Auth)
          <br>• <strong>Internal Ops</strong> (2FA Fortress)
          <br>• <strong>Drivers</strong> (Device-Bound Tokens)
        </p>
      </div>

      <div style="background: #f6f8fa; padding: 20px; border-radius: 6px; border: 1px solid #e1e4e8;">
        <h4 style="margin-top: 0; color: #24292e;">💾 The "Jukebox" Data Model</h4>
        <p style="font-size: 0.9rem; margin-bottom: 0;">
          Designed a hierarchical relational model separating <strong>Service Definitions</strong> from <strong>Tenant Availability</strong>. 
          <br><br>
          The system orchestrates <strong>98+ micro-services</strong> and <strong>18+ core clusters</strong> across <strong>8+ tenants</strong> , utilizing <strong>Redis</strong> to serve <strong>10,000+ cached keys</strong>  with <strong>millisecond latency</strong>.
        </p>
      </div>

    </div>

    <div style="margin-top: 25px;">
      <span class="tech-tag">Python (Django)</span>
      <span class="tech-tag">PostgreSQL (Multi-tenant)</span>
      <span class="tech-tag">Redis (Broker)</span>
      <span class="tech-tag">Celery (Async)</span>
      <span class="tech-tag">Docker</span>
    </div>

    <div style="margin-top: 30px; margin-bottom: 20px; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden;">
      <img src="/assets/images/technical_architecture_diagram.png" alt="MESS Tracker End-to-End Architecture" style="width: 100%; display: block;">
      <div style="background: #f6f8fa; padding: 10px 15px; font-size: 0.85rem; color: #586069; border-top: 1px solid #e1e4e8;">
        <strong>Figure 1:</strong> The "End-to-End" Orchestration Flow: Connecting Demand Creation to Settlement.
      </div>
    </div>

    <div class="project-card" style="margin-top: 20px; border-top: 4px solid #0366d6; box-shadow: none; padding: 25px;">

      <div style="text-align: center; margin-bottom: 30px;">
        <h2 style="margin-bottom: 5px;">AI as Infrastructure</h2>
        <p style="color: #586069; font-size: 1.1rem; margin-top: 0;">Operational Intelligence (Not a Feature)</p>
      </div>

      <p>
        AI inside MESS Tracker is an <strong>operational infrastructure</strong> embedded directly into the "Three-Gate" workflow. It coordinates <strong>Vision, Language (Multilingual), Risk-analysis (Regression/Classification), and Time-Series</strong> intelligence to automate logistics.
      </p>

      <div style="margin-top: 10px; margin-bottom: 10px; border: 1px solid #e1e4e8; border-radius: 2px; overflow: hidden;">
        <img src="/assets/images/ai-pipeline2.png" alt="MESS Tracker AI Pipeline" style="width: 100%; display: block;">
        <div style="background: #f6f8fa; padding: 10px 15px; font-size: 0.85rem; color: #586069; border-top: 1px solid #e1e4e8;">
          <strong>Figure 2: The ML Pipeline.</strong> Data ingestion (ETL), Multi-model training (RoBERTa, YOLOv11, LSTM), and Cloud Deployment.
        </div>
      </div>

      <h3 style="border-bottom: 1px solid #eaecef; padding-bottom: 10px; margin-bottom: 20px;">Implemented Capabilities</h3>

      <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 20px;">

        <div style="background: #f6f8fa; padding: 20px; border-radius: 6px; border: 1px solid #e1e4e8;">
          <h4 style="margin-top: 0; color: #24292e;">💬 NLP & Transformers</h4>
          <p style="font-size: 0.9rem; margin-bottom: 15px;">
            <strong>Intent Recognition:</strong> Acts as the "Front Door," routing unstructured requests to DB tables.
          </p>
          <div>
            <span class="tech-tag">RoBERTa</span>
            <span class="tech-tag">SpaCy</span>
            <span class="tech-tag">GPT-2</span>
          </div>
        </div>

        <div style="background: #f6f8fa; padding: 20px; border-radius: 6px; border: 1px solid #e1e4e8;">
          <h4 style="margin-top: 0; color: #24292e;">👁️ Computer Vision</h4>
          <p style="font-size: 0.9rem; margin-bottom: 15px;">
            <strong>Automated Inspection:</strong> Real-time waste classification and contamination detection.
          </p>
          <div>
            <span class="tech-tag">YOLOv11</span>
            <span class="tech-tag">Segmentation</span>
            <span class="tech-tag">OpenCV</span>
          </div>
        </div>

        <div style="background: #f6f8fa; padding: 20px; border-radius: 6px; border: 1px solid #e1e4e8;">
          <h4 style="margin-top: 0; color: #24292e;">📈 Predictive Ops</h4>
          <p style="font-size: 0.9rem; margin-bottom: 15px;">
            <strong>Demand Forecasting:</strong> Predicting operational load to optimize driver scheduling.
          </p>
          <div>
            <span class="tech-tag">SARIMA</span>
            <span class="tech-tag">LSTM / GRU</span>
          </div>
        </div>

      </div>

    </div>

  <style>
    /* Hidden by default */
    #lightbox-modal {
      display: none;
      position: fixed;
      z-index: 9999;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: rgba(0, 0, 0, 0.95);
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }

    /* The content (image/video) inside modal */
    #lightbox-content {
      max-width: 95%;
      max-height: 80vh;
      border-radius: 4px;
      box-shadow: 0 0 20px rgba(255,255,255,0.1);
    }

    /* Close Button */
    .close-btn {
      position: absolute;
      top: 20px;
      right: 30px;
      color: #f1f1f1;
      font-size: 40px;
      font-weight: bold;
      cursor: pointer;
      z-index: 10000;
    }
  </style>

  <div class="project-card" style="margin-top: 40px; border-top: 4px solid #f6ad55; box-shadow: none; padding: 25px;">
    
    <div style="text-align: center; margin-bottom: 30px; margin-top: 10px;">
      <h2 style="margin-bottom: 5px;">🎨 Frontend & Execution</h2>
      <p style="color: #586069; font-size: 1.1rem; margin-top: 0;">From Insight to Automation</p>
    </div>

    <p>
      The User Interface is the bridge between the AI models and the real world. Below is the operational workflow: <strong>Dashboarding → Predictive Planning → AI Automation → Final Dispatch.</strong>
    </p>
     
    <p style="text-align: center; font-size: 0.85rem; color: #d03801; font-weight: bold; margin-bottom: 20px;">
      👆 Tap any slide below to view full screen
    </p>

    <div style="display: flex; overflow-x: auto; gap: 20px; padding-bottom: 20px; scroll-snap-type: x mandatory; -webkit-overflow-scrolling: touch;">
       
      <div onclick="openLightbox('img', 'assets/images/user_dashboard_overview.png')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <img src="assets/images/user_dashboard_overview.png" alt="User Dashboard Overview" style="width: 100%; display: block;">
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #24292e;">1. User Command Center</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Service shortcuts and a Multilingual AI Chatbot.</span>
        </div>
      </div>

      <div onclick="openLightbox('img', 'assets/images/user_service_analytics.png')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <img src="assets/images/user_service_analytics.png" alt="Analytics" style="width: 100%; display: block;">
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #0366d6;">2. Live Analytics & Forecasts</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">7/14/30-day demand forecasting models.</span>
        </div>
      </div>

      <div onclick="openLightbox('img', 'assets/images/user_service_calendar.png')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <img src="assets/images/user_service_calendar.png" alt="Smart Calendar" style="width: 100%; display: block;">
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #0366d6;">3. Smart Scheduling Calendar</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Risk Analysis based scheduling.</span>
        </div>
      </div>

      <div onclick="openLightbox('vid', 'assets/videos/predictive_scheduling.mp4')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer; position: relative;">
        <video class="lazy-video" muted loop playsinline controls poster="assets/images/user_service_calendar.png" style="width: 100%; display: block; pointer-events: none;">
          <source data-src="assets/videos/predictive_scheduling.mp4" type="video/mp4">
        </video>
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #d03801;">4. Demo: Predictive Scheduling</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Processing structured data to suggest slots.</span>
        </div>
      </div>

      <div onclick="openLightbox('vid', 'assets/videos/nlp_scheduling.mp4')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <video class="lazy-video" muted loop playsinline controls poster="assets/images/user_dashboard_overview.png" style="width: 100%; display: block; pointer-events: none;">
          <source data-src="assets/videos/nlp_scheduling.mp4" type="video/mp4">
        </video>
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #d03801;">5. Demo: NLP Scheduling</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Converting text requests into events.</span>
        </div>
      </div>

      <div onclick="openLightbox('vid', 'assets/videos/cv_waste_sorting.mp4')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <video class="lazy-video" muted loop playsinline controls poster="assets/images/user_service_analytics.png" style="width: 100%; display: block; pointer-events: none;">
          <source data-src="assets/videos/cv_waste_sorting.mp4" type="video/mp4">
        </video>
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #d03801;">6. Demo: Computer Vision</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Automated waste identification.</span>
        </div>
      </div>

      <div onclick="openLightbox('vid', 'assets/videos/dispatch_management.mp4')" style="min-width: 85%; scroll-snap-align: center; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; flex-shrink: 0; cursor: pointer;">
        <video class="lazy-video" muted loop playsinline controls poster="assets/images/user_dashboard_overview.png" style="width: 100%; display: block; pointer-events: none;">
          <source data-src="assets/videos/dispatch_management.mp4" type="video/mp4">
        </video>
        <div style="background: #fff; padding: 12px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #159957;">7. Demo: Dispatch Execution</strong><br>
          <span style="font-size: 0.85rem; color: #586069;">Routing the finalized task.</span>
        </div>
      </div>

    </div>

    <p style="text-align: center; font-size: 0.85rem; color: #999; margin-top: 5px;">
      (Swipe right to view AI Demos & Dispatch Video) →
    </p>

  </div>

  <div id="lightbox-modal" onclick="closeLightbox()">
    <span class="close-btn">&times;</span>
    <div id="lightbox-container" style="display: flex; justify-content: center; width: 100%; align-items: center; height: 100%;"></div>
  </div>

  <script>
    // --- 1. Lightbox Logic ---
    function openLightbox(type, src) {
      var modal = document.getElementById("lightbox-modal");
      var container = document.getElementById("lightbox-container");
       
      container.innerHTML = ""; // Clear previous

      if (type === 'img') {
        var img = document.createElement("img");
        img.src = src;
        img.id = "lightbox-content";
        container.appendChild(img);
      } else if (type === 'vid') {
        var vid = document.createElement("video");
        vid.src = src;
        vid.id = "lightbox-content";
        vid.controls = true; 
        vid.autoplay = true; 
        // Remove 'playsinline' here so it can go native fullscreen if user wants
        container.appendChild(vid);
      }

      modal.style.display = "flex";
    }

    function closeLightbox() {
      var modal = document.getElementById("lightbox-modal");
      var container = document.getElementById("lightbox-container");
      modal.style.display = "none";
      container.innerHTML = ""; // Stop video playback
    }

    // --- 2. Lazy Load & Smart Auto-Play Logic ---
    document.addEventListener("DOMContentLoaded", function() {
      var lazyVideos = [].slice.call(document.querySelectorAll("video.lazy-video"));

      if ("IntersectionObserver" in window) {
        var videoObserver = new IntersectionObserver(function(entries, observer) {
          entries.forEach(function(video) {
            if (video.isIntersecting) {
              // Video entered view
              var sources = video.target.querySelectorAll('source');
              sources.forEach(function(source) {
                  if (source.dataset.src) {
                    source.src = source.dataset.src;
                    delete source.dataset.src; 
                  }
              });
               
              video.target.load();
              video.target.classList.remove("lazy-video");
               
              // Force play promise to handle browser restrictions
              var playPromise = video.target.play();
              if (playPromise !== undefined) {
                playPromise.then(_ => {
                  // Autoplay started!
                }).catch(error => {
                  // Auto-play was prevented.
                  console.log("Autoplay prevented:", error);
                });
              }

            } else {
              // Video left view -> Pause it
               video.target.pause();
            }
          });
        }, { threshold: 0.1 }); // Trigger as soon as 10% is visible

        lazyVideos.forEach(function(lazyVideo) {
          videoObserver.observe(lazyVideo);
        });
      }
    });
  </script>

  <div class="project-card" style="margin-top: 40px; border-top: 4px solid #6f42c1; box-shadow: none; padding: 25px;">
    
    <div style="text-align: center; margin-bottom: 30px; margin-top: 10px;">
      <h2 style="margin-bottom: 5px;">🏆 Real-World Impact</h2>
      <p style="color: #586069; font-size: 1.1rem; margin-top: 0;">Beyond Localhost: Defense & Recognition</p>
    </div>

    <p>
      MESS Tracker wasn't just a theoretical exercise. It was a rigorous Capstone project that involved <strong>academic defense, stakeholder presentations, and public showcasing</strong>. It stands as a proof-of-concept for how AI can tangibly modernize municipal infrastructure.
    </p>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 25px; margin-top: 30px;">

      <div style="border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden;">
        <img src="assets/images/mess_presentation.jpg" alt="Capstone Project Defense" style="width: 100%; height: 250px; object-fit: cover; display: block;">
        <div style="background: #fff; padding: 15px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #6f42c1;">1. The Technical Defense</strong>
          <p style="font-size: 0.85rem; color: #586069; margin: 5px 0 0 0;">
            Presenting the "Three-Gate" Architecture and AI Integration strategy to the review board.
          </p>
        </div>
      </div>

      <div style="border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden;">
        <img src="assets/images/mess_showcase.jpg" alt="Capstone Showcase with Supervisor" style="width: 100%; height: 250px; object-fit: cover; object-position: top; display: block;">
        <div style="background: #fff; padding: 15px; border-top: 1px solid #e1e4e8;">
          <strong style="color: #6f42c1;">2. Industry Showcase</strong>
          <p style="font-size: 0.85rem; color: #586069; margin: 5px 0 0 0;">
            Demonstrating the live MVP alongside Project Supervisor, Reeta Suman, at the Capstone Exhibition.
          </p>
        </div>
      </div>

      <div style="grid-column: 1 / -1; border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; margin-top: 10px;">
        <div style="display: flex; flex-wrap: wrap; align-items: center;">
           
          <div style="flex: 1; min-width: 300px; padding: 25px;">
            <h3 style="margin-top: 0; color: #24292e;">📜 Official Project Poster</h3>
            <p>
              The comprehensive breakdown of the <strong>CRISP-DM Methodology</strong> used to build MESS Tracker. 
            </p>
            <ul style="font-size: 0.9rem; color: #586069; margin-bottom: 20px;">
              <li><strong>Methodology:</strong> Phase 1-5 (Business Understanding to Maintenance)</li>
              <li><strong>Tech Stack:</strong> Django, YOLOv11, LSTM, SARIMA</li>
              <li><strong>Outcome:</strong> A scalable, AI-driven operating system.</li>
            </ul>
            <a href="assets/images/mess_poster.png" target="_blank" class="btn" style="font-size: 0.9rem; background-color: #6f42c1; color: white; padding: 12px 24px; border-radius: 6px; text-decoration: none; display: inline-block; font-weight: 600; box-shadow: 0 2px 5px rgba(0,0,0,0.2); transition: all 0.2s ease-in-out;">
  View Full Size Poster →
</a>
          </div>

          <div style="flex: 1; min-width: 300px; background: #f6f8fa; text-align: center;">
            <img src="assets/images/mess_poster.png" alt="MESS Tracker Official Poster" style="max-width: 100%; max-height: 500px; display: block; margin: 0 auto;">
          </div>

        </div>
      </div>

    </div>

  </div>
  </div> </details>

<details class="project-accordion" style="border-top: 4px solid #e53e3e;">
  <summary class="project-summary">
    <div style="text-align: center;">
      <h2 style="margin-bottom: 5px; color: #24292e;">Collaborative AI: StrokeRisk System</h2>
      <p style="color: #586069; font-size: 1.1rem; margin-top: 0; margin-bottom: 0;">Clinical Decision Support & MLOps Governance</p>
    </div>
  </summary>

  <div class="accordion-content">
  
    <div style="background: rgba(229, 62, 62, 0.05); padding: 20px; border-radius: 8px; border-left: 5px solid #e53e3e; margin-bottom: 30px; margin-top: 25px;">
      <p style="font-size: 1rem; margin: 0; color: #24292e;">
        <strong>The Leadership Context:</strong> While MESS Tracker showcases my solo architectural skills, StrokeRisk demonstrates my ability to lead and integrate within high-performance teams. 
        <br><br>
        Leading <strong>Group 4 (G4 Pulse): Fuad, Preston and Marrium in our first semester</strong> for development and <strong>Group 2 (G2): Kevin and Shalin in our second semester </strong> for MLOps, I orchestrated the transition from a raw dataset to a governed, FDA-aligned deployment. We moved beyond "just coding" to building a compliant, auditable lifecycle.
      </p>
    </div>

    <p>
      StrokeRisk is an end-to-end clinical decision-support system built using the <strong>CRISP-DM Methodology</strong>. It leverages a <strong>Soft-Voting Ensemble Model</strong> to predict stroke probability with high recall, ensuring high-risk patients are identified early.
    </p>

    <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(350px, 1fr)); gap: 25px; margin-top: 30px;">

      <div style="border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column;">
        <div style="background: #f6f8fa; padding: 15px; border-bottom: 1px solid #e1e4e8;">
          <h3 style="margin: 0; font-size: 1.1rem; color: #24292e;">⚙️ Phase 1: The Ensemble Innovation</h3>
        </div>
        
        <div style="width: 100%; height: 220px; overflow: hidden; border-bottom: 1px solid #eaecef;">
             <img src="assets/images/phase_1_team.jpg" alt="Phase 1 Development Team" style="width: 100%; height: 100%; object-fit: cover; object-position: center;">
        </div>

        <div style="padding: 20px; display: flex; flex-direction: column; flex-grow: 1;">
          <p style="font-size: 0.9rem; color: #586069; margin-bottom: 15px;">
            To tackle the "Accuracy Paradox" in medical AI (where 95% accuracy hides missed diagnoses), we rejected single models in favor of a <strong>Soft-Voting Ensemble</strong>.
          </p>
          
          <ul style="font-size: 0.9rem; margin-bottom: 20px;">
            <li><strong>Data Balancing:</strong> Applied <strong>SMOTE</strong> to correct the 4.9% minority class imbalance, achieving a perfect 50/50 training split.</li>
            <li><strong>The Architectures:</strong> Aggregated <strong>Random Forest, XGBoost, and Extra Trees</strong>.</li>
            <li><strong>The Result:</strong> The ensemble stabilized variance and maximized Recall (Safety).</li>
          </ul>

          <div style="display: flex; gap: 10px; margin-top: auto;">
             <span class="tech-tag" style="background: #e1e4e8; color: #000;">PyCaret</span>
             <span class="tech-tag" style="background: #e1e4e8; color: #000;">SMOTE</span>
             <span class="tech-tag" style="background: #e1e4e8; color: #000;">XGBoost</span>
          </div>
        </div>
      </div>

      <div style="border: 1px solid #e1e4e8; border-radius: 8px; overflow: hidden; display: flex; flex-direction: column;">
        <div style="background: #f6f8fa; padding: 15px; border-bottom: 1px solid #e1e4e8;">
          <h3 style="margin: 0; font-size: 1.1rem; color: #24292e;">🛡️ Phase 2: Governance-as-Code</h3>
        </div>

        <div style="width: 100%; height: 220px; overflow: hidden; border-bottom: 1px solid #eaecef;">
             <img src="assets/images/phase_2_team.jpg" alt="Phase 2 MLOps Team" style="width: 100%; height: 100%; object-fit: cover; object-position: center;">
        </div>

        <div style="padding: 20px; display: flex; flex-direction: column; flex-grow: 1;">
          <p style="font-size: 0.9rem; color: #586069; margin-bottom: 15px;">
            We didn't just train a model; we built an immutable audit trail using <strong>MLflow</strong> to satisfy <strong>PIPEDA & FDA SaMD</strong> reproducibility guidelines.
          </p>
          
          <ul style="font-size: 0.9rem; margin-bottom: 20px;">
            <li><strong>Reproducibility:</strong> Enforced `conda.yaml` environment locking to prevent dependency drift.</li>
            <li><strong>Auditability:</strong> Every run logged Git Hashes, Dataset Digests, and Parameters.</li>
            <li><strong>Gated Promotion:</strong> Implemented a strict <em>Staging &rarr; Production</em> workflow requiring governance approval.</li>
          </ul>

          <div style="display: flex; gap: 10px; margin-top: auto;">
             <span class="tech-tag" style="background: #e53e3e; color: #fff;">MLflow</span>
             <span class="tech-tag" style="background: #e53e3e; color: #fff;">CI/CD</span>
             <span class="tech-tag" style="background: #e53e3e; color: #fff;">Audit Logs</span>
          </div>
        </div>
      </div>

    </div>

    <h3 style="border-bottom: 1px solid #eaecef; padding-bottom: 10px; margin-top: 40px; margin-bottom: 20px;">🏆 Validated Performance</h3>

    <div style="display: grid; grid-template-columns: repeat(3, 1fr); gap: 15px; text-align: center; margin-bottom: 30px;">
      
      <div style="padding: 15px; background: #fff; border: 1px solid #e1e4e8; border-radius: 6px;">
        <div style="font-size: 2rem; font-weight: bold; color: #24292e;">95.8%</div>
        <div style="font-size: 0.85rem; color: #586069; text-transform: uppercase; letter-spacing: 1px;">Accuracy</div>
      </div>

      <div style="padding: 15px; background: #fff; border: 1px solid #e1e4e8; border-radius: 6px;">
        <div style="font-size: 2rem; font-weight: bold; color: #0366d6;">0.992</div>
        <div style="font-size: 0.85rem; color: #586069; text-transform: uppercase; letter-spacing: 1px;">AUC Score</div>
      </div>

      <div style="padding: 15px; background: #fff; border: 1px solid #e1e4e8; border-radius: 6px;">
        <div style="font-size: 2rem; font-weight: bold; color: #28a745;">96.5%</div>
        <div style="font-size: 0.85rem; color: #586069; text-transform: uppercase; letter-spacing: 1px;">Recall (Safety)</div>
      </div>

    </div>

    <div style="background: #f6f8fa; border: 1px solid #e1e4e8; border-radius: 8px; padding: 25px;">
      <div style="display: flex; flex-wrap: wrap; align-items: center; gap: 30px;">
        
        <div style="flex: 1; min-width: 300px;">
          <h3 style="margin-top: 0; color: #24292e;">Cloud Deployment</h3>
          <p style="margin-bottom: 20px;">
            The final system was deployed on <strong>Streamlit Cloud</strong>, serving the MLflow-registered model via a REST API. The frontend was designed using <strong>Human-Centered Design</strong> principles (Fogg Behavior Model) to ensure clinician trust.
          </p>
          <p>
            <strong>Features Implemented:</strong>
            <br>• Real-time Risk Assessment
            <br>• SHAP-based Explainability (Why did the model say yes?)
            <br>• PDF Report Generation
          </p>
          <div style="margin-top: 25px; display: flex; flex-direction: column; gap: 15px; align-items: flex-start;">
            
            <a href="https://strokerisktool.streamlit.app/Patient_Data_Entry" target="_blank" class="btn" style="background-color: #0366d6; color: #ffffff; padding: 10px 20px; border-radius: 6px; text-decoration: none; font-weight: 600; display: inline-block; box-shadow: 0 2px 4px rgba(0,0,0,0.1);">
              Launch Live App 🚀
            </a>

            <a href="https://github.com/FemiJames070/StrokeRisk_Tool/" target="_blank" style="color: #0366d6; text-decoration: none; font-weight: 600;">
              View GitHub Repo →
            </a>

        </div>
        </div>

        <div style="flex: 1; min-width: 300px;">
        
        <div style="border-radius: 6px; overflow: hidden; box-shadow: 0 4px 12px rgba(0,0,0,0.1); border: 1px solid #e1e4e8; line-height: 0;">
          <video class="lazy-video" width="100%" height="auto" controls muted playsinline poster="assets/images/strokerisk_ui_preview.png">
            <source data-src="assets/videos/strokerisk_demo.mp4" type="video/mp4">
            Your browser does not support the video tag.
          </video>
        </div>

        <div style="text-align: center; font-size: 0.8rem; color: #586069; margin-top: 8px;">
          <strong>Figure 3:</strong> Live Demo: The Clinician Dashboard & Explainable AI
        </div>

      </div>

<script>
  document.addEventListener("DOMContentLoaded", function() {
    var lazyVideos = [].slice.call(document.querySelectorAll("video.lazy-video"));

    if ("IntersectionObserver" in window) {
      var videoObserver = new IntersectionObserver(function(entries, observer) {
        entries.forEach(function(video) {
          if (video.isIntersecting) {
            // Video entered view: Load and Play
            var sources = video.target.querySelectorAll('source');
            sources.forEach(function(source) {
                if (source.dataset.src) {
                  source.src = source.dataset.src;
                  delete source.dataset.src; 
                }
            });
            
            video.target.load();
            video.target.classList.remove("lazy-video");
            
            // Attempt to play (muted is required for autoplay)
            var playPromise = video.target.play();
            if (playPromise !== undefined) {
              playPromise.catch(error => {
                console.log("Autoplay prevented:", error);
              });
            }
          } else {
            // Video left view: Pause to save resources
             video.target.pause();
          }
        });
      }, { threshold: 0.25 }); // 25% visibility required to trigger start

      lazyVideos.forEach(function(lazyVideo) {
        videoObserver.observe(lazyVideo);
      });
    }
  });
</script>

      </div>
    </div>

  </div> </details>

<hr style="margin-top: 50px; margin-bottom: 30px; border: 0; border-top: 1px solid #eaecef;">

<div style="margin-top: 60px; margin-bottom: 40px; padding: 50px 30px; background: #f6f8fa; border-radius: 8px; border: 1px solid #e1e4e8; text-align: center;">
  
  <h2 style="color: #24292e; margin-top: 0; margin-bottom: 15px; font-size: 2rem;">Ready to build for the real world?</h2>
  
  <p style="font-size: 1.15rem; color: #586069; margin-bottom: 35px; line-height: 1.6;">
    I am currently based in <strong>Calgary, AB</strong> and available for <br>
    <strong style="color: #0366d6;">Senior Engineering & Platform Leadership</strong> roles.
  </p>
  
  <div style="display: flex; gap: 20px; justify-content: center; flex-wrap: wrap;">
    
    <a href="mailto:femijames070@gmail.com" class="btn" style="background-color: #24292e; color: #ffffff; padding: 12px 28px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 1.05rem; box-shadow: 0 4px 6px rgba(0,0,0,0.1); transition: transform 0.2s ease;">
      📬 Send me an Email
    </a>

    <a href="https://www.linkedin.com/in/femijames/" target="_blank" class="btn" style="background-color: #ffffff; color: #0077b5; border: 1px solid #0077b5; padding: 12px 28px; border-radius: 6px; text-decoration: none; font-weight: 600; font-size: 1.05rem; box-shadow: 0 2px 4px rgba(0,0,0,0.05); transition: background-color 0.2s ease;">
      in Connect on LinkedIn
    </a>

  </div>

</div>
