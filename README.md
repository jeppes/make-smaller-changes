# Make Smaller Changes

Staying productive in an evergrowing codebase can be an uphill battle. Sometimes merging seemingly simple things can take days or even weeks. By the time someone gets around to reviewing your diff its often outdated and riddled with merge conflicts. The one strategy that has helped me deal with this more than any other is to **make smaller changes**.

I follow the rule of thumb that PRs with the word "and" in the description should probably be broken up - even if they are small to begin with. Not only do these PRs get reviewed and merged significantly faster, the quality of reviews also tends to be better. The process of dividing up a PR into independently mergeable parts also encourages simpler, more decoupled designs.

If possible, you should try to break your PR down into pieces which are independent of each other. These pieces can then be merged in any order and some pieces may never be merged. Even when it isn't possible to break down a PR in this manner, there can still be value in breaking a large PR up into a series of smaller PRs, but be mindful of the order and communicate that clearly in the PR descriptions.

Put yourself in the shoes of the reviewer when submitting a PR. Which of the following would you rather be faced with when a colleague sends you a PR to look at?

![PR Diff with 17 lines added, 15 lines removed](https://github.com/jeppes/make-smaller-changes/blob/main/small-pr.png?raw=true)
![PR Diff with 536 lines added, 80 lines removed](https://github.com/jeppes/make-smaller-changes/blob/main/large-pr.png?raw=true)


Make a habit of making smaller changes.
