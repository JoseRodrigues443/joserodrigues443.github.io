---
# An instance of the Accomplishments widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: accomplishments

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

active: true

# Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
title: 'Accomplish&shy;ments'
subtitle:

# Date format
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

image = "ribeira_porto.jpg"  # Name of image in `static/media/`.
  # image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  # image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  # image_position = "center"  # Options include `left`, `center` (default), or `right`.
image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

# Accomplishments.
#   Add/remove as many `item` blocks below as you like.
#   `title`, `organization`, and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
item:
- certificate_url: https://www.netacad.com/courses/networking/ccna-introduction-networks
  date_end: "2016-09-01"
  date_start: "2016-01-01"
  description: "Certification of the Level 1 and 2 of the CISCO networking course."
  organization: CCNA 1, CCNA 2 and CCENT
  organization_url: https://www.netacad.com
  title: Cisco Certified Entry Networking Technician
  url: "https://www.netacad.com/courses/networking/ccna-introduction-networks"
# - certificate_url: https://www.edx.org
#   date_end: ""
#   date_start: "2021-01-01"
#   description: Formulated informed blockchain models, hypotheses, and use cases.
#   organization: edX
#   organization_url: https://www.edx.org
#   title: Blockchain Fundamentals
#   url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
# - certificate_url: https://www.datacamp.com
#   date_end: "2020-12-21"
#   date_start: "2020-07-01"
#   description: ""
#   organization: DataCamp
#   organization_url: https://www.datacamp.com
#   title: 'Object-Oriented Programming in R'
#   url: ""

design:
  columns: '2' 
---
