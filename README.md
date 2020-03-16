# Eighth Inning

The average life cycle of a computer for me is about 3 years; which means every time I have to set up a new one, I spend hours, if not days, trying to get it perfect. From installing the latest software for all of my various use cases to getting all of my personal settings and preferences, it becomes a very tedious operation.  It got me thinking to myself,

> How can I automate this process?

Inspired by a [few peoples](#acknowledgements) `.dotfiles` scripts, I decided to create this library for installing and setting up my OS X machines.

**Why a separate repository?**

I didn't like the connection between setting up your development machine, or `.dotfiles` and setting up your computer with various software and settings.  It appeared to me to be better served from a separate repository so that I could run both my dotfiles install and eighth-inning scripts concurrently if needed; or even better I didn't have to install my dotfiles on a machine that just needed some synchronized OS X settings.

## How to install

```bash
$ bash -c "$(curl -#fL raw.github.com/iamnewton/eighth-inning/go/install)" && \
    bash /tmp/eighth-inning/bin/eighth-inning
```

## Acknowledgements

Inspiration and code was taken from many sources, including:

* [@sindresorhus](https://github.com/sindresorhus) (Sindre Sorhus) https://github.com/sindresorhus/quick-look-plugins
* [@necolas](https://github.com/necolas) (Nicolas Gallagher) https://github.com/necolas/dotfiles
* [@mathiasbynens](https://github.com/mathiasbynens) (Mathias Bynens) http://mths.be/osx
