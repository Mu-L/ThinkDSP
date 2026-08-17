# ThinkDSP

*Think DSP* is an introduction to Digital Signal Processing in Python.

[Order *Think DSP* from Amazon.com](http://amzn.to/1naaUCN).

[Download the first edition in PDF](https://github.com/AllenDowney/ThinkDSP/raw/master/book/thinkdsp.pdf).

[Download the first edition in EPUB](https://github.com/AllenDowney/ThinkDSP/raw/master/book/thinkdsp.epub).

[Read the second edition draft in HTML](https://allendowney.github.io/ThinkDSP2/index.html).

The premise of this book (and the other books in the Think X series) is that if you know how to program, you can use that skill to learn other things. I am writing this book because I think the conventional approach to digital signal processing is backward: most books (and the classes that use them) present the material bottom-up, starting with mathematical abstractions like phasors.

With a programming-based approach, I can go top-down, which means I can present the most important ideas right away. By the end of the first chapter, you can decompose a sound into its harmonics, modify the harmonics, and generate new sounds.

Here's a notebook that previews what you will see in Chapter 1:

* [chap01.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap01.ipynb)

And if you want to see where we are headed, here's a preview of Chapter 10:

* [chap10.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap10.ipynb)

Think DSP is a Free Book. It is available under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/), which means that you are free to copy, distribute, and modify it, as long as you attribute the work and don't use it for commercial purposes.

## Which repository?

*Think DSP* has two GitHub homes.

* This repository, [ThinkDSP](https://github.com/AllenDowney/ThinkDSP), contains the LaTeX source for the published first edition, the source code for the `think-dsp` package, and two notebooks for each chapter, one with examples and exercises, the other with solutions. It is the home of the PDF and EPUB versions of the book. A frozen first-edition HTML build still lives on Green Tea Press; the HTML to read is the ThinkDSP2 draft.

* A newer repository, [ThinkDSP2](https://github.com/AllenDowney/ThinkDSP2), contains a draft second edition with one Jupyter notebook per chapter and a more polished HTML generated with [Jupyter Book](https://allendowney.github.io/ThinkDSP2/index.html).

If you have the published first edition and are looking for the supporting materials, you probably want [ThinkDSP](https://github.com/AllenDowney/ThinkDSP).
If you are just getting started and you want the most current version, you might want [ThinkDSP2](https://github.com/AllenDowney/ThinkDSP2).


## Running the code

The code for this book is in Jupyter notebooks.
If you are not familiar with Jupyter, you can run a tutorial by [clicking here](https://jupyter.org/try).
To run the ThinkDSP code, you have several options:

1. **Google Colab** — Best for a quick start: no local install, works in a browser, free.
2. **Conda on your computer** — Best for a stable local setup and offline work.
3. **Poetry on your computer** — Best if you already use Poetry / prefer a project-local virtualenv.

The following sections explain these options in detail.

Note: I have heard from a few people who tried to run the code in Spyder.  Apparently there were problems, so I don't recommend it.

### Option 1: Run on Colab

Most of the notebooks in this repository also run on Colab. If you find one that doesn't, let me know and I will update it.

You can open any of them by clicking on the links below.  If you want to modify and save any of them, you can use Colab to save a copy in a Google Drive or your own GitHub repo, or on your computer.

* [chap01.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap01.ipynb)
* [chap01soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap01soln.ipynb)
* [chap02.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap02.ipynb)
* [chap02soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap02soln.ipynb)
* [chap03.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap03.ipynb)
* [chap03soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap03soln.ipynb)
* [chap04.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap04.ipynb)
* [chap04soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap04soln.ipynb)
* [chap05.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap05.ipynb)
* [chap05soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap05soln.ipynb)
* [chap06.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap06.ipynb)
* [chap06soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap06soln.ipynb)
* [chap07.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap07.ipynb)
* [chap07soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap07soln.ipynb)
* [chap08.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap08.ipynb)
* [chap08soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap08soln.ipynb)
* [chap09.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap09.ipynb)
* [chap09soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap09soln.ipynb)
* [chap10.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap10.ipynb)
* [chap10soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap10soln.ipynb)
* [chap11.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap11.ipynb)
* [chap11soln.ipynb](https://colab.research.google.com/github/AllenDowney/ThinkDSP/blob/master/nb/chap11soln.ipynb)


### Option 2: Install Python+Jupyter with Conda

First, download the files from this repository.  If you are a Git user, you can run

```
git clone --depth 1 https://github.com/AllenDowney/ThinkDSP.git
```

Otherwise you can [download this Zip file](https://github.com/AllenDowney/ThinkDSP/archive/master.zip) and unzip it.
Either way, you should end up with a directory called `ThinkDSP`.

Now, if you don't already have Jupyter, I highly recommend installing Anaconda, which is a Python distribution that contains everything you need to run the ThinkDSP code.  It is easy to install on Windows, Mac, and Linux, and because it does a
user-level install, it will not interfere with other Python installations.

[Information about installing Anaconda is here](https://www.anaconda.com/distribution/).

There are two ways to get the packages you need for ThinkDSP.  You can install them by hand or create a Conda environment.

To install them by hand run

```
conda install jupyter numpy scipy pandas matplotlib seaborn
```

Or, to create a conda environment, run

```
cd ThinkDSP
conda env create -f environment.yml
conda activate ThinkDSP
```

Once the environment is active, open the notebooks under `nb/`. You do not need to `pip install think-dsp`; see [Install](#install) if you want the library in your own code.


### Option 3: Install Python+Jupyter with Poetry

Clone the repository as in Option 2. Then, assuming you have [Poetry](https://python-poetry.org) installed, run

```
cd ThinkDSP
poetry install --extras notebooks
```

to install the libraries you need in a virtual environment. Start Jupyter with

```
poetry run jupyter notebook
```

(`poetry shell` is deprecated in recent Poetry.) Then see [Install](#install) if you want the `thinkdsp` library in your own code.


## Install

How you get the `thinkdsp` library depends on what you are doing:

1. If you are running the chapter notebooks, you do not need to install the `think-dsp` package. Notebooks download `thinkdsp.py` into the working directory when you run them. If you already set up Conda or Poetry above, you have the notebook stack. Otherwise:

   ```bash
   pip install -r requirements.txt
   ```

2. If you want to use the `thinkdsp` library in your own code, you can install the `think-dsp` package from PyPI:

   ```bash
   pip install think-dsp
   ```

   Most readers will not need to do this.

3. If you want to do development in this repository, you can install an editable checkout plus the development tools that test the code:

   ```bash
   pip install -r requirements-dev.txt
   ```

   Or with conda: `make create_environment_dev` (also does `pip install -e .`).

Chapter notebooks live under `nb/`. Shared datasets (CSV, WAV) live under `data/`.


## Building the book

The LaTeX source for the first edition is in `book/`, and `book/book.tex` is the single source for every output format.

### PDF

Requires a LaTeX distribution (TeX Live, MacTeX, or `texlive-latex-extra` on Debian
and Ubuntu):

```bash
cd book
make
```

### EPUB

Produces a reflowable EPUB3 with MathML equations, suitable for e-readers:

```bash
cd book
make epub          # writes build/epub/thinkdsp.epub
```

Requires [Pandoc](https://pandoc.org) 3 or later and
[Poppler](https://poppler.freedesktop.org) (for `pdftocairo`, which rasterizes the
vector figures into PNGs that e-readers can display):

```bash
brew install pandoc poppler              # macOS
sudo apt install pandoc poppler-utils    # Debian / Ubuntu
```

No LaTeX installation is needed for the EPUB. The build rewrites a copy of
`book.tex` under `build/epub/`; the original is never modified. Figures are
rendered at 150 dpi by default, which fits a typical e-ink screen — override with
`make epub EPUB_DPI=200`.

To validate the result, install [EPUBCheck](https://www.w3.org/publishing/epubcheck/)
(`brew install epubcheck`, or `sudo apt install epubcheck`) and run:

```bash
make epub-check
```

Three errors are expected and harmless: two links in Chapter 5 come from `\url{}`
being used for a bare domain and a filename in `book.tex`, and one figure
cross-reference between chapters is not rewritten by Pandoc when it splits the
book into per-chapter files.

Use `make epub-clean` to remove the build directory.

### HTML

The HTML to read is the second-edition Jupyter Book draft:
[ThinkDSP2](https://allendowney.github.io/ThinkDSP2/index.html).

The first-edition Hevea HTML on Green Tea Press is frozen and is not
updated by a routine release. Rebuilding with `make hevea` is optional
legacy tooling.

## Freesound

Special thanks to Freesound (http://freesound.org), which is the source of many of the sound samples I use in this book, and to the Freesound users who uploaded those sounds.  I include some of their wave files in
the GitHub repository for this book, using the original file
names, so it should be easy to find their sources.

Unfortunately, most Freesound users don't make their real names
available, so I can only thank them using their user names.  Samples
used in this book were contributed by Freesound users: iluppai,
wcfl10, thirsk, docquesting, kleeb, landup, zippi1, themusicalnomad,
bcjordan, rockwehrmann, marcgascon7, jcveliz.  Thank you all!

Here are links to the sources:

http://www.freesound.org/people/iluppai/sounds/100475/

http://www.freesound.org/people/wcfl10/sounds/105977/

http://www.freesound.org/people/Thirsk/sounds/120994/

http://www.freesound.org/people/ciccarelli/sounds/132736/

http://www.freesound.org/people/Kleeb/sounds/180960/

http://www.freesound.org/people/zippi1/sounds/18871/

http://www.freesound.org/people/themusicalnomad/sounds/253887/

http://www.freesound.org/people/bcjordan/sounds/28042/

http://www.freesound.org/people/rockwehrmann/sounds/72475/

http://www.freesound.org/people/marcgascon7/sounds/87778/

http://www.freesound.org/people/jcveliz/sounds/92002/
