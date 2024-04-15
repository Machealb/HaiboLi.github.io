---
layout: about
title: About
permalink: /
subtitle: <a href='https://ms.unimelb.edu.au/'> School of Mathematics and Statistics, The University of Melbourne </a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p> G82, Peter Hall Building </p>
    <p> Swanston Street </p>
    <p> Melbourne, Victoria 3010 Australia </p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

Welcome to my website! I am Haibo Li, working on applied and computational mathematics. I am currently a Research Fellow in [School of Mathematics and Statistics](https://ms.unimelb.edu.au) at [The University of Melbourne](https://www.unimelb.edu.au/). I completed my Ph.D. in Mathematics at [Tsinghua Univeristy](https://www.tsinghua.edu.cn/en/), China, in 2021. My full CV can be found <a href="/cv_haibo.pdf">here</a>.

My research centers around utilizing mathematical modeling and computational techniques to address challenging problems arising from scientific computing, matrix computation and data science. I am always looking to collaborate with researchers from mathematics, statistics, artificial intelligence, high performance computing and etc. 

If you want to work with me or discuss potential collaborations, please reach out to me by <u>haibo.li@unimelb.edu.au</u> or my personal email <u>haibolee1729@gmail.com</u>.
 
### Research Interests
My research interests include:
- Inverse problems, regularization
- Numerical linear algebra, Matrix analysis and computation
- Scientific machine learning, kernel method
  
Many other topics are also related to my research, such as numerical optimization, numerical PDEs, and statistical learning.

### Open Source
Some codes related to my research can be found in my [Github repositories](https://github.com/Machealb). 
{% if site.data.repositories.github_users %}

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>




