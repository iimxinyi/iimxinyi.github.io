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
    margin: 0 0 0 10px;
    padding: 2px 13px;
    vertical-align: middle;
    font-size: 12px;
    font-weight: normal;
    color: #7f8c8d;
    background: transparent;
    border: 1px solid #d5d5d5;
    border-radius: 14px;
    cursor: pointer;
    transition: all 0.15s ease;
  }
  .pub-toggle-btn:hover { background: #f4f4f4; color: #2c3e50; border-color: #bbb; }

  /* ---- publication cards ---- */
  .paper-card {
    display: flex;
    align-items: flex-start;
    padding: 0.5em 0;
  }
  .paper-badge {
    flex: 0 0 auto;
    width: 76px;
    margin-right: 22px;
    padding: 3px 5px;
    color: #fff;
    font-size: 11px;
    font-weight: normal;
    letter-spacing: 0.02em;
    text-align: center;
    border-radius: 4px;
  }
  .paper-content { flex: 1; }
  .paper-content p { margin: 0 0 0.4em 0; text-align: left; line-height: 1.4; }
  .pub-title { font-weight: bold; }
  .pub-venue { font-style: normal; }
  .pub-tags { font-size: 0.9em; color: #7f8c8d; }
  .pub-rank { color: #1a1a1a; font-weight: bold; }
  .abs-btn, .link-btn {
    display: inline-block;
    padding: 2px 12px;
    margin: 2px 6px 2px 0;
    font-size: 12px;
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
  .year-divider {
    text-align: right;
    font-size: 0.8em;
    font-weight: bold;
    color: #c4c4c4;
    letter-spacing: 0.04em;
    margin: 1.3em 0 0.2em 0;
    padding-top: 0.15em;
    border-top: 1px solid #ececec;
  }
</style>

Summary: Among the journal papers, 1/3 are in CCF A journals, 2/3 in SCI Q1, and 3/3 in JCR Q1; among the conference papers, 1/4 are in CCF A proceedings and 2/4 in CCF B/C. <button id="pubToggleBtn" class="pub-toggle-btn" onclick="toggleAllPubs()">Show All Publications &#9660;</button>

{% include publications.html %}

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

