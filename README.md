# JMusicBot

### Status - Original Repo
[![Downloads](https://img.shields.io/github/downloads/jagrosh/MusicBot/total.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![Stars](https://img.shields.io/github/stars/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/stargazers)
[![Release](https://img.shields.io/github/release/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/releases/latest)
[![License](https://img.shields.io/github/license/jagrosh/MusicBot.svg)](https://github.com/jagrosh/MusicBot/blob/master/LICENSE)
[![Discord](https://discordapp.com/api/guilds/147698382092238848/widget.png)](https://discord.gg/0p9LSGoRLu6Pet0k)<br>
[![CircleCI](https://dl.circleci.com/status-badge/img/gh/jagrosh/MusicBot/tree/master.svg?style=svg)](https://dl.circleci.com/status-badge/redirect/gh/jagrosh/MusicBot/tree/master)
[![Build and Test](https://github.com/jagrosh/MusicBot/actions/workflows/build-and-test.yml/badge.svg)](https://github.com/jagrosh/MusicBot/actions/workflows/build-and-test.yml)
[![CodeFactor](https://www.codefactor.io/repository/github/jagrosh/musicbot/badge)](https://www.codefactor.io/repository/github/jagrosh/musicbot)

---

### Notes
> **<p style="color:yellow;background-color:dark-grey">This is just a fork of the original MusicBot from Jagrosh for fixing some errors that has not been addressed yet</p>**
---
### Patches
#### Updated Lavaplayer to v2.2.4
```
<version>2.2.4</version> >> <version>2.2.1</version>
```
- **Source** : https://github.com/lavalink-devs/lavaplayer/releases
#### Updated Lavalink Youtube Source to v1.13.3
```
<version>1.5.2</version> >> <version>1.13.3</version>
```
- **Source** : https://github.com/lavalink-devs/youtube-source/releases
---
$\longrightarrow$ ***Reason*** : [[SignatureCipherManager Error](https://github.com/jagrosh/MusicBot/issues1694)]

---
#### Changed JDA Utilities repo for Local Compilation from Source
```
<dependency>
    <groupId>com.jagrosh</groupId>
    <artifactId>jda-utilities</artifactId>
    <version>3.0.5</version>
    <type>pom</type>
</dependency>
```
- **To**
```
<dependency>
    <groupId>com.github.Nagami-Yukki</groupId>
    <artifactId>JDA-Utilities</artifactId>
    <version>1.0</version>
</dependency>
```
---
$\longrightarrow$ **Reason** : ***Missing Dependency*** :  [[Issue-1686](https://github.com/jagrosh/MusicBot/issues/1686)]

---