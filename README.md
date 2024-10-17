# TaskRay
Using CumulusCI to automate the Trial Setup per https://support.taskray.com/hc/en-us/articles/115000173448-Trial-Setup

# CumulusCI Setup
'Enable Chatter [Admin]' handled by the scratch org definition file 'orgs/trial.json'
Installs 04t4U000001E1cxQAC package id

# Project Setup
This project is preconfigured with D2X for a comprehensive Development-to-Delivery Experience including CI/CD using GitHub Actions and development environments using GitHub Codespaces.

D2X requires some minimal configuration of your GitHub organization or repository to complete the setup and enable builds:
* [Configure Secrets](https://d2x.readthedocs.io/en/latest/tutorial/#secrets)
* [Develop Your First Change](https://d2x.readthedocs.io/en/latest/tutorial/#develop)
* [Merge Your First Change](https://d2x.readthedocs.io/en/latest/tutorial/#merge)
* [Release Your First Change](https://d2x.readthedocs.io/en/latest/tutorial/#release)

You can check the status of your setup by monitoring the status of the following GitHub Actions workflows:
* [![Feature Test](https://github.com/beAGoodQE/TRay/actions/workflows/feature.yml/badge.svg)](https://github.com/beAGoodQE/TRay/actions/workflows/feature.yml)

