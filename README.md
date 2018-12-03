[![GitPitch](https://gitpitch.com/assets/badge.svg)](https://gitpitch.com/gitpitch/in-60-seconds/master?grs=github)

# GitPitch In 60 Seconds

To experience just how simple it is to create a GitPitch slideshow
presentation, follow along with this short tutorial.

> Tutorial also available for [GitLab](https://gitlab.com/gitpitch/in-60-seconds) and [Bitbucket](https://bitbucket.org/gitpitch/in-60-seconds) users.

### Introduction

As a *GitHub* user you are probably familiar with the **README.md** convention. A convention that automatically turns any **README.md** file found within a *GitHub* repository into nicely rendered project documentation.

GitPitch introduces a brand new convention for all *GitHub* users, the **PITCHME.md** convention. This new convention automatically turns any **PITCHME.md** file found within a *GitHub* repository into a modern, responsive slideshow deck that is available for sharing and presenting directly from [gitpitch.com](https://gitpitch.com).

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

There is only one file required in your repository to create a GitPitch slideshow presentation, a **PITCHME.md** markdown file. Additional files, such as **PITCHME.yaml** and **PITCHME.css** can be added to customize settings and styles for your slide deck.

One of the many unique features of GitPitch is it's seamless integration with Git. Any file found in the repository can be used as slide content within your slide deck, including *source-code* files and *image* files.

### Step 2. Congrats on creating your first GitPitch Slideshow Presentation!

Following the *repository fork* in step 1. a **PITCHME.md** markdown file will be found in your new repository. This means that your first GitPitch slide deck is immediately available at the following URL:

```
https://gitpitch.com/$USER/in-60-seconds
```

> You must substitute your *GitHub* account name for `$USER` in the slideshow URL.

For example, the slideshow URL for the GitPitch In-60-Seconds sample presentation associate with the *gitpitch* GitHub account  is found here:

```
https://gitpitch.com/gitpitch/in-60-seconds
```

As you can see I have substituted my *GitHub* account name - `gitpitch` - for `$USER` on the slideshow URL. To launch the slide deck associated with the *gitpitch* GitHub account click on the following link, [here](https://gitpitch.com/gitpitch/in-60-seconds). 


### Step X. Create a **PITCHME.md** file in the root directory of your Repository

Using your preferred code editor create a file called **PITCHME.md**, then add 
and save the following Markdown content within that file:

```
# Flux 

An application architecture for React

---

### Flux Design

- Dispatcher: Manages Data Flow
- Stores: Handle State & Logic
- Views: Render Data via React

---

![Flux Explained](https://facebook.github.io/flux/img/flux-simple-f8-diagram-explained-1300w.png)
```

Please take note of the following:

1. The **PITCHME.md** file name is a new convention introduced by GitPitch
1. The **PITCHME.md** file name is case sensitive
1. The **PITCHME.md** file content is standard GitHub Flavored Markdown
1. The `---` markdown fragment acts as a slide delimiter that partitions your slideshow content

For the sample markdown used in this tutorial, when GitPitch processes the sample **PITCHME.md** markdown content it will result in a simple presentation with just three slides.


### Step 3. Push **PITCHME.md** to your upstream GitHub Repository in the Cloud

At this point you have simply created one new file within your chosen repository. Now you need to add this file under Git version control and then push your local changes to your upstream repository on GitHub in the cloud:

```
git add PITCHME.md
git commit -m "Added my first GitPitch slideshow content."
git push
```

At this point, the upstream version of your chosen repository on GitHub should have the new **PITCHME.md** file in it's root directory.


### Step 4. Done!

After you `git-push`, you are done! Your GitPitch slideshow presentation is now waiting for you to share or present at its public URL.

You can build the public URL for your slideshow presentation on `gitpitch.com` using the following structure:

```
https://gitpitch.com/$USER/$REPO/$BRANCH
```

Where the following substitutions must be made by you to reflect your specific Git account and respository details:

- `$USER` - must be replaced with your GitHub account name
- `$REPO` - must be replaced with the name of your chosen GitHub repository
- `$BRANCH` - must be replaced with the branch you used when adding your `PITCHME.md` file. If you did not specifically create a feature branch for this tutorial, then the default branch name is `master`.

For example, this tutorial is itself within a repository. And that repository includes a `PITCHME.md` file. So you can view the GitPitch slideshow presentation associated with this tutorial at the following URL:

[https://gitpitch.com/gitpitch/in-60-seconds/master](https://gitpitch.com/gitpitch/in-60-seconds/master)

Note how `$USER` has been replaced with my GitHub account name ( gitpitch ) and `$REPO` has been replaced with the name of my repository ( in-60-seconds ). 

Once you have created your own GitPitch slideshow presentation URL it should open and look a lot like this:

![Slideshow-In-60-Seconds](/images/in-60-seconds.jpg)

Immediately you can [download](https://gitpitch.com/docs/foundation-features/offline/) 
your slideshow for offline presentation, 
[print](https://gitpitch.com/docs/foundation-features/pdf/) it as a 
PDF document, or simply share a link to your presentation on social media.

### The Fastest Way from Idea to Presentation.

Beyond support for standard Markdown on presentation slides, GitPitch 
delivers a [wide range of features](https://gitpitch.com/features) that cater
to developers, speakers, educators, etc.

See the [Template Gallery](https://gitpitch.com/docs/the-template) for quickstart
markdown presentaton templates. Simply fork or download the templates
repo and start customizing the presentation markdown to reflect your needs.

To view a live slideshow demonstration of a wide range of features try
out the GitPitch [Kitchen Sink](https://gitpitch.com/gitpitch/kitchen-sink).
To dig deeper, see the [GitPitch Docs](https://gitpitch.com/docs) 
for live, interactive feature guides.

And don't forget to check out [GitPitch Pro Features](https://gitpitch.com/pro-features) to learn how you can achieve even more with GitPitch using **GitPitch Desktop**, **GitPitch Surveys**, and **GitPitch Security**.
