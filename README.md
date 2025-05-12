
# 🧠 MISP Threat Intelligence Labs

This repository contains practical labs for learning how to use the [Malware Information Sharing Platform (MISP)](https://www.misp-project.org/) for cyber threat intelligence (CTI) operations. Each chapter focuses on real-world use cases to help security analysts and CTI practitioners gain hands-on experience.

The labs cover the entire workflow from setting up a MISP environment to enriching and analyzing Indicators of Compromise (IOCs) through automation.

## 📌 What You Will Learn

- Deploying MISP with Docker on Ubuntu 20.04
- Creating and managing threat events
- Adding and classifying IOCs (IP, domains, URLs, files)
- Applying taxonomies and galaxy clusters for threat classification
- Using Malpedia and MITRE ATT&CK for TTP mapping
- Automating IOC searches and statistics with the MISP API
- Visualizing threat data using Python

## 📂 Repository Structure

| Folder | Description |
|---------|-------------|
| `01-setup-docker` | Deploying MISP using Docker |
| `02-adding-threat-intelligence` | Creating events, adding tags, galaxies, attributes, and objects |
| `03-api-automation` | Automating tasks like retrieving stats, IOCs, and visualizing TTPs |
| `screenshots/` | Supporting images for each lab |

## 🎯 Target Audience

- Security analysts and SOC teams
- Threat Intelligence (CTI) professionals
- Students practicing threat enrichment workflows
- Anyone learning to automate CTI processes using MISP

## 🚀 Requirements

- Basic Linux command-line knowledge
- Python 3.x environment for API automation labs
- Working MISP instance (local via Docker or remote)
