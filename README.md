# Complete Minecraft Server Guide
> Complete Minecraft Server Guide © 2024 by This-Is-An-Alt-Account is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International. To view a copy of this license, visit https://creativecommons.org/licenses/by-nc-sa/4.0/

> [!WARNING]
> This README is actively being developed and information may be missing.

This is an open-source documentation project with the goal of creating an expansive guide which explains how to create Minecraft servers. The guide aims to be easy to read, easy to understand, and approachable for those of all skill and experience levels.

Though the name implies the guide is strictly about Minecraft servers, the guide should cover information that is relevant to the creation and upkeep of a server.

## Read the Guide
The guide is available at:<br>https://this-is-an-alt-account.github.io/cmsg/

## Goals of This Project
- Be easy to read and comprehend.
- Cater to those of all skill and experience levels.
- Explain necessary information and concepts outside of the strict scope of Minecraft.

and most importantly...
- Help anyone and everyone make a Minecraft server!

---

# Contributing
Any and all contributions are welcome!

### A Note on Translations
At this time, there is no plan to support multiple languages. Thanks to our license, however, those seeking to create a translated copy are allowed to do so as long as their copy of this metarial complies with and uses the license.

## Ways to Contribute
### Fork the repository
[Fork this repository](https://github.com/This-Is-An-Alt-Account/cmsg/fork) (link opens on same page) then make your edits. When you've made all of the edits you'd like, [open a pull request on this repo](https://github.com/This-Is-An-Alt-Account/cmsg/compare) asking to pull your fork into our main branch.
### Open an issue
Your can use [GitHub's issue tracker](https://github.com/This-Is-An-Alt-Account/cmsg/issues?q=is%3Aissue) to [open an issue](https://github.com/This-Is-An-Alt-Account/cmsg/issues/new) and describe your suggestion. In the future, issue templates will be added to make the process more streamlined for common suggestions.

---

# Repository Overview
The repository is configured to deploy the guide with Material on MkDocs via GitHub Pages. 
## Branches
There are three primary branches for this repo: `main`, `dev`, and `gh-pages`.
### main
The main branch contains the latest version of the guide's contents. When changes are pushed to main, a GitHub action is triggered which builds the site with the contents of main. Main will and should always represent the latest release of the guide. It should never contain WIP sections that would break the cohesiveness of the guide.
### dev
The dev branch is very similar to main except it contains in-development changes or other changes that have not yet been "released" into main. All contributions are done on the devc branch and only after manual checks are these changes pulled into main. The dev branch also builds the site on push and it can be found on the cmsg/dev/ path of the site. A warning is shown so that accidental visitors know that it is not the release version.
### gh-pages
This branch contains the actual site and is updated when the site is built on a push to main or dev. It is never manually edited.

# License
License information can be found in THE LICENSE file and at the top of this README. [Click here](https://creativecommons.org/licenses/by-nc-sa/4.0/) to visit the Creative Commons webpage that explains the CC BY-NC-SA 4.0 license.

Please review this license carefully if you intend to do anything outside of directly contributing to this repository. Most importantly, please note that you are required to give appropriate credit to the original work and that using this material for commercial purposes is prohibited.
