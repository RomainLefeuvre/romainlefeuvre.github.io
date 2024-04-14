---
title: "Reasoning over time into models with DataTime"
authors:
- Gauthier Lyan
- Jean-Marc Jézéquel
- David Gross-Amblard 
- Romain Lefeuvre
- Benoit Combemale
date: "2023-01-10"
doi: "https://doi.org/10.1007/s10270-023-01080-x"



# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Software and Systems Modeling"
publication_short: "SoSyM"

abstract: Models at runtime have been initially investigated for adaptive systems. Models are used as a reflective layer of the current state of the system to support the implementation of a feedback loop. More recently, models at runtime have also been identified as key for supporting the development of full-fledged digital twins. However, this use of models at runtime raises new challenges, such as the ability to seamlessly interact with the past, present, and future states of the system. In this paper, we propose a framework called DataTime to implement models at runtime which capture the state of the system according to the dimensions of both time and space, here modeled as a directed graph where both nodes and edges bear local states (i.e., values of properties of interest). DataTime offers a unifying interface to query the past, present, and future (predicted) states of the system. This unifying interface provides (i) an optimized structure of the time series that capture the past states of the system, possibly evolving over time, (ii) the ability to get the last available value provided by the system’s sensors, and (iii) a continuous micro-learning over graph edges of a predictive model to make it possible to query future states, either locally or more globally, thanks to a composition law. The framework has been developed and evaluated in the context of the Intelligent Public Transportation Systems of the city of Rennes (France). This experimentation has demonstrated how DataTime can be used for managing data from the past, the present, and the future and facilitate the development of digital twins.

# Summary. An optional shortened abstract.
summary: Models at runtime have been initially investigated for adaptive systems. Models are used as a reflective layer of the current state of the system to support the implementation of a feedback loop. More recently, models at runtime have also been identified as key for supporting the development of full-fledged digital twins. However, this use of models at runtime raises new challenges, such as the ability to seamlessly interact with the past, present, and future states of the system. In this paper, we propose a framework called DataTime to implement models at runtime which capture the state of the system according to the dimensions of both time and space, here modeled as a directed graph where both nodes and edges bear local states (i.e., values of properties of interest). DataTime offers a unifying interface to query the past, present, and future (predicted) states of the system. This unifying interface provides (i) an optimized structure of the time series that capture the past states of the system, possibly evolving over time, (ii) the ability to get the last available value provided by the system’s sensors, and (iii) a continuous micro-learning over graph edges of a predictive model to make it possible to query future states, either locally or more globally, thanks to a composition law. The framework has been developed and evaluated in the context of the Intelligent Public Transportation Systems of the city of Rennes (France). This experimentation has demonstrated how DataTime can be used for managing data from the past, the present, and the future and facilitate the development of digital twins.

tags:
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://inria.hal.science/hal-03921928/document
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

projects: []

---
