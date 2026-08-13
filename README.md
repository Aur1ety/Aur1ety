<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:1F1F1F,50:2A2A2A,100:1F1F1F&height=160&section=header&text=AUR1ETY&fontSize=58&fontColor=E8FF4D&fontAlignY=52" width="100%" alt="AUR1ETY"/>

<img src="https://img.shields.io/badge/AI%2FML%20ENGINEER-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<img src="https://img.shields.io/badge/SPACE%20TECH%20%2B%20HEALTHCARE-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<img src="https://img.shields.io/badge/INDIA-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<img src="https://img.shields.io/badge/STATUS-OPEN%20TO%20WORK-E8FF4D?style=flat-square&labelColor=1F1F1F"/>

<a href="https://linkedin.com/in/arinjaypawar"><img src="https://img.shields.io/badge/LINKEDIN-E8FF4D?style=for-the-badge&logo=linkedin&logoColor=1F1F1F"/></a>
<a href="mailto:pawararinjay06@gmail.com"><img src="https://img.shields.io/badge/EMAIL-2E2E2E?style=for-the-badge&logo=gmail&logoColor=E8FF4D"/></a>
<a href="https://github.com/Aur1ety"><img src="https://img.shields.io/badge/GITHUB-2E2E2E?style=for-the-badge&logo=github&logoColor=E8FF4D"/></a>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=ABOUT&fontSize=19&fontColor=E8FF4D&fontAlign=9&fontAlignY=58" width="100%" alt="ABOUT"/>

<table width="100%">
<tr>
<td width="62%" valign="top">

I build end-to-end machine learning systems for **space tech** and **healthcare** — the kind that run on real scientific data and get judged on blind hold-outs, not notebook accuracy.

Most of my work lives at the messy end: raw instrument data, brutal class imbalance, and metrics that have to survive an audit.

<sub>`B.TECH AI/ML` &nbsp;·&nbsp; `RAIT, DY PATIL UNIVERSITY` &nbsp;·&nbsp; `CLASS OF '27`</sub>

</td>
<td width="38%" align="center" valign="middle">

<img src="https://raw.githubusercontent.com/Aur1ety/Aur1ety/main/Pixel%20Art%208Bit%20GIF%20by%20pixel%20jeff.gif" width="88%"/>

<sub><code>upper management</code></sub>

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=MODEL%20STACK&fontSize=19&fontColor=E8FF4D&fontAlign=13&fontAlignY=58" width="100%" alt="MODEL STACK"/>

<table width="100%">
<tr>
<td valign="top">

**EOS 6** &nbsp; <img src="https://img.shields.io/badge/FLAGSHIP-E8FF4D?style=flat-square&labelColor=1F1F1F"/>

<sub>`TASK-ROUTED MIXTURE OF EXPERTS`</sub>

Hand it raw solar X-ray telemetry and it does the rest — builds its own features, routes them through every expert, and streams one combined result: what is flaring right now, and the probability of a major flare in the next 24 hours.

<img src="https://img.shields.io/badge/NOWCAST%20%2B%2024H%20FORECAST-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/END--TO--END-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/SINGLE%20ENTRY%20POINT-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="50%" valign="top">

**LUMEN 6&#42;** &nbsp; <img src="https://img.shields.io/badge/FORECAST%20EXPERT-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

<sub>`P(MAJOR FLARE, NEXT 24H)`</sub>

Gradient-boosted ensemble over magnetogram-derived active-region features, with calibrated probabilities.

<img src="https://img.shields.io/badge/TSS-0.811-E8FF4D?style=flat-square&labelColor=1F1F1F"/> <img src="https://img.shields.io/badge/SWAN--SF-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="50%" valign="top">

**SPECTRA 6&#42;** &nbsp; <img src="https://img.shields.io/badge/NOWCAST%20EXPERTS-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

<sub>`LIVE FLARE STATE + CLASS`</sub>

Twin temporal convolutional networks reading per-minute X-ray telemetry, one per channel.

<img src="https://img.shields.io/badge/TCN-x2-E8FF4D?style=flat-square&labelColor=1F1F1F"/> <img src="https://img.shields.io/badge/PER--MINUTE-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

```
BENCHMARK  ·  SWAN-SF  ·  TRUE SKILL STATISTIC

  lumen 6                ███████████████████████████   0.811
  gctaf   published sota ████████████████████████      0.748

  leakage-audited  ·  protocol-matched
```

<sub><code>*</code> work in progress</sub>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=PROJECTS&fontSize=19&fontColor=E8FF4D&fontAlign=11&fontAlignY=58" width="100%" alt="PROJECTS"/>

<table width="100%">
<tr>
<td width="66%" valign="top">

**ROENTGEN**

<sub>`solar flare nowcast + 24h forecast`</sub>

Mixture-of-experts over dual-channel solar X-ray telemetry, soft and hard: two TCN nowcasters, a gradient-boosted forecaster, and an independently built flare catalogue. Above the published attention-based SOTA on SWAN-SF.

<img src="https://img.shields.io/badge/pytorch-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/xgboost-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/heliophysics-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="34%" valign="middle">

<img src="https://img.shields.io/badge/TSS-0.811-E8FF4D?style=flat-square&labelColor=1F1F1F"/>
<br/>
<img src="https://img.shields.io/badge/SOTA%20BASELINE-0.748-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<br/>
<img src="https://img.shields.io/badge/CATALOGUE-15%2C550%20EVENTS-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="66%" valign="top">

**MAGNUSON**

<sub>`geomagnetic storm onset forecasting`</sub>

1M+ 10-second magnetometer observations from L1 orbit driving a real-time onset pipeline, with seven sequential architectures benchmarked head to head.

<img src="https://img.shields.io/badge/patchtransformer-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/hmm-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/viterbi-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="34%" valign="middle">

<img src="https://img.shields.io/badge/F1-0.919-E8FF4D?style=flat-square&labelColor=1F1F1F"/>
<br/>
<img src="https://img.shields.io/badge/HSS-0.908-E8FF4D?style=flat-square&labelColor=1F1F1F"/>
<br/>
<img src="https://img.shields.io/badge/FALSE%20ALARM%20RATE-0.0044-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="66%" valign="top">

**CME DETECTION**

<sub>`autonomous coronal mass ejection detection`</sub>

Two-model TCN + TCAN ensemble over in-situ solar wind plasma at L1 — bulk velocity, proton density, thermal temperature, helium-to-proton ratio and their gradients. Causal dilated convolutions give a 10.6-hour receptive field, so the model only ever looks backwards and stays valid for real-time use.

Beat XGBoost (0.210) and BiLSTM (0.195) on identical data. F1 sits near the physical ceiling for single-point plasma sensing — 30 to 50% of CMEs are stealth events that leave no plasma precursor at all. On the unseen May 2026 eruption it peaked at P = 0.8707, corroborated by a helium-to-proton ratio of 0.2965, roughly 7x the quiet-wind baseline.

<img src="https://img.shields.io/badge/tcn%20%2B%20tcan-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/causal%20dilated%20conv-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/weighted%20bce-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="34%" valign="middle">

<img src="https://img.shields.io/badge/BLIND%20DETECTION-0.8707-E8FF4D?style=flat-square&labelColor=1F1F1F"/>
<br/>
<img src="https://img.shields.io/badge/VAL%20F1-0.318-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<br/>
<img src="https://img.shields.io/badge/TRAINING-44%2C103%20SEQUENCES-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<br/>
<img src="https://img.shields.io/badge/EVENT%20RATE-3.2%25-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="66%" valign="top">

**SPACE WEATHER CLI**

<sub>`live interplanetary telemetry`</sub>

Async CLI aggregating NOAA and NASA DONKI feeds, built for headless systems with zero graphical dependencies.

<img src="https://img.shields.io/badge/python-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/rich-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/asyncio-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="34%" valign="middle">

<img src="https://img.shields.io/badge/FEEDS-NOAA%20%2B%20NASA%20DONKI-2E2E2E?style=flat-square&labelColor=2E2E2E"/>
<br/>
<img src="https://img.shields.io/badge/HEADLESS-ZERO%20GUI%20DEPS-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="66%" valign="top">

**NEUROPHARMA**

<sub>`drug-drug interaction risk engine`</sub>

Cross-references patient prescription profiles against pharmacological datasets and generates automated hazard alerts for clinical review. Next.js on Vercel, FastAPI and Docker on Hugging Face.

<img src="https://img.shields.io/badge/next.js-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/fastapi-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/docker-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/hugging%20face-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
<td width="34%" valign="middle">

<img src="https://img.shields.io/badge/STATUS-LIVE-39D353?style=flat-square&labelColor=1F1F1F"/>
<br/>
<img src="https://img.shields.io/badge/HEALTHCARE-2E2E2E?style=flat-square&labelColor=2E2E2E"/>

</td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=CORE%20TECHNOLOGIES&fontSize=19&fontColor=E8FF4D&fontAlign=17&fontAlignY=58" width="100%" alt="CORE TECHNOLOGIES"/>

<table width="100%">
<tr>
<td width="22%" align="right" valign="middle"><sub><code>STACK</code></sub></td>
<td valign="middle"><img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,postgres&theme=dark"/></td>
</tr>
<tr>
<td width="22%" align="right" valign="middle"><sub><code>WEB / OPS</code></sub></td>
<td valign="middle"><img src="https://skillicons.dev/icons?i=nextjs,react,ts,git,linux,vercel&theme=dark"/></td>
</tr>
<tr>
<td width="22%" align="right" valign="middle"><sub><code>MODELING</code></sub></td>
<td valign="middle"><img src="https://img.shields.io/badge/xgboost-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/lightgbm-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/transformers-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/tcn-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/tft-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/hmm-2E2E2E?style=flat-square&labelColor=2E2E2E"/></td>
</tr>
<tr>
<td width="22%" align="right" valign="middle"><sub><code>SCIENTIFIC</code></sub></td>
<td valign="middle"><img src="https://img.shields.io/badge/numpy-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/pandas-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/scipy-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/xarray-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/latex-2E2E2E?style=flat-square&labelColor=2E2E2E"/> <img src="https://img.shields.io/badge/hugging%20face-2E2E2E?style=flat-square&labelColor=2E2E2E"/></td>
</tr>
</table>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=CONTRIBUTIONS&fontSize=19&fontColor=E8FF4D&fontAlign=14&fontAlignY=58" width="100%" alt="CONTRIBUTIONS"/>

<div align="center">

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=Aur1ety&graph_type=bar&bg_color=2E2E2E&color=A0A0A0&line=E8FF4D&point=E8FF4D&title_color=E8FF4D&border_color=4A4A4A&custom_title=COMMIT%20FREQUENCY"/>

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Aur1ety&theme=gruvbox"/>
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Aur1ety&theme=gruvbox"/>

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Aur1ety&theme=gruvbox"/>

<br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg" width="98%"/>
</picture>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:242424,100:2E2E2E&height=54&section=header&text=RUNNING&fontSize=19&fontColor=E8FF4D&fontAlign=11&fontAlignY=58" width="100%" alt="RUNNING"/>

```
BUILDING    eos — fusing X-ray nowcasting with magnetogram-based 24h forecasting
WRITING     a paper on the SWAN-SF result + an independent solar flare catalogue
CURIOUS     neuromorphic computing · LLM agent architectures · MLOps at scale
OPEN TO     AI/ML roles in space tech, scientific computing, and clinical ML
BACKGROUND  anime, games, and being thoroughly outranked by my cats
```
