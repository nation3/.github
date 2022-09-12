# Nation3 Contributing Guidelines

A document with pragmatic standards and best-practices used by Nation3 developers.

## Pull Requests

### Pull Request Philosophy

Commits in a pull request should always be focused. For example, a commit could add a feature, fix a bug, or refactor code; **but not a mixture**. Please also avoid super commits which attempt to do too much, are overly large, or overly complex as this makes review difficult.

### Dework Integration

If the pull request is related to a [Dework](https://app.dework.xyz/nation3) task, remember to include a link to a Dework task in the description:

> ![dework](https://user-images.githubusercontent.com/95955389/188814985-4208bc7a-a8aa-4f61-a31e-2c6cb7c3249f.png)

### Test Checklist

Before requesting a review of your pull request, make sure that all the status checks are passing:

> ![status_checks](https://user-images.githubusercontent.com/95955389/188814554-191fe7c0-d99a-4b9c-b30b-9e6a5b04b5af.png)

Also test that that your code changes work on both Goerli and Mainnet.

### Pull Request Review

After creating a pull request, assign one of the Nation3 [teams](https://github.com/orgs/nation3/teams) as reviewers.

When you have at least 2 approved reviews, merge the pull request.

## Testnet Tokens

### Goerli Eth

We use Goerli for our testnet deployments. You can get some testnet `ETH` from the following faucets:

- [Goerli PoW Faucet](https://goerli-faucet.pk910.de/)
- [Alchemy Faucet](https://goerlifaucet.com/)
- [https://faucet.paradigm.xyz/](https://faucet.paradigm.xyz/)

### $NATION

`$NATION` tokens can be purchased from the Goerli Balancer Pool at https://goerli.balancer.fi/#/trade/ether/0x333A4823466879eeF910A04D473505da62142069 or by asking one of the members of the developer guild in [Discord](https://discord.gg/nation3)

### $veNATION

Once you hold `$NATION` tokens, head over to the staking page in the [Citizen App](https://app.nation3.org/lock).

Note that you will need to lock _more than_ 2 `$NATION` to get 2 `$veNATION` (since your `$veNATION` balance decreases over time.)

## Code Syntax/Formatting

### TypeScript/JavaScript

We use [ESLint](https://eslint.org) as a linter, and [Prettier](https://prettier.io) to automatically format code so it adheres to our coding style.
Default config files for both can be seen [here](https://github.com/nation3/app/blob/main/ui/.eslintrc) and [here](https://github.com/nation3/app/blob/main/ui/.prettierrc.json). It is recommended to use Prettier inside your development environment to format your code with the right coding style on the fly.
