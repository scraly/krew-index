# Scraly's krew-index

Welcome in my custom index for Krew.

## Krew?

[Krew](https://github.com/kubernetes-sigs/krew) is a package manager for kubectl plugins, like “brew” but for Kubectl (Kubernetes CLI).

## Krew index?

Krew have an index but it's possible to create its own krew custom index, and this repository it's my krew-index ;-).

## Add scraly/krew-index

`kubectl krew index add scraly https://github.com/scraly/krew-index`

## List available plugins contined in this index

`kubectl krew search scraly`

## Install Kubernetes plugins

`kubectl krew install scraly/halloween`
