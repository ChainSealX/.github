# Contributing to ChainSealX

First off, thank you for considering contributing to ChainSealX! It is people like you who make the decentralized web a more secure and reliable place.

To maintain the high quality of our blockchain infrastructure, we ask that you follow these guidelines.

## 🏛️ Code of Conduct
By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We expect all contributors to be respectful, collaborative, and professional.

## 🛡️ Security Vulnerabilities
**Please do not report security vulnerabilities via public GitHub issues.** Because ChainSealX handles encrypted ledgers, any security flaw must be handled with extreme care. Please follow the instructions in our [Security Policy](SECURITY.md) to report vulnerabilities privately.

## 🐞 Bug Reports
To encourage active collaboration, we prefer **Pull Requests** over simple bug reports. However, if you must file an issue, please:
* Use a clear and descriptive title.
* Provide a minimal reproduction case (a script or a failing test).
* Describe the expected behavior versus what is actually happening.

## 🚀 Pull Request Process
We follow a strict "Data Integrity First" workflow. Please ensure your contributions meet these requirements:

1. **Which Branch?** All bug fixes should be sent to the latest stable branch. New features should be sent to the `master` branch.
2. **Coding Standards:** We follow the **PSR-12** coding standard. We recommend using [Laravel Pint](https://laravel.com/docs/pint) to format your code.
3. **Tests Required:** No pull request will be merged without accompanying tests. We use **Pest** or **PHPUnit**.
4. **Atomic Commits:** Keep your commits small and focused. One feature or fix per pull request.
5. **Documentation:** If you are changing how a feature works, please update the relevant documentation in the `docs` repository or the `README.md`.

## 🛠️ Local Development Setup
1. Fork the repository and clone it to your machine.
2. Install dependencies: `composer install`
3. Run the test suite to ensure everything is green: `vendor/bin/pest`

## ⚖️ License
By contributing to ChainSealX, you agree that your contributions will be licensed under its [MIT License](LICENSE).

---
*“ChainSealX: Once sealed, forever traced.”*
