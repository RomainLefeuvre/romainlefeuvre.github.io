---
title: 'Evaluating the Energy Profile of Tasks Managed by Build Automation Tools in Continuous Integration Workflows: The Case of Apache Maven and Gradle'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Sérgio Queiroz de Medeiros 
  - Romain Lefeuvre
  - Quentin Perez
  - Benoit Combemale


date: '2025-06-11T00:00:00Z'
doi: 'hal-05090865v2'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: 2025 The International Conference on Information and Communications Technology for Sustainability

publication_short: In *ICT4S 2025*

abstract: There is a growing interest in the energy impact of computing-related activities, which is expected to increase in the coming years. Modern software development usually relies on Continuous Integration (CI) to support short iterations, where code changes are integrated on a daily basis. The implementation of CI workflows usually relies on build automation tools, (e.g. Apache Maven or Gradle), to automate several activities such as testing or compiling. The large adoption of CI practices raises concerns about the impact of such tasks usually run on cloud environments, where the underlying hardware and its associated energy consumption remain intangible to developers. To better understand the energy footprint related to modern software development, it is essential to investigate the energy profile of the tasks managed by Apache Maven and Gradle. To achieve such goal, we performed a large-scale study with 1167 CI workflows implemented through GitHub Actions and mined from popular Java projects hosted on GitHub. After executing them locally, in a controlled environment, we analyzed in depth the energy profile of 183 355 tasks managed by Apache Maven and Gradle. These tasks represent a quarter of the total energy consumption associated with the CI workflows. We found that tasks from workflows of small-sized projects do not necessarily consume less energy than tasks from workflows of medium-sized and largesized projects. We also found that testing-related tasks consume the most energy, and that the larger the project, the higher the percentage of energy consumption related to testing. Moreover, tasks of different categories have a different profile regarding energy consumption per task and per unit of time.  

# Summary. An optional shortened abstract.
summary: 'In this paper, we investigate the energy profiles of Continuous Integration (CI) tasks managed by Maven and Gradle. Build systems like Maven and Gradle, with their internal models, provide opportunities for fine-grained classification, which we leverage to study energy-intensive tasks and their associated profile.' 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hal.science/hal-05090865v2/document'
url_code: 'https://archive.softwareheritage.org/browse/revision/17b995c36af45da00e1ad5bc48f3ad460ef7abc6/?origin_url=https://github.com/RomainLefeuvre/ICT4S_2025'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'ICT4S_25.pdf'
url_source: ''
url_video: ''


---
