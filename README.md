# homelab-guides
Hi, welcome to my homelab guides (it's really a collection of my notes that I tried to organize). I've recently been gifted a few old computers and wanted to run some applications in my home as a way to explore and potentially provide infrastructure for some side projects. I work as a SRE currently and have a varied background including development, infrastructure, system processes, and product management but always feel like there's more to learn. This is not meant to be an exhaustive list of production ready guides but rather guides that show a way to set up things in a more stable and convenient manner for homelabs, but there are things in here that can probably apply to both audiences.

These are a collection of my notes and guides that I personally collected and/or created to make installation/configuration of applications easier to follow and understand for my homelab. These guides will not go into deep detail about the applications we use but rather try to cover the entire process around using them together. I am assuming readers will have some background experience and general baseline about most of the individual applications.

I create guides and take notes as a part of my normal reading/understanding process and thought I might as well use github to store a copy of them. I do this because a lot of the guides we find today are very narrow in scope, or have a use-case/example that is too simple, or does not have enough details to actually learn/understand something. I also thought I could hopefully give back to the online community who helps us do our jobs every day. I hope I can provide some help/info to anyone that may read this. 

Each guide will cover an entire process/pipeline and may include several applications and dependencies. If an entire process is not needed, it's certainly possible to read up on only the applications/processes you need.

## Table of Contents
| Folder | Description | Requirements |
| --- | --- | --- |
| `k8_cluster` | This guide sets up a local k8 cluster with cloud-like features and covers the following processes: <br/> - Install/Configure Kubernetes Cluster with Storage Provider<br/> - Install/Configuring Applications Including MetalLB, Nginx, CertManager, etc. <br/> - Configuring Router (USG PRO) For K8 Loadbalancer IP Allocation <br/> - Using Ingress-Nginx with MetalLB and Cert-Manager (for adding TLS support for internal websites) <br/> | - 3 Nodes with Linux Installed (can work with 1 though) <br/>- Configurable Router (Using USG Pro in my set up) | 
