## Personal Site / Portfolio
This repository is my personal site / portfolio written with Hugo using  the
[npqhugo theme](https://github.com/saadjsct/npqhugo) and hosted on Github Pages
at https://meowcenary.github.io/personal-site/

Deployments are run through Github Actions. The workflow for this project is:
`.github/workflows/hugo.yaml`

The directory `public/` is included to `.gitignore` because the deployment
workflow builds the site, but if the deployment process is changed to something
that simply tranfsers the files this directory should be removed from
`.gitignore`. Read more [here](https://gohugo.io/getting-started/usage/#the-hugo-command)
