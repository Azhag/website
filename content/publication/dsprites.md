+++

# Title
title = "dSprites: Disentanglement testing Sprites dataset"
date = "2017-05-25"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Loic Matthey", "Irina Higgins", "Demis Hassabis", "Alexander Lerchner"]

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
publication_types = ["7"]

# Publication name and optional abbreviated version.
publication = "Github"
publication_short = ""

# Abstract and optional shortened version.
abstract = "This dataset consists of 737,280 images of 2D shapes, procedurally generated from 5 ground truth independent latent factors, controlling the shape, scale, rotation and position of a sprite. This data can be used to assess the disentanglement properties of unsupervised learning methods."
abstract_short = ""

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image thumbnail (optional)
image = "dsprites.gif"
image_preview = "dsprites.gif"

# Is this a selected publication? (true/false)
selected = true

# Links (optional)
url_pdf = ""
url_code = ""
url_dataset = "https://github.com/deepmind/dsprites-dataset/"
url_project = ""
url_slides = ""
url_video = ""

# Additional URLs
#[[url_custom]]
#name = ""
#url = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++


dSprites is a dataset of 2D shapes procedurally generated from 6 ground truth independent latent factors. These factors are color, shape, scale, rotation, x and y positions of a sprite.

All possible combinations of these latents are present exactly once, generating N = 737280 total images.

See [Github](https://github.com/deepmind/dsprites-dataset) for a simple [Jupyter Notebook example](https://github.com/deepmind/dsprites-dataset/blob/master/dsprites_reloading_example.ipynb) using it and more informations.