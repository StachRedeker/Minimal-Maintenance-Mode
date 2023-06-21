# WP Minimal Maintenance Mode

![Maintenance Mode Screenshot](/assets/activated.png)

## Description

The WP Minimal Maintenance Mode plugin is a simple and lightweight solution to enable maintenance mode on your WordPress website. When maintenance mode is enabled, it displays a customizable message to all users who are not logged in.

## Features

- Enable maintenance mode to restrict access to your website.
- Customize the maintenance mode message and heading.
- Bypass maintenance mode for logged-in users and administrators.
- Option to set a secret phrase to bypass maintenance mode via URL parameter.

## Installation

1. Download the [latest release](https://github.com/StachRedeker/WP-Minimal-Maintenance-Mode/releases) of the plugin.
2. Extract the plugin folder to the `wp-content/plugins/` directory of your WordPress installation.
3. Activate the plugin through the WordPress admin interface.
4. Configure the plugin settings by navigating to "Maintenance Mode" in the WordPress admin menu.

## Configuration

To enable maintenance mode and set the message displayed during maintenance, follow these steps:

1. Go to the WordPress admin menu and click on "Maintenance Mode."
2. Customize the maintenance mode heading and message.
3. Save the settings.

## Bypassing Maintenance Mode

If you need to access your website during maintenance mode, you can use the following methods:

1. **For Administrators and Logged-In Users**: Logged-in users with administrator privileges can access the website normally.
2. **Using the Secret Phrase**: Append `?[SECRET PHRASE]` to any URL to bypass maintenance mode for a week. The secret phrase can be configured in the plugin settings.

## Screenshots

![Settings Page](/assets/settings.png)

## Contributing



## License

The WP Minimal Maintenance Mode plugin is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html).

## Author

This plugin is developed and maintained by Stach Redeker. You can find more information about the author on their [website](https://www.stachredeker.nl).
