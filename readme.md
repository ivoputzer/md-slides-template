# md-slides-template
![Github Actions Badge][gh_actions_badge]
![Github Issues Badge][gh_issues_badge]
![Github Pages Badge][gh_pages_badge]
![Github Releases Badge][gh_releases_badge]

**Is used to deliver [Marp][marp_url] presentations quickly.** When you push to `master` it will render your slides, create a [release][releases_url] and [deploy][deployments_url] your [page][page_url] automatically without any additional configuration.

This template follows the `PITCHME.md` convention introduced by [GitPitch][gitpitch_url].

## Instructions
1. Navigate to the main page of this template repository.
2. Above the file list, click **Use this template**.
![Use this template](data/use-this-template.png)
1. Select the owner account and name your repository.
2. Click **Create repository from template**.

This steps will boostrap your presentation using this template.

## Pull changes
Setup `upstream` to whatever name you want
```bash
git remote add upstream https://github.com/ivoputzer/md-slides-template.git
```

Merge changes from `upstream` into your own repository
```bash
git fetch --all
git checkout upstream/master .github/workflows/md-slides.yml
git commit -m "Merges upstream changes from ivoputzer/md-slides-template"
```

## Customize
1. Fork this repository.
2. Apply changes you want your template to implement.
3. Remember to update instructions.
4. Use your own template when creating new presentations 🎉

Eventually consider submitting a [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests#about-pull-requests) to improve this project 😉 It'd be very much appreciated!

[gh_actions_badge]: https://img.shields.io/github/workflow/status/ivoputzer/md-slides-template/markdown%20slides/master?style=for-the-badge&logo=github
[gh_issues_badge]: https://img.shields.io/github/issues/ivoputzer/md-slides-template?style=for-the-badge&logo=github
[gh_pages_badge]: https://img.shields.io/static/v1?style=for-the-badge&label=page&message=online&color=success&logo=github
[gh_releases_badge]: https://img.shields.io/github/v/release/ivoputzer/md-slides-template?style=for-the-badge&logo=github
[page_url]: https://ivoputzer.github.io/md-slides-template
[releases_url]: https://github.com/ivoputzer/md-slides-template/releases
[deployments_url]: https://github.com/ivoputzer/md-slides-template/deployments
[marp_url]: https://marp.app
[gitpitch_url]: https://gitpitch.com/docs/getting-started/pitchme
