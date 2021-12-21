# Requirements for community built bots

## Open Source

Community Bots running in the [Golem Discord](https://chat.golem.network) has to be open source to encourage people contributing to the bot itself. Along with that it allows Golem Factory to make sure there's no malicious purposes behind the bot.

## The bot must be containerized.

To facilitate automatic deployments on PR merges, the bot's repository must contain a Dockerfile that makes it possible to run the bot with Docker.

## The bot must be hosted by Golem Factory

This ensures that we know what codebase is running on the bot and we take care of the cost associated with running the bot.

## Testing must take place in its own Discord

The official [Golem Discord](https://chat.golem.network) cannot be used to test the bot during development - a separate discord server must be used.

## Credit where credit is due

The bot must include the code example to properly credit contributors to the bot via the bot command /credits
