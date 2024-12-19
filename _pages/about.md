---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I received my B.S, M.S degree (with honors) in Electrical Engineering and Automation, Electrical and Control Engineering from Shanghai Ocean University and Fudan University, China, in 2019 and 2022, respectively. I’m current pursing my Ph.D. degree on the interface of energy storage and power systems, electrochemistry and aritificail intelligence (AI), sponsored by a joint training program from Tsinghua University and UC Berkeley. I work with Prof. [Xuan Zhang](https://scholar.google.com/citations?hl=zh-CN&user=B-I9FY8AAAAJ&view_op=list_works&sortby=pubdate), [Guangmin Zhou](https://scholar.google.com/citations?user=smzbtMcAAAAJ&hl=zh-CN), [Scott Moura](https://scholar.google.com/citations?user=5sLngc0AAAAJ&hl=zh-CN) and [Hongbin Sun](https://www.eea.tsinghua.edu.cn/en/faculties/shb.htm) with a balanced focus on real wolrd applicaiton and theoretical depth. I was also a research intern in Tencent AI Lab and Microsoft Research Asia (MSRA). \| [\[CV\]](https://drive.google.com/file/d/1nTQgSXYFpNPcvuclv0ixZGA5rLxwBKjr/view?usp=drive_link) (updated 15 Dec 2024) 

My research interest includes **AI**-enabled **applications** for **sustainable use of retired electric vehicle batteries** (reuse and recycling), e.g., power grid energy storage and strategical material recycling.
Special attention is paid to state estimation and aging pattern diagnosis under **limited and heterogeneous data availability**. I also work closely with material scientist on AI for Science (**AI4S**) topics.

I have pubulished serveral research papers on **Nature Catalysis**, **Nature Communications**, **Energy and Environmental Science**, **ACS Energy Letters**, **Journal of Power Sources** and **Applied Energy**, etc. <a href='https://scholar.google.com/citations?hl=zh-CN&user=MHzCCogAAAAJ&view_op=list_works'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 🔥 News
- *2024.12*: &nbsp;🪫♻️🔋 I am attending [The 3rd Battery Sustainability Workshop 2024](https://www.batterysustain.center/2024-workshop) initiated by Prof. [Martin Bazant](https://scholar.google.com.hk/citations?user=rcGnOdYAAAAJ&hl=en) and others at MIT.  \| [\[pic\]](https://drive.google.com/file/d/14xUQYq3QcvdpD6LN1pStaofJfEMAfdLi/view?usp=drive_link)
- *2024.11*: &nbsp;🎉🎉🎉 Our project **Large Scale Rapid Internal State Estimation Technology and Applications for Sustainable Utilization of Retired Batteries** are granted the **first prize (rank 1st)** in the 3rd China Postgraduate “Carbon Peak and Carbon Neutrality” Innovation and Creativity Competition, hosted by China Postgraduate Innovation and Practice Competition Series ([CPIPC](https://cpipc.acge.org.cn/)).  \| [\[link\]](https://mp.weixin.qq.com/s/ZsflAzA3QusH4liDsUu-5g).
**Special congratulations to Prof. Xuan Zhang for the Excellent Supervisor Award!** \| [\[pic\]](https://drive.google.com/file/d/1zrMu6KMKgSWA270YqsBsjzbb8QS60vU9/view?usp=drive_link)
- *2024.09*: &nbsp;🎉🎉🎉 I am visiting Energy, Controls and Applications Lab (eCAL) at UC Berkeley, working with Prof. [Scott Moura](https://scholar.google.com/citations?user=5sLngc0AAAAJ&hl=zh-CN). 

# 📝 Publications 
J = Journal, S = Submitted

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">_Nat Commun_ **15**, 10154 (2024)</div><img src='images/Nat Commun 15, 10154 (2024).png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generative learning assisted state-of-health estimation for sustainable battery recycling with random retirement conditions](https://www.nature.com/articles/s41467-024-54454-0)

**Tao, S.**, Ma, R., Zhao, Z. et al.

[**Dataset**](https://github.com/terencetaothucb/Pulse-Voltage-Response-Generation) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
We open source the world-largest retired battery dataset using pulse test measurements:
- 464 retired lithium-ion batteries;
- SOH from 40% to 95% (with label);
- **The battery heterogeneities**
- 3 cathode types;
- 6 historical usages;
- 3 physical formats;
- 6 capacity designs;
- **The pulse test parameters**
- 10 pulse width (30-5000ms);
- 10 pulse magnitude ±(0.5-2.5C);
- 10 SOC levels (5-50%);
</div>
</div>

- [J15] **Tao, S.**, Ma, R., Zhao, Z. et al. Generative learning assisted state-of-health estimation for sustainable battery recycling with random retirement conditions. _Nature Communications_ **15**, 10154 (2024). Click to [view](https://www.nature.com/articles/s41467-024-54454-0). 
- [J14] Ma, R., **Tao, S.** et al. Pathway decisions for reuse and recycling of retired lithium-ion batteries considering economic and environmental functions. _Nature Communications_ **15**, 7641 (2024). Click to [view](https://www.nature.com/articles/s41467-024-52030-0).
- [J13] **Tao, S.** et al. Rapid and sustainable battery health diagnosis for recycling pretreatment using fast pulse test and random forest machine learning. _Journal of Power Sources_ **597**, 234156 (2024). Click to [view](https://doi.org/10.1016/j.jpowsour.2024.234156).
- [J12] **Tao, S.**, Liu, H., Sun, C. et al. Collaborative and privacy-preserving retired battery sorting for profitable direct recycling via federated machine learning. _Nature Communications_ **14**, 8032 (2023). Click to [view](https://www.nature.com/articles/s41467-023-43883-y), selected as **[Editor’s highlight](https://www.nature.com/collections/bchahibchi) paper** and the **[Focus](https://www.nature.com/collections/dmmhtcypsc) paper**.
- [J11] **Tao, S.**, Sun, C., Fu, S. et al. Battery Cross-Operation-Condition Lifetime Prediction via Interpretable Feature Engineering Assisted Adaptive Machine Learning. _ACS Energy Letters_ **8**, 3269-3279 (2023). Click to [view](https://pubs.acs.org/doi/10.1021/acsenergylett.3c01012).
- [J10] **Tao, S.** et al. The proactive maintenance for the irreversible sulfation in lead-based energy storage systems with a novel resonance method. _Journal of Energy Storage_ **42**, 103093 (2021). Click to [view](https://www.sciencedirect.com/science/article/abs/pii/S2352152X21007982).
- [J9] Fu, S, **Tao, S.** et al. Data-driven capacity estimation for lithium-ion batteries with feature matching based transfer learning method. _Applied Energy_ **353**, 121991 (2024). Click to [view](https://www.sciencedirect.com/science/article/abs/pii/S0306261923013557).
- [J8] Han, Z., Gao, R., Wang, T., **Tao, S.** et al. Machine-learning-assisted design of a binary descriptor to decipher electronic and structural effects on sulfur reduction kinetics. _Nature Catalysis_ **6**, 1073-1086 (2023). Click to [view](https://www.nature.com/articles/s41929-023-01041-z). **Selected as cover paper in Nature Catalysis**.
- [J7] **Tao, S.** et al. Behavioral Economics Optimized Renewable Power Grid: A Case Study of Household Energy Storage. _Energies_ **14**, 4154 (2021). Click to [view](https://www.mdpi.com/1996-1073/14/14/4154).
- [J6] Talihati, B., **Tao, S.** et al. Energy storage sharing in residential communities with controllable loads for enhanced operational efficiency and profitability. _Applied Energy_ **373**, 123880 (2024). Click to [view](https://www.sciencedirect.com/science/article/abs/pii/S0306261924012637).
- [J5] Liu, X., **Tao, S.** et al. Binary multi-frequency signal for accurate and rapid electrochemical impedance spectroscopy acquisition in lithium-ion batteries. _Applied Energy_ **364**, 123221 (2024). Click to [view](https://www.sciencedirect.com/science/article/abs/pii/S0306261924006044).
- [J4] He, K. , **Tao, S.** et al. A Novel Quick Screening Method for the Second Usage of Parallel-connected Lithium-ion Cells Based on the Current Distribution. _Journal of The Electrochemical Society_ **170**, 030514 (2023). Click to [view](https://iopscience.iop.org/article/10.1149/1945-7111/acbf7e).
- [J3] Li, T. , **Tao, S.** et al. V2G Multi-Objective Dispatching Optimization Strategy Based on User Behavior Model. _Frontiers in Energy Research_ **9** (2021). Click to [view](https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2021.739527/full)
- [J2] Hu, M. , **Tao, S.** et al. Non-Intrusive Load Monitoring for Residential Appliances with Ultra-Sparse Sample and Real-Time Computation. _Sensors_ **21**, 5366 (2021). Click to [view](https://www.mdpi.com/1424-8220/21/16/5366)
- [J1] T. Cao, Y. Xu, G. Liu, **Tao, S.** et al. Feature-enhanced deep learning method for electric vehicle charging demand probabilistic forecasting of charging station. _Applied Energy_ **371**, 123751 (2024). Click to [view](https://www.sciencedirect.com/science/article/abs/pii/S0306261924011346).
- [S6] **Tao, S.**, Zhao, Z., Zhang, M., et al., Non-destructive degradation pattern decoupling for early battery trajectory prediction via physics-informed learning. Submitted to _Energy and Environmental Science_, 1st revision.
- [S5] **Tao, S.**, et al., Immediate remaining capacity estimation of heterogeneous retired lithium-ion batteries via deep generative transfer learning. 
- [S4] **Tao, S.**, et al., The role of hysteresis effect in battery energy storage systems on supporting grid frequency stability. Power and Energy Society General Meeting (PESGM)
- [S3] **Tao, S.**, et al., Artificial intelligence for sustainable battery reuse, recycling, and remanufacturing. 
- [S2] Piao, Z., Han, Z., **Tao, S.**, et al., Deciphering failure trajectories in lithium metal anodes through electrochemical curve fingerprint. 
- [S1] Han, Z., **Tao, S.**, Jia, Y., et al., Discovering catalysis principles by crowd intelligence. 

# 🎖 Honors and Awards
- *2024.12*: &nbsp;🎉🎉🎉 I am granted the [Wang Dazhong](https://en.wikipedia.org/wiki/Wang_Dazhong) Scholarship [王大中奖学金] (0.01%).
- *2024.11*: &nbsp;🎉🎉🎉 My leading project **Large Scale Rapid Internal State Estimation Technology and Applications for Sustainable Utilization of Retired Batteries** are granted the **first prize (rank 1st)** in the 3rd China Postgraduate “Carbon Peak and Carbon Neutrality” Innovation and Creativity Competition, hosted by [CPIPC](https://cpipc.acge.org.cn/).
- *2024.11*: &nbsp;🎉🎉🎉 I am nominated the Tsinghua Presidential Scholarship [清华大学特等奖学金] (0.01%, finalist).
- *2024.10*: &nbsp;🎉🎉🎉 I am granted the National Scholarship (Doctoral Students) (1%, rank first among all candidates) [国家奖学金(博士研究生)] (0.01%). 
- *2024.08*: &nbsp;🎉🎉🎉 I am granted the Future Leaders Scholarship (Excellent Scholarship), Tsinghua Berkeley Shenzhen Institute (TBSI).

# 📖 Educations
- *2022.08 - 2025.6 (expected)*, Tsinghua University, Beijing, China
Supervised by Prof. Guangmin Zhou and Xuan Zhang
Ph.D. candidate in Electrical Engineering **GPA: 3.9/4.0**
- *2024.09 - now*, UC Berkeley, CA, USA
Supervised by Prof. Scott J. Moura
Visiting Research Scholar in Energy, Controls and Applications Lab (eCAL)
- *2019.09 - 2022.6*, Fudan University, Shanghai, China
Supervised by Prof. Yaojie Sun
M.S. Electrical and Control Engineering(with honors) **GPA: 3.85/4.0** (**1/64**)
- *2015.09 - 2019.6*, Shanghai Ocean University, Shanghai, China
Supervised by Prof. Yue Zhou and Chen Yang
B.S. Electrical and Control Engineering (with honors) **GPA: 3.95/4.0** (**1/62**)

# 💬 Invited Talks
- *2023.11*, **Tao, S.**, Generating the voltage response of retired batteries for data augmentation from pulse test using variational autoencoder, **Best Paper**, and **Best Oral** presentation at New Energy Science and Electrification of Transportation International Conference, Elsevier, eTransportation.
- *2023.10*, **Tao, S.**, Collaborative and privacy-preserving retired battery sorting for profitable direct recycling via federated machine learning, **Best Paper**, and **Best Oral** presentation at closing ceremony of International Carbon Neutrality Forum for Doctoral Students, Tsinghua University. 

# 💻 Internships
- *2024.05 - 2024.11*, **Microsoft Research Asia Research (MSRA)** Intern in Innovation Center. Topic: First principle based battery data generation and foundational model. Working with Bian Jiang Ph.D., Zhen Shun Ph.D., and Xiaofan Gui.
- *2023.09 - 2024.05*, **Tencent AI Lab Research Intern in Scientific Large Model Group**. Topic: Generative modeling for battery state and health estimations. Working with Rong Yu Ph.D. and Xu Tingyang Ph.D.
