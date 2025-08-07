# GitHub Actions CI for Tests

A minimal JavaScript project demonstrating a CI pipeline using GitHub Actions.

![CI](https://github.com/kiefertaylorland/github-actions-ci-for-tests/actions/workflows/test.yml/badge.svg)

![Screenshot 2025-08-05 at 2 43 21 PM](https://github.com/user-attachments/assets/21faa44d-0dc9-438c-9287-a1f364e2a64b)
![Screenshot 2025-08-05 at 3 05 13 PM](https://github.com/user-attachments/assets/77c32980-1c9d-4de1-8a1d-357445f6abad)
![Screenshot 2025-08-05 at 3 05 20 PM](https://github.com/user-attachments/assets/2511b291-202e-496a-b55e-0c17e6da8d32)

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
