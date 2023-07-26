- [Usage](#usage)
- [Example Reports](#example-reports)
- [Installation](#installation)

## Usage

```bash
yarn analyze <BASE_PATH> <SCOPE_FILE> <GITHUB_URL>

# Example
yarn analyze contracts scope.example.txt
```

- `BASE_PATH` is a relative path to the folder containing the smart contracts.
- `SCOPE_FILE` is an optional file containg a specific smart contracts scope (see [scope.example.txt](./scope.example.txt))
- `GITHUB_URL` is an optional url to generate links to github in the report
- The output will be saved in a `report.md` file.

## Example Reports
~ [Holograph](https://code4rena.com/contests/2022-10-holograph-contest)
  [Report(https://gist.github.com/Picodes/e9f1bb87ae832695694175abd8f9797f) |

## Installation

You'll need [Node.js](https://nodejs.org/) and [Yarn](https://yarnpkg.com/). Then clone the repo and run:

```bash
yarn
```

You're all set!
