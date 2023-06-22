# icwsm23_tutorial
Code for the ICWSM 2023 tutorial "Collecting and Sharing Twitter Data for Academic Research: A hands-on tutorial using twarc2 and the Social Media Archive at ICPSR (SOMAR)"

## Tutorial Website
[https://icpsr-somar-devs.github.io/](https://icpsr-somar-devs.github.io/)

## Tutorial Description
This hands-on tutorial will walk participants through the data lifecycle of a social media data research project. Participants will learn how to collect data from Twitter using the twarc2 command line tool, how to share Twitter data using the Social Media Archive at ICPSR, and how to “hydrate” Twitter data shared by other researchers. After completing this tutorial, participants will be able to collect or reuse social media data in their own projects and share that data with others to verify, reproduce, and extend their work.

## Tutorial Program
This tutorial assumes a beginner-level knowledge of Python (>=3.0) programming language and [Jupyter notebook](https://jupyter.org/install) environment. Please have these installed before the tutorial.
Note: The instructor will be using a Linux-based system during the tutorial, but participants are welcome to use any OS, so long as they have a functioning Jupyter notebook and Python programing environment.
### Install Pre-requisite Libraries
1. Install [twarc2](https://twarc-project.readthedocs.io/en/latest/twarc2_en_us/) by [DocumentingTheNow](http://www.docnow.io/) using Python `pip3` (can be done at the beginning of the tutorial): `pip3 install twarc2`
2. Install following packages `httpx` as follows (for Mastodon): `pip3 install httpx`
3. Create an account on [Mastodon](https://mastodon.social/auth/sign_up). We will setup the API during the tutorial.

## About SOMAR
The Social Media Archive at ICPSR (SOMAR) is a revolutionary initiative and data resource that makes social media data accessible and useful to researchers like never before. Housed in the Inter-university Consortium for Political and Social Research (ICPSR) at the University of Michigan Institute for Social Research (ISR), SOMAR will democratize access to some of the most consequential information in contemporary society. From the emotional well-being of local youth to the outcomes of global political processes, social media play a critical, but poorly understood, role in socio-political life. Social media platforms contain a treasure trove of information that can help us better understand human behavior, social systems, and psychological processes.   

SOMAR’s mission is to provide a centralized and reliable repository for social media research data. Our archive contains a wide range of data collected from large-scale social media platforms such as Twitter, Facebook, Instagram, and Reddit, as well as smaller, more specialized data sets focused on specific research topics. The data in our archive takes two forms. They can be public, i.e., available for immediate download, and/or restricted, i.e., available within our secure data enclave after receiving approval following a submitted restricted data application.
