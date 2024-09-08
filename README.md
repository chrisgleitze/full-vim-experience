---
title: My Vim journey
permalink:
date: 2024-09-03
---

My Vim journey - Neovim recommendations, Vim lessons, Vim in the browser and OS

Here I recommend how you can start your Vim journey, use Neovim and eventually use quick Vim-style navigation in the browser and Operation System (OS).

# The problem: Navigating a decentralized, innovative ecosystem

Vim was released in 1991. It's a legendary text editor that makes navigating and editing code easy and fast with very specific keyboard motions. Neovim is a fork of Vim which roughly means that some people took Vim and made something new out of it. They wanted Vim to be more customizable and extensible, so they made Neovim. You can write your own plugins or fork existing plugins and change them to your gusto.

A decentralized information system like the one for Neovim is a blessing and a curse. The blessing is the innovation and wide variety of sources of information. Users come up with new, often easier ways of how to do something in the editor. And to understand Neovim you can read documentation, blog and reddit posts or watch videos on YouTube.

The curse is that you need to find your way through the Neovim jungle. What plugin should I use to create and rename files? nvim-tree, Neotree or Oil? Or should I just use Vim’s built-in functionality for that and not use a plugin? The short answer is: You need to find out for yourself.

The longer answer is: Read this blog article or watch the accompanying YouTube videos.

# tl;dr - just give me the summary

The situation: You’re coding in an IDE like VS Code, IntelliJ, Emacs or whatever else. “I want to try Vim but I don’t know where to start.”

Here's my suggestion for how to start and progress:

Use [Vim in VS Code](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim), [IntelliJ](https://www.jetbrains.com/help/idea/using-product-as-the-vim-editor.html) or what ever your current IDE is to see if you like it.
If you do and you want the full Vim in Neovim experience, then
A) build your own Neovim config if you’re an advanced programmer
OR
B) use a Neovim distribution, a so called “distro”. That is an out of the box Neovim configuration that includes everything you need, so you can start coding right away. I highly recommend the [LazyVim](https://www.lazyvim.org/) distro.
For efficient keyboard-only navigation in the browser use [Vimium](https://vimium.github.io/) in Chrome and Firefox.
For efficient keyboard-only navigation on OS use [Fluent Search](https://fluentsearch.net/) on Windows and [Homerow](https://www.homerow.app/) on Mac.

# Why Vim? And what makes it so good?

Once you're used to coding with Vim, coding without Vim will feel like editing code in Word (yes, the Windows program). Coding with Vim feels like working on code with an editor that is specifically tailored to navigating and editing code efficiently, or any text for that matter. A legendary Vim book is called "Practical Vim: Edit Text at the Speed of Thought" by Drew Neil. The title hits the nail on the head: You can do with your text whatever comes to mind lightning fast.

Examples: efficient multi-line editing, quick navigation of complex codebases

# Distro or building your own config?

My recommendations are the following:

Do you want to start with Vim and you’re on VS Code, a Jetbrains IDE etc.? Stay in your chosen editor. Use the Vim mode there first to get a taste of Vim. If you like it and you want to continue to use it, then you can think about starting to use Neovim.

If you do want to use Neovim, then you got two options: Build your own Neovim config or use a distro. I strongly recommend to build your own Neovim config only if you're an advanced programmer. Handling LSPs (Language Server Protocols) and auto-complete functionality can get quite complex and is not as straight forward to setup as you'd like it to be.

With a Neovim distro like NVChad, LunarVim, AstroVim or LazyVim you get everything you need and more out of the box. I recommend LazyVim as it's viewed as a new standard in the Neovim community and I can attest to how good it is because I use it myself. Careful: LazyVim is [a Neovim distro](https://www.lazyvim.org/) and lazy.nvim is [a Neovim plugin manager](https://github.com/folke/lazy.nvim) built by the same developer.

# Know why! Understand the concepts, don’t just memorize the motions

So, don’t just memorize that ‘A’ is to go into insert mode at the end of a line. Understand that ‘a’ stands for ‘append’ which means “to add something to the end of a piece of writing” (Cambridge). You add something to the end of a line. That’s also why it’s called the Appendix of a book, “a separate part at the end of a book or magazine that gives extra information” (Cambridge). You’ll notice the consistency of the Vim motions when you dive into plugins. E.g. with neo-tree, a file manager, you can add files and directories simply with ‘a’ in the file explorer. Once you're familiar with the underlying concepts, learning new plugins and advanced motions will get easier.

If you know this then other stuff in Vim or Neovim will make more sense to you. You want to create a new file with the Neotree plugin? Click ‘a’ to add a file.

Another example: In RegEx (Regular Expressions) $ indicates the end of the string. In Vim with '$' in normal mode you jump to the end of a line. This stuff doesn’t happen by coincidence.

Borrow from the right people
Like this handy little command to edit all occurrences of a word in a file. I copied that one from a video from the Primeagen.

# Vim navigation in the Browser

gg
G

# Vim navigation on Windows/Apple/Linux
