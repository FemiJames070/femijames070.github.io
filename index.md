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

<div class="project-card" style="border-top: 4px solid #159957;">
  
  <div style="text-align: center; margin-bottom: 30px;">
    <h2 style="margin-bottom: 5px;">Flagship Platform: MESS Tracker</h2>
    <p style="color: #586069; font-size: 1.1rem; margin-top: 0;">The Asset-Light Operating System for Waste Management</p>
  </div>

  <p>
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

<div class="project-card" style="margin-top: 40px; border-top: 4px solid #0366d6;">
  
<div class="project-card" style="margin-top: 40px; border-top: 4px solid #0366d6;">
  
<div class="project-card" style="border-top: 4px solid #0366d6;">
  
<div class="project-card" style="margin-top: 40px; border-top: 4px solid #0366d6;">
  
  <h3 style="margin-top: 0;">AI as Infrastructure</h3>
  <p>AI inside MESS Tracker is <strong>operational infrastructure</strong>. It coordinates <strong>Vision, Language, and Time-Series</strong> intelligence to automate logistics.</p>

  <div style="margin: 40px 0 20px 0;">
    <img src="/assets/images/ai_pipeline.png" alt="MESS Tracker AI Pipeline" style="width: 100%; border-radius: 4px;">
    <div style="margin-top: 8px; font-size: 0.85rem; color: #666; font-style: italic;">
      <strong>Figure 2:</strong> The ML Pipeline. Data ingestion (ETL), Multi-model training (RoBERTa, YOLOv11, LSTM), and Cloud Deployment.
    </div>
  </div>

  <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 30px;">

    <div>
      <h4 style="margin: 0 0 8px 0; color: #0366d6;">💬 NLP & Transformers</h4>
      <p style="font-size: 0.9rem; color: #586069; margin-bottom: 12px;">
        <strong>Intent Recognition:</strong> Acts as the "Front Door," routing requests to DB tables.
      </p>
      <div>
        <span class="tech-tag">RoBERTa</span>
        <span class="tech-tag">SpaCy</span>
        <span class="tech-tag">GPT-2</span>
      </div>
    </div>

    <div>
      <h4 style="margin: 0 0 8px 0; color: #0366d6;">👁️ Computer Vision</h4>
      <p style="font-size: 0.9rem; color: #586069; margin-bottom: 12px;">
        <strong>Automated Inspection:</strong> Real-time classification and contamination detection.
      </p>
      <div>
        <span class="tech-tag">YOLOv11</span>
        <span class="tech-tag">Segmentation</span>
        <span class="tech-tag">OpenCV</span>
      </div>
    </div>

    <div>
      <h4 style="margin: 0 0 8px 0; color: #0366d6;">📈 Predictive Ops</h4>
      <p style="font-size: 0.9rem; color: #586069; margin-bottom: 12px;">
        <strong>Demand Forecasting:</strong> Predicting operational load to optimize driver scheduling.
      </p>
      <div>
        <span class="tech-tag">SARIMA</span>
        <span class="tech-tag">LSTM / GRU</span>
      </div>
    </div>

  </div>
</div>

## 🏗️ Technical Proof: StrokeRisk

<div class="project-card">
<div class="project-title-row">
<h3>StrokeRisk System</h3>
<small>Clinical Decision Support</small>
</div>

<p>An end-to-end clinical decision-support system featuring explainable AI (SHAP) and model monitoring built using the CRISP-DM lifecycle.</p>

<div class="tag-container">
<span class="tech-tag">Python</span>
<span class="tech-tag">Scikit-Learn</span>
<span class="tech-tag">SHAP (XAI)</span>
</div>

<a href="/projects/strokerisk" class="btn">View Case Study →</a>
</div>

---

### 📬 Let's Talk
**Ready to build for the real world?** Currently in Calgary, AB | Available for Senior Engineering & Platform Leadership.

[Email Me](mailto:femijames070@gmail.com) • [LinkedIn](https://www.linkedin.com/in/femijames/)
