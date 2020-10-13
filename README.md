# What is this?
This is an extraction of the formula that installs helm version 2.13.1 using homebrew.

# How to use it
## Extract it:
`brew extract --version=2.13.1 kubernetes-helm bjacog/kubernetes-helm`

## Install it:
`brew install kubernetes-helm@2.13.1`

## Add the bin folder to your path
`export PATH="/usr/local/Cellar/kubernetes-helm@2.13.1/2.13.1/bin:$PATH"`