# Game Theory Summer School – Kyiv 2025

This repository contains the materials for my presentation at the **2025 Summer School on Game Theory** in **Kyiv**.

You can find more information about the summer school [here](https://game-theory-school.kse.ua).


## 📚 Lecture Title and Abstract

Title: A computational approach to cooperation

Description:

The Iterated Prisoner’s Dilemma (IPD) has long been a cornerstone model for
understanding behavioral interactions and the emergence of cooperation. From
early successes of strategies like Tit for Tat to the development of
zero-determinant strategies and contemporary implementations using neural
networks, the IPD remains a powerful framework for exploring strategic behavior.

In this lecture, we will introduce the fundamental concepts of repeated games,
strategies, and computer tournaments. We will focus on how data-driven
approaches can help us understand what makes a strategy successful.

A central part of the discussion will be the `Axelrod-Python` library, an
open-source tool for simulating and analyzing strategic interactions in the IPD.
We will demonstrate how it can be used to run large-scale round-robin
tournaments, and train strategies using reinforcement
learning. We will also explore how this framework enables us to ask new,
previously unexplored research questions.

This lecture offers a computational perspective on cooperation and is aimed at
anyone interested in game theory, behavioral modeling, or data-driven research
in social science.


## 📝 Material

This repository includes the following:

1. **Lecture slides.** You’ll find the slides used during the talk in the `slides/` folder.

2. **Jupyter notebooks.** Throughout the presentation, we switched to Jupyter
   notebooks to showcase interactive code examples using the
   [Axelrod-Python](https://axelrod.readthedocs.io/en/stable/) package. These
   notebooks can be found in the folder `nbs`. Namely,

   * [Matches_and_tournaments](./nbs/Matches_and_tournaments.ipynb)
   * [Training_strategies](./nbs/Training_strategies.ipynb)

3. **Literature folder.** PDFs of the papers referenced in the lecture and
   useful for your projects can be found in the `literature/` folder.

4. **Final case study** – In the last part of the lecture, we discussed the
   following publication: [Properties of winning Iterated Prisoner’s Dilemma
   strategies](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1012644).
   The dataset used in the paper is archived and publicly available
   [here](https://zenodo.org/records/3753498). The code for analyzing
   the results can be found: [https://github.com/Nikoleta-v3/meta-analysis-of-prisoners-dilemma-tournaments](https://github.com/Nikoleta-v3/meta-analysis-of-prisoners-dilemma-tournaments).


## ▶️ How to Run the Code

To run the notebooks:

1. Install [Anaconda](https://www.anaconda.com/), the easiest way to get Python and Jupyter Notebooks up and running.
2. The only required package is **Axelrod-Python**. You can install it via pip:

```bash
pip install axelrod
```

Or refer to the official documentation: [Axelrod-Python Docs](https://axelrod.readthedocs.io/en/stable/)


## ⬇️ Download the Material

To download the materials in this repository, you have two options:

### Option 1: Direct Download

Click the green **Code** button at the top right of the repository page and select **Download ZIP**.

### Option 2: Clone via Git

If you have Git installed, run the following in your terminal:

```bash
cd Desktop  # Or navigate to any folder where you'd like to save the material
git clone git@github.com:Nikoleta-v3/Game-theory-summer-school-Kyiv.git
```