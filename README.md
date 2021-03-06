<p align="center">
  <img src="https://raw.githubusercontent.com/kubernetes/kops/master/docs/img/k8s-aws.png"> </image>
</p>

Here is a repository that holds some common `kops` Kubernetes clusters. I think these are great discussion points, and this repository offers a good way to see what `kops` has to offer on AWS. Below you will find some example cluster configurations, with working `shell` scripts to run them. Also provided is a convenient diagram of each cluster and how the configuration and topology change with each type of cluster. My personal favorite happens to be the [highly available private topology configuration](ha-master-private/README.md)

The demonstrations here make an assumption that you have been able to get through `kops` cluster up and running in AWS.

## Getting Started with Kops

| Article                |  Link                                            |                                          
| ---------------------- |:-------------------------------------------: |
| Seeting up an HA Kubernetes cluster in AWS with private topology | [nivenly.com/kops-1-5-1](mailto:kris@nivenly.com)  |
| Booting Kubernetes on EC2 with kops|[deis.com/docs/workflow/quickstart/provider/aws/boot](https://deis.com/docs/workflow/quickstart/provider/aws/boot)    |
| Offical Guide                | [aws.md](https://github.com/kubernetes/kops/blob/master/docs/aws.md)|
| kops download                  | [kops v1.5.3](https://github.com/kubernetes/kops/releases/tag/1.5.3) |

## Kubernetes Cluster Examples

| Type                   | Topology      | Link                                                           |
| ---------------------- |:-------------:| -------------------------------------------------------------- |
| single-master          | public        | [Example](single-master-public/README.md)                      |
| single-master          | private       | [Example](single-master-private/README.md)                     |
| highly-available-master| private       | [Example](ha-master-private/README.md)                         |
| highly-available-master (with a subdomain) | private | [Example](ha-master-private-subdomain/README.md) |


## About me

I think I am pretty cool, and try to work really hard at making this stuff easy for you. I would love to hear what you think, or if this was helpful to you! It's hard to see how much attention this stuff gets so please feel free to give me a shout.

| Kris Nova              |                                              |                                          
| ---------------------- |:-------------------------------------------: |
| Email                  | [kris@nivenly.com](mailto:kris@nivenly.com)  |
| GitHub                 | [kris-nova](https://github.com/kris-nova)    |
| Twitter                | [@kris__nova](https://twitter.com/Kris__Nova)|
| My life story          | [nivenly.com](https://www.nivenly.com/)      |

## Legal

*AWS Trademark used with limited permission under the [AWS Trademark
Guidelines](https://aws.amazon.com/trademark-guidelines/)*

*Kubernetes Logo used with permission under the [Kubernetes Branding
Guidelines](https://github.com/kubernetes/kubernetes/blob/master/logo/usage_guidelines.md)*


