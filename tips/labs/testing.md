+++
title = "Testing Labs"
tags = ["tips","labs","testing"]
+++

# Testing your Lab
\toc


## Running automated tests on your system
- When you're done with a notebook, make sure it is saved (Ctrl+S) and close the tab.
- Test your code on Roar Collab (or you local computer) using
```shell
cd REPO_DIR
julia --project -e 'using Pkg; Pkg.instantiate(); '
```
- Inspect the test report results and identify any areas that you want to revisit before submitting.
- Once  you're happy with the results (or run out of time) [commit your changes](../commit) and [submit](../submitting).

---
## Push commits to Github and review results of automated testing via web
- Return to the terminal tab, make sure you're in your repo's directory.
- [Commit your changes](../commit) to your local repository and [submit](../submitting) by pushing to your GitHub repository.
- For repositories that are configured to apply tests via continuous integration, you can navigate to your repository's webpage, click Actions, then look under "All Workflows" and choose "Test notebooks".  There will be some tests of early versions that have red x's next to them.  Hopefully, your latest submission (typically at the top of the list) will have a green checkbox next to it.  If not, then you can click on that commit string, then click "test (...)" and see the results of the continuous integration tests.
