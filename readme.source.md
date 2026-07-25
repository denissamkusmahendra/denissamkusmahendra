```aura width=860 height=300
<div style={{ position: 'relative', display: 'flex', flexDirection: 'column', justifyContent: 'space-between', width: '100%', height: '100%', overflow: 'hidden', borderRadius: 20, background: '#0B0F14', border: '1px solid #243447', fontFamily: 'Inter, sans-serif', padding: '34px 42px' }}>
  <style>{`
    @keyframes orbit { to { transform: rotate(360deg); } }
    @keyframes breathe { 0%, 100% { opacity: .5; } 50% { opacity: 1; } }
    #orbit { animation: orbit 24s linear infinite; transform-origin: 742px 151px; }
    #signal { animation: breathe 2.4s ease-in-out infinite; }
  `}</style>
  <svg width="860" height="300" style={{ position: 'absolute', inset: 0 }}>
    <defs>
      <pattern id="grid" width="42" height="42" patternUnits="userSpaceOnUse">
        <path d="M 42 0 L 0 0 0 42" fill="none" stroke="rgba(36,52,71,.42)" strokeWidth="1" />
      </pattern>
      <radialGradient id="cyanGlow" cx="88%" cy="48%" r="52%">
        <stop offset="0%" stopColor="rgba(34,211,238,.17)" />
        <stop offset="100%" stopColor="rgba(34,211,238,0)" />
      </radialGradient>
      <radialGradient id="amberGlow" cx="5%" cy="0%" r="72%">
        <stop offset="0%" stopColor="rgba(245,158,11,.13)" />
        <stop offset="100%" stopColor="rgba(245,158,11,0)" />
      </radialGradient>
    </defs>
    <rect width="860" height="300" fill="url(#grid)" />
    <rect width="860" height="300" fill="url(#cyanGlow)" />
    <rect width="860" height="300" fill="url(#amberGlow)" />
    <g id="orbit">
      <circle cx="742" cy="151" r="82" fill="none" stroke="rgba(34,211,238,.34)" strokeWidth="1" strokeDasharray="4 10" />
      <circle cx="742" cy="69" r="4" fill="#22D3EE" />
    </g>
    <circle cx="742" cy="151" r="53" fill="rgba(11,15,20,.64)" stroke="rgba(245,158,11,.34)" />
    <path d="M714 164 L731 147 L744 158 L772 130" fill="none" stroke="#22D3EE" strokeWidth="3" strokeLinecap="round" strokeLinejoin="round" />
    <circle cx="772" cy="130" r="4" fill="#F59E0B" />
  </svg>

  <div style={{ position: 'relative', display: 'flex', alignItems: 'center', justifyContent: 'space-between' }}>
    <span style={{ color: '#F59E0B', fontSize: 12, fontWeight: 800, fontFamily: 'monospace', letterSpacing: 2.2 }}>MARVRCH / PROFILE</span>
    <div style={{ display: 'flex', alignItems: 'center', gap: 8, border: '1px solid rgba(34,211,238,.28)', borderRadius: 999, background: 'rgba(15,23,42,.58)', padding: '7px 12px' }}>
      <span id="signal" style={{ width: 7, height: 7, borderRadius: 999, background: '#22D3EE' }} />
      <span style={{ color: '#CBD5E1', fontSize: 11, fontFamily: 'monospace', letterSpacing: 1 }}>JAKARTA, INDONESIA</span>
    </div>
  </div>

  <div style={{ position: 'relative', display: 'flex', flexDirection: 'column', width: 610 }}>
    <span style={{ color: '#F8FAFC', fontSize: 50, fontWeight: 800, lineHeight: 1.04, letterSpacing: -1.4 }}>Marvin Chandiary</span>
    <span style={{ color: '#22D3EE', fontSize: 18, fontWeight: 700, marginTop: 12 }}>Data Analytics &amp; Business Intelligence</span>
    <span style={{ color: '#94A3B8', fontSize: 15, lineHeight: 1.55, marginTop: 12, maxWidth: 570 }}>Turning raw data into reliable datasets, clear analysis, and decision-ready dashboards.</span>
  </div>

  <div style={{ position: 'relative', display: 'flex', alignItems: 'center', gap: 9 }}>
    {['SQL + PYTHON', 'BUSINESS INTELLIGENCE', 'LEARNING DATA ENGINEERING'].map(function(item, index) {
      return <span key={item} style={{ color: index === 2 ? '#F59E0B' : '#CBD5E1', border: '1px solid rgba(148,163,184,.22)', borderRadius: 7, background: 'rgba(15,23,42,.72)', padding: '7px 10px', fontSize: 10, fontWeight: 700, fontFamily: 'monospace', letterSpacing: .7 }}>{item}</span>;
    })}
  </div>
</div>
```

<p align="center">
  <a href="https://www.datascienceportfol.io/marvinchandiary"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=googlechrome&logoColor=22D3EE" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/marvinchandiary"><img src="https://img.shields.io/badge/LinkedIn-0F172A?style=for-the-badge&logo=linkedin&logoColor=22D3EE" alt="LinkedIn" /></a>
  <a href="mailto:marvinchandiary@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=F59E0B" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1lQHH1OpiArFIfbbTV92y0YXVZJhw-1rv/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-0F172A?style=for-the-badge&logo=readme&logoColor=F59E0B" alt="Resume" /></a>
</p>

<p align="center"><sub>Information Systems student at BINUS University · Building at the intersection of data, systems, and business decisions</sub></p>

## About

I enjoy the part of data work where technical detail meets business context: defining useful metrics, cleaning imperfect data, finding the signal, and communicating it clearly. My foundation is in **analytics and BI**, and I am currently expanding toward **data engineering** to build more reliable end-to-end data workflows.

<table>
  <tr>
    <td width="33%" valign="top">
      <strong>01 · Analyze</strong><br><br>
      <sub>Explore data, define KPIs, and turn business questions into measurable insights.</sub>
    </td>
    <td width="33%" valign="top">
      <strong>02 · Communicate</strong><br><br>
      <sub>Build focused dashboards and explain findings in language stakeholders can act on.</sub>
    </td>
    <td width="33%" valign="top">
      <strong>03 · Engineer</strong><br><br>
      <sub>Develop stronger pipelines, modeling habits, and dependable data foundations.</sub>
    </td>
  </tr>
</table>

## Toolbox

<p>
  <img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=F59E0B" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-111827?style=flat-square&logoColor=22D3EE" alt="SQL" />
  <img src="https://img.shields.io/badge/BigQuery-111827?style=flat-square&logo=googlebigquery&logoColor=22D3EE" alt="BigQuery" />
  <img src="https://img.shields.io/badge/Pandas-111827?style=flat-square&logo=pandas&logoColor=F8FAFC" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-111827?style=flat-square&logo=numpy&logoColor=22D3EE" alt="NumPy" />
  <img src="https://img.shields.io/badge/Power_BI-111827?style=flat-square&logo=powerbi&logoColor=F59E0B" alt="Power BI" />
  <img src="https://img.shields.io/badge/Looker_Studio-111827?style=flat-square&logo=looker&logoColor=22D3EE" alt="Looker Studio" />
  <img src="https://img.shields.io/badge/Streamlit-111827?style=flat-square&logo=streamlit&logoColor=F59E0B" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Git-111827?style=flat-square&logo=git&logoColor=F59E0B" alt="Git" />
</p>

## Selected work

| Project | What it demonstrates | Stack |
| :--- | :--- | :--- |
| **[Kimia Farma Performance Analytics](https://github.com/marvrch/Kimia-Farma-Performance-Analytics)** | Business performance analysis from 2020–2023, translated into an interactive decision-support dashboard. | `BigQuery` `Looker Studio` |
| **[SaleCraft Data Wrangling](https://github.com/marvrch/SaleCraft_DataWrangling)** | Auditable cleaning, data-quality checks, and feature preparation from messy retail invoices. | `Python` `Pandas` `NumPy` |
| **[Retail Sales & Customer Analysis](https://github.com/marvrch/Retail-Business-Sales-Customer-Analysis)** | KPI design and RFM segmentation used to surface retention and sales opportunities. | `SQL Server` `Power BI` |
| **[Smartphone Price Prediction](https://github.com/marvrch/Smartphone-Price-Prediction)** | Leak-safe regression workflow with a tuned SVR model and a deployed prediction app. | `scikit-learn` `Streamlit` |

> **Now:** strengthening my data engineering fundamentals through the [Data Engineering Zoomcamp](https://github.com/marvrch/data-engineering-zoomcamp), with an emphasis on reproducible workflows and solid foundations.

## GitHub pulse

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=marvrch&bg_color=0B0F14&color=94A3B8&line=22D3EE&point=F59E0B&area=true&hide_border=true" alt="Marvin's GitHub contribution graph" />
</p>

<details>
  <summary><strong>More GitHub statistics</strong></summary>
  <br>
  <p align="center">
    <a href="https://github.com/stats-organization/github-stats-extended"><img height="180" src="https://github-stats-extended.vercel.app/api?username=marvrch&show_icons=true&count_private=true&title_color=22D3EE&text_color=94A3B8&icon_color=F59E0B&bg_color=0B0F14&border_color=243447&border_radius=8" alt="Marvin's GitHub statistics" /></a>
    <img height="180" src="https://github-stats-extended.vercel.app/api/top-langs?username=marvrch&layout=compact&langs_count=8&title_color=22D3EE&text_color=94A3B8&icon_color=F59E0B&bg_color=0B0F14&border_color=243447&border_radius=8" alt="Most used languages" />
  </p>
  <p align="center"><sub>Language statistics reflect public repository code, not proficiency.</sub></p>
</details>

---

<p align="center">
  <sub>Build clearly · Measure honestly · Keep learning</sub><br>
  <sub>Header rendered with <a href="https://github.com/collectioneur/readme-aura">readme-aura</a>.</sub>
</p>
