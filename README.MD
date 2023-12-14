# Terraform-latest Chocolatey Package

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<!-- Github Release BADGES -->

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/RolfMoleman/Terraform-Latest?style=for-the-badge&label=Latest%20SemVer)](https://github.com/RolfMoleman/Terraform-Latest/tags)

<!-- Github Workflow BADGES -->

[![GitHub Workflow Status (Automatically update terraform.nuspec)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/autoupdate_terraform.yml?style=for-the-badge&label=Automatically%20update%20terraform.nuspec)]()

[![GitHub Workflow Status (build)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/build.yml?style=for-the-badge&label=Build)]()

[![GitHub Workflow Status (Publish chocolatey package)](https://img.shields.io/github/actions/workflow/status/RolfMoleman/Terraform-Latest/publish.yml?style=for-the-badge&label=Publish%20Chocolatey%20PAckage)]()

<!-- Made With Badges -->

[![made%20with-bash](https://img.shields.io/badge/Made%20with-Bash-1f425f.svg?style=for-the-badge)](https://www.gnu.org/software/bash/)
[![made%20with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg?style=for-the-badge)](http://commonmark.org)
[![made%20with-MegaLinter](https://img.shields.io/badge/Made%20with-MegaLinter-1f425f.svg?style=for-the-badge)](https://megalinter.io/latest/)
[![made%20with-PowerShell](https://img.shields.io/badge/Made%20with-PowerShell-1f425f.svg?style=for-the-badge)](https://github.com/PowerShell/PowerShell)
[![made%20with-pre-commit](https://img.shields.io/badge/Made%20with-pre--commit-1f425f.svg?style=for-the-badge)](https://github.com/pre-commit/pre-commit)

<!-- Precommit Badges -->
<!--
*** replace with badges relevant to your repo
-->

these are the pre-commit hooks used for this repo:

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-added-large-files)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-case-conflict)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-merge-conflict)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-json)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=check-yaml)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=detect-private-key)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=end-of-file-fixer)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/pre-commit/pre-commit-hooks.svg?style=for-the-badge&label=trailing-whitespace)](https://github.com/pre-commit/pre-commit-hooks/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/streetsidesoftware/cspell.svg?style=for-the-badge&label=CSpell)](https://github.com/streetsidesoftware/cspell/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/tag/pre-commit/mirrors-prettier.svg?style=for-the-badge&label=Prettier)](https://github.com/pre-commit/mirrors-prettier/tags)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/antonbabenko/pre-commit-terraform.svg?style=for-the-badge&label=terraform_fmt)](https://github.com/antonbabenko/pre-commit-terraform/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/antonbabenko/pre-commit-terraform.svg?style=for-the-badge&label=tfupdate)](https://github.com/antonbabenko/pre-commit-terraform/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/terraform-docs/terraform-docs.svg?style=for-the-badge&label=terraform-docs-go)](https://github.com/terraform-docs/terraform-docs/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/oxsecurity/megalinter.svg?style=for-the-badge&label=megalinter-incremental)](https://github.com/oxsecurity/megalinter/releases)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/mattlqx/pre-commit-sign.svg?style=for-the-badge&label=pre-commit-sign)](https://github.com/mattlqx/pre-commit-sign/releases)

<!-- included tool versions -->

<!-- Azure Devops Navigation -->
<!-- markdown-table-prettify-ignore-start -->

|                                                                                                                |                                                                                                             |                                                                                                      |                                                                                                      |                                                                                                                      |                                                                                             |                                                                                                             |                                                                                                     |                                                                                                                    |
| :------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
|                                                                                                                |                                                                                                             |                                                                                                      |                                                                                                      |                [![terraform-latest][logo-image]](https://github.com/RolfMoleman/Terraform-Latest)                |                                                                                             |                                                                                                             |                                                                                                     |                                                                                                                    |
|                                                                                                                |                                                                                                             |                                                                                                      |                                                                                                      | [**README**](https://github.com/RolfMoleman/Terraform-Latest/blob/main/README.md) |                                                                                             |                                                                                                             |                                                                                                     |                                                                                                                    |
|                                                                                                                |                                                                                                             |                                                                                                      |                                                                                                      |       [**DOCUMENTS**](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/docs&version=GBmaster)        |                                                                                             |                                                                                                             |                                                                                                     |                                                                                                                    |
| [Checkov Baseline](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/.config/.checkov.baseline) | [Cspell config file](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/.config/.cspell.json) | [Gitversion config](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/GitVersion.yml) | [JSCPD config](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/.config/.jspcd.json) |  [KICS config file](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/kics.config&version=GBmaster)   | [License file](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/LICENSE.md) | [Megalinter config file](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/.mega-linter.yml) | [Readme Template](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/BLANK_README.md) | [tflint config file](https://dev.azure.com/Organisation_Name/Project_Name/_git/terraform-latest?path=/build/terraform/.tflint.hcl) |

<!-- markdown-table-prettify-ignore-end -->
<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Terraform-latest Chocolatey Package](#terraform-latest-chocolatey-package)
  - [Table of Contents](#table-of-contents)
  - [About The Project](#about-the-project)
    - [Built With](#built-with)
    - [Terraform](#terraform)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
  - [Usage](#usage)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgments](#acknowledgments)

<!-- ABOUT THE PROJECT -->

## About The Project

[![Product Name Screen Shot][product-screenshot]](https://example.com)

Repo_Description

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

### Built With

- [Terraform](https://nextjs.org/)
- [Powershell](https://reactjs.org/)
- [Github Actions](https://vuejs.org/)

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- Terraform -->

### Terraform

<!-- markdown-table-prettify-ignore-start -->
<!-- markdownlint-disable -->
<!-- prettier-ignore-start -->
<!-- start_of_terraform_docs -->

<!-- end_of_terraform_docs -->
<!-- prettier-ignore-end -->
<!-- markdownlint-enable -->
<!-- markdown-table-prettify-ignore-end -->

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- GETTING STARTED -->

## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

- npm

  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get a free API Key at [https://example.com](https://example.com)
2. Clone the Repo

   ```sh
   git clone https://bcagroup@dev.azure.com/bcagroup/Project_Name/terraform-latest.git
   ```

3. Install NPM packages

   ```sh
   npm install
   ```

4. Enter your API in `config.js`

   ```js
   const API_KEY = "ENTER YOUR API";
   ```

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- USAGE EXAMPLES -->

## Usage

Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For more examples, please refer to the [Documentation](https://bcagroup@dev.azure.com/bcagroup/Project_Name/terraform-latest/?path=/docs&)_

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- ROADMAP -->

## Roadmap

- [ ] Feature 1
- [ ] Feature 2
- [ ] Feature 3
  - [ ] Nested Feature

See the [open issues](https://github.com/RolfMoleman/Terraform-Latest/issues?q=is%3Aopen) for a full list of proposed features (and known issues).

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- CONTRIBUTING -->

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the Repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- LICENSE -->

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- CONTACT -->

## Contact

To contact me please use the discussion against the relevant release.

Project Link: [https://github.com/RolfMoleman/Terraform-Latest](https://github.com/RolfMoleman/Terraform-Latest)

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- ACKNOWLEDGMENTS -->

## Acknowledgments

- [jamestoyer](https://github.com/jamestoyer/) - for the repo [chocolatey-packages](https://github.com/jamestoyer/chocolatey-packages) which provided the inspiration for this repository.
- [othneildrew](https://github.com/othneildrew) - for the repo [Best-README-Template](https://github.com/othneildrew/Best-README-Template) which provided the inspiration for this readme.
- [sabihsaleh](https://github.com/sabihsaleh) - for the inspiration to do this.

---

<!-- Readme Navigation -->

[(Back to the Table of Contents)](#table-of-contents)

---

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->


<!-- BADGES AND SHIELDS -->

<!-- GITHUB LINKS -->

[contributors-shield]: https://img.shields.io/github/contributors/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[contributors-url]: https://github.com/RolfMoleman/Terraform-Latest/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[forks-url]: https://github.com/RolfMoleman/Terraform-Latest/network/members
[stars-shield]: https://img.shields.io/github/stars/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[stars-url]: https://github.com/RolfMoleman/Terraform-Latest/stargazers
[issues-shield]: https://img.shields.io/github/issues/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[issues-url]: https://github.com/RolfMoleman/Terraform-Latest/issues
[license-shield]: https://img.shields.io/github/license/RolfMoleman/Terraform-Latest.svg?style=for-the-badge
[license-url]: https://github.com/RolfMoleman/Terraform-Latest/blob/main/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/carlrdawson

<!-- IMAGES AND ICONS -->

[logo-image]: /.assets/logo.png

<!-- MARKDOWN DOCUMENT LINKS -->


<!-- PIPELINE LINKS -->
