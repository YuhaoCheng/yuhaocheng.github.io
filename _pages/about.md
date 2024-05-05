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

My name is Yuhao Cheng, and I'm currently a Researcher at Lenovo Research, before that I got the Master's and Bachelor's degree at Beijing University of Posts and Telecommunications and got the Bachelor's degree at Queen Mary University of London. My research interests are in Artificial Intelligence, Computer Vision, and Computer Graphics.

[//]: # (I have published several papers AI conferences with total <a href='https://scholar.google.com/citations?user=Uki0KqEAAAAJ&hl'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> &#40;You can also use google scholar badge <a href='https://scholar.google.com/citations?user=Uki0KqEAAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>&#41;.)

# 🔥 News
- *2024.04*: &nbsp;🎉🎉 ConsistentID's paper is on arXiv.

[//]: # (- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2024</div><img src='images/consistent_id.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ConsistentID: Portrait Generation with Multimodal Fine-Grained Identity Preserving](https://arxiv.org/pdf/2404.16771)

[//]: # (**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun)

[**Project Homepage**](https://ssugarwh.github.io/consistentid.github.io/)

[//]: # (- Diffusion-based technologies have made significant strides, particularly in personalized and customized facialgeneration. However, existing methods face challenges in achieving high-fidelity and detailed identity &#40;ID&#41;consistency, primarily due to insufficient fine-grained control over facial areas and the lack of a comprehensive strategy for ID preservation by fully considering intricate facial details and the overall face. To address these limitations, we introduce ConsistentID, an innovative method crafted for diverseidentity-preserving portrait generation under fine-grained multimodal facial prompts, utilizing only a single reference image. ConsistentID comprises two key components: a multimodal facial prompt generator that combines facial features, corresponding facial descriptions and the overall facial context to enhance precision in facial details, and an ID-preservation network optimized through the facial attention localization strategy, aimed at preserving ID consistency in facial regions. Together, these components significantly enhance the accuracy of ID preservation by introducing fine-grained multimodal ID information from facial regions. To facilitate training of ConsistentID, we present a fine-grained portrait dataset, FGID, with over 500,000 facial images, offering greater diversity and comprehensiveness than existing public facial datasets. % such as LAION-Face, CelebA, FFHQ, and SFHQ. Experimental results substantiate that our ConsistentID achieves exceptional precision and diversity in personalized facial generation, surpassing existing methods in the MyStyle dataset. Furthermore, while ConsistentID introduces more multimodal ID information, it maintains a fast inference speed during generation. )
</div>
</div>

- Pose-guided tracking-by-detection: Robust multi-person pose tracking. Bao Qian, Wu Liu, **Yuhao Cheng**, Boyan Zhou, and Tao Mei. IEEE Transactions on Multimedia 23 (2020): 161-175.
- Please refer the Google Scholar for more papers. <a href='https://scholar.google.com/citations?user=Uki0KqEAAAAJ&hl'>Google Scholar</a>

# 🎖 Honors and Awards
- *2021* Distinguished Master-Degree Dissertation Award, Beijing Univ. of Posts and Telecommunications. 
- *2021* Outstanding Graduate Award (1%), Beijing City. 
- *2021* National Scholarship (1%), Ministry of Education, China
- *2018* Distinguished Bachelor-Degree Dissertation Award, Beijing Univ. of Posts and Telecommunications
- *2018* Distinguished Bachelor-Degree Dissertation Award, Queen Mary Univ. of London
- *2018* Undergraduate Collage Prize, Queen Mary Univ. of London

# 📖 Educations
- *2018.09 - 2021.07*, M.S. in Computer Technology, Beijing University of Posts and Telecommunications, Computer Science School. Major in the Artificial Intelligence and Computer Vision. 
- *2014.09 - 2018.06*, B.Eng. in Internet of Things Engineering, Beijing University of Posts and Telecommunications. International School. Major in Internet of Things Engineering.
- *2014.09 - 2018.06*, B.Sc. (Engineering) with First-Class Honor, Queen Mary University of London. 

[//]: # (# 💬 Invited Talks)

[//]: # (- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. )

[//]: # (- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]]&#40;https://github.com/&#41;)

# 💻 Work Experience
- *2017.06 - 2021.05*, **Algorithm Intern**, JD, China.
- *2021.07 - Now*, **Researcher**, [Lenovo Research](https://research.lenovo.com/webapp/view/index.html), China