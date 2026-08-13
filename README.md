<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0E17,45:7B2FFF,100:00D9FF&height=200&section=header&text=Arinjay%20Pawar&fontSize=52&fontColor=FFFFFF&fontAlignY=34&animation=fadeIn&desc=AI%2FML%20Engineer%20%C2%B7%20Space%20Weather%20%26%20Medical%20Imaging&descAlignY=54&descSize=16" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=3200&pause=900&color=00D9FF&center=true&vCenter=true&width=720&lines=Forecasting+solar+flares+from+ISRO+Aditya-L1+telemetry;Beat+the+published+SOTA+on+the+SWAN-SF+benchmark;Time-series+deep+learning+on+real+satellite+data;AI%2FML+Head+%40+Google+Developer+Group" alt="Typing SVG"/>

<br/>

<img src="https://img.shields.io/badge/AI%2FML_Head-Google_Developer_Group-00D9FF?style=for-the-badge&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/B.Tech_AI%2FML-RAIT%2C_DY_Patil_'27-7B2FFF?style=for-the-badge&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/Navi_Mumbai-India-00FFA3?style=for-the-badge&labelColor=0B0E17"/>

</div>

---

I build end-to-end machine learning systems for **space weather forecasting** and **medical imaging** — the kind that run on real satellite telemetry and get evaluated on blind hold-outs, not just notebooks. Most of my work lives at the messy end: raw Level-1 instrument data, class imbalance at 1-in-50, and metrics that have to survive an audit.

Currently deep in solar physics with **ISRO's Aditya-L1** mission data, and shipping clinical ML on the side.

<br/>

## 🛰️ &nbsp;Space Weather

<table>
<tr>
<td width="50%" valign="top">

### Roentgen
**Solar flare nowcast + 24h forecast**

Mixture-of-experts on Aditya-L1 SoLEXS/HEL1OS X-ray telemetry. Two TCN nowcasters, a gradient-boosted forecaster, and an independently built flare catalogue.

`TSS 0.811 on SWAN-SF` — above the published attention-based SOTA (GCTAF 0.748), leakage-audited, protocol-matched

<sub>PyTorch · XGBoost · 15,550-event catalogue</sub>

</td>
<td width="50%" valign="top">

### Magnuson
**Geomagnetic storm onset forecasting**

1M+ 10-second MAG Level-2 observations from Aditya-L1 into a real-time onset pipeline. Benchmarked 7 sequential architectures.

`F1 0.919 · HSS 0.908 · FAR 0.0044`

<sub>PatchTransformer + HMM · Viterbi decoding</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### CME Detection
**Coronal mass ejection prediction**

Plasma-based predictor on SWIS Level-2 solar wind variables — bulk velocity, proton density, thermal temperature, ionic ratios.

<sub>TCN + TCAN · focal loss for extreme imbalance</sub>

</td>
<td width="50%" valign="top">

### Space Weather CLI
**Live interplanetary telemetry**

Async CLI aggregating NOAA and NASA DONKI feeds, built for headless systems with zero graphical dependencies.

<sub>Python · Rich · asyncio</sub>

</td>
</tr>
</table>

<br/>

## 🧬 &nbsp;Healthcare

<table>
<tr>
<td width="50%" valign="top">

### NeuroPharma &nbsp;<img src="https://img.shields.io/badge/live-00FFA3?style=flat-square&labelColor=0B0E17"/>
**Drug-drug interaction risk engine**

Cross-references patient prescription profiles against pharmacological datasets and generates automated hazard alerts for clinical review.

<sub>Next.js on Vercel · FastAPI + Docker on Hugging Face</sub>

</td>
<td width="50%" valign="top">

### Clinical Data QA
**Mammography & X-ray pipelines**

Annotated and validated large-scale imaging datasets for an AI-driven breast cancer detection system, building QA checks with medical and engineering teams.

<sub>Pulse Hitech · Data Analyst Intern</sub>

</td>
</tr>
</table>

<br/>

## ⚙️ &nbsp;Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,pytorch,sklearn,fastapi,docker,postgres&theme=dark" /><br/>
<img src="https://skillicons.dev/icons?i=nextjs,react,ts,git,linux,vercel&theme=dark" />

<br/><br/>

<img src="https://img.shields.io/badge/XGBoost-00D9FF?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/LightGBM-00D9FF?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/Transformers-7B2FFF?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/TCN-7B2FFF?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/NumPy-00FFA3?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/Pandas-00FFA3?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/xarray-00FFA3?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/SciPy-00FFA3?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/Hugging%20Face-FFB000?style=flat-square&labelColor=0B0E17"/>
<img src="https://img.shields.io/badge/LaTeX-FFB000?style=flat-square&labelColor=0B0E17"/>

</div>

<br/>

## 📊 &nbsp;Activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Aur1ety&show_icons=true&hide_border=true&bg_color=0B0E17&title_color=00D9FF&text_color=C9D1D9&icon_color=7B2FFF&include_all_commits=true"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Aur1ety&layout=compact&hide_border=true&bg_color=0B0E17&title_color=00D9FF&text_color=C9D1D9&langs_count=8"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Aur1ety&bg_color=0B0E17&color=00D9FF&line=7B2FFF&point=00FFA3&area=true&hide_border=true&custom_title=Contribution%20Graph" width="98%"/>

</div>

<br/>

## 🔭 &nbsp;Currently

```yaml
building:   Eos — fusing X-ray nowcasting with magnetogram-based 24h forecasting
writing:    a paper on the SWAN-SF result + an independent solar flare catalogue
curious:    neuromorphic computing, LLM agent architectures, MLOps at scale
open to:    AI/ML roles in space tech, scientific computing, and clinical ML
```

<sub>Off the clock: anime, games, and being thoroughly outranked by my cats.</sub>

<br/>

<div align="center">

### Reach me

<a href="https://linkedin.com/in/arinjaypawar"><img src="https://img.shields.io/badge/LinkedIn-0B0E17?style=for-the-badge&logo=linkedin&logoColor=00D9FF"/></a>
<a href="mailto:pawararinjay06@gmail.com"><img src="https://img.shields.io/badge/Email-0B0E17?style=for-the-badge&logo=gmail&logoColor=00FFA3"/></a>
<a href="https://github.com/Aur1ety"><img src="https://img.shields.io/badge/GitHub-0B0E17?style=for-the-badge&logo=github&logoColor=7B2FFF"/></a>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00D9FF,55:7B2FFF,100:0B0E17&height=110&section=footer"/>

</div>
