# Neovim Homepage

> The Vim text editor has been loved by a generation of users.
> This is the next generation.

## Navigation

- Planned features
- Getting involved
- FAQs
- Contributing
- Installing

## Project Goals

### More powerful plugins

Neovim plans to think of plugins from the start and provide a system that allows
for extension in any language. The idea is to allow plugins to be co-processes
that communicate with Vim asynchronously. This allows the plugin to listen for
events and to send commands to Vim at anytime.

Your old plugins will still work as well as compatibility layers will be
provided. Little to no modification will be required.

### Better GUI architecture

Neovim will focus on providing a headless text editing environment. This will
allow any GUI to be written that ties into the native GUI of whatever operating
system it is running on.

### First class support for embedding

Since Neovim will be provide the interface to interacting with text, any program
will be able to tap into this potential and be able to include Neovim commands
right in the application.

## Latest development practices

[GitHub][github] has changed how developers do open source. Neovim will use the
features of GitHub to create a cohesive development environment with GUI's,
plugins, runtime files, and distributions all in one place.

Continuous integration through [TravisCI][travis] will provide seamless testing
and ensure that changes don't break existing features.

## Getting invovled

### Community

- GitHub: [Neovim][neovim-org]
- Twitter: [@Neovim][twitter]
- Discussion: [Google Group][google-group]

### Developer

The development is happening in the [GitHub repository][github]. With discussion
in the IRC `irc.freenode.net` **#neovim** channel. If you'd like to get involved
in the development process start by joining there.

## FAQs

[github]: https://github.com
[google-group]: https://groups.google.com/forum/#!forum/neovim
[neovim-org]: https://github.com/neovim
[neovim]: https://github.com/neovim/neovim
[travis]: https://travis-ci.org/
[twitter]: https://twitter.com/neovim
