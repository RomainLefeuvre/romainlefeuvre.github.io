---
title: 'On the Effect of Feature Reduction on Energy Consumption: An Exploratory Study'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Xhevahire Tërnava  
  - Romain Lefeuvre
  - Quentin Perez
  - Djamel Eddine Khelladi
  - Mathieu Acher
  - Benoit Combemale


date: '2025-06-11T00:00:00Z'
doi: ''


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2025 ACM International Systems and Software Product Line Conference

publication_short: In *SPLC 2025*

abstract: Energy consumption has become a growing concern in the pursuit of a more sustainable software industry, particularly in advocating for its reduction. In the last decade, this issue has been increasingly investigated by the software engineering community. However, few studies have investigated it in configurable systems that can embed thousands of implemented features. As configurable systems become more complex, feature reduction can help focus on essential features while eliminating bloated and unnecessary ones. Although several studies have explored how feature interactions and runtime performance affect energy consumption, none, to our knowledge, have studied the impact of feature reduction. This paper fills this gap. In particular, we investigate how both on-demand and built-in feature reduction affect the energy consumption of configurable systems. On-demand reduction allows users to retain only the features necessary for their specific usage. In contrast, built-in reduction provides a predefined set of features tailored to address a fixed set of usage. We conducted a first exploratory study using 28 programs from three systems that offer built-in feature reduction, namely ToyBox, BusyBox, and GNU, along with 6 GNU programs debloated on-demand with Chisel, Debop, and Cov tools. In our results, built-in feature reduction led to statistically significant energy decreases in 7% of the cases, while on-demand reduction, despite achieving energy decreases in 67% of cases, showed no statistical significance. However, when energy consumption increased, it was often more substantial than the reductions observed (occurring in 25% of built-in cases and 11% of on-demand cases) showing the complex and sometimes counterintuitive interplay between feature reduction and energy. Additionally, the observed strong correlation between energy consumption and execution time motivates a shift from traditional debloating goals, centered on binary size/attack surface, to energy-aware strategies that prioritize performance concerns. Finally, we provide an in-depth analysis and discuss the perspective.  

# Summary. An optional shortened abstract.
summary: 'Configurable systems become more complex, feature reduction can help focus on essential features while eliminating bloated and unnecessary ones. Although several studies have explored how feature interactions and runtime performance affect energy consumption, none, to our knowledge, have studied the impact of feature reduction. This paper fills this gap. In particular, we investigate how both on-demand and built-in feature reduction affect the energy consumption of configurable systems.' 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---

Camera Ready to be published 