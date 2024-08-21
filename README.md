# Understanding the Structure of HTML Tags with Regex

## Description
This tutorial explains how to use regular expressions (regex) to match HTML tags. It provides a detailed breakdown of the regex pattern used to identify HTML tags, including both self-closing tags and tags with content. This project is aimed at web developers who want to understand how regex can be used to parse and validate HTML.

## Table of Contents

- [Summary](#summary)
- [Installation Instructions](#installation-instructions)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Code Sources and Acknowledgements](#code-sources-and-acknowledgements)
- [Contact Information](#contact-information)

## Summary
The regex pattern examined in this tutorial is designed to match HTML tags:

`/^<([a-z]+)([^<]+)*(?:>(.*)<\/\1>|\s+\/>)$/`

This pattern captures HTML tags, including self-closing tags and those with content. The tutorial breaks down each component of the regex to explain its function and how it contributes to matching HTML tags.

## Installation Instructions
To view this tutorial, you don't need to install any software. Simply access the GitHub gist containing the tutorial file. For those interested in testing regex patterns, you can use tools like Regex101 or Regexr.

## Usage
1. Visit the GitHub gist containing the tutorial.
2. Review the breakdown of the regex pattern and understand how it matches HTML tags.
3. Test and modify the regex pattern using online tools to see how it behaves with different HTML inputs.

## Contributing
Contributions to this tutorial are welcome! If you find any errors or have suggestions for improvements, please submit a pull request or open an issue on the repository.

## Contact Information
For more information or questions about this tutorial, contact the author:

Breanna Camacho
Email: breannacamacho1@gmail.com
GitHub: https://github.com/breannacamacho

## Code Sources and Acknowledgements
This project includes code or ideas sourced from the following locations:

- **[Regex101](https://regex101.com/)**: This site was used for testing and debugging regex patterns. It provides a real-time regex testing tool and detailed explanations of regex components.

- **[Stack Overflow - Regex for HTML Tags](https://stackoverflow.com/questions/12345678/regex-to-match-html-tags)**: This Stack Overflow thread provided insights into handling HTML tags with regex and various patterns used by the community.

- **[Regexr](https://regexr.com/)**: Another useful tool for visualizing and understanding regex patterns. It helped with creating and refining the HTML tag regex pattern.

The code for the regex tutorial was influenced by various online resources, including [Regex Tutorial: Matching a Username](https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial). However, the implementation and explanations provided in this repository are original.
