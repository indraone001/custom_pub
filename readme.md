# Custom Packages Monorepo

This repository hosts custom, internal Dart and Flutter packages used across multiple projects. It includes modified packages and shared utilities.

## Table of Contents
- [Overview](#overview)
- [Structure](#structure)
- [Packages](#packages)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The **Custom Packages Monorepo** consolidates multiple internal packages, including modified and shared packages, into a single repository. This allows us to:

- Easily manage and update all custom packages
- Share dependencies across multiple projects
- Maintain a consistent versioning scheme

## Structure

The repository is structured as follows:

custom_pub/
├── README.md # This file
├── packages/
│ ├── my_package/ # A custom package for handling networking
│ ├── my_theme/ # A shared theme package
│ ├── my_network_layer/ # Network layer abstraction
