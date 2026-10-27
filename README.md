# Plugin Installer

Run-on-demand installer for the audio plugin family. Browse the same signed catalogue used inside FAVE, TUN and LEV, then download/install supported products. There is no permanent hub, login, startup item or background service.

Platform-specific beta downloads will appear in [Releases](https://github.com/mrjellifish/PluginInstaller-releases/releases) after validation. Mac and Windows use different files. Product installers handle their own folder choices, backup and loaded-plugin checks. TUN/LEV are currently Apple silicon Mac only; FAVE supports Windows x64 and Intel/Apple silicon Macs.

Private implementation: mrjellifish/PluginKit. The public catalogue endpoint remains compatible with installed plugins. Publisher certificates/notarization are not configured yet.
