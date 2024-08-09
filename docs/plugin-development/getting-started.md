# Getting Started

Plugins allow you to interact with the game and add features, modify
functionality, and do much more. We ask you to be respectful of
[our guidelines](../plugin-publishing/restrictions.md) to ensure
that your plugin is approved into the official plugin repository, and to
minimise the risk of action by Square Enix. You can read more about this
[here](../plugin-publishing/approval-process.md).

We recommend that you start by cloning one of the following templates, and then
customising it to your requirements. While `SamplePlugin` is the most actively
maintained, the others are updated as required:

- [@goatcorp/SamplePlugin](https://github.com/goatcorp/SamplePlugin)
- [@karashiiro/DalamudPluginProjectTemplate](https://github.com/karashiiro/DalamudPluginProjectTemplate)
- [@lmcintyre/PluginTemplate](https://github.com/lmcintyre/PluginTemplate)

To distribute a plugin, it needs to be packaged correctly. This can be done
manually or [with DalamudPackager](https://github.com/goatcorp/DalamudPackager).

When your plugin is ready for testing/release, you should make a pull request to
the [DalamudPluginsD17](https://github.com/goatcorp/DalamudPluginsD17) repo.
**Please place testing plugins in the testing/live folder**.
