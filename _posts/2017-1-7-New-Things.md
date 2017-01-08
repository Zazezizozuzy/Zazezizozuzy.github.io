
---
post:
title: New Things
---

I think I've accomplished a good bit in the last couple days. First of all, I set up a Linux server. Most of my Linux experience is from messing around with a Raspberry Pi. Installation and initial setup was easy. User authorization and access is fairly simple. There are a few weird settings that I had to figure out. After that, I could use it as I do any other computer. This server will house the local repository for this blog. Git seems like a tool worth knowing how to use (part of the reason I set the blog up On GitHub). Along with that, I do use it at work. However, being a C# dev, I had to luxury of doing it through VS, which makes it a little easier. I wanted to learn what is actually happening with Git files, so I'm storing the repos on this machine. I will attempt to exclusively edit them through this machine as well. During setup, I just used the site editting tools. Having never used GitHub before, it was a good start. This setup instead forces me to edit locally (with nano) and push commits to the site to be loaded. I also had to pull down the master files and close them into a local repo. All good things to know. Now I'm currently typing this from that machine. The best thing I've learned from it: SSH. Part of the blog updating was the centralize everything and make it easily accessible. I wanted to be able to edit it from multiple machines. So, server is setup for me to store the files. The terminal/bash shell allows me to access the files and edit them with nano. SSH allows me to connect to that machine from either my desk at home, one at work, or on my laptop. And I just push changes back up to GitHub. It may seem very minor, but I'm happy with it. I've posted a few resources I used below. They are in a mixed order, but helped with some minor issues. 

[1]https://www.linux.com/learn/beginning-git-and-github-linux-users
[2]stackoverflow.com
[3]https://help.github.com/articles/adding-an-existing-project-to-github-using-the-command-line/
[4]http://www.makeuseof.com/tag/beginners-guide-setting-ssh-linux-testing-setup/

###What I haven't done yet

I do need to make this machine accessible externally. If I understand the SSH configs, it's currently only running with connection from local machines. Without knowing how to set static IP addresses in Linux (yet), I'm not sure how to direct the SSH listener out to the internet. Perhaps I'll read up on that tomorrow. If that works, the next step will be updating externally. Again, not a huge feat, but one I'll be happy with.

Thanks,
Z&#151;
