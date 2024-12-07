# ServerSwitcher

ServerSwitcher is a powerful plugin designed for Minecraft servers utilizing the Velocity/BungeeCord proxy. This plugin allows players to seamlessly switch between registered servers using customizable commands. With ServerSwitcher, server administrators can easily manage and configure commands for players to navigate their server network efficiently.

## Features

- **Custom Commands**: Define custom commands for each server you wish to register, allowing players to switch servers with ease.
- **Command Aliases**: Each command can have aliases, enabling players to use alternative names for server switching.
- **Permission Management**: Control access to commands through a permission system, ensuring that only authorized players can execute specific commands.
- **Custom Messages**: The plugin supports customizable messages that can be displayed to players upon successful server switching or when they lack the necessary permissions.
- **Command Permissions**: Players without the required permissions will receive an "unknown command" message when attempting to execute the command.

## Command Examples

Once the plugin is installed and configured, players can use the following commands to switch servers:

- **/hub**: This command will redirect the player to the designated hub server.
- **/survival**: This command will transport the player to the survival server.

These commands can be customized in the configuration file to point to any server you wish.

## Permissions

The following permissions are utilized by the ServerSwitcher plugin:

- `serverswitcher.default`: This permission grants players access to the default server switching commands.
- `serverswitcher.<server/custompermission>`: Replace `<server>` with the specific command name to grant access to that command. For example, to allow access to the `/survival` command, you would use `serverswitcher.default' **or** 'serverswitcher.survival`.

## Installation

1. **Download the Plugin**: Obtain the latest JAR file from the [releases page](link-to-releases-page).
2. **Place in Plugins Folder**: Copy the JAR file into the `plugins` folder of your Velocity/BungeeCord server directory.
3. **Configuration**: Adjust the `config.yml` file to define the servers and commands you wish to set up.
4. **Start the Server**: Launch your Velocity/BungeeCord server. The plugin will automatically load the defined commands.

## Example Configuration

Here is an example configuration for `config.yml`: [https://raw.githubusercontent.com/kinawnn/ServerSwitcher/refs/heads/main/src/main/resources/config.yml/](https://github.com/kinawnn/ServerSwitcher/blob/main/src/main/resources/config.yml)

Here is an example configuration for `message.yml`: [https://raw.githubusercontent.com/kinawnn/ServerSwitcher/refs/heads/main/src/main/resources/message.yml/](https://github.com/kinawnn/ServerSwitcher/blob/main/src/main/resources/message.yml)
