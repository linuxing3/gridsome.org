---
title: My emacs development workflow
author: Xing Wenju
date: 2018-11-18
excerpt: "Awesome and fluid workflow with emacs when developing"
---

# My Daily Emacs workflow

## Doom Emacs

As you know, I’m fond of the notion of living in Emacs to the greatest extent
possible. For me, that’s an ongoing process:a process that is always seeking
perfection but that is never complete.

One of the highest learning curves I have ever had to deal with was getting into
`Emacs`. `Doom` is very much built around Evil Mode. I also would like to call
my Emacs configuration EOS, The Emacs Operating System. It’s a thing of beauty.
Those modules are supported with a powerful configuration made by `doom emacs`,
a configuration for stuborn emacs user.

To get started, make sure you have Emacs installed and then follow the [Doom
installation guide](https://github.com/hlissner/.emacs.d#installation)

The `module` setup is nice because it allows you to choose the parts that
support your workflow while ignoring the rest. If you have a minimal
configuration, a good strategy would be to clone EOS, make the changes that are
sensible for your workflow, and then install it.

If you already have an extensive configuration, `doom’s configuration` will
serve as a model for rationalizing your configuration’s structure and as a
source of ideas for additions to your configuration.

Even if you aren’t interested in moving your life into Emacs, doom’s
configuration is worth looking at for the many ideas you can mine from it. It’s
an excellent resource.

## Edit my `doom` configuration

`ctrl-enter` to jump to `doom emacs private dir`, like `~/.doom.d`

`SPC-p-/` to find and edit `module`, like the `config` files

`ctrl-enter` to jump to `user emacs dir`, like `~/.emacs.d`

`SPC-p-!` to run `bin/doom refresh` to start install and generate autoloads

`SPC-r` to reload settings

## Writing a blog

`SPC-SPC` to call `my-gridsome-create-newpost-empty`

`SPC-p-!` to call `projectile-run-command-in-root` and then type
`deploy-master`, this will push to `github` and deploy directly in [My Gridsome
Blog](https://gridsome.netlify.com)

`ctrl-c ctrl-c` in `org` file and generate a `plantuml` image and sync to
`dropbox` and insert in this blog

![plantuml](https://www.dropbox.com/s/9c0tewnhc6st34r/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202018-11-18%2021.11.38.png?dl=0)

## Start a agenda and capture

`f9` to quickly capture anything, `blog`, `billing`, `bookmark`, `gtd`, etc.

`f10` to open my `agenda`

All changes will be saved to my `dropbox/org` directory and automatically
synchronized.

## Frontend Development

![editing1](https://www.dropbox.com/s/d6fd2pp50js4wcd/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202018-11-18%2020.57.43.png?dl=0)

![editing3](https://www.dropbox.com/s/eruprwitzttfuli/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202018-11-18%2021.08.32.png?dl=0)

![editing2](https://www.dropbox.com/s/z64hl19njf66gi2/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202018-11-18%2021.07.22.png?dl=0)

![editing4](https://www.dropbox.com/s/yx0ssjomfiqexax/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202018-11-18%2021.09.36.png?dl=0)

`ctrl+enter` to jump to my project

`f4` to review the directory structure

`SPC-.` to open files under my project

`SPC-p-/` to find files under my project

`i` start the `insert` mode and start editing a `store.ts` in my `vue` project

`jk` to exit to `normal` mode

`f12` to jump to the definition of a variable or methods

`SPC-w-v` to vertically split a window and refer to `component.vue` file

`SPC-w-v` to vertically split a window and refer to `router.ts` file

`/**` to trigger `js-doc` to write a function doc

`SPC-p-!` to call `yarn test:unit` to start a test or `yarn story` to start a
`storybook`. Another way is to `SPC-SPC-eshell` to call a `eshell`

`SPC-p-p` to switch to another project

`Meta-t` to open a new workspace

`[-b` to switch to previews buffer and `]-b` to switch to next buffer

`SPC-b-k` to kill the buffer

`Meta-number` to go back to any workspace

Continue the workflow...

``