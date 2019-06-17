# SciPy 2019 `xonsh` tutorial

# Getting started

We're excited to show you `xonsh` and we hope this is the beginning of a long friendship!
Before we get started, we need to get `xonsh` installed on your machine, but
don't worry, it's not too hard!

## Installation with `conda`

`xonsh` is available on conda-forge, so if you are a `conda` user you can install it by running

```console
$ conda install -c conda-forge xonsh
```

## Installation with `pip`

More of a `pip` fan?  No worries!  You can install `xonsh` by running

```console
$ pip install xonsh[ptk]
```

(the `[ptk]` bit ensures that you also install `prompt_toolkit`. While this
isn't a strict dependency of `xonsh` it does allow for a bunch of cool features
we'll cover in this tutorial)

## Test it out!

We aren't going to ask you to switch over to `xonsh` as your default shell right
away, that's a big decision. But let's make sure it can start up correctly!

The simplest way to start `xonsh` is to open up your terminal emulator of choice and type:

```console
$ xonsh
```

You _should_ be greeted with something like the following:

```
Welcome to the xonsh shell (0.9.4)

                                       ~ Exofrills in the shell ~

--------------------------------------------------------------------------------------------------------
xonfig tutorial    ->    Launch the tutorial in the browser
xonfig wizard      ->    Run the configuration wizard and claim your shell
(Note: Run the Wizard or create a ~/.xonshrc file to suppress the welcome screen)

gil@badcatredux ~ $
```

If that worked, you can type `exit` to return to your current default shell.
