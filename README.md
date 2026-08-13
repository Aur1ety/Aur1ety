<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:05010D,40:B026FF,100:FF2E97&height=230&section=header&text=AUR1ETY&fontSize=72&fontColor=00F0FF&fontAlignY=42&animation=fadeIn" width="100%"/>

<img src="https://img.shields.io/badge/SYS-ONLINE-39FF14?style=for-the-badge&labelColor=05010D"/>&nbsp;<img src="https://img.shields.io/badge/CLASS-AI%2FML%20ENGINEER-B026FF?style=for-the-badge&labelColor=05010D"/>&nbsp;<img src="https://img.shields.io/badge/SECTOR-SPACE%20TECH%20%2B%20HEALTHCARE-00F0FF?style=for-the-badge&labelColor=05010D"/>&nbsp;<img src="https://img.shields.io/badge/NODE-INDIA-FF2E97?style=for-the-badge&labelColor=05010D"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,25:00F0FF,50:B026FF,75:FF2E97,100:05010D&height=3&section=header" width="100%"/>

### ▓▒░ ESTABLISH UPLINK ░▒▓

<a href="https://linkedin.com/in/arinjaypawar"><img src="https://img.shields.io/badge/LINKEDIN-00F0FF?style=for-the-badge&logo=linkedin&logoColor=05010D"/></a>&nbsp;
<a href="mailto:pawararinjay06@gmail.com"><img src="https://img.shields.io/badge/EMAIL-FF2E97?style=for-the-badge&logo=gmail&logoColor=05010D"/></a>&nbsp;
<a href="https://github.com/Aur1ety"><img src="https://img.shields.io/badge/GITHUB-39FF14?style=for-the-badge&logo=github&logoColor=05010D"/></a>

</div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,12:05010D,88:05010D,100:FF2E97&height=100&section=header&text=INTRODUCING%20%2F%2F%20EOS%206&fontSize=30&fontColor=39FF14&fontAlignY=52" width="100%" alt="INTRODUCING // EOS 6"/></div>

<table width="100%">
<tr>
<td>

### ▓▒░ EOS 6 — THE SOLAR FLARE FORECASTER AND NOWCASTER

`raw data in — predictions out // task-routed mixture of experts`

Hand it raw solar X-ray telemetry and it does the rest: builds its own features, routes them through every expert, and streams one combined picture — **what is flaring right now** and **the probability of a major flare in the next 24 hours**. Nowcast and forecast, one load, one call.

<img src="https://img.shields.io/badge/MIXTURE--OF--EXPERTS-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/NOWCAST%20%2B%2024H%20FORECAST-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/END--TO--END-39FF14?style=flat-square"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### ▒░ LUMEN 6*

`the forecast expert // P(M-class in 24h)`

Gradient-boosted ensemble over magnetogram-derived active-region features with calibrated probabilities — **TSS 0.811 on SWAN-SF**, above the published attention-based SOTA.

<img src="https://img.shields.io/badge/XGBOOST-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/CALIBRATED-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/24H%20HORIZON-39FF14?style=flat-square"/>

</td>
<td width="50%" valign="top">

#### ▒░ SPECTRA 6*

`the nowcast experts // soft + hard X-ray`

Twin temporal convolutional networks reading per-minute X-ray telemetry — one per channel — classifying live flare state and class as it happens.

<img src="https://img.shields.io/badge/TCN%20x2-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/PER--MINUTE-39FF14?style=flat-square"/> <img src="https://img.shields.io/badge/DUAL%20CHANNEL-39FF14?style=flat-square"/>

</td>
</tr>
</table>

<div align="center"><sub><code>* work in progress</code></sub></div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,50:39FF14,100:05010D&height=3&section=header" width="100%"/></div>

```console
aur1ety@l1-station:~$ ./boot_sequence --identity

  ┌──[ MANIFEST ]────────────────────────────────────────────
  │
  │   CLASS      AI/ML Engineer :: Space Tech x Healthcare
  │   ACADEMY    B.Tech AI/ML :: RAIT, DY Patil University :: '27
  │
  └──────────────────────────────────────────────────────────

  [ OK ] deep_learning .................................. ONLINE
  [ OK ] time_series_forecasting ........................ ONLINE
  [ OK ] blind_holdout_evaluation ....................... ENFORCED
  [ OK ] production_deployment .......................... ONLINE
  [FAIL] sleep_schedule ................................. NOT_FOUND
```

<table width="100%">
<tr>
<td width="58%" valign="middle">

I build end-to-end machine learning systems for **space tech** and **healthcare** — the kind that run on real scientific data and get judged on blind hold-outs, not notebook accuracy.

Most of my work lives at the messy end: raw instrument data, brutal class imbalance, and metrics that have to survive an audit.

</td>
<td width="42%" align="center" valign="middle">

<img src="https://raw.githubusercontent.com/Aur1ety/Aur1ety/main/cat.gif" width="92%"/>
<br/>
<sub><code>chief_morale_officer.exe — always running</code></sub>

</td>
</tr>
</table>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F0FF,12:05010D,88:05010D,100:00F0FF&height=100&section=header&text=SYS.01%20%2F%2F%20SPACE%20TECH&fontSize=30&fontColor=00F0FF&fontAlignY=52" width="100%" alt="SYS.01 // SPACE TECH"/></div>

<table width="100%">
<tr>
<td width="66%" valign="top">

### ▓▒░ ROENTGEN

`mixture-of-experts // solar flare nowcast + 24h forecast`

Dual-channel solar X-ray telemetry (soft + hard) feeding two TCN nowcasters and a gradient-boosted forecaster, backed by an independently built flare catalogue. Clear of the published attention-based SOTA on SWAN-SF — leakage-audited, protocol-matched.

<img src="https://img.shields.io/badge/PYTORCH-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/XGBOOST-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/DUAL%20TCN%20%2B%20GBM-00F0FF?style=flat-square"/>

</td>
<td width="34%" align="center" valign="middle">

<img src="https://img.shields.io/badge/SWAN--SF%20TSS-0.811-39FF14?style=for-the-badge&labelColor=05010D"/>
<br/>
<img src="https://img.shields.io/badge/SOTA%20BASELINE-GCTAF%200.748-B026FF?style=for-the-badge&labelColor=05010D"/>
<br/>
<img src="https://img.shields.io/badge/CATALOGUE-15%2C550%20EVENTS-39FF14?style=for-the-badge&labelColor=05010D"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="66%" valign="top">

### ▓▒░ MAGNUSON

`geomagnetic storm onset forecasting`

1M+ 10-second magnetometer observations from L1 orbit driving a real-time onset pipeline. Benchmarked seven sequential architectures; false alarm rate of 0.0044 on held-out data.

<img src="https://img.shields.io/badge/PATCHTRANSFORMER-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/HMM-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/VITERBI%20DECODING-00F0FF?style=flat-square"/>

</td>
<td width="34%" align="center" valign="middle">

<img src="https://img.shields.io/badge/F1-0.919-39FF14?style=for-the-badge&labelColor=05010D"/>
<br/>
<img src="https://img.shields.io/badge/HSS-0.908-39FF14?style=for-the-badge&labelColor=05010D"/>
<br/>
<img src="https://img.shields.io/badge/FALSE%20ALARM%20RATE-0.0044-39FF14?style=for-the-badge&labelColor=05010D"/>

</td>
</tr>
</table>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### ▒░ CME DETECTION

`coronal mass ejection prediction`

Plasma-based predictor on Level-2 solar wind variables — bulk velocity, proton density, thermal temperature, ionic ratios — under extreme class imbalance.

<img src="https://img.shields.io/badge/TCN%20%2B%20TCAN-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/FOCAL%20LOSS-00F0FF?style=flat-square"/>

</td>
<td width="50%" valign="top">

#### ▒░ SPACE WEATHER CLI

`live interplanetary telemetry`

Async CLI aggregating NOAA and NASA DONKI feeds, built for headless systems with zero graphical dependencies.

<img src="https://img.shields.io/badge/PYTHON-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/RICH-00F0FF?style=flat-square"/> <img src="https://img.shields.io/badge/ASYNCIO-00F0FF?style=flat-square"/>

</td>
</tr>
</table>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,50:00F0FF,100:05010D&height=3&section=header" width="100%"/></div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:FF2E97,12:05010D,88:05010D,100:FF2E97&height=100&section=header&text=SYS.02%20%2F%2F%20HEALTHCARE&fontSize=30&fontColor=FF2E97&fontAlignY=52" width="100%" alt="SYS.02 // HEALTHCARE"/></div>

<table width="100%">
<tr>
<td width="66%" valign="top">

### ▓▒░ NEUROPHARMA

`drug-drug interaction risk engine`

Cross-references patient prescription profiles against pharmacological datasets and generates automated hazard alerts for clinical review. Frontend on Vercel, containerized API on Hugging Face.

<img src="https://img.shields.io/badge/NEXT.JS-FF2E97?style=flat-square"/> <img src="https://img.shields.io/badge/VERCEL-FF2E97?style=flat-square"/> <img src="https://img.shields.io/badge/FASTAPI-FF2E97?style=flat-square"/> <img src="https://img.shields.io/badge/DOCKER-FF2E97?style=flat-square"/> <img src="https://img.shields.io/badge/HUGGING%20FACE-FF2E97?style=flat-square"/>

</td>
<td width="34%" align="center" valign="middle">

<img src="https://img.shields.io/badge/STATUS-LIVE-39FF14?style=for-the-badge&labelColor=05010D"/>

</td>
</tr>
</table>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,50:FF2E97,100:05010D&height=3&section=header" width="100%"/></div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:B026FF,12:05010D,88:05010D,100:B026FF&height=100&section=header&text=SYS.03%20%2F%2F%20LOADOUT&fontSize=30&fontColor=B026FF&fontAlignY=52" width="100%" alt="SYS.03 // LOADOUT"/></div>

<div align="center">

<table>
<tr>
<td align="right" valign="middle"><kbd>&nbsp;CORE&nbsp;</kbd></td>
<td><img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,postgres&theme=dark"/></td>
</tr>
<tr>
<td align="right" valign="middle"><kbd>&nbsp;WEB / OPS&nbsp;</kbd></td>
<td><img src="https://skillicons.dev/icons?i=nextjs,react,ts,git,linux,vercel&theme=dark"/></td>
</tr>
<tr>
<td align="right" valign="middle"><kbd>&nbsp;MODELS&nbsp;</kbd></td>
<td><img src="https://img.shields.io/badge/XGBOOST-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/LIGHTGBM-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/TRANSFORMERS-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/TCN-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/TFT-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/HMM-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/HUGGING%20FACE-B026FF?style=flat-square"/></td>
</tr>
<tr>
<td align="right" valign="middle"><kbd>&nbsp;SCIENCE&nbsp;</kbd></td>
<td><img src="https://img.shields.io/badge/NUMPY-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/PANDAS-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/SCIPY-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/XARRAY-B026FF?style=flat-square"/> <img src="https://img.shields.io/badge/LATEX-B026FF?style=flat-square"/></td>
</tr>
</table>

</div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,50:B026FF,100:05010D&height=3&section=header" width="100%"/></div>

<div align="center"><img src="https://capsule-render.vercel.app/api?type=rect&color=0:39FF14,12:05010D,88:05010D,100:39FF14&height=100&section=header&text=SYS.04%20%2F%2F%20TELEMETRY&fontSize=30&fontColor=39FF14&fontAlignY=52" width="100%" alt="SYS.04 // TELEMETRY"/></div>

<div align="center">

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=Aur1ety&show_icons=true&hide_border=true&include_all_commits=true&bg_color=05010D&title_color=00F0FF&text_color=C9C9D6&icon_color=FF2E97&ring_color=39FF14" alt="github stats"/>
<img width="49%" src="https://streak-stats.demolab.com?user=Aur1ety&hide_border=true&background=05010D&stroke=B026FF&ring=39FF14&fire=FF2E97&currStreakNum=00F0FF&sideNums=00F0FF&currStreakLabel=FF2E97&sideLabels=B026FF&dates=7A7A8C" alt="streak"/>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Aur1ety&theme=2077" width="98%" alt="profile details"/>

<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aur1ety&layout=compact&hide_border=true&langs_count=8&bg_color=05010D&title_color=00F0FF&text_color=C9C9D6" alt="top languages"/>
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Aur1ety&utcOffset=5.5&theme=2077" alt="productive time"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aur1ety&graph_type=bar&hide_border=true&bg_color=05010D&color=00F0FF&line=FF2E97&point=39FF14&title_color=39FF14&border_color=05010D&custom_title=COMMIT%20TELEMETRY" width="98%" alt="commit telemetry"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg"/>
  <img alt="snake" src="https://raw.githubusercontent.com/Aur1ety/Aur1ety/output/github-snake.svg" width="98%"/>
</picture>

</div>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:05010D,25:00F0FF,50:B026FF,75:FF2E97,100:05010D&height=3&section=header" width="100%"/>

<sub><code>[EOF] // connection closed by remote host — see you in orbit</code></sub>

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:00F0FF,50:B026FF,100:05010D&height=130&section=footer" width="100%"/>

</div>
