## Introduction
This project aims to deepen our knowledge by making us use **K3d** and **K3s** with **Vagrant**.
We'll learn how to set up a personal virtual machine with **Vagrant** and the **distribution of our choice**. Then, we'll learn how to use **K3s** and its **Ingress**. Last but not least, we'll discover **K3d** that will simplify our life.
These steps will get us started with **Kubernetes**.
> This project is a minimal introduction to Kubernetes. Indeed, this
tool is too complex to be mastered in a single subject.

## General guidelines
• The whole project has to be done in a **virtual machine**. </br>
• We have to put all the configuration files of our project in folders located at the
root of our repository. The folders of the mandatory part will be named: **p1**, **p2** and **p3**. And the bonus
one: **bonus**. </br>
• This topic requires us to apply concepts that, depending on our background, we
may not have covered yet. We therefore advise you not to not be afraid to read a
lot of documentation to learn how to use **K8s** with **K3s**, as well as **K3d**. </br>
> We can use any tools we want to set up our host virtual machine as
well as the provider used in Vagrant.

## Mandatory part
This project will consist of setting up several environments under specific rules.

It is divided into three parts we have to do in the following order:
- **Part 1**: K3s and Vagrant
- **Part 2**: K3s and three simple applications
- **Part 3**: K3d and Argo CD

## Bonus part
The following extra is intended to be useful: [Gitlab] needs to be added in the lab we did in Part 3.

☠️ **[This bonus](https://github.com/wen/iot/tree/master/bonus) is complex**. The latest version available of Gitlab from the official website is expected.

We are allowed to use whatever we need to achieve this extra. For example, [helm](https://helm.sh) could be useful here.
- Our Gitlab instance must run locally
- Gitlab must be configured to make it work with our cluster
- A dedicated namespace named `gitlab` needs to be created
- Everything we did in [Part 3](https://github.com/wen/iot/tree/master/p3) must work with our local Gitlab

We can add everything needed so our entire cluster works.

