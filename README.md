# COS561 Final Project

Some quick notes

1. I created a "fork" repository of the Gitlab ns-3 development repository at [https://github.com/cdgreenidge/ns-3-cos561]. It's not a Github-style fork since the original is on Gitlab, basically the `upstream` remote points to the Gitlab repo and the `origin` remote (when you clone it) should point to `cdgreenidge/ns-3-cos561`. I made a `dev` branch off of tag `ns-3.32`, which is the latest release as of 2020-10-19. I think we can do our TCP congestion control development on this branch.
2. This repository includes `cdgreenidge/ns-3-cos561` as a submodule. Our sim scripts and data analysis/plotting code/latex can go in other directories. Make sure to run `git submodule update --init --recursive` after cloning to grab the ns-3 code.
