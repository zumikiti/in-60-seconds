[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/gitpitch/in-60-seconds/master?grs=github)

# GitPitch In 60 Seconds

To experience just how simple it is to create a GitPitch slideshow
presentation on *GitHub*, follow along with this short tutorial.

> Tutorial also available for [GitLab](https://gitlab.com/gitpitch/in-60-seconds) and [Bitbucket](https://bitbucket.org/gitpitch/in-60-seconds) users.

### Introduction

As a *GitHub* user you are probably familiar with the **README.md** convention. A convention that automatically turns any **README.md** file found within a *GitHub* repository into nicely rendered project documentation.

GitPitch introduces a brand new convention for all *GitHub* users, the **PITCHME.md** convention. This new convention automatically turns any **PITCHME.md** file found within a *GitHub* repository into a modern, responsive slideshow deck that is available for sharing and presenting directly from [gitpitch.com](https://gitpitch.com).

With knowledge of this new **PITCHME.md** convention in mind, let's jump straight into the *GitPitch In 60 Seconds* tutorial.

### Step 1. Fork this Repository

Click the **Fork** button at the top of this page to create a fork of this repository.

Forking this repository will create a new `in-60-seconds` repository under your own *GitHub* account. Within your new repository you will find the basic file structure for a GitPitch slideshow presentation:

```
.
├── PITCHME.md
├── PITCHME.yaml
└── assets
    ├── css
    │   └── PITCHME.css
    └── img
        └── *.png, jpg, gif
```

There is only one *required* file in your repository to create a GitPitch slideshow presentation, a **PITCHME.md** markdown file. This is the file where you add the markdown for your slides. Additional files, such as **PITCHME.yaml** and **PITCHME.css** can be added to customize settings and styles for your slide deck.

> One of the many unique features of GitPitch is it's seamless integration with Git. Any file found in the repository can be used to create slide content within your slide deck, including *source-code* files and *image* files.

### Step 2. Congratulations on creating your first GitPitch Slideshow Presentation!

Following a *fork* of the repository a **PITCHME.md** markdown file will be found in your new repository. This means that your first GitPitch slide deck is immediately available at the following URL:

```
https://gitpitch.com/$USER/in-60-seconds
```

> You must substitute your *GitHub* account name for `$USER` in the above slideshow URL.

For example, the slideshow URL for the GitPitch In-60-Seconds sample presentation associated with the *gitpitch* GitHub account  is found here:

```
https://gitpitch.com/gitpitch/in-60-seconds
```

As you can see I have substituted my *GitHub* account name - `gitpitch` - for `$USER` on the slideshow URL. To see the slide deck associated with the *gitpitch* GitHub account live, click on the following [link](https://gitpitch.com/gitpitch/in-60-seconds). 

Before reading ahead make sure you try out your own GitPitch slide deck at the following URL:

```
https://gitpitch.com/$USER/in-60-seconds
```

> You must substitute your *GitHub* account name for `$USER` in the above slideshow URL.

<br>

That's it for the *GitPitch In 60 Seconds* tutorial. If you are eager to jump straight back into the *GitPitch Docs*, click [here](https://gitpitch.com/docs/getting-started/tutorial).

If you want to learn a little more about how the sample presentation for this tutorial was created - recommended - then read on for additional details and tips.

<br>

### The PITCHME.md Markdown File

Here are some top tips about **PITCHME.md** markdown files that are used to create GitPitch slide decks:

1. The **PITCHME.md** file name is a new convention introduced by GitPitch
1. The **PITCHME.md** file name is case sensitive
1. The **PITCHME.md** file content is standard GitHub Flavored Markdown
1. The **PITCHME.md** file content also supports [GitPitch Markdown Shortcuts](https://gitpitch.com/docs/markdown-features) 
1. An unlimited number of **PITCHME.md** can be [added to any branch in your repository](https://gitpitch.com/docs/git/branch-many-slideshows/)
1. The `---` markdown fragment acts as a slide delimiter that partitions your slideshow content


<br>

### Inside the PITCHME.md Markdown File

xxx

<br>

### The Fastest Way from Idea to Presentation.

xxx
