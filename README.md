# Thesis

This repo is where I will write my PhD thesis.
See [this doc](https://docs.google.com/document/d/1Ez7LculGFcjLHr-peoyE0Qa1vGOFB6jmgUzD6eyO7vc/edit?usp=sharing) 
for planning and organisation.


## How to compile the tex

I'm using [this template](https://github.com/kks32/phd-thesis-template) for
the thesis. In order to make it work, I had to run the following commands to
install missing packages:

```
sudo apt install latexmk
sudo apt-get install texlive-science
```

The tex is compiled by running the following command:

```
latexmk -pdf thesis
```
