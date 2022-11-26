---
pageClass: home-page
# some data for the components

name: Guo Chen (陈果)
profile: /profile.jpg

socials:
  - title: github
    icon: "/icons/github.svg"
    link: https://github.com/cg1177
  - title: email
    icon: "/icons/email.svg"
    link: mailto:chenguo1177[at]gmail.com  

bio: Ph.d Candidate at Nanjing University
email: chenguo1177@gmail.com  
---

<ProfileSection :frontmatter="$page.frontmatter" />

## About Me

I‘m pursuing a Ph.D. in Computer Science at [Nanjing University](https://en.wikipedia.org/wiki/Nanjing_University), advised by Prof. [Limin Wang](http://wanglimin.github.io/) and Prof. [Tong Lu](https://cs.nju.edu.cn/lutong/index.htm). Now I'm working at [Shanghai AI Lab](https://www.shlab.org.cn/).

My research interests are MetaUniverse and Robotic intelligence. I am studying about Video Understanding, including Video Pretraining, Action Detection and Egoentric Vision Perception.



## News

- [2022-11-17] We provide the final Ego4D [report](https://arxiv.org/pdf/2211.09529.pdf) and the [code](https://github.com/OpenGVLab/ego4d-eccv2022-solutions) have been released.
- [2022-09-19] We win top-1 rankings in **7** tracks in [Ego4D ECCV2022 Challenge](https://ego4d-data.org/workshops/eccv22/).
- [2022-09-15] We have released the [source code](https://github.com/MCG-NJU/BasicTAD) of [BasicTAD](https://arxiv.org/abs/2205.02717).
- [2022-06-21] Code of [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is released in [here](https://github.com/cg1177/DCAN).
- [2022-05-05] We present the [BasicTAD](https://arxiv.org/abs/2205.02717), an end-to-end TAD baseline method. 
- [2021-12-01] Our paper [DCAN](https://ojs.aaai.org/index.php/AAAI/article/view/19900) is accepted by AAAI.




## Education & Experiences

- **Hogwarts School of Witchcraft and Wizardry** <br/>
Sept 1991 - 1997


## Publication


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  **The Making of Harry Potter's Wand**

  Harry P., Hermione G., *et al*
  
  Harry's wand was broken in 1997, but was repaired by him after the 1998 Battle of Hogwarts. Usually the repair of a wand is impossible, but with the use of the Elder Wand it was achievable.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **Harry Potter and the Deathly Hallows**
  
  In the epilogue of Deathly Hallows, which is set 19 years after Voldemort's death, Harry and Ginny are a couple and have three children: James Sirius Potter, who has already been at Hogwarts for at least one year, Albus Severus Potter, who is starting his first year there, and Lily Luna Potter, who is two years away from her first year at the school.

  [[Link](https://www.google.com)]

</ProjectCard>


## Techical Reports


[→ Full list](/projects/)

<ProjectCard image="/projects/1.png" hideBorder=true>

  **The Making of Harry Potter's Wand**

  Harry P., Hermione G., *et al*
  
  Harry's wand was broken in 1997, but was repaired by him after the 1998 Battle of Hogwarts. Usually the repair of a wand is impossible, but with the use of the Elder Wand it was achievable.
  
  [[PDF](https://www.google.com)] [[arXiv](https://arxiv.org)]

</ProjectCard>

<ProjectCard hideBorder=true>

  **Harry Potter and the Deathly Hallows**
  
  In the epilogue of Deathly Hallows, which is set 19 years after Voldemort's death, Harry and Ginny are a couple and have three children: James Sirius Potter, who has already been at Hogwarts for at least one year, Albus Severus Potter, who is starting his first year there, and Lily Luna Potter, who is two years away from her first year at the school.

  [[Link](https://www.google.com)]

</ProjectCard>


### Awards

- First place in **The Hogwarts House Cup**


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
