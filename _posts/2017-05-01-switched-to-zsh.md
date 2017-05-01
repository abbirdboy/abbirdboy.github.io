---
layout: post
title: Switched to Zsh
tags: 
  - bash
  - zsh
  - terminal
  - workflow
---

*TLDR;* `bindkey -e` in .zshrc to enable Emacs bindings.

Some time ago I wrote a blog about [Mastering Bash and Terminal](https://www.blockloop.io/mastering-bash-and-terminal). In that blog I commented on zsh and other shells and how I never felt comfortable with them. After watching a video of [Dan North](https://www.youtube.com/watch?v=7uwW20odwEk&t=7m) on Unix power use where he mentioned zsh I decided to give it another try and here’s why I think I’m sticking with zsh. Also, if you have not seen that video I highly recommend it. He covers more commands than I did in my previous post. Most of which I use daily.

Whenever I wrote the previous post I talked about keyboard shortcuts that I use like ALT+F, etc. I am a vim power user and have been for over ten years. Although I am a huge GNU fan, I have only ever fiddled with Emacs. Why does this matter? Well after being on top of Hacker News for some time I was humbly informed that those key bindings I was using were Emacs bindings. As it turns out, Bash (being a GNU project) defaults to Emacs (another GNU project) key bindings and that’s what I have been memorizing for almost twenty years. Who knew? Probably everyone but me.

*Before you reprimand me*: Years ago I used to pair program with a friend who used vim keybindings in bash and I hated it. When I am in vim I use vim. When I am in bash I use bash. Mixing the two was uncomfortable for me and even though I tried it on my own for a few weeks I couldn’t do it. I had to switch back to “default” keybindings. This time, after I installed zsh, knowing what to look for, I googled Emacs keybindings and found [this little gem](https://github.com/robbyrussell/oh-my-zsh/blob/5667161d49b9ddc4ea8de7a379d50fc2cb7ffb50/lib/key-bindings.zsh#L18). Once I dropped that into [my ~/.zshrc](https://dl.dropbox.com/s/o1amog09srbp7bc/.zshrc) I felt at home. My bash (Emacs) keybindings work in zsh!

![](https://dl.dropboxusercontent.com/s/ar1xqy7coy3bm9k/zsh-terminal.png)

## Bundlers and Distributions
For what it’s worth, I still don’t like the idea of Oh My Zsh just as I don’t like the idea of [spf13-vim](http://vim.spf13.com/) or any other vim distributions. I am a roll-your-own kind of user. Oh My Zsh is default for most of the people I know that use zsh. In fact, I have often seen Oh My Zsh become synonymous with zsh like git and GitHub. Github and git are not synonyms. Oh My ZSH and zsh are not synonyms. Oh My Zsh is a bundle of zsh with a bunch of features already included. I am a minimalist and only want a few small features that work well. I like to start with the basic installation and tack on things as I find them useful. 
