# squeak-smalltalk-bot

Serverless configuration to automatically forward GitHub notifications to the a mailing list and post replies from there back on GitHub.

## Configuration

### 1. Sign up on the mailing list

- For instance, for the Squeak mailing lists, start [here](https://lists.squeakfoundation.org/accounts/signup/).
- For bootstrapping, use an existing mail address in the beginning to confirm your account.
- Create one account like this for each of the following addresses and and change the primary email address:
  * <notifications@github.com> (used for notifications about new issues, pull requests, etc.)
  * <noreply@github.com> (used for notifications about new commits)
- Subscribe each account to the target mailing list (e.g., `squeak-dev`).
- Confirm each email address through the admin interface (as you won't be able to receive the automatic notifications send to these addresses).

### 2. Create a GitHub Account

- For bootstrapping, use an existing mail address in the beginning to confirm your account.
- In your [account settings](https://github.com/settings/emails), specify the mailing list address as your primary email address (e.g., `squeak-dev@lists.squeakfoundation.org`).
- An email verification should be sent from <noreply@github.com> to the list. Open the confirmation link.
- Watch the repositories of interesting for the mailing list.

## Credentials

Are documented in this PRIVATE repository: <https://github.com/squeak-smalltalk-bot/credentials>

## Known Issues

*to be added (If you think you find a problem with this bot, please [open an issue](https://github.com/squeak-smalltalk-bot/squeak-smalltalk-bot/issues/new)!)*
