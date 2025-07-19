# Artifical Intelligence Stitches Lazy Outsourced Prototypes
![](00-supporting-files/images/README/20250718213304.png)
## Background
I wanted to learn how agentic ai frameworks work, so I made my own project

## Features I would like to look into/implement
- [ ] Native integration with OpenAI API with specifically local llms
- [ ] Agent features
  - [ ] Agent Group Chats similar to AG2
  - [ ] Tool/Function calling (caching the outputs so that agents can reference reference it later)

## Getting Started
This repo uses git submodules to embed other repos. To get started, clone the repository and initialize the submodules:

If you would like a quick one line clone, you can use the following command:
```bash
git clone --recurse-submodules https://github.com/progressEdd/project-template.git
```

If you have already cloned the repository, you can initialize the submodules with the following commands:
```bash
git pull
git submodule update --init --recursive
```

If you only need specific submodules, you can initialize them individually:
```bash
# For just the dev-onboarding submodule
git submodule update --init 01-dev-onboarding
```
