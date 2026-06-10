# JT Toast Messages

**JT Toast Messages** is a lightweight Joomla system plugin that displays Joomla system messages as Bootstrap 5 toast notifications.

It uses Joomla's built-in Bootstrap 5 support and Web Asset Manager. No third-party notification library or extra CSS framework is included.

## Features

- Converts Joomla system messages into Bootstrap 5 toast notifications
- Supports success, info, warning, and error message types
- Configurable toast position
- Configurable top spacing for sticky headers
- Configurable toast title
- Auto-hide option with custom delay
- Optional front-end support
- Optional administrator support
- Optional successful login notification
- English and Turkish language files
- Joomla update server and changelog support

## Compatibility

- Joomla 6.1.x
- PHP 8.3 or newer
- Bootstrap 5 supported Joomla templates

## Installation

1. Download the latest package from the GitHub Releases page.
2. In Joomla Administrator, go to **System → Install → Extensions**.
3. Upload and install the ZIP package:

   ```text
   plg_system_jttoastmessages_1.0.9.zip
   ```

4. Go to **System → Manage → Plugins**.
5. Search for **System - JT Toast Messages**.
6. Open the plugin, configure the options, and enable it.

## Plugin Options

### Display

- **Enable in front-end**  
  Converts front-end Joomla system messages to Bootstrap 5 toast notifications.

- **Enable in back-end**  
  Converts administrator Joomla system messages to Bootstrap 5 toast notifications. Disabled by default to avoid disrupting administrator workflows.

- **Position**  
  Choose where toast notifications appear on the screen.

- **Top spacing**  
  Adds Bootstrap spacing for top positions so notifications do not sit under sticky headers.

- **Toast title**  
  Custom text displayed in the toast header. Leave blank to use the default language value.

- **Auto-hide**  
  Automatically hides notifications after the configured delay.

- **Delay**  
  Time in milliseconds before each notification is hidden.

### User Messages

- **Login message**  
  Shows a notification after a successful front-end login.

## Update Server

This extension includes Joomla update server support.

Update XML:

```text
https://raw.githubusercontent.com/joomtheme/JT-Toast-Messages/main/updates/update.xml
```

Changelog XML:

```text
https://raw.githubusercontent.com/joomtheme/JT-Toast-Messages/main/updates/changelog.xml
```

Latest package:

```text
https://github.com/joomtheme/JT-Toast-Messages/releases/download/v1.0.9/plg_system_jttoastmessages_1.0.9.zip
```

SHA256:

```text
d5ec5afc5d9e68930b4c69ca6ef2a258807423f5a08fe6a717e3aa43a641e223
```

## Package Structure

```text
jttoastmessages.xml
services/provider.php
src/Extension/JtToastMessages.php
media/joomla.asset.json
media/js/jttoastmessages.js
language/en-GB/plg_system_jttoastmessages.ini
language/en-GB/plg_system_jttoastmessages.sys.ini
language/tr-TR/plg_system_jttoastmessages.ini
language/tr-TR/plg_system_jttoastmessages.sys.ini
```

## Changelog

### 1.0.9

- Removed manually inserted external-link icons from the manifest description links.
- Relies on Joomla administrator's default external-link display behavior.
- Keeps extension information links clean in the plugin details view.

## Support

- Website: [JoomTheme](https://joomtheme.com)
- Email: [support@joomtheme.com](mailto:support@joomtheme.com)
- JED Reviews: [extensions.joomla.org profile](https://extensions.joomla.org/profile/profile/details/147240?)

## License

GNU General Public License version 3 or later. See the `LICENSE` file for details.
