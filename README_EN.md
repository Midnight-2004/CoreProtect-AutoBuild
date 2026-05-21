# CoreProtect-AutoBuild

English | [简体中文](README.md)

[![Build and Deploy](https://github.com/Midnight-2004/CoreProtect-AutoBuild/actions/workflows/build.yml/badge.svg)](https://github.com/Midnight-2004/CoreProtect-AutoBuild/actions/workflows/build.yml)

Automatically fetches and builds CoreProtect every Sunday.

## Why does this repository exist?

Since the release of version `22.4` in May 2024, CoreProtect has not released updates compatible with Minecraft 1.21. However, by supporting the project on Patreon, users can access the latest builds.

Although the developers have not updated CoreProtect on SpigotMC or Modrinth platforms, the GitHub repository continues to receive updates. Therefore, we maintain a repository that synchronizes with the latest builds.

## Important Notes

> [!IMPORTANT]
>To download a version supporting MC 26.1.2, please find the latest pre-release version on the [Releases](https://github.com/Midnight-2004/CoreProtect-AutoBuild/releases/) page.
>Currently, these plugins supporting version 26.1.2 will not be included in the weekly automatic build.

The CoreProtect builds from this repository are `development` versions. According to feedback from other users on SpigotMC and Discord, **these manually built versions** cannot use databases from version `22.4` and earlier, so you need to delete your original database to continue using these plugin versions.

Tips:

- If you're using a `SQLite` database, I recommend adding a `.disabled` suffix to your original database and plugin files to disable them. You can simply remove the suffix when you need to restore them.
- If you're using `MySQL`, why not just create a new database?

## Chinese Language File Download and Usage

> [!TIP]
> Non-Chinese speaking users, please disregard the content of this section.

Please follow these steps to update the CoreProtect plugin's language file:

1. Go to [MineBBS](https://www.minebbs.com/resources/coreprotect.8820/) to download the Chinese language file archive.
2. Extract the downloaded file and locate the `language.yml` file.
   Copy this new `language.yml` file to your server's plugin directory at `/plugins/CoreProtect/`.
3. Note: When copying, make sure to replace the existing `language.yml` file. This will overwrite the old version with the newly downloaded one.
4. After completing the above steps, the CoreProtect plugin will use the updated language settings. It is recommended to back up your current language file before performing this operation, in case you need to revert to the previous settings.

## About CoreProtect

![CoreProtect](https://userfolio.com/uploads/coreprotect-banner-v19.png)

[CoreProtect](https://github.com/PlayPro/CoreProtect) is an ultra-fast data logging and anti-griefing tool for Minecraft servers.

For detailed information about the plugin, please visit [coreprotect.net](https://coreprotect.net).

### bstats

[![bStats Graph Data](https://bstats.org/signatures/bukkit/CoreProtect.svg)](https://bstats.org/plugin/bukkit/CoreProtect)

## Star History of This Repository

[![Star History Chart](https://api.star-history.com/svg?repos=Midnight-2004/CoreProtect-AutoBuild&type=Date)](https://www.star-history.com/#Midnight-2004/CoreProtect-AutoBuild&Date)
