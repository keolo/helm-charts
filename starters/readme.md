## Download and Overwrite Base Starter Chart

    svn export https://github.com/keolo/helm-charts.git/trunk/starters/base $(helm home)/starters/base --force

## Package Chart Locally

    helm package charts/go-learn/ --dependency-update --destination /tmp
