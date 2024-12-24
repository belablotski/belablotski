# Installation and setup

## Install Hugo

1. Install Hugo for Debian Linux (ChromeOS) `sudo dpkg -i /mnt/chromeos/MyFiles/Downloads/hugo_extended_0.140.1_linux-amd64.deb` binaries are from [hugo/releases](https://github.com/gohugoio/hugo/releases)
2. Unfortunately Debian package repo has very old version, but `sudo apt install hugo` still works.

## Hosting

1. [GitHub Pages](https://gohugo.io/hosting-and-deployment/hosting-on-github/)

# Pages

1. Create page `hugo new content content/posts/my-first-post.md`

# Preview and publish

## Preview

1. Local site `hugo server`
2. Preview your work before publishing `hugo server --buildDrafts --buildFuture`