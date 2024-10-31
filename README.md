# Nuclei Templates for 1C-Bitrix Vulnerability Scanning

## Description

This repository contains a collection of Nuclei templates designed to scan for common vulnerabilities in 1C-Bitrix systems. Nuclei is a fast, customizable vulnerability scanner that can help you identify security issues in your applications.

## Contents
- [Installation](#installation)
- [Usage](#usage)
- [Templates](#templates)

## Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/vaag4b0nd/BitrixCollection.git
   cd BitrixCollection
   ```

2. **Install Nuclei:**
   Follow the installation instructions from the [official Nuclei documentation](https://nuclei.projectdiscovery.io/getting-started/).

## Usage

1. **Configure Nuclei:**
   Ensure that Nuclei is installed and configured on your system.

2. **Run the templates:**
   ```sh
   nuclei -t BitrixCollection -u http://your-bitrix-site.com
   ```

   Replace `http://your-bitrix-site.com` with the URL of your 1C-Bitrix site.

## Templates

The repository includes various Nuclei templates tailored to detect common vulnerabilities in 1C-Bitrix systems, such as:
- Information Disclosure
- Content Spoofing
- Enum admin interfaces
- Cross-Site Scripting (XSS)
- Path Traversal
- and others.

You can find the templates in the `templates` directory. Each template is designed to check for specific vulnerabilities and provide actionable information.
