# NGINX Kubernetes Ingress Controller Reference Architectures
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fnginxinc%2Fkic-reference-architectures.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fnginxinc%2Fkic-reference-architectures?ref=badge_shield)


This repository contains multiple projects that illustrate patterns for
deploying NGINX Kubernetes Ingress Controller (KIC).

Subdirectories contained within the root directory separate reference
architectures by infrastructure deployment tooling.

## Deployment Tools

### Pulumi

[Pulumi](https://www.pulumi.com/) is an infrastructure as code tool that
allows you to write code (node, Python, Go, etc) that defines cloud 
infrastructure. Within the [`pulumi`](./pulumi) folder are examples for
building and deploying KIC on different cloud environments.

## Contribution

We welcome PRs and issues!

Please refer to the [Contributing Guidelines](CONTRIBUTING.md) when doing a 
pull request.  

## License

All code in this repository is licensed under the 
[Apache License v2 license](./LICENSE).

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fnginxinc%2Fkic-reference-architectures.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fnginxinc%2Fkic-reference-architectures?ref=badge_large)