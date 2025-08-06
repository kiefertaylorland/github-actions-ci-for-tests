# GitHub Actions CI for Tests

A minimal JavaScript project demonstrating a CI pipeline using GitHub Actions.

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
