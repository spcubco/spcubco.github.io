# SPC UBCO

This repository hosts the website for SPC!

SPC is the student-run programming club for the UBC Okanagan Campus! We participate in programming competitions at the national and international level and give the resources for our students to excel at them.

SPC students have participated in competitions such as Google Code Jam, Facebook Hacker Cup, and ACM ICPC.

If you are interested in competing in those or just want to improve your programming skills, this is the club for you!

## How this website works

This website is generated using [Hugo](https://gohugo.io/) and [Github-Actions](https://github.com/features/actions). To edit it, you need to know Markdown and Git. 

Check the [Markdown guide](https://guides.github.com/features/mastering-markdown/) and [Git guide](http://rogerdudler.github.io/git-guide/) to get familiar with the technologies to edit the website.

## Editing the website

If you don't have the repository alreadty, clone the repository:

```
git clone https://github.com/spcubco/spcubco.github.io.git
```

Then, start up the Hugo server. If you don't have Hugo installed, [check here how to install it](https://gohugo.io/getting-started/installing/).

```
hugo server
```

Now, you can access a locally hosted website at `http://localhost:1313/` (or maybe other address or port, check your console output).

Make changes to the files in `/content` to update the content of the wbsite.

## Publishing your changes

Once you're done with your changes, it's time to publish them.

First, add the changes to the index and commit the files

```
git add *
```

Second, commit the files and add a message to tell us what changed

```
git commit -m "Commit message"
```

And that's it - Github Actions will take care of the rest of the work to deploy the website. Do not edit the `gh-pages` branch directly.