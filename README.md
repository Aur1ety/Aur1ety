<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:05010D,45:B026FF,100:FF2E97&height=210&section=header&text=ARINJAY%20PAWAR&fontSize=46&fontColor=00F0FF&fontAlignY=38&animation=fadeIn&desc=%5B%20SPACE%20WEATHER%20%2F%2F%20CLINICAL%20ML%20%5D&descAlignY=58&descSize=15" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=20&duration=3000&pause=800&color=FF2E97&background=05010D00&center=true&vCenter=true&width=760&lines=%3E+forecasting+solar+flares+from+satellite+X-ray+telemetry;%3E+beat+the+published+SOTA+on+the+SWAN-SF+benchmark;%3E+time-series+deep+learning+on+real+spacecraft+data;%3E+AI%2FML+head+%40+google+developer+group" alt="typing"/>

<br/>

<img src="https://img.shields.io/badge/STATUS-ONLINE-39FF14?style=for-the-badge&labelColor=05010D"/>
<img src="https://img.shields.io/badge/SECTOR-SPACE%20TECH-00F0FF?style=for-the-badge&labelColor=05010D"/>
<img src="https://img.shields.io/badge/NODE-NAVI%20MUMBAI-FF2E97?style=for-the-badge&labelColor=05010D"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:B026FF,100:00F0FF&height=3&section=header" width="100%"/>

</div>

```console
root@aur1ety:~$ ./whoami --verbose

  ┌─ IDENTITY ───────────────────────────────────────────┐
  │  AI/ML Engineer  ·  Space Weather & Medical Imaging  │
  │  B.Tech AI/ML  ·  RAIT, DY Patil University  ·  '27  │
  │  AI/ML Head  ·  Google Developer Group  (200+ devs)  │
  └──────────────────────────────────────────────────────┘

  [OK] time-series deep learning ............ ONLINE
  [OK] satellite telemetry pipelines ........ ONLINE
  [OK] blind-holdout evaluation ............. ENFORCED
  [OK] clinical ML deployment ............... ONLINE
  [!!] sleep schedule ....................... NOT FOUND
```

I build end-to-end ML systems for **space weather forecasting** and **medical imaging**. The kind that run on real spacecraft telemetry and get judged on blind hold-outs, not notebook accuracy. Most of my work lives at the messy end: raw Level-1 instrument data, 1-in-50 class imbalance, and metrics that have to survive an audit.

I work across solar physics missions and open space-weather datasets from **NASA, NOAA and ISRO**, with clinical ML shipping on the side.

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:B026FF,100:FF2E97&height=3&section=header" width="100%"/></div>

## `[ 01 ]` &nbsp;ORBITAL &nbsp;`//` &nbsp;SPACE WEATHER

<table>
<tr>
<td width="50%" valign="top">

### ▰ ROENTGEN
`solar flare nowcast + 24h forecast`

Mixture-of-experts on dual-channel solar X-ray telemetry (soft + hard). Two TCN nowcasters, a gradient-boosted forecaster, and an independently built flare catalogue.

<img src="https://img.shields.io/badge/TSS_0.811_on_SWAN--SF-39FF14?style=flat-square&labelColor=05010D"/>

Above the published attention-based SOTA (GCTAF 0.748). Leakage-audited, protocol-matched.

<sub>`PyTorch` `XGBoost` `15,550-event catalogue`</sub>

</td>
<td width="50%" valign="top">

### ▰ MAGNUSON
`geomagnetic storm onset forecasting`

1M+ 10-second magnetometer observations from L1 orbit into a real-time onset pipeline. Benchmarked 7 sequential architectures.

<img src="https://img.shields.io/badge/F1_0.919_·_HSS_0.908-39FF14?style=flat-square&labelColor=05010D"/>

False alarm rate 0.0044 on held-out data.

<sub>`PatchTransformer` `HMM` `Viterbi decoding`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ▰ CME DETECTION
`coronal mass ejection prediction`

Plasma-based predictor on Level-2 solar wind variables: bulk velocity, proton density, thermal temperature, ionic ratios.

<sub>`TCN + TCAN` `focal loss` `extreme imbalance`</sub>

</td>
<td width="50%" valign="top">

### ▰ SPACE WEATHER CLI
`live interplanetary telemetry`

Async CLI aggregating NOAA and NASA DONKI feeds, built for headless systems with zero graphical dependencies.

<sub>`Python` `Rich` `asyncio`</sub>

</td>
</tr>
</table>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:B026FF,100:00F0FF&height=3&section=header" width="100%"/></div>

## `[ 02 ]` &nbsp;BIOMETRIC &nbsp;`//` &nbsp;HEALTHCARE

<table>
<tr>
<td width="50%" valign="top">

### ▰ NEUROPHARMA &nbsp;<img src="https://img.shields.io/badge/LIVE-39FF14?style=flat-square&labelColor=05010D"/>
`drug-drug interaction risk engine`

Cross-references patient prescription profiles against pharmacological datasets and generates automated hazard alerts for clinical review.

<sub>`Next.js / Vercel` `FastAPI + Docker / Hugging Face`</sub>

</td>
<td width="50%" valign="top">

### ▰ CLINICAL DATA QA
`mammography & X-ray pipelines`

Annotated and validated large-scale imaging datasets for an AI-driven breast cancer detection system, building QA checks alongside medical and engineering teams.

<sub>`Pulse Hitech` `Data Analyst Intern`</sub>

</td>
</tr>
</table>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:B026FF,100:FF2E97&height=3&section=header" width="100%"/></div>

## `[ 03 ]` &nbsp;LOADOUT

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,postgres&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,git,linux,vercel&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/XGBoost-FF2E97?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/LightGBM-FF2E97?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/Transformers-B026FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/TCN-B026FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/TFT-B026FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/HMM-B026FF?style=flat-square&labelColor=05010D"/>
<br/>
<img src="https://img.shields.io/badge/NumPy-00F0FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/Pandas-00F0FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/SciPy-00F0FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/xarray-00F0FF?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/Hugging%20Face-39FF14?style=flat-square&labelColor=05010D"/>
<img src="https://img.shields.io/badge/LaTeX-39FF14?style=flat-square&labelColor=05010D"/>

</div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:B026FF,100:00F0FF&height=3&section=header" width="100%"/></div>

## `[ 04 ]` &nbsp;TELEMETRY

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=Aur1ety&show_icons=true&include_all_commits=true&bg_color=05010D&title_color=FF2E97&text_color=E0D7FF&icon_color=00F0FF&border_color=B026FF"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aur1ety&layout=compact&langs_count=8&bg_color=05010D&title_color=FF2E97&text_color=E0D7FF&border_color=B026FF"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aur1ety&graph_type=bar&bg_color=05010D&color=00F0FF&line=FF2E97&point=39FF14&title_color=FF2E97&border_color=B026FF&custom_title=COMMIT%20FREQUENCY" width="98%"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg" width="98%"/>
</picture>

</div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,50:B026FF,100:FF2E97&height=3&section=header" width="100%"/></div>

## `[ 05 ]` &nbsp;RUNNING PROCESSES

```yaml
building:   Eos — fusing X-ray nowcasting with magnetogram-based 24h forecasting
writing:    a paper on the SWAN-SF result + an independent solar flare catalogue
curious:    neuromorphic computing, LLM agent architectures, MLOps at scale
open_to:    AI/ML roles in space tech, scientific computing, and clinical ML
```

<sub>`background_process:` anime, games, and being thoroughly outranked by my cats.</sub>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,50:B026FF,100:00F0FF&height=3&section=header" width="100%"/>

### `>` ESTABLISH CONNECTION

<a href="https://linkedin.com/in/arinjaypawar"><img src="https://img.shields.io/badge/LINKEDIN-05010D?style=for-the-badge&logo=linkedin&logoColor=00F0FF"/></a>
<a href="mailto:pawararinjay06@gmail.com"><img src="https://img.shields.io/badge/EMAIL-05010D?style=for-the-badge&logo=gmail&logoColor=FF2E97"/></a>
<a href="https://github.com/Aur1ety"><img src="https://img.shields.io/badge/GITHUB-05010D?style=for-the-badge&logo=github&logoColor=39FF14"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:FF2E97,55:B026FF,100:05010D&height=120&section=footer"/>

</div>
