---
permalink: /
title: "Xinyi Zhuang (庄新一)"
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

# Xinyi Zhuang (庄新一)
Hi, I'm a third-year direct-track Ph.D. candidate at the School of Information Science and Technology, Harbin Institute of Technology, Shenzhen.
I received my B.Eng. degree in Communication Engineering from Northwestern Polytechnical University (NWPU) in 2023.
Now, I am pursuing my Ph.D. degree in Information and Communication Engineering at Harbin Institute of Technology, Shenzhen (HITsz), under the supervision of Prof. [Lin Gao](https://scholar.google.com/citations?user=41wcJi4AAAAJ&hl=en).

My research interests include Networks for Large AI Models and AI for Networking.

My Google Scholar citations: <a href='https://scholar.google.com/citations?user=IkhGGKUAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

Feel free to contact me for communication and collaboration: <u>zhuangxinyi@stu.hit.edu.cn</u>.

# 1 News
- *2025.09:* One first-author paper has been submitted to IEEE Transactions on Mobile Computing (Major Revision).
- *2026.07:* Two collaborative paper has been submitted to IEEE Transactions on Mobile Computing.


# 2 Education and Experience
- *2019.09 - 2023.05*, Bachelor of Engineering, Communication Engineering, Northwestern Polytechnical University (NWPU).
- *2023.09 - Now*, Doctor of Philosophy Student, Information and Communication Engineering, Harbin Institute of Technology, Shenzhen (HITsz).
- *2026.01 - Now*, AI Algorithm Engineer (Research Intern), Data Systems Department, ZTE Corporation.


<!-- color: https://colorkit.co/palette/1abc9c-16a085-2ecc71-27ae60-3498db-2980b9-9b59b6-8e44ad-34495e-2c3e50-f1c40f-f39c12-e67e22-d35400-e74c3c-c0392b-ecf0f1-bdc3c7-95a5a6-7f8c8d/ -->
# 3 Publications

<style>
  .extra-pub { display: none; }
  .extra-pub.show { display: block; }
  .pub-toggle-btn {
    display: inline-block;
    margin: 0.2em 0 1em 0;
    padding: 5px 16px;
    font-size: 13px;
    font-family: "Times New Roman", Times, serif;
    font-weight: bold;
    color: #fff;
    background-color: #2980b9;
    border: none;
    border-radius: 4px;
    cursor: pointer;
  }
  .pub-toggle-btn:hover { background-color: #1f6391; }

  /* ---- Wenchao-Xu-style publication cards ---- */
  .paper-card {
    display: flex;
    align-items: flex-start;
    padding: 0.9em 0;
    border-bottom: 1px solid #efefef;
  }
  .paper-badge {
    flex: 0 0 auto;
    width: 104px;
    margin-right: 16px;
    padding: 5px 4px;
    color: #fff;
    font-size: 12px;
    font-weight: bold;
    text-align: center;
    border-radius: 4px;
  }
  .paper-content { flex: 1; }
  .paper-content p { margin: 0 0 0.5em 0; text-align: left; line-height: 1.5; }
  .pub-title { font-weight: bold; }
  .pub-venue { font-style: italic; }
  .pub-tags { font-size: 0.9em; color: #7f8c8d; }
  .pub-tags strong { color: #c0392b; }
  .abs-btn, .link-btn {
    display: inline-block;
    padding: 2px 12px;
    margin: 2px 6px 2px 0;
    font-size: 12px;
    font-family: "Times New Roman", Times, serif;
    line-height: 1.6;
    border: 1px solid #2980b9;
    border-radius: 4px;
    background: #fff;
    color: #2980b9 !important;
    cursor: pointer;
    text-decoration: none !important;
  }
  .abs-btn:hover, .link-btn:hover { background: #2980b9; color: #fff !important; }
  .abstract {
    margin-top: 8px;
    padding: 10px 12px;
    border: 1px dashed #b0b0b0;
    border-radius: 4px;
    background: #fafafa;
    font-size: 0.92em;
    text-align: justify;
  }
  .hidden { display: none; }
</style>

<sup>&dagger;</sup>Co-First Author &nbsp;&nbsp; \*Corresponding Author. By default, only first-author / co-first / corresponding-author papers are shown. Click the button to expand all publications on this page.

<button id="pubToggleBtn" class="pub-toggle-btn" onclick="toggleAllPubs()">Show All Publications &#9660;</button>

#### Journal/Magazine Papers:
Summary: 1 out of 3 papers are published in CCF A journals, 2 out of 3 papers are published in SCI Q1 journals, and 3 out of 3 papers are published in JCR Q1 journals.

<div class="paper-card">
<div class="paper-badge" style="background-color: #f39c12;">COMMAG</div>
<div class="paper-content" markdown="1">

<span class="pub-title">When AIGC meets MEC: A novel diffusion-based collaborative inference paradigm</span><br>
H. Wu<sup>&dagger;</sup>, **Xinyi Zhuang**<sup>&dagger;</sup>, J. Wu, L. Gao, D. Niyato, and T.-T. Chan<br>
<span class="pub-venue">IEEE Communications Magazine (IEEE Commun. Mag.), Early Access</span><br>
<span class="pub-tags">**Co-First Author** · SCI Q2 · JCR Q1</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/11503883" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

<div class="extra-pub">

<div class="paper-card">
<div class="paper-badge" style="background-color: #c5ca30;">IoTJ</div>
<div class="paper-content" markdown="1">

<span class="pub-title">Joint communication and computation scheduling for MEC-enabled AIGC services: A game-theoretic stochastic learning approach</span><br>
H. Liu, **Xinyi Zhuang**, J. Wu, Y. Luo, B. Cao, and L. Gao<br>
<span class="pub-venue">IEEE Internet of Things Journal (IEEE Internet Things J.), Early Access</span><br>
<span class="pub-tags">**Collaborative Author** · CCF C · SCI Q1 · JCR Q1</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://arxiv.org/abs/2605.22277" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

<div class="paper-card">
<div class="paper-badge" style="background-color: #e74c3c;">TMC</div>
<div class="paper-content" markdown="1">

<span class="pub-title">QoE-aware offloading and resource allocation for MEC-empowered AIGC services</span><br>
J. Wu, **Xinyi Zhuang**, M. Tang, and L. Gao<br>
<span class="pub-venue">IEEE Transactions on Mobile Computing (IEEE Trans. Mobile Comput.), vol. 24, no. 10, pp. 9664-9682, Oct. 2025</span><br>
<span class="pub-tags">**Collaborative Author** · CCF A · SCI Q1 · JCR Q1</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/10972066" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

</div>

#### Conference Papers:
Summary: 1 out of 4 papers are published in CCF A conference proceedings, and 2 out of 4 papers are published in CCF B/C conference proceedings.

<div class="paper-card">
<div class="paper-badge" style="background-color: #27ae60;">GLOBECOM</div>
<div class="paper-content" markdown="1">

<span class="pub-title">Joint optimization of offloading, scheduling, and inferencing for MEC-empowered AIGC services</span><br>
X. Guo, C. Zhang, X. Chen, D. Zhao, **Xinyi Zhuang**\*, J. Wu\*, H. Liu, and L. Gao\*<br>
<span class="pub-venue">Proc. IEEE Global Communications Conference (GLOBECOM), Taipei, Taiwan, Dec. 2025, pp. 823-828</span><br>
<span class="pub-tags">**Corresponding Author** · CCF C</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/11431795" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

<div class="paper-card">
<div class="paper-badge" style="background-color: #27ae60;">ICC</div>
<div class="paper-content" markdown="1">

<span class="pub-title">QoS-driven hybrid inference scheme for generative diffusion models in MEC-enabled AI-generated content networks</span><br>
**Xinyi Zhuang**, J. Wu, H. Wu, M. Tang, and L. Gao<br>
<span class="pub-venue">Proc. IEEE International Conference on Communications (ICC), Montreal, QC, Canada, Jun. 2025, pp. 1151-1156</span><br>
<span class="pub-tags">**First Author** · CCF C</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/11161497" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

<div class="paper-card">
<div class="paper-badge" style="background-color: #e74c3c;">INFOCOM</div>
<div class="paper-content" markdown="1">

<span class="pub-title">Joint optimization of model inferencing and task offloading for MEC-empowered large vision model services</span><br>
**Xinyi Zhuang**, J. Wu, H. Wu, T. Zhang, and L. Gao<br>
<span class="pub-venue">Proc. IEEE International Conference on Computer Communications (INFOCOM), London, United Kingdom, May 2025</span><br>
<span class="pub-tags">**First Author** · CCF A</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/11044689" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

<div class="extra-pub">

<div class="paper-card">
<div class="paper-badge" style="background-color: #3498db;">WiOpt</div>
<div class="paper-content" markdown="1">

<span class="pub-title">Joint communication and computation scheduling for MEC-enabled AIGC services based on generative diffusion model</span><br>
H. Liu, J. Wu, **Xinyi Zhuang**, H. Wu, and L. Gao<br>
<span class="pub-venue">Proc. International Symposium on Modeling and Optimization in Mobile, Ad Hoc, and Wireless Networks (WiOpt), Seoul, Republic of Korea, Oct. 2024, pp. 345-352</span><br>
<span class="pub-tags">**Collaborative Author**</span>

<button class="abs-btn">Abstract</button> <a class="link-btn" href="https://ieeexplore.ieee.org/document/10778362" target="_blank">Paper</a>

<div class="abstract hidden">Abstract: 请在此填写本文摘要 / Fill in the abstract of this paper here.</div>

</div>
</div>

</div>

<script>
function toggleAllPubs() {
  var extras = document.getElementsByClassName('extra-pub');
  var btn = document.getElementById('pubToggleBtn');
  var willShow = !(extras.length > 0 && extras[0].classList.contains('show'));
  for (var i = 0; i < extras.length; i++) {
    if (willShow) { extras[i].classList.add('show'); }
    else { extras[i].classList.remove('show'); }
  }
  btn.innerHTML = willShow ? 'Show Selected Only &#9650;' : 'Show All Publications &#9660;';
}
// Toggle a paper's abstract when its Abstract button is clicked
document.addEventListener('click', function (e) {
  if (e.target && e.target.classList && e.target.classList.contains('abs-btn')) {
    var card = e.target.closest('.paper-content');
    if (card) {
      var abs = card.querySelector('.abstract');
      if (abs) { abs.classList.toggle('hidden'); }
    }
  }
});
</script>


# 4 Honors and Awards
- Outstanding Graduation Thesis (5%), Northwestern Polytechnical University, 2023.
- Outstanding Graduate (10%), Northwestern Polytechnical University, 2023.
- Soaring Scholarship (1%), Beijing International Trust Co., Ltd, 2022.


# 5 Talks
- Advances and reflections on enhanced inference techniques for generative diffusion models (in collaboration with my Ph.D. supervisor Prof. Lin Gao), International Conference on Intelligent Networks and Communication Systems, 2025.
- The theory and application of diffusion models: From fundamentals to autonomous path planning, AI4Energy Group, Shenzhen Loop Area Institute, 2025.
- Multi-task hybrid inference optimization for large vision models (in collaboration with my Ph.D. supervisor Prof. Lin Gao), International Conference on Intelligent Networks and Communication Systems, 2024.


# 6 Services
- Technical Reviewer for Conferences: IEEE Conference on Vehicular Technology (VTC)

