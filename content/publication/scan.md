+++

# Title
title = "SCAN: Learning Abstract Hierarchical Compositional Visual Concepts"
date = "2017-07-11"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Irina Higgins", "Nicolas Sonnerat", "Loic Matthey", "Arka Pal", "Christopher P Burgess", "Matthew Botvinick", "Demis Hassabis", "Alexander Lerchner"]

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
# 8 = ArXiv
publication_types = ["8"]

# Publication name and optional abbreviated version.
publication = "arXiv"
publication_short = ""

# Abstract and optional shortened version.
abstract = "The natural world is infinitely diverse, yet this diversity arises from a relatively small set of coherent properties and rules, such as the laws of physics or chemistry. We conjecture that biological intelligent systems are able to survive within their diverse environments by discovering the regularities that arise from these rules primarily through unsupervised experiences, and representing this knowledge as abstract concepts. Such representations possess useful properties of compositionality and hierarchical organisation, which allow intelligent agents to recombine a finite set of conceptual building blocks into an exponentially large set of useful new concepts. This paper describes SCAN (Symbol-Concept Association Network), a new framework for learning such concepts in the visual domain. We first use the previously published beta-VAE (Higgins et al., 2017a) architecture to learn a disentangled representation of the latent structure of the visual world, before training SCAN to extract abstract concepts grounded in such disentangled visual primitives through fast symbol association. Our approach requires very few pairings between symbols and images and makes no assumptions about the choice of symbol representations. Once trained, SCAN is capable of multimodal bi-directional inference, generating a diverse set of image samples from symbolic descriptions and vice versa. It also allows for traversal and manipulation of the implicit hierarchy of compositional visual concepts through symbolic instructions and learnt logical recombination operations. Such manipulations enable SCAN to invent and learn novel visual concepts through recombination of the few learnt concepts."
abstract_short = "This paper describes SCAN (Symbol-Concept Association Network), a new framework for learning recombinable concepts in the visual domain. We first use the previously published beta-VAE (Higgins et al., 2017a) architecture to learn a disentangled representation of the latent structure of the visual world, before training SCAN to extract abstract concepts grounded in such disentangled visual primitives through fast symbol association."

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image thumbnail (optional)
image = "scan_hierarchy_walking.gif"
image_preview = "scan_hierarchy_walking.gif"

# Is this a selected publication? (true/false)
selected = true

# Links (optional)
url_pdf = "https://arxiv.org/abs/1707.03389"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""

# Additional URLs
[[url_custom]] 
name = "DeepMind blog"
url = "https://deepmind.com/blog/imagine-creating-new-visual-concepts-recombining-familiar-ones/"

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++
