<!--
Add here global page variables to use throughout your website.
-->
+++
prepath = "Fall2023"
author = "Eric Ford"
author_link = """<a href="https://science.psu.edu/astro/people/ebf11">Eric Ford</a>"""
mintoclevel = 2

# uncomment and adjust the following line if the expected base URL of your website is something like [www.thebase.com/yourproject/]
# please do read the docs on deployment to avoid common issues: https://franklinjl.org/workflow/deploy/#deploying_your_website
# prepath = "yourproject"

# Add here files or directories that should be ignored by Franklin, otherwise
# these files might be copied and, if markdown, processed by Franklin which
# you might not want. Indicate directories by ending the name with a `/`.
# Base files such as LICENSE.md and README.md are ignored by default.
ignore = ["node_modules/"]

# RSS (the website_{title, descr, url} must be defined to get RSS)
generate_rss = false
website_title = "Astro 528"
website_descr = "Penn State Astro 528: High-Performance Computing for Astrophysics"
website_url   = "https://psuastro528.github.io/Fall2023/"
version       = "v0.1"

# Class specific variables
class_name = "High-Performance Computing for Astrophysics"
class_number = "Astro 528"
semester = "Fall 2023"
#class_times = "10:10-11:00am MWF"
#class_location = "Davey Lab 538 (MF), Online (W)"
#class_location_long = "Davey Lab 538 (Mondays & Fridays) and Online (Wednesdays)"
instructor_name = "Eric Ford"
instructor_link = "[Eric Ford](https://science.psu.edu/astro/people/ebf11)"
instructor_email = "ebf11 _at_ psu.edu"
instructor_phone = "x3-5558"
#ta_name = "Zhenyuan Wang"
#ta_link = "[Zhenyuan Wang](https://science.psu.edu/astro/people/zzw173)"
#ta_email = "zzw173 _at_ psu.edu"
office_hours = "Mondays TBD (Davey Lab 408A)"

# Assignment deadlines
lab1_title = "Lab 1: Getting Started"
lab1_start = "Aug 23"  # wk 1
lab1_due = "Aug 30"    # wk 2
lab2_title = "Lab 2: Best Practices"
lab2_start = "Aug 30"  # wk 2
lab2_due = "Sept 6"    # wk 3; This week has Labor Day

project_proposal_title = "Project: Plan"
project_proposal_due = "Sept 6" # wk 3

lab3_title = "Lab 3: Memory Heirarchy"
lab3_start = "Sept 6"  # wk 3
lab3_due = "Sept 13"   # wk 4

lab4_title = "Lab 4: Probablistic Programming"
lab4_start = "Sept 13" # wk 4
lab4_due = "Sept 20"   # wk 5

lab5_title = "Lab 5: Serial Optimization"
lab5_start = "Sept 20" # wk 5
lab5_due = "Sept 27"   # wk 6

project_serial_title = "Project: Serial Code"
project_serial_due = "Oct 2"  # wk 7
project_codereview_title = "Project: Peer Code Review"
project_codereview_due = "Oct 9"  # wk 8

lab6_title = "Lab 6: Parallelization I"
lab6_start = "Oct 11"  # wk 8
lab6_due = "Oct 18"    # wk 9

lab7_title = "Lab 7: Parallelization II"
lab7_start = "Oct 18"  # wk 9
lab7_due = "Oct 25"    # wk 10

project_parallel1_title = "Project: Parallel Code 1"
project_parallel1_due = "Oct 30"   # wk 11

lab8_title = "Lab 8: GPU Accelerators"
lab8_start = "Nov 1"   # wk 11
lab8_due = "Nov 8"     # wk 12

lab9_title = "Lab 9: Reproducibility"
lab9_start = "Nov 8"   # wk 12
lab9_due = "Nov 15"    # wk 13

project_parallel2_title = "Project: Parallel Code 2"
project_parallel2_due = "Nov 13"   # wk 13

# Thanksgiving break between weeks 13 & 14

project_final_title = "Project: Final"
project_final_due = "Nov 29"  # week 14
project_presentation_title = "Project Presentations"
project_presentation_due = "Nov 27 - Dec 6"  # wk 14 & 15
#project_report_title = "Individual Report & Reflection"
#project_report_due = "Dec 9"

hasplotly = false
+++


<!--
Add here global latex commands to use throughout your pages.
-->
\newcommand{\R}{\mathbb R}
\newcommand{\scal}[1]{\langle #1 \rangle}

\newcommand{\lineskip}{@@blank@@}
\newcommand{\skipline}{\lineskip}
\newcommand{\note}[1]{@@note @@title ⚠ Note@@ @@content #1 @@ @@}
\newcommand{\warn}[1]{@@warning @@title ⚠ Warning!@@ @@content #1 @@ @@}
