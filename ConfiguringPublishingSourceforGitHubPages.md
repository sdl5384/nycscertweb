**Source Link**

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

Choosing a publishing source
1. On GitHub, navigate to your site's repository
2. Under your repository name, click Gear Icon (Settings)

To find potential errors with the build or deployment, you can check the workflow run for your GitHub Pages site by reviewing your repository's workflow runs.

Viewing workflow run history link:

https://docs.github.com/en/actions/monitoring-and-troubleshooting-workflows/viewing-workflow-run-history

Rerunning workflows and jobs:

https://docs.github.com/en/actions/managing-workflow-runs/re-running-workflows-and-jobs

**Jekyll**
Jekyll allows you to build a more robust website from text files…lets start a jekyll thread instead

Daring Fireball (Markdown for HTML syntax)

https://daringfireball.net/projects/markdown/syntax

***Markdown Errors***

Repository contains errors.  Make sure you are using a supported Markdown processor.  See Jekyll link above.

***Missing docs folder error***
You have chosen the docs folder on a brance as your publishing source, but there is no docs folder in the root of your repository on that branch.

***Missing submodule***

Your repository includes a submodule that does not exist or hasn't been properly initialized.  IF you don't want to use it, remove the submodule, replace PATH-TO-SUBMODULE with the path to the submodule:

$ git submodule deinit PATH-TO-SUBMODULE
$ git rm PATH-TO-SUBMODULE
$ git commit -m "Remove submodule"
$ rm -rf .git/modules/PATH-TO-SUBMODULE

***Basic writing and formatting syntax***

https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
