---
pageClass: home-page
# some data for the components

name: Guo Chen (éę)
profile: /red panda.jpeg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/cg1177
  - title: email
    icon: "/icons/email.svg"
    link: mailto:chenguo1177[at]gmail.com  

bio: Ph.D Candidate at Nanjing University
email: chenguo1177@gmail.com  
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

Iām pursuing a Ph.D. in Computer Science at [Nanjing University](https://en.wikipedia.org/wiki/Nanjing_University), advised by Prof. [Limin Wang](http://wanglimin.github.io/) and Prof. [Tong Lu](https://cs.nju.edu.cn/lutong/index.htm). Now I'm working at [Shanghai AI Lab](https://www.shlab.org.cn/).

My research interests are Meta Universe and Robotic intelligence. I am studying Video Understanding, including Video Pretraining, Action Detection and Egocentric Vision Perception.



## News

- [2022-11-17] š We provide the final Ego4D [report](https://arxiv.org/pdf/2211.09529.pdf) and the [code](https://github.com/OpenGVLab/ego4d-eccv2022-solutions).
- [2022-09-19] Our team wins <font color="#dd0000"><strong>Top-1</strong></font> rankings in <font color="#dd0000"><strong>7 tracks</strong></font> of [Ego4D ECCV2022 Challenge](https://ego4d-data.org/workshops/eccv22/).
- [2022-09-15] We have released the [source code](https://github.com/MCG-NJU/BasicTAD) of [BasicTAD](https://arxiv.org/abs/2205.02717).
- [2022-06-21] Code of [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is released in [here](https://github.com/cg1177/DCAN).
- [2022-05-05] We present the [BasicTAD](https://arxiv.org/abs/2205.02717), an end-to-end TAD baseline method. 
- [2021-12-01] Our paper [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is accepted by AAAI.



## Education & Experiences

- **Nanjing University, Nanjing, China** <br/>
Sept 2020 - present
- **University of South China, Hengyang, China** <br/>
Sept 2015 - Jun 2019


## Publication


<ProjectCard image="/projects/dcan.png" hideBorder=true>

  **DCAN: Improving Temporal Action Detection via Dual Context Aggregation**

  **Guo Chen**, Yin-Dong Zheng, Limin Wang, Tong Lu#
  
  Thirty-Sixth AAAI Conference on Artificial Intelligence (AAAI), 2022
  
  This work explored boundary-based methods for temporal action detection and proposed a novel network, termed DCAN, to improve temporal action detection via temporal-level and proposal-level context aggregation.
  
  [[PDF](https://ojs.aaai.org/index.php/AAAI/article/view/19900/19659)] [[bibtex](/bibtex/dcan.txt)] [[code](https://github.com/cg1177/DCAN)]

</ProjectCard>


## Technical Reports

<ProjectCard image="/projects/internvideo.png" hideBorder=true>

  **InternVideo: General Video Foundation Models via Generative and Discriminative Learning**

  Yi Wang, Kunchang Li, Yizhuo Li, Yinan He, Bingkun Huang, Zhiyu Zhao, Hongjie Zhang, Jilan Xu, Yi Liu, Zun Wang, Sen Xing, **Guo Chen**, Junting Pan, Jiashuo Yu, Yali Wang, Limin Wang, Yu Qiao#

Arxiv, 2022

  
  [[PDF](https://arxiv.org/pdf/2212.03191)] [[bibtex](/bibtex/internvideo.txt)] [[code](https://github.com/OpenGVLab/InternVideo)]

</ProjectCard>

<ProjectCard image="/projects/ego4d.png" hideBorder=true>

  **InternVideo-Ego4D: A Pack of Champion Solutions to Ego4D Challenges**

  **Guo Chen***, Sen Xing*, Zhe Chen*, Yi Wang*, Kunchang Li, Yizhuo Li, Yi Liu, Jiahao Wang, Yin-Dong Zheng, Bingkun Huang, Zhiyu Zhao, Junting Pan, Yifei Huang, Zun Wang, Jiashuo Yu, Yinan He, Hongjie Zhang, Tong Lu, Yali Wang, Limin Wang, Yu Qiao#

Arxiv, 2022

Introduction: This work presents our champion solutions to five tracks at Ego4D challenge.
  
  [[PDF](https://arxiv.org/pdf/2211.09529.pdf)] [[bibtex](/bibtex/ego4d.txt)] [[code](https://github.com/OpenGVLab/ego4d-eccv2022-solutions)]

</ProjectCard>

<ProjectCard image="/projects/ego4d_2.png" hideBorder=true>

  **Exploring State Change Capture of Heterogeneous Backbones@ Ego4D Hands and Objects Challenge 2022**

  Yin-Dong Zheng, **Guo Chen**, Jiahao Wang, Tong Lu, Limin Wang

Arxiv, 2022

Introduction: This work presents our champion solutions to two tracks at Ego4D challenge.
  
  [[PDF](https://arxiv.org/pdf/2211.08728)] [[bibtex](/bibtex/ego4d_2.txt)] [[code](https://github.com/misanthrope-goth/OSCC_PNR)]

</ProjectCard>

<ProjectCard image="/projects/basictad.png" hideBorder=true>

  **BasicTAD: an Astounding RGB-Only Baseline for Temporal Action Detection**

  Min Yang*, **Guo Chen***, Yin-Dong Zheng, Tong Lu, Limin Wang#

Arxiv, 2022

Introduction: This work presents a simple yet effective end-to-end training framework for temporal action detection.
  
  [[PDF](https://arxiv.org/abs/2205.02717)] [[bibtex](/bibtex/basic.txt)] [[code](https://github.com/MCG-NJU/BasicTAD)]

</ProjectCard>



### Contests and Awards

- [2022-10] 2nd Ego4D Challenge, ECCV2022,**7 Top-1 Rankings**
- [2017-12] CCPC Final Contest, **Bronze Medal**
- [2017-10] CCPC Regional Contest, **Bronze Medal**
- [2017-10] ACM-ICPC Asia Regional Contest, **Silver Medal**

<!-- Custom style for this page -->

<style lang="stylus">

.theme-container.home-page .page
  font-size 14px
  font-family "lucida grande", "lucida sans unicode", lucida, "Helvetica Neue", Helvetica, Arial, sans-serif;
  p
    margin 0 0 0.5rem
  p, ul, ol
    line-height normal
  a
    font-weight normal
  .theme-default-content:not(.custom) > h2
    margin-bottom 0.5rem
  .theme-default-content:not(.custom) > h2:first-child + p
    margin-top 0.5rem
  .theme-default-content:not(.custom) > h3
    padding-top 4rem

  /* Override */
  .md-card
    margin-top 0.5em
    .card-image
      padding 0.2rem
      img
        max-width 120px
        max-height 120px
    .card-content p
      -webkit-margin-after 0.2em

@media (max-width: 419px)
  .theme-container.home-page .page
    p, ul, ol
      line-height 1.5

    .md-card
      .card-image
        img 
          width 100%
          max-width 400px

</style>
