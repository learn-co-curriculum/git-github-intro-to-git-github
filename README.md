# Welcome to Git/GitHub

## Learning Goals

- Describe the purpose of this module and the tools you will be using.
- Prepare your environment to practice with version control, Git, and GitHub.

## Introduction

Git is a widely-used, powerful tool that many companies in the tech industry use
on a daily basis, especially in software engineering. Developing good Git habits
and becoming comfortable with common workflows will help you in your job search
and in your daily work life once you find a job.

Git has many powerful features that give you almost unlimited control over
maintaining the code in your projects. But it is also, as a result, quite
complex. The good news is that a handful of commands and processes constitute
the bulk of what is used most of the time.

In this section, you will learn to use Git and GitHub for version control and
for collaboration. The material covered here should prepare you for the most
common usages and workflows that represent the majority of what you will
need for most jobs.

## About this Material

The material in this section is designed for use by students in both the
Software Engineering and Data Science programs. Because the setup for working
with Git is a bit different for the two programs, be prepared to see things that
aren't quite the same as you're used to. The content — the commands and
workflows — will be the same.

Before proceeding, we recommend you go back and review any Git lessons you've
already completed in the curriculum to refresh your memory and give you a jump
start on the material. These lessons will be in Software Engineering Prep for
Software Engineering students and in Phase 1 for Data Science students.

## How to Approach the Material in this Module

As mentioned above, Git has many powerful features and commands that can be
overwhelming when you first start to use it. To help keep things manageable as
you're learning the material, here are some general guidelines to keep in mind:

- **Do** follow along with the examples and exercises, and practice the things
  you're learning. You will learn the most common commands and workflows through
  sheer repetition and will get to the point where you don't even need to think
  about them.
- **Don't** try to memorize commands or syntax. Instead, focus on understanding
  _what_ Git enables you to do rather than _how_ to do it.
- **Do** use Google, the Git documentation, etc. If you know _what_ you can
  accomplish with Git, you can always look up the exact command or syntax you
  need.
- **Do** focus on developing good Git habits early. Because Git is so complex,
  once things go wrong it can be hard to recover. Developing good Git habits
  from the start will go a long way toward protecting you from winding up in a
  bind.

## Setup

For Software Engineering students, you should have gotten everything you need
set up in Software Engineering Prep. If you haven't, we strongly recommend you
complete all the lessons in the appropriate (Windows or Mac) Environment Setup
module, available in the Canvas Software Engineering Prep course or Canvas
Homeroom, before you continue.

For Data Science students, make sure you have completed the Setting up a
Professional Data Science Environment lessons, including Introduction,
MacOS/Windows, and Configuring Git. These lessons can be found in the beginning
of Phase 1 in the section titled Getting Started with Data Science.

The specific requirements are outlined below.

### Git

Git should be installed on your local machine. At the time of this writing, the
latest version of Git is v2.35. While other recent versions of Git should work
fine, be aware that the appearance of some Git output may be different from
examples you see in these lessons.

If you want to upgrade to the latest version of Git, you can check and update
your version using the steps [in this article][updating-git-version].

### Terminal Application for Running Shell Commands

For Mac users, this will be the resident MacOS Terminal application, and for
Windows users, it will be either Ubuntu (for Software Engineering students) or
Git Bash (for Data Science students).

### GitHub Account

You will need to [sign up for a GitHub account][github-signup], if you do not
already have one. Additionally, you will need to configure your account
according to the directions provided by your program.

**Note**: The setup instructions for Software Engineering students include
setting up an SSH key, but this is not part of the setup instructions used by
Data Science students. Using an SSH key makes it unnecessary to enter your
GitHub credentials when you're interacting with GitHub from your local machine,
for example, pushing code up to GitHub. Setting up an SSH key is not necessary
to complete the material in this module, but if you'd like to, see **steps 6
through 11** in the **Configure Git** section of the relevant instructions:

- [Instructions for Mac users](https://github.com/learn-co-curriculum/phase-0-macos-env-git-github)
- [Instructions for Windows users](https://github.com/learn-co-curriculum/phase-0-wsl2-env-git-github)

### Text Editor

It will be much easier to follow along with the examples and exercises in this
module if you have a text editor installed on your local machine. We recommend
[Visual Studio Code][vscode] (VS Code) and will use it in the examples in this
module, but you are free to use whichever text editor you prefer.

## Conclusion

Now that you have these tools in place, you're ready to learn about version
control, Git, and GitHub.

## Resources

- [How to Check and Update Your Git Version][updating-git-version]

[updating-git-version]: https://www.howtogeek.com/759319/how-to-check-and-update-your-git-version/
[github-signup]: https://github.com/join
[vscode]: https://code.visualstudio.com/Download
