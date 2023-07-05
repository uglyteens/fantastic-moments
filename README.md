# Fantastic Moments

Repo for recording the fantastic moments of ugly teens.

## Prerequisites

- Be familiar with basic Markdown syntax
- Ability to use basic Git operations

## How To Use

`moments` folder is used to store images and corresponding Markdown files containing extra details of the images.

1. Create a folder under `moments` folder. e.g. `never-stop-learning`.
2. Put image into the folder just created. e.g. `never_stop_learning.jpg`
3. Create a `README.md` file for the image, recording extra image information. Use a [YAML frontmatter](https://daily-dev-tips.com/posts/what-exactly-is-frontmatter/) block to do this. e.g.

```md
---
title: "学到晕厥"
date: "2015-06-15"
description: "一些描述信息"
tags: "dtc,电力拖动,电力拖动控制系统,电拖"
---

![never_stop_learning.jpg](./never_stop_learning.jpg)
```

And you can even put multiple images into one folder and reference them in the `README.md`.

```md
---
title: "学到晕厥"
---

![image-1.jpg](./image-1.jpg)
![image-2.jpg](./image-2.jpg)
```

Normally, each image should have its own folder and `README.md`, making it easier to orgnize, and the file stucture should be like this

```bash
.
├── README.md
└── moments
    └── never-stop-learning
        ├── README.md
        └── never_stop_learning.jpg
```

Then go and upload your fantastic moments.
