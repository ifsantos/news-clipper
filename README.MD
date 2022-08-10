# news-clipper
Clips the news from the major techlology sistes, at one click.

## tasks

- Get links on Site's initial page
- Sites in initial clipping list:
    - https://dzone.com
    - https://devclass.com
    - https://github.blog
    - https://stackoverflow.blog/
    - https://blog.devgenius.io/
    - https://www.quantamagazine.org
    - https://towardsdatascience.com
    - https://thenewstack.io
    - https://dev.to/
    - https://dev.to/code_jedi
    - https://www.howtogeek.com

- From each link, extract theese information to feed the clipper
    - get image by:
        - \<meta property="og:image" content="https://github.blog/wp-content/uploads/2022/06/git-2.37.png">
        - \<meta data-rh="true" property="og:image" content="https://miro.medium.com/max/960/0*6k5eURomcpoZ_76M.png">
    - get Title by:
        - \<meta data-rh="true" property="og:title" content="Kubeflow MLOps&nbsp;: Automatic pipeline deployment with CI / CD / CT">
        - \<meta property="og:title" content="Highlights from Git 2.37 | The GitHub Blog">
    - get Modificantion time by:
        - \<meta property="article:modified_time" content="2022-06-29T19:24:56+00:00">


### References
- 