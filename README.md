# Windows On AWS - Amazon WorkSpaces

> Running Windows workloads on AWS.

A hands-on workshop from the [AWS First Cloud Journey](https://github.com/vanhoangkha/aws-first-cloud-journey) series.

**Read the workshop online:** https://vanhoangkha.github.io/000093-Windows/

## Overview

To adapt the modern-working, you, as a System Administrator of a company has been tasked to research and to experience the state-of-the-art of the cloud technology - AWS Workspace.

In this lab, we will examine and experience AWS Workspace environment

## Workshop contents

1. Introduction
2. Preparation
3. Preparation
   - Prepare To Deploy Amazon WorkSpaces
   - Deploy Amazon WorkSpaces
4. Prepare To Deploy Amazon WorkSpaces
   - Access WorkSpaces - Browser
   - Access WorkSpaces - WorkSpaces Client
5. Clean up resources

## Prerequisites

- An AWS account with permissions to create the resources used in the labs
- Basic familiarity with the AWS Management Console
- [Hugo](https://gohugo.io/installation/) (extended edition) if you want to run the site locally

## Run locally

```bash
git clone --recurse-submodules https://github.com/vanhoangkha/000093-Windows.git
cd 000093-Windows
hugo server
```

Then open http://localhost:1313 in your browser.

## Repository structure

| Path | Purpose |
| --- | --- |
| `content/` | Workshop pages |
| `static/` | Images and other static assets |
| `layouts/` | Hugo layout overrides |
| `themes/` | Hugo theme |
| `config.toml` | Site configuration |

## Cost and cleanup

The labs create AWS resources that may incur charges. Complete the **Clean up** chapter when you finish to remove them.

## Contributing

Contributions are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md).

To report a security issue, see [SECURITY.md](SECURITY.md).

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
