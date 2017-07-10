+++

# Title
title = "$\\beta$-VAE: Learning Basic Visual Concepts with a Constrained Variational Framework"
date = "2017-02-06"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Irina Higgins", "Loic Matthey", "Arka Pal", "Christopher Burgess", "Xavier Glorot", "Matthew Botvinick", "Shakir Mohamed", "Alexander Lerchner"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
# 7 = Dataset
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "5th International Conference on Learning Representations"
publication_short = "ICLR 2017"

# Abstract and optional shortened version.
abstract = "Learning an interpretable factorised representation of the independent data generative factors of the world without supervision is an important precursor for the development of artificial intelligence that is able to learn and reason in the same way that humans do. We introduce beta-VAE, a new state-of-the-art framework for automated discovery of interpretable factorised latent representations from raw image data in a completely unsupervised manner. Our approach is a modification of the variational autoencoder (VAE) framework. We introduce an adjustable hyperparameter beta that balances latent channel capacity and independence constraints with reconstruction accuracy. We demonstrate that beta-VAE with appropriately tuned beta > 1 qualitatively outperforms VAE (beta = 1), as well as state of the art unsupervised (InfoGAN) and semi-supervised (DC-IGN) approaches to disentangled factor learning on a variety of datasets (celebA, faces and chairs). Furthermore, we devise a protocol to quantitatively compare the degree of disentanglement learnt by different models, and show that our approach also significantly outperforms all baselines quantitatively. Unlike InfoGAN, beta-VAE is stable to train, makes few assumptions about the data and relies on tuning a single hyperparameter, which can be directly optimised through a hyper parameter search using weakly labelled data or through heuristic visual inspection for purely unsupervised data."
abstract_short = "Learning an interpretable factorised representation of the independent data generative factors of the world without supervision is an important precursor for the development of artificial intelligence that is able to learn and reason in the same way that humans do. We introduce beta-VAE, a new state-of-the-art framework for automated discovery of interpretable factorised latent representations from raw image data in a completely unsupervised manner."

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image thumbnail (optional)
image = "beta-vae.png"
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Links (optional)
url_pdf = "pdf/betavae_iclr_2017.pdf"
url_code = ""
url_dataset = "https://github.com/deepmind/dsprites-dataset"
url_project = ""
url_slides = ""
url_video = ""

# Additional URLs
[[url_custom]]
name = "Abstract & reviews"
url = "https://openreview.net/forum?id=Sy2fzU9gl"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

Accepted as a Conference Track paper at [ICLR 2017](http://www.iclr.cc/doku.php?id=iclr2017:main). 
Paper and reviews are available on [OpenReview](https://openreview.net/forum?id=Sy2fzU9gl).

A modification to the VAE framework that successfully learns disentangled factors of variations in a fully unsupervised manner.

Uses [dSprites](https://github.com/deepmind/dsprites-dataset) as one of the ground-truth dataset.