# GitHub Actions CI Demo

A minimal test project with a CI pipeline using GitHub Actions.

![CI (failing-test)](https://github.com/kiefertaylorland/github-actions-ci-for-tests/actions/workflows/test.yml/badge.svg?branch=demo/failing-test)

![Screenshot 2025-08-05 at 4 26 04 PM](https://github.com/user-attachments/assets/424a8423-12b3-436d-a441-f2445fbb08aa)
![Screenshot 2025-08-05 at 4 24 09 PM](https://github.com/user-attachments/assets/bca2574e-d1f6-4d43-b9e6-ba2503e9ec2e)

## Branches

- **main**: Default branch with working tests and CI.
- **demo/failing-test**: Example branch showing a failing test in CI.

## Features

- 100% JavaScript.
- Runs automated tests via GitHub Actions on every push or pull request.
- Easy to extend for more complex workflows.

## Getting Started

1. **Clone the repo**

   ```bash
   git clone https://github.com/kiefertaylorland/github-actions-ci-for-tests.git
   cd github-actions-ci-for-tests
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run tests locally**

   ```bash
   npm test
   ```

## Continuous Integration

- All pushes and PRs trigger the GitHub Actions workflow.
- The workflow will install dependencies and run tests automatically.
- Check the Actions tab for results.

## Contributing

Feel free to open issues or submit pull requests!
