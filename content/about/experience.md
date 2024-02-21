---
# An instance of the Experience widget.
# Documentation: https://docs.hugoblox.com/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: Experience
subtitle:

# Date format for experience
#   Refer to https://docs.hugoblox.com/customization/#date-format
date_format: January 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Staff Software Engineer
    company: Codecademy
    company_logo: Codecademy
    location: New York, NY
    date_start: '2022-02-01'
    date_end: '2022-08-01'
    description: |2-
      * Led development and technical design of several new services, each spanning multiple engineering teams, from conception to deployment. 
      * Established engineering best practices, code review processes, training and mentorship programs, and hiring practices. Mentored engineers throughout the organization.


  - title: Senior Backend Engineer
    company: Codecademy 
    company_logo: Codecademy
    location: New York, NY
    date_start: '2019-06-01'
    date_end: '2022-02-01'
    description: |2-
      * Designed and improved backed services for payments, subscriptions, data tracking, course catalog, content management, search, and remote code evaluation.
      * Implemented a delayed payment trial model that drove an increase of over $1M in annual revenue. Reworked data models, access control, and subscription lifecycle management.
      * Transformed the course catalog from a static list to a dynamic, tag-based system with sorting and filtering. Implemented caching for fast performance and scalability.
      * Created a machine learning-driven recommendation service from scratch.

  - title: Software Engineer
    company: Facebook, Inc.
    company_logo: Facebook
    location: Menlo Park, CA
    date_start: '2017-08-01'
    date_end: '2019-05-01'
    description: |2-
      * Built systems, tools, automation, and machine learning to defend against spam and abuse.
      * Automated the deployment of weekly retrained ML models to reduce manual effort.
      * Implemented a graph embedding covering >1 billion users that was used to improve training data quality, extract new features, and increase classifier recall.
      * Helped mitigate a security breach affecting 50 million users.
      * Improved incident response time by 90% by adding anomaly detection around reports.

  - title: Software Engineer
    company: REAL Software Systems
    company_logo: RSS2
    location: Los Angeles, CA
    date_start: '2014-06-01'
    date_end: '2017-07-01'
    description: |2-
      * Developed enterprise software for royalties accounting and IP management.
      * Led development of a data import service that processes >100k sales transactions at a time.
      * Refactored extensive legacy codebase to improve reusability, readability and stability.

design:
  columns: '1'
---
