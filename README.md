<div align="center">

# *Hexated-Extensions*

##

<!-- Badges -->
<p>
  <a href="https://github.com/AmineSoukara/EgyBest-Api/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/hexated/cloudstream-extensions-hexated" alt="contributors" />
  </a>
  <a href="">
    <img src="https://img.shields.io/github/last-commit/hexated/cloudstream-extensions-hexated" alt="last update" />
  </a>
  <a href="https://github.com/hexated/cloudstream-extensions-hexated/network/members">
    <img src="https://img.shields.io/github/forks/hexated/cloudstream-extensions-hexated" alt="forks" />
  </a>
  <a href="https://github.com/hexated/cloudstream-extensions-hexated/stargazers">
    <img src="https://img.shields.io/github/stars/hexated/cloudstream-extensions-hexated" alt="stars" />
  </a>
  <a href="https://github.com/hexated/cloudstream-extensions-hexated/issues/">
    <img src="https://img.shields.io/github/issues/hexated/cloudstream-extensions-hexated" alt="open issues" />
  </a>
  <a href="https://github.com/hexated/cloudstream-extensions-hexated/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/hexated/cloudstream-extensions-hexated.svg" alt="license" />
  </a>
  <a href="https://github.com/AmineSoukara/EgyBest-API">
    <img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fhexated%2Fcloudstream-extensions-hexated&count_bg=%23FF0000&title_bg=%23555555&icon=tinder.svg&icon_color=%23FF0000&title=Hits&edge_flat=false" alt="hits" />
  </a>
</p>

##

# 🕹 Libraries:

<a href="https://github.com/AmineSoukara/Py-EgyBest-Api"><img src="https://img.shields.io/badge/Kotlin-8000FF?style=flat&logo=github&logoColor=white?logoWidth=100"></a>

##

[![Discord](https://invidget.switchblade.xyz/5Hus6fM)](https://discord.gg/5Hus6fM)

</div>


**⚠️ This is currently under development, dont use it yet if you're not comfortable with constantly merging new changes**

# Cloudstream English Plugin Repository 🇬🇧

All available repositories: https://recloudstream.github.io/repos/

Plugin json: https://raw.githubusercontent.com/recloudstream/cloudstream-extensions/builds/plugins.json

Not all extractors are included, only those need to compile. We need to use loadExtractor in the future.

## Getting started with writing your first plugin

1. Open the root build.gradle.kts, read the comments and replace all the placeholders
2. Familiarize yourself with the project structure. Most files are commented
3. Build or deploy your first plugin using:
   - Windows: `.\gradlew.bat ExampleProvider:make` or `.\gradlew.bat ExampleProvider:deployWithAdb`
   - Linux & Mac: `./gradlew ExampleProvider:make` or `./gradlew ExampleProvider:deployWithAdb`

## Attribution

This template as well as the gradle plugin and the whole plugin system is **heavily** based on [Aliucord](https://github.com/Aliucord).
*Go use it, it's a great mobile discord client mod!*
