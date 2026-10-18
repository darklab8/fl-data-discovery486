# Description

This repository shows how to use project [fl-darkstat](https://github.com/darklab8/fl-darkstat) (Online flstat)
for automated build of static assets and deployment to github pages

this repository deploys Ancient Freelancer Discovery 4.86 version downloaded from https://www.moddb.com/mods/discovery-freelancer/downloads/discovery-freelancer-486-exiles

# More info

- Check [fl-darkstat](https://github.com/darklab8/fl-darkstat) repository for more information about product
- Check [Freelancer Discovery](https://discoverygc.com/) for current Freelancer mod
- Check https://darklab8.github.io/fl-data-discovery/ for deployed web site

# Deployment

- Your repository should be containing minimal file amount needed for fl-stat
- And it could use CI workflow for autodeployment similar to [shown example](./.github/workflows/publish.yaml).
    - You are provided with [Github Action](https://github.com/darklab8/fl-darkstat/blob/master/.github/actions/build/action.yml) for building. You can customize workflow to what u wish.
    - Instead of deploying to github pages, you can deploy to any other target capable to server static assets (html/css/js)
- Alternatively fl-darkstat is usable locally, see its repository for more information

# Updates

- Periodically auto updated by cron job in Github Actions CI
- See [contacts here](<https://darklab8.github.io/blog>) in case of problems
