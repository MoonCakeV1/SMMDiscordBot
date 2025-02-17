# SMM Bot - Discord Bot for Social Media Marketing

## Features

- **Balance Management**: Users can check their account balance, and admins can set custom balances for users.
- **Order Placement**: Users can place orders for various SMM services directly through the bot.
- **Instant Orders**: Admins can configure instant orders for quick access to popular services.
- **Whitelist System**: Only whitelisted users can access the bot's features.
- **Admin Commands**: Admins can manage users, revoke access, and control the bot's functionality.
- **Redeem Codes**: Admins can generate redeem codes that users can redeem for balance.
- **Logging**: All actions are logged to a specified channel for monitoring and auditing.

## Commands

### User Commands

- `!balance`: Check your account balance.
- `!help`: Display a list of available commands.
- `!status <order_id>`: Check the status of an order.
- `!instant`: Place an instant order for a predefined service.
- `!prices`: View the prices of available services.
- `!redeem <key>`: Redeem a code for balance.

### Admin Commands

- `!whitelist <user_id>`: Whitelist a user and set their balance to $0.
- `!unwhitelist <user_id>`: Remove a user from the whitelist.
- `!setadmin <user_id>`: Add a user as an admin.
- `!removeadmin <user_id>`: Remove a user from the admin list.
- `!revoke <user_id> <reason>`: Revoke a user's access to the bot.
- `!unrevoke <user_id>`: Unrevoke a user's access.
- `!turnoff`: Disable the bot.
- `!turnon`: Re-enable the bot.
- `!setbalance <user_id> <amount>`: Set a user's custom balance.
- `!rbal`: Check the API balance.
- `!nuke`: Delete all messages in the current channel.
- `!stopbot`: Shut down the bot.
- `!addinstant <order_id> <name>`: Add an instant order service.
- `!addcode <key> <balance>`: Add a redeem code with a specific balance.
- `!addservice <service_id> <name>`: Add a new service to the bot.
