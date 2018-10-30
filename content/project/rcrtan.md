+++
# Date this page was created.
date = "2018-10-30"

# Project title.
title = "rcrtan: Criterion-Referenced Test Analysis"

# Project summary to display on homepage.
summary = "Contains methods for criterion-referenced test analyses as described by Brown & Hudson (2002) in Criterion-referenced Language Testing (ISBN: 9780521000833). This includes cut-score item discrimination analyses and measures of dependability."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = ""

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["assessment", "r-package"]

# Optional external URL for project (replaces project detail page).
external_link = "https://cran.r-project.org/package=rcrtan"

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""
caption = ""

+++

rcrtan provides functions for criterion-referenced test analyses as described in Brown & Hudson (2002). Currently it supports the following item and test analyses:

* Item discrimination
     + Item facility (including IF for passing test takers and failing test takers)
     + B-index
     + Agreement index
     + Item Phi
  
* Test dependability
     + Subkoviak's (1988) single administration kappa coefficient
     + Subkoviak's (1988) single administration agreement coefficient
     + Brown's (1990) short-cut estimate for phi dependability
     + Brennan's (1984) estimate for phi lambda
