# k8sconnector-restore-helm

## Lint the chart

        $ helm lint restorehub-restore/*
        // $ helm lint restorehub-restore/ # for Windows

## Change chart version

Bump the Chart.version in Chart.yaml. For example from 0.1.0 to 0.1.1

## Generate a new package

        $ helm package restorehub-restore/*
        // $ helm package restorehub-restore/ # for Windows

## Reindex a package index file

        $ helm repo index --url https://restorehub.github.io/k8sconnector-restore-helm/ .

## Push the changes

Make git add/commit/push
