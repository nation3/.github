# Nation3 Contributing Guidelines

A document with pragmatic standards and best-practices used by Nation3 developers.

## First-Time Contributor?

If you are new to Nation3, see https://nation3.org/join for information on how to join the community 💚

## Pull Requests

### Pull Request Philosophy

Commits in a pull request should always be focused. For example, a commit could add a feature, fix a bug, or refactor code; **but not a mixture**. Please also avoid super commits which attempt to do too much, are overly large, or overly complex as this makes review difficult.

### GitHub Issues

If the pull request is related to a GitHub issue, remember to include a reference to the GitHub issue in the description. Example: `closes #123`

### Test Checklist

Before requesting a review of your pull request, make sure that all the status checks are passing:

> ![status_checks](https://user-images.githubusercontent.com/95955389/188814554-191fe7c0-d99a-4b9c-b30b-9e6a5b04b5af.png)

Also test that that your code changes work on both Sepolia and Mainnet.

### Code Syntax/Formatting

#### TypeScript/JavaScript

We use [ESLint](https://eslint.org) as a linter, and [Prettier](https://prettier.io) to automatically format code so it adheres to our coding style.
Default config files for both can be seen [here](https://github.com/nation3/app/blob/main/ui/.eslintrc) and [here](https://github.com/nation3/app/blob/main/ui/.prettierrc.json). It is recommended to use Prettier inside your development environment to format your code with the right coding style on the fly.a

### Pull Request Review

After creating a pull request, assign one of the Nation3 [teams](https://github.com/orgs/nation3/teams) as reviewers.

When you have at least 1 approved review, merge the pull request.

## Testnet Development

### Sepolia `ETH`

We use Sepolia for our testnet deployments. You can get some testnet `ETH` from the [QuickNode - Ethereum Sepolia Faucet](https://faucet.quicknode.com/ethereum/sepolia).

### Sepolia `$NATION`

`$NATION` tokens can be purchased from the Sepolia Balancer Pool at https://app.balancer.fi/#/sepolia/swap/ether/0x23Ca3002706b71a440860E3cf8ff64679A00C9d7

### Sepolia `$veNATION`

Once you hold `$NATION` tokens, head over to the staking page: https://app-sepolia.nation3.org/lock

| ⚠️ Note that you will need to lock _more than_ 3 `$NATION` to get 3 `$veNATION` (since your `$veNATION` balance decreases over time). |
| --- |

### Sepolia Contract Deployments

See https://app.clarity.so/nation3-public/docs/9dcef8f6-ecd8-45f8-ab46-22d5f0fda30d
