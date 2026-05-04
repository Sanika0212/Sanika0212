<p align="center">
  <img src="https://github.com/user-attachments/assets/ef6b36f4-7841-4ff0-b8ba-ace3dcc70742" width="100%" alt="pixel-art café banner" />
</p>

<h1 align="center">Sanika Najan</h1>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2800&pause=900&color=B5838D&center=true&vCenter=true&width=640&height=36&lines=AI+researcher+%2B+engineer;medical+VLMs+%C2%B7+production+RAG+%C2%B7+agentic+systems;M.Eng+AI+%E2%80%94+University+at+Buffalo;two+peer-reviewed+papers%2C+six+systems+in+flight" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sanikanajan"><img src="https://img.shields.io/badge/LinkedIn-3D405B?style=for-the-badge&logo=linkedin&logoColor=EAE0D5" /></a>
  <a href="https://www.sanikanajan.com/"><img src="https://img.shields.io/badge/sanikanajan.com-3D405B?style=for-the-badge&logo=safari&logoColor=EAE0D5" /></a>
  <a href="mailto:sanikanajan@gmail.com"><img src="https://img.shields.io/badge/Gmail-3D405B?style=for-the-badge&logo=gmail&logoColor=EAE0D5" /></a>
</p>

---

<table align="center">
  <tr>
    <td width="170" align="center" valign="middle">
      <sub><b>NOW</b></sub><br/>
      <sub>actively shipping</sub>
    </td>
    <td valign="middle">
      <b>ReXGroundingCT</b> — a hallucination-resistant vision-language model for chest CT.<br/>
      <sub>Co-designing a 5-stage pipeline (MedNeXt-L encoder · learned foveation RPN · multi-scale Local3DTransformer · mask-conditioned decoder · structured report head). Targeting <b>40–45% hallucination reduction</b> on radiology reports via foveated chain-of-thought grounded in 3D spatial masks. Grounded in a 13-paper literature review.</sub>
    </td>
  </tr>
  <tr>
    <td width="170" align="center" valign="middle">
      <sub><b>NEXT</b></sub><br/>
      <sub>in development</sub>
    </td>
    <td valign="middle">
      <b>Self-Healing RAG Engine</b> — a 10-layer production RAG with three-way hybrid search (dense + sparse + KG), multi-signal confidence estimation, and LangGraph-orchestrated agentic self-correction.<br/>
      <sub>Owning data ingestion, BM25 + embedding + KG hybrid retrieval, LangGraph orchestration, monitoring dashboard, and Docker deployment. Claim-level causal validation to reduce hallucinations at retrieval time.</sub>
    </td>
  </tr>
  <tr>
    <td width="170" align="center" valign="middle">
      <sub><b>HERE</b></sub><br/>
      <sub>locally</sub>
    </td>
    <td valign="middle">
      Buffalo, NY — <b>M.Eng in Artificial Intelligence</b> at the University at Buffalo (Aug 2025 – Present).<br/>
      <sub>Coursework: Deep Learning · NLP & Text Mining · Algorithm Analysis & Design · Data Engineering · Computer Vision · Medical Image Analysis · High Performance Computing.</sub><br/>
      <sub>Previously: B.E. Computer Engineering, Jayawantrao Sawant College of Engineering, Pune — CGPA 8.25/10.</sub>
    </td>
  </tr>
</table>

---

<h3 align="center">research</h3>

<p align="center"><sub>Two peer-reviewed publications on cardiovascular risk prediction from retinal imaging.<br/>Full pipeline ownership: preprocessing → modeling → evaluation → manuscript.</sub></p>

<table align="center">
  <tr>
    <td width="100" align="center" valign="middle"><sub><b>2025</b></sub><br/><sub>IJIRT</sub><br/><sub>peer-reviewed</sub></td>
    <td valign="middle">
      <b>CNN-Based Cardiovascular Risk Assessment Using Retinal Imaging Biomarkers</b><br/>
      <sub>End-to-end CNN + SVM/RF pipeline for cardiac risk prediction from retinal fundus images. Full ownership from preprocessing through evaluation.</sub>
    </td>
  </tr>
  <tr>
    <td width="100" align="center" valign="middle"><sub><b>2024</b></sub><br/><sub>IJIRT</sub><br/><sub>peer-reviewed</sub></td>
    <td valign="middle">
      <b>ML-Driven Heart Disease Risk Prediction from Retinal Fundus Images</b><br/>
      <sub>CNNs with ensemble classifiers for cardiac risk stratification. Full pipeline ownership including paper writing.</sub>
    </td>
  </tr>
</table>

---

<h3 align="center">systems in flight</h3>

<table align="center">
  <tr>
    <th width="33%" align="center"><sub>medical AI</sub></th>
    <th width="33%" align="center"><sub>production RAG</sub></th>
    <th width="33%" align="center"><sub>LLM tooling</sub></th>
  </tr>
  <tr>
    <td valign="top">
      <b>ReXGroundingCT</b><br/>
      <sub><i>Independent research</i></sub>
      <br/><br/>
      <sub>Vision-language model for chest CT that decomposes clinical reasoning into region-specific steps, anchored to 3D spatial masks via foveated chain-of-thought.</sub>
      <br/><br/>
      <code>PyTorch</code> <code>MedNeXt</code> <code>ViT</code> <code>MONAI</code>
    </td>
    <td valign="top">
      <b>Self-Healing RAG</b><br/>
      <sub><i>In development</i></sub>
      <br/><br/>
      <sub>10-layer hybrid retrieval (dense + sparse + KG) with multi-signal confidence estimation and agentic self-correction via LangGraph. Claim-level causal validation.</sub>
      <br/><br/>
      <code>FastAPI</code> <code>LangGraph</code> <code>pgvector</code> <code>Redis</code> <code>Docker</code>
    </td>
    <td valign="top">
      <b>VectorLens</b><br/>
      <sub><i>Active</i></sub>
      <br/><br/>
      <sub>Local-first observability tool surfacing which retrieved chunks caused each sentence in LLM output. LIME-style bounded perturbation for causal importance; httpx transport patching for transparent interception.</sub>
      <br/><br/>
      <code>FastAPI</code> <code>SBERT</code> <code>React</code> <code>Tailwind</code>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <b>HippoFormer</b><br/>
      <sub><i>Completed</i></sub>
      <br/><br/>
      <sub>Hippocampus-inspired transformer encoding memory formation and consolidation as custom layers with salience gating. Hit <b>11.83 perplexity on WikiText-2</b> — 35% better than Gemma-2B baseline. Validated across 15 ablation variants with statistical significance testing.</sub>
      <br/><br/>
      <code>PyTorch</code> <code>PEFT/LoRA</code> <code>HuggingFace</code>
    </td>
    <td valign="top">
      <b>UnMask</b><br/>
      <sub><i>Completed</i></sub>
      <br/><br/>
      <sub>Socratic AI tutor for occupational therapy. <b>Progressive Context Revelation</b> gates answer chunks at the retrieval layer based on student mastery. DeBERTa NLI for mastery assessment, NetworkX prerequisite DAGs, dual-model routing across Llama 3.1 8B and GPT-4o.</sub>
      <br/><br/>
      <code>LangGraph</code> <code>Qdrant</code> <code>DeBERTa</code> <code>Llama 3.1</code>
    </td>
    <td valign="top">
      <b>AgentReplay</b><br/>
      <sub><i>Active</i></sub>
      <br/><br/>
      <sub>Time-travel debugger for LLM agents. Intercepts every step into a SQLite DAG. React dashboard scrubs backward through context windows, tool payloads, and token usage. Supports LangChain, OpenAI, and Anthropic.</sub>
      <br/><br/>
      <code>Python</code> <code>SQLite</code> <code>FastAPI</code> <code>React</code>
    </td>
  </tr>
</table>

---

<h3 align="center">stack</h3>

<table align="center">
  <tr>
    <td align="right" width="180"><sub><b>deep learning</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-81B29A?style=for-the-badge&logo=PyTorch&logoColor=white" />
      <img src="https://img.shields.io/badge/TensorFlow-81B29A?style=for-the-badge&logo=TensorFlow&logoColor=white" />
      <img src="https://img.shields.io/badge/Keras-81B29A?style=for-the-badge&logo=Keras&logoColor=white" />
      <img src="https://img.shields.io/badge/MONAI-81B29A?style=for-the-badge&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/MedNeXt-81B29A?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/ViT-81B29A?style=for-the-badge&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>LLMs · agents</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/HuggingFace-81B29A?style=for-the-badge&logo=huggingface&logoColor=white" />
      <img src="https://img.shields.io/badge/LangChain-81B29A?style=for-the-badge&logo=langchain&logoColor=white" />
      <img src="https://img.shields.io/badge/LangGraph-81B29A?style=for-the-badge&logo=graphql&logoColor=white" />
      <img src="https://img.shields.io/badge/PEFT%20%2F%20LoRA-81B29A?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/Llama%203-81B29A?style=for-the-badge&logo=meta&logoColor=white" />
      <img src="https://img.shields.io/badge/GPT--4o-81B29A?style=for-the-badge&logo=openai&logoColor=white" />
      <img src="https://img.shields.io/badge/DeBERTa-81B29A?style=for-the-badge&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>retrieval · vectors</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/Qdrant-B5838D?style=for-the-badge&logo=qdrant&logoColor=white" />
      <img src="https://img.shields.io/badge/pgvector-B5838D?style=for-the-badge&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/BM25-B5838D?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/SBERT-B5838D?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/Knowledge%20Graphs-B5838D?style=for-the-badge&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>data · ML</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/scikit--learn-B5838D?style=for-the-badge&logo=scikit-learn&logoColor=white" />
      <img src="https://img.shields.io/badge/XGBoost-B5838D?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-B5838D?style=for-the-badge&logo=numpy&logoColor=white" />
      <img src="https://img.shields.io/badge/Pandas-B5838D?style=for-the-badge&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/Matplotlib-B5838D?style=for-the-badge&logoColor=white" />
      <img src="https://img.shields.io/badge/Tableau-B5838D?style=for-the-badge&logo=tableau&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>infra · APIs · DBs</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-E07A5F?style=for-the-badge&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/Flask-E07A5F?style=for-the-badge&logo=flask&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-E07A5F?style=for-the-badge&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/PostgreSQL-E07A5F?style=for-the-badge&logo=postgresql&logoColor=white" />
      <img src="https://img.shields.io/badge/MongoDB-E07A5F?style=for-the-badge&logo=mongodb&logoColor=white" />
      <img src="https://img.shields.io/badge/Redis-E07A5F?style=for-the-badge&logo=redis&logoColor=white" />
      <img src="https://img.shields.io/badge/SQLite-E07A5F?style=for-the-badge&logo=sqlite&logoColor=white" />
      <img src="https://img.shields.io/badge/GCP-E07A5F?style=for-the-badge&logo=google-cloud&logoColor=white" />
      <img src="https://img.shields.io/badge/AWS-E07A5F?style=for-the-badge&logo=amazon-aws&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>languages</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3D405B?style=for-the-badge&logo=python&logoColor=EAE0D5" />
      <img src="https://img.shields.io/badge/Java-3D405B?style=for-the-badge&logo=openjdk&logoColor=EAE0D5" />
      <img src="https://img.shields.io/badge/C++-3D405B?style=for-the-badge&logo=cplusplus&logoColor=EAE0D5" />
      <img src="https://img.shields.io/badge/JavaScript-3D405B?style=for-the-badge&logo=javascript&logoColor=EAE0D5" />
      <img src="https://img.shields.io/badge/SQL-3D405B?style=for-the-badge&logo=postgresql&logoColor=EAE0D5" />
    </td>
  </tr>
  <tr>
    <td align="right"><sub><b>frontend</b></sub></td>
    <td>
      <img src="https://img.shields.io/badge/React-EAE0D5?style=for-the-badge&logo=react&logoColor=3D405B" />
      <img src="https://img.shields.io/badge/Tailwind-EAE0D5?style=for-the-badge&logo=tailwindcss&logoColor=3D405B" />
      <img src="https://img.shields.io/badge/Angular-EAE0D5?style=for-the-badge&logo=angular&logoColor=3D405B" />
    </td>
  </tr>
</table>

---

<h3 align="center">experience</h3>

<table align="center">
  <tr>
    <td width="160" align="right" valign="top"><sub><b>Sep – Oct 2024</b></sub><br/><sub>Remote</sub></td>
    <td valign="top">
      <b>ML Engineer Intern</b> · <i>InternPe</i><br/>
      <sub>Delivered four end-to-end ML projects across healthcare, sports analytics, and price prediction. SVM, RF, and CNN models evaluated with accuracy, precision, recall, F1, and RMSE.</sub>
    </td>
  </tr>
  <tr>
    <td width="160" align="right" valign="top"><sub><b>Dec 2023 – Feb 2024</b></sub><br/><sub>Pune, India</sub></td>
    <td valign="top">
      <b>Software Developer Intern</b> · <i>Dnyano Solutions Pvt. Ltd.</i><br/>
      <sub>Built a responsive educational-institute website using Angular, Sass, and MongoDB with accessible UI and MongoDB-backed services.</sub>
    </td>
  </tr>
</table>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sanika0212&theme=vue-dark&hide_border=true&include_all_commits=true&count_private=true&show_icons=true&rank_icon=github&title_color=B5838D&icon_color=E07A5F&text_color=EAE0D5&bg_color=1F2128" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Sanika0212&hide_border=true&layout=compact&count_private=true&title_color=B5838D&text_color=EAE0D5&bg_color=1F2128" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Sanika0212&hide_border=true&background=1F2128&stroke=3D405B&ring=B5838D&fire=E07A5F&currStreakLabel=B5838D&sideLabels=EAE0D5&currStreakNum=EAE0D5&sideNums=EAE0D5&dates=EAE0D5" />
</p>

---

<p align="center">
  <sub>
    <a href="https://www.sanikanajan.com/">sanikanajan.com</a>
    &nbsp; · &nbsp;
    research <b>×</b> systems
    &nbsp; · &nbsp;
    Buffalo, NY
  </sub>
</p>
