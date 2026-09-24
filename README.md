# edak82.github.io

## What this repository is

Hello this repository was creatd for my DSCI 521 class. It helps log my progress & teach me certain concepts of data science.

## What to install first

- Quarto, version 1.10.18
- uv, version 0.12.5
- R, version 4.6.1

##The exact commands, in order, from git clone to a built site. Copy-pasteable, shell and R, saying where each one is run.

Run these all in the terminal:

git clone git@github.com:edak82/edak82.github.io.git
cd Desktop/521\ dsci/edak82.github.io/
uv sync
r
renv::restore()
q()
uv run quarto render

## Where the built site lands and how to open it locally.

The built site is in **docs/index.html**
Open that file to open it locally.

## Where the data comes from, and whether the build needs the network to fetch it.

I used the palmerpenguins package [https://allisonhorst.github.io/palmerpenguins/] to get my data. 
The build does not need the network to fetch it.
