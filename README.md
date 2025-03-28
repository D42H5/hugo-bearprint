# ᕦʕ •ᴥ•ʔᕤ Bear Print

[![MIT license](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/D42H5/hugo-bearprint/blob/main/LICENSE)

## Overview

🐻 A lightweight [Hugo](https://gohugo.io/) theme based on [Bear
Blog](https://bearblog.dev) and [Hugo Bear
Blog](https://github.com/janraasch/hugo-bearblog), forked from
[Bear Cub](https://github.com/clente/hugo-bearcub).

**Bear Print** takes care of speed and optimization, so you can focus on writing
good content. It is free, multilingual, optimized for search engines,
no-nonsense, responsive, light, and fast. Really fast.

## Installation

Follow Hugo's [quick start](https://gohugo.io/getting-started/quick-start/) to
create an empty website and then clone **Bear Print** into the themes directory as
a [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules):

```sh
git submodule add https://github.com/D42H5/hugo-bearprint themes/hugo-bearprint
```

To finish off, append a line to the site configuration file:

```sh
echo 'theme = "hugo-bearprint"' >> hugo.toml
```

## Features

Currently, **Bear Print** sources all of its features directly from
[Bear Cub](https://github.com/clente/hugo-bearcub). As, or if, I
add features in the future, this section will be updated with summaries
of those changes.

## Configuration

**Bear Print**'s configuration closely matches the configuration of
[Bear Cub](https://github.com/clente/hugo-bearcub), but with some
differences:

```toml
# ... snip

# Multilingual mode config. More for information about how to setup translation,
# see https://gohugo.io/content-management/multilingual/
[languages]
  [languages.en]
    # ... snip
    [languages.en.params]
      madeWith = "Made with [Bear Print](https://github.com/D42H5/hugo-bearprint)"
      poweredBy = "Powered by [Hugo](https://gohugo.io)"

# ... snip
```

## Contributing

If you come across any problems while using **Bear Print**, you can file an
[issue](https://github.com/D42H5/hugo-bearprint/issues) or create a [pull
request](https://github.com/D42H5/hugo-bearprint/pulls).
