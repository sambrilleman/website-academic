+++
date = 2017-07-12T00:00:00  # Schedule page publish date.

title = "Bayesian joint models for multiple longitudinal biomarkers and a time-to-event outcome: software development and a melanoma case study"

time_start = 2017-07-12

abstract = "Methodological developments in the joint modelling of longitudinal and time-to-event data abound. Implementations of various versions of this methodology now enable researchers to fit joint models using standard statistical software packages. Yet the software options available to users remain limited in several respects. In particular, situations in which there are multiple longitudinal markers are not well accommodated. The modelling of longitudinal biomarker data in patients diagnosed with melanoma, and their association with the risk of clinical events such as death or disease progression, is one situation in which such extensions would prove useful. A framework for fitting a multivariate joint model can be specified as follows. The longitudinal biomarkers are each modelled using a generalized linear mixed model, whilst the time-to-event is modelled through a parametric proportional hazards regression model. Dependence between the multiple biomarkers within a subject is captured through shared subject-specific random effects following a multivariate normal distribution. Dependence between each biomarker and the time-to-event can be parameterised in a variety of ways. This project motivated the development of general purpose software that allows users to fit these multivariate joint models under a Bayesian approach, now implemented as part of the rstanarm R package. Using data from the Melanoma Institute Australia, I will demonstrate how these models can be used to provide insights into the relationships between patient-specific longitudinal trajectories for biomarkers such as LDH, neutrophils and lymphocyte counts, and the risk of either death or disease progression."

event = "38th Annual Conference of the International Society for Clinical Biostatistics"
event_url = "http://iscb2017.info/"
location = "Vigo, Spain"

# Is this a selected talk? (true/false)
selected = true

# Links (optional).
url_slides = "slides/2017_contributed_ISCB"

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true

+++

{{< speakerdeck a06ef2c98c6349b19f7b8721a2d1c3c8 >}}