# kCTF
[![GKE Deployment](https://github.com/google/kctf/workflows/GKE%20Deployment/badge.svg?branch=master)](https://github.com/google/kctf/actions?query=workflow%3A%22GKE+Deployment%22)

kCTF is a Kubernetes-based infrastructure for CTF competitions.

## Prerequisites

* [gcloud](https://cloud.google.com/sdk/install)
* [docker](https://docs.docker.com/install/)
* [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) 1.17+

## Getting Started / Documentation

For an introduction to what kCTF is and how it interacts with Kubernetes, see [kCTF in 8 Minutes](https://google.github.io/kctf/introduction.html).

Additional documentation resources are:

* [Local Testing Walkthrough](https://google.github.io/kctf/local-testing.html) – A quick start guide showing you how to build and test challenges locally.
* [Google Cloud Walkthrough](https://google.github.io/kctf/google-cloud.html) – Once you have everything up and running, try deploying to Google Cloud. 
* [Troubleshooting](https://google.github.io/kctf/troubleshooting.html) – Help with fixing broken challenges.
* [DNS Setup](https://google.github.io/kctf/dns.html) – Information on setting up DNS for the CTF.
* [Security Threat Model](https://google.github.io/kctf/security-threat-model.html) – Security considerations regarding kCTF including information on assets, risks, and potential attackers.

## Samples

The [samples](https://github.com/google/kctf/tree/master/samples) directory contains two examples:
* A web challenge that acts like an XSS bot.
* A web challenge that acts like a vulnerable PHP application with support for sessions and file uploads.

