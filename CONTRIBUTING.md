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
