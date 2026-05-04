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

# 👋🏼 About Me

<span class='anchor' id='about-me'></span>

Hi, there! I'm Jingcheng Yang. You can also call me Jesse. I'm a first-year PhD student from Tsinghua University's Network and Information Security Lab (NISL), advised by [Prof. Jianjun Chen](https://jianjunchen.com/).

My research interests include Web Security, Protocol Security, and AI Security. I focus on systematically discovering protocol vulnerabilities and building automated vulnerability mining systems, as well as constructing agents to more efficiently uncover security flaws. Additionally, I am committed to building a more secure Internet infrastructure. I have submitted contributions to the IETF to supplement the JWT Best Current Practice (BCP), which were incorporated into the latest version of [draft-ietf-oauth-rfc8725bis](https://datatracker.ietf.org/doc/draft-ietf-oauth-rfc8725bis/).

Beyond research, I am also a CTF player in Tsinghua University's CTF team [Redbud](https://ctftime.org/team/20555/), specializing in the Web Security.


# 🔥 News
- **[Feb. 2026]** I’m so honoured to have been selected into the IETF Elite Talent Program (IETF“菁才计划”). See you in IETF 125 Shenzhen!

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2026</div><img src='images/NDSS26-JWT.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[Token Time Bomb: Evaluating JWT Implementations for Vulnerability Discovery](https://www.ndss-symposium.org/ndss-paper/token-time-bomb-evaluating-jwt-implementations-for-vulnerability-discovery/)

**Jingcheng Yang**, Enze Wang, Jianjun Chen, Qi Wang, Yuheng Zhang, Haixin Duan, Wei Xie, Baosheng Wang

**2026 Network and Distributed System Security (NDSS) Symposium**

<span class="paper-btn">[Paper](papers/NDSS26-JWT.pdf)</span><span class="paper-btn">[Code](https://github.com/JWTeemo/JWTeemo)</span><span class="paper-btn">[Slide](slides/NDSS26-JWT.pdf)</span><span class="paper-btn bibtex-toggle" onclick="this.closest('.paper-box').querySelector('.bibtex-box').toggleAttribute('open')">BibTeX</span>

</div>

<details class="bibtex-box">
<summary style="display:none"></summary>
<pre>@inproceedings{yang2025token,
  title     = {Token Time Bomb: Evaluating JWT Implementations for Vulnerability Discovery},
  author    = {Yang, Jingcheng and Wang, Enze and Chen, Jianjun and Wang, Qi and Zhang, Yuheng and Duan, Haixin and Xie, Wei and Wang, Baosheng},
  booktitle = {Proceedings of the 32nd Network and Distributed System Security Symposium (NDSS)},
  year      = {2025},
  publisher = {Internet Society},
  doi       = {10.14722/ndss.2025.24116},
  url       = {https://www.ndss-symposium.org/ndss-paper/token-time-bomb-evaluating-jwt-implementations-for-vulnerability-discovery/}
}</pre>
</details>

</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NDSS 2026</div><img src='images/NDSS26-SIP.png' alt="sym" width="80%"></div></div>
<div class='paper-box-text' markdown="1">

[SIPConfusion: Exploiting SIP Semantic Ambiguities for Caller ID and SMS Spoofing](https://www.ndss-symposium.org/ndss-paper/sipconfusion-exploiting-sip-semantic-ambiguities-for-caller-id-and-sms-spoofing/)

Qi Wang, Jianjun Chen, **Jingcheng Yang**, Jiahe Zhang, Yaru Yang, Haixin Duan

**2026 Network and Distributed System Security (NDSS) Symposium**

<span class="paper-btn">[Paper](papers/NDSS26-SIP.pdf)</span><span class="paper-btn">[Code](https://github.com/EkiXu/SIPChimera)</span><span class="paper-btn">[Slide](slides/NDSS26-SIP.pdf)</span><span class="paper-btn bibtex-toggle" onclick="this.closest('.paper-box').querySelector('.bibtex-box').toggleAttribute('open')">BibTeX</span>

</div>

<details class="bibtex-box">
<summary style="display:none"></summary>
<pre>@inproceedings{wang2026sipconfusion,
  title     = {SIPconfusion: Exploiting SIP Semantic Ambiguities for Caller ID and SMS Spoofing},
  author    = {Wang, Qi and Chen, Jianjun and Yang, Jingcheng and Zhang, Jiahe and Yang, Yaru and Duan, Haixin},
  booktitle = {Proceedings of the 33rd Network and Distributed System Security Symposium (NDSS)},
  year      = {2026},
  publisher = {Internet Society},
  url       = {https://www.ndss-symposium.org/ndss-paper/sipconfusion-exploiting-sip-semantic-ambiguities-for-caller-id-and-sms-spoofing/}
}</pre>
</details>

</div>


# 🎖 Honors and Awards

<table class="cv-table">
  <tr>
    <td class="cv-year">2025</td>
    <td>Outstanding Undergraduate Award, Sichuan Province (Top 3% in the Province).</td>
  </tr>
  <tr>
    <td class="cv-year">2023</td>
    <td>National Scholarship, Ministry of Education of China (Top 0.2% in China).</td>
  </tr>
</table>

# 📖 Educations

<table class="cv-table">
  <tr>
    <td class="cv-year">2025 –</td>
    <td>Ph.D., Network and Information Security Lab, Institute for Network Sciences and Cyberspace, Tsinghua University.</td>
  </tr>
  <tr>
    <td class="cv-year">2021 – 2025</td>
    <td>B.Eng. in Cyber Science and Engineering, Sichuan University.</td>
  </tr>
</table>

# 📋 Services

## External Reviewer

<table class="cv-table">
  <tr>
    <td class="cv-year">2026</td>
    <td>Network and Distributed System Security Symposium (NDSS)<br>ACM Asia Conference on Computer and Communications Security (AsiaCCS)</td>
  </tr>
  <tr>
    <td class="cv-year">2025</td>
    <td>ACM Conference on Computer and Communications Security (CCS)<br>IEEE European Symposium on Security and Privacy (EuroS&amp;P)<br>Network and Distributed System Security Symposium (NDSS)</td>
  </tr>
</table>

# 🏆 Selected Competition Awards

<table class="cv-table">
  <tr>
    <td class="cv-year">2025</td>
    <td><b>6th Place</b>, at the 1st Tencent Intelligent Penetration Testing Challenge.<br><b>5th</b>, at Black Hat MEA CTF Final with Redbud.<br><b>1st Prize</b>, at QiangWang Cup CTF with Redbud.<br><b>4th</b>, at XCTF Final with Redbud.</td>
  </tr>
  <tr>
    <td class="cv-year">2022</td>
    <td><b>Silver Medal</b>, at ACM-ICPC Asia Nanjing Regional Contest.</td>
  </tr>
</table>

# 🐛 StarBugs

I have discovered some vulnerabilities in popular OSS. A selective list of them is shown below.

| Project  | Vulnerability | Advisory |
| :------  | :------------ | :------- |
| [Anonymous GitHub](https://anonymous.4open.science) | XSS | [GHSA-g485-8j3v-p6x8](https://github.com/tdurieux/anonymous_github/security/advisories/GHSA-g485-8j3v-p6x8) |
| [Anything LLM](https://anythingllm.com/) | RCE | [CVE-2026-32626](https://github.com/Mintplex-Labs/anything-llm/security/advisories/GHSA-rrmw-2j6x-4mf2)
| [Shiro](https://shiro.apache.org/) | ACL Bypass | [CVE-2026-23903](https://lists.apache.org/thread/5jjf0hnjcol58z2m5y255c7scz1lnp8k)
| [Asterisk](https://www.asterisk.org/) | Identity forgery | [CVE-2025-47779](https://github.com/asterisk/asterisk/security/advisories/GHSA-2grh-7mhv-fcfw)
| [Jetty](https://jetty.org/) | Parsing Difference | [CVE-2025-11143](https://github.com/jetty/jetty.project/security/advisories/GHSA-wjpw-4j6x-6rwh)
| [GoLang/NET/URL](https://pkg.go.dev/net/url) | Parsing Difference | [CVE-2025-47912](https://github.com/advisories/GHSA-447v-2qg4-h8hc)
| [CXF](https://cxf.apache.org/) | DoS | [CVE-2024-32007](https://lists.apache.org/thread/stwrgsr1llb73nkl16klv9vjqgmmx633)
| [telemeter](https://github.com/openshift/telemeter) | Authentication Bypass | [CVE-2024-5037](https://nvd.nist.gov/vuln/detail/cve-2024-5037)
| [wildfly-elytron](https://wildfly-security.github.io/wildfly-elytron/) | Authentication Bypass | [CVE-2024-1233](https://access.redhat.com/security/cve/cve-2024-1233)
| [nimbus-jose-jwt](https://connect2id.com/products/nimbus-jose-jwt) | DoS | [CVE-2023-52428](https://github.com/advisories/GHSA-gvpg-vgmx-xg6w)