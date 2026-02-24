---
title: 'Did You Forkget It? Detecting One-Day Vulnerabilities in Open-source Forks With Global History Analysis'
type: publication
layout: single
# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Romain Lefeuvre
  - Charly Reux 
  - Stephano Zacchiroli
  - Olivier Barais
  - Benoit Combemale


date: '2025-01-02T00:00:00Z'
doi: ''


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In review

publication_short: In review

abstract: 'Tracking vulnerabilities inherited from third-party open-source software is a well-known challenge, often addressed by tracing the threads of dependency information. However, vulnerabilities can also propagate through forking: a code repository forked after the introduction of a vulnerability, but before it is patched, may remain vulnerable long after the vulnerability has been fixed in the initial repository. History analysis approaches are used to track vulnerable software versions at scale. However, such approaches fail to track vulnerabilities in forks, leaving fork maintainers to identify them manually. This paper presents a global history analysis approach to help software developers identify one-day (known but unpatched) vulnerabilities in forked repositories. Leveraging the global graph of public code, as captured by the Software Heritage archive, our approach propagates vulnerability information at the commit level and performs automated impact analysis. Starting from 7162 repositories with vulnerable commits listed in OSV, we propagate vulnerability information to 2.2 million forks. We evaluate our approach by filtering forks with significant user bases whose latest commit is still potentially vulnerable, manually auditing the code, and contacting maintainers for confirmation and responsible disclosure. This process identified 135 high-severity one-day vulnerabilities, achieving a precision of 0.69, with 9 confirmed by maintainers.'


tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://hal.science/hal-05349203'
url_code: 'https://gitlab.inria.fr/rlefeuvr/did-you-forkget-it/'
url_dataset: ''
url_poster: ''
url_project: 'https://didyouforkgetit.dev/'
url_slides: 'pirat.pdf'
url_source: ''
url_video: ''


---
