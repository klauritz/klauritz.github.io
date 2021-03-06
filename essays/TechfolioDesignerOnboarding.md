---
layout: essay
type: essay
title: Building a Portfolio using Techfolios Designer
# All dates must be YYYY-MM-DD format!
date: 2018-08-26
labels:
  - Techfolios Designer
  - ICS 491
  - Electron
---

# Introduction

Currently enrolled in ICS 314, I've started to build my professional persona. Creating accounts and webpages where i can exhibit my skills and projects to future employers is a big part in developing my professional persona. Using [Techfolio Designer](https://techfolios.github.io/) helps me create a professional portfolio that is concise, easy to digest, and available to everyone. Contributing to Techfolio Designer will help me understand the development process of desktop applications. Not only will I be helping develop an important tool, but I will also be improving my skills and experience in application development.

# Problems and Issues
This was my first time using Techfolio Designer, and the instructions left by Professor Philip Johnson helped me with a hassle-free installation and setup of the Techfolio Designer. However, there were a few problems while using Techfolio Designer to edit my techfolio. Additionally, installing and running Techfolio Designer through Electron Forge proved problematic. I couldn't get Techfolios Designer to open using Electron Forge on my Windows Machine, so I tried on my Linux machine running Ubuntu as well. However, Electron Forge still could not open Techfolio Designer.

### Techfolio Designer
- **Had to Manually Clone the Git Repo:** In the config menu on splash page, cloning the repo through the config option would always fail, saying it couldnt get permissions for my acccount, however it replaced my account name with a random string. Therefore,I had to manually clone the git repo into a directory and set Techfolio Designer's local directory to that directory.


### Installing and Running through Electron Forge
- **Finding the App Directory:** After downloading the .exe file for Windows, there is no prompt telling the user where the files were installed. I later found them under the /AppData/Local/ directory, but it would be useful and less of a hassle for Windows users to be notified where the program is being installed (and perhaps choose where to install). Searching for the app directory itself was a bit of a hassle as well. Perhaps listing the precise directory location in the instruction page would help users find it. (for the linux .rpm: /./usr/share/TechfolioDesigner/resources/app/)
- **Running Through Electron Forge:** When running `npm install` in the app directory gave a lot of strange error messages, such as saying it needed node 6.0.0 or higher when I had node 10.9.0 installed. Additionally, `electron-forge start` prompts me saying that Electron can't find any files that it can open, even though the package.json and es6-shim.js is present in the directory. Because of this, I couldn't open Techfolio Designer through Electron Forge on my Windows or my Ubuntu machine.

# Looking Forward
As I learn about Techfolio Designer, I hope I can further understand why I'm getting these errors, then help fix them. Even with the issues listed above, I still consider Techfolio Designer to be a vital tool for anybody that wants to build a professional portfolio. This program allows people with little technical experience to build a stunning online portfolio. I look forward to learning all I can about this program and how to develop appications like this.