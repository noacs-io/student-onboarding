# Welcome!

## We are very happy that you are considering taking on a project with our lab!

The No Accidents ([NOACS](https://noacs.io)) lab researches how to predict and prevent morbidity and mortality in trauma patients, by developing and validating prediction models for early trauma care and evaluating system level interventions for improved trauma care. 

Our research is based primarily in Sweden and India and it is funded by the Swedish Research Council and the Laerdal Foundation.

This repository includes information that applies to most projects that we supervise. It also outlines  expectations on our collaboration, and what you can expect from us as supervisors. 

To get the most out of this repository start by reading the [project timeline](project-timeline.md) and then about our [expectations](expectations.md). 

# Supervision structure

# Getting started

## Setting up a GitHub project

Before you do anything else, please sign up for a [GitHub
account](https://github.com). Create a new, empty, public repository
by following [GitHub's own
guide](https://docs.github.com/en/get-started/quickstart/create-a-repo).
Please use a short project name, for example if your project is about
how early interventions are associated with opportunities for
improvement, use `early-interventions-ofi` as the repository name. **Do
not initialize your repository with a README**.

## Signing in to our RStudio test server

Once you have created your GitHub repository, browse to our [RStudio
test server](https://rstudio.test.noacs.io) and sign in with the
credentials sent to you over email or Slack.

## Importing your GitHub project into the RStudio environment

Once logged in to RStudio server you will need to setup a way to
access GitHub. We recommend using a so called SSH key to do
this. Click Tools > Global Options... > Git/SVN > Create RSA key. You
can leave the Passphrase blank. Click Create > Close. Click View
public key and copy the key to the clipboard. [Then follow GitHub's
guide on how to add a SSH key to your
account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

Once you have added the SSH key to your GitHub account click File >
New Project > Version Control > Git. You will now need to enter the
SSH version of your repository url, which you find if you browse to
your GitHub repository, click the green button Code and select
SSH. Copy the url that starts with git@github.com and paste it into
Repository url. Then enter the directory name, typically the same as
the repository name. Finally, click Create Project.
