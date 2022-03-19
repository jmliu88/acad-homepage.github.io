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
I'm a Stuff Software Engineer at Computer Vision Technology Department(VIS), Baidu. 

My current research interests forcus in using GANs to solve industrial problems, including face/head editing and font generation. 


# 🔥 News
- *2022.03*: &nbsp;🎉🎉 Two papers accepted to CVPR2022.
- *2021.08*: &nbsp;🎉🎉 I, as the team leader, won the first place out of 200+ teams in 25-th Hackathon of Baidu. 
- *2019.08*: &nbsp;🎉🎉 One paper accepted to ICCV2019.
- *2019.07*: &nbsp;🎉🎉 One paper accepted to ACM MM2019.

# 📝 Publications(* equal contribution, † corresponding)

<div class='paper-box'><div class='paper-box-image'><img src='images/500x300.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

[Few-Shot Head Swapping in the Wild], CVPR2022, Changyong Shu\*, Hang Zhou\*, Hemao Wu, **Jiaming Liu†**, Zhibin Hong, Changxing Ding, Junyu Han, Jingtuo Liu, Errui Ding, Jingdong Wang

First attemp to swap heads between source and target images with 10-ish images given.

</div>
  
</div>

<div class='paper-box'><div class='paper-box-image'><img src='images/500x300.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="2">

[Few-Shot Font Generation by Learning Fine-Grained Local Styles], CVPR2022, Licheng Tang*, Yiyang Cai*, **Jiaming Liu†**, Zhibin Hong, Mingming Gong, Minhu Fan, Junyu Han, Jingtuo Liu, Errui Ding, Jingdong Wang

Improving performance of few shot font generation by introducing cross attention. 
</div>
</div>


# 🎖 Honors and Awards
- *2021.8* First place of the 25th Hackathon of Baidu. 

# 📖 Educations
- *2010.06 - 2017.04*, Ph.D., Tongji University, Shanghai.
- *2014.09 - 2015.09*, Visiting Scholar, Columbia University, New York City. 

{% # 💬 Invited Talks %}
{% - *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. %}
{% - *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) %}

{% # 💻 Internships %}
{% - *2019.05 - 2020.02*, [Lorem](https://github.com/), China. %}
