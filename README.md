# Renovate Rules

Welcome to the `renovate-rules` repository! This project provides custom rules for the Renovate bot, an open-source dependency update tool. With these custom rules, you can tailor the behavior of Renovate to meet your specific requirements and conditions.

## Table of Contents

- [Introduction](#introduction)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The `renovate-rules` project is designed to extend the functionality of the Renovate bot by allowing users to create and apply custom rules for dependency updates. Whether you need to enforce specific versioning policies, handle special cases, or automate complex update workflows, this project provides the flexibility to do so.

## Usage

To use a custom rule in your Renovate configuration, add it to your `.renovate.json` file. Here is an example:

```json
{
  "extends": [
    "config:base",
    "github>erhardtconsulting/renovate-rules//my-rules.json"
  ]
}
```

Replace `github>erhardtconsulting/renovate-rules//my-rules.json` with the actual path to your custom rule file.

## Contributing

We welcome contributions to the `renovate-rules` project! If you have a custom rule that you think would benefit others, please submit a pull request. For bug reports or feature requests, please open an issue on GitHub.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

Thank you for using `renovate-rules`! We hope this project helps you manage your dependencies more effectively.