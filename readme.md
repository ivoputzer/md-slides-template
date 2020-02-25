# md-slides-template

![GitHub Actions Badge](https://img.shields.io/github/workflow/status/ivoputzer/md-slides-template/markdown%20slides/master?style=for-the-badge&logo=github)
![Github Issues Badge](https://img.shields.io/github/issues/ivoputzer/md-slides-template?style=for-the-badge&logo=github)
![GitHub Pages Badge](https://img.shields.io/static/v1?style=for-the-badge&label=page&message=online&color=success&logo=github)
![GitHub Releases Badge](https://img.shields.io/github/v/release/ivoputzer/md-slides-template?style=for-the-badge&logo=github)

This template can be used to deliver [Marp](https://marp.app) presentations quickly. When you push to `master` the workflow will render your slides, create a github release, and update your github page automatically without any additional configuration.

The workflow follows the `PITCHME.md` convention introduced by [GitPitch](https://gitpitch.com/docs/getting-started/pitchme/).

## Instructions
1. Navigate to the main page of the template repository.
2. Above the file list, click **Use this template**.
![](data/use-this-template.png)
3. Select the owner account and name the new repository.
4. Click **Create repository from template**.

This steps will boostrap your new presentation using this template.

## Pull upstream changes
Setup `upstream` to whatever name you want
```sh
git remote add upstream git@github.com:ivoputzer/md-slides-template.git
```

Integrate changes from `upstream` into your own repository
```sh
git fetch --all
git checkout upstream/master .github/workflows/md-slides.yml
git commit -m "integrates md-slides workflow changes from upstream"
```

## Create your own template
1. Fork this repository.
2. Apply any edit you with having in the template.
3. Use your own template when following [instructions](#Instructions).
4. Consider to submit a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests#about-pull-requests) 🎉
