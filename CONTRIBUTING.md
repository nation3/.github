# Nation3 Contributing Guidelines

A document with pragmatic standards and best-practices used by Nation3 developers.

## Pull Requests

If the pull request is part of a retroactive [Dework](https://app.dework.xyz/nation3) session, remember to include a link to a Dework task in the description:

> ![Screen Shot 2022-08-04 at 1 18 45 PM](https://user-images.githubusercontent.com/95955389/182770285-5355cd10-ebbd-4acf-87a8-0c2d1213fc42.png)

After creating a pull request, assign one of the Nation3 [teams](https://github.com/orgs/nation3/teams) as reviewers.

When you have 2 approved reviews, merge the pull request.

## Testnet Tokens

### Goerli Eth

We use Goerli for our testnet deployments. You can get some testnet `ETH` from the following faucets:

- [Goerli PoW Faucet](https://goerli-faucet.pk910.de/)
- [Alchemy Faucet](https://goerlifaucet.com/):
- [https://faucet.paradigm.xyz/](https://faucet.paradigm.xyz/)

### $NATION

`$NATION` tokens can be purchased from the Goerli [Balancer Pool](https://goerli.balancer.fi/#/pool/0x6f57329d43f3de9ff39d4424576db920b55060b30002000000000000000000d7) or by asking one of the members of the developer guild in [discord](https://discord.gg/zYsf6edHBf)

### $veNATION

Once you have 2 `$NATION` tokens, head over to the staking page in the [Citizen App](https://app.nation3.org/lock)

## Code Syntax/Formatting

### TypeScript/JavaScript

We use [ESLint](https://eslint.org) as a linter, and [Prettier](https://prettier.io) to automatically format code so it adheres to our coding style.
Default config files for both can be seen [here](https://github.com/nation3/app/blob/main/ui/.eslintrc) and [here](https://github.com/nation3/app/blob/main/ui/.prettierrc.json). It is recommended to use Prettier inside your development environment to format your code with the right coding style on the fly.
