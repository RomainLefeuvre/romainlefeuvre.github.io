---
title: 'Software Frugality in an Accelerating World: the Case of Continuous Integration'

type: publication
layout: single
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Quentin Perez
  - Romain Lefeuvre
  - Thomas Degueule
  - Olivier Barais
  - Benoit Combemale


date: '2024-01-01T00:00:00Z'
doi: 'arXiv:2410.15816'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: In review

publication_short: In review

abstract: "Tracking vulnerabilities inherited from third-party open-source components is a well-known challenge, often addressed by tracing the threads of dependency information. However, vulnerabilities can also propagate through forking: a repository forked after the introduction of a vulnerability, but before it is patched, may remain vulnerable in the fork well after being fixed in the original project. Current approaches for vulnerability analysis lack the commit-level granularity needed to track vulnerability introductions and fixes across forks, potentially leaving one-day vulnerabilities undetected. This paper presents a novel approach to help developers identify one-day vulnerabilities in forked repositories. Leveraging the global graph of public code, as captured by the Software Heritage archive, the approach propagates vulnerability information at the commit level and performs automated impact analysis. This enables automatic detection of forked projects that have not incorporated fixes, leaving them potentially vulnerable. Starting from 7162 repositories that, according to OSV, include vulnerable commits in their development histories, we identify 2.2 M forks, containing at least one vulnerable commit. Then we perform a strict filtering, allowing us to find 356 ⟨vulnerability,fork⟩ pairs impacting active and popular GitHub forks, we manually evaluate 65 pairs, finding 3 high-severity vulnerabilities, demonstrating the impact and applicability of this approach."

# Summary. An optional shortened abstract.
summary: 'In recent years, the popularization of DevOps and integrated software forges like GitLab and GitHub has largely democratized Continuous Integration (CI) practices for a growing number of software. However, this trend intersects significantly with global energy consumption concerns and the growing demand for frugality in the Information and Communication Technology (ICT) sector. In this paper, we conducted the first large-scale analysis of the energy footprint of CI pipelines implemented with GitHub Actions and provide a first overview of the energy impact of CI' 
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2410.15816'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


---
