+++
title = "Joint longitudinal hurdle and time-to-event models: an application related to viral load and duration of the first treatment regimen in HIV patients initiating therapy"
date = "2016-03-29"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Brilleman SL", "Crowther MJ", "May M", "Gompels M", "Abrams K"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "*Statistics in Medicine*"
publication_short = ""

# Abstract and optional shortened version.
abstract = "Shared parameter joint models provide a framework under which a longitudinal response and a time to event can be modelled simultaneously. A common assumption in shared parameter joint models has been to assume that the longitudinal response is normally distributed. In this paper, we instead propose a joint model that incorporates a two-part ‘hurdle’ model for the longitudinal response, motivated in part by longitudinal response data that is subject to a detection limit. The first part of the hurdle model estimates the probability that the longitudinal response is observed above the detection limit, whilst the second part of the hurdle model estimates the mean of the response conditional on having exceeded the detection limit. The time-to-event outcome is modelled using a parametric proportional hazards model, assuming a Weibull baseline hazard. We propose a novel association structure whereby the current hazard of the event is assumed to be associated with the current combined (expected) outcome from the two parts of the hurdle model. We estimate our joint model under a Bayesian framework and provide code for fitting the model using the Bayesian software Stan. We use our model to estimate the association between HIV RNA viral load, which is subject to a lower detection limit, and the hazard of stopping or modifying treatment in patients with HIV initiating antiretroviral therapy"

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.

# Links (optional).
url_pdf = "http://onlinelibrary.wiley.com/doi/10.1002/sim.6948/full"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
url_custom = [{name = "NCBI", url = "https://www.ncbi.nlm.nih.gov/pubmed/27027882"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""
+++
