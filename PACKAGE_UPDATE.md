### Specific upgrade steps

- [ ] `/scripts/build` is still working for new upstream version or it was fixed in accordance with upstream commits diffs.
- [ ] A build action for this version is successfully completed in the [Action](https://github.com/YunoHost-Apps/jsoncrack_ynh/actions) tabs.
- [ ] A new [release](https://github.com/YunoHost-Apps/jsoncrack_ynh/releases) is published with the new build attached 
- [ ] `url` and `sha256` fields under `[resources.sources.ynh_build]` section in `manifest.toml` are updated to meet the file attached in the new release.
- [ ] CI test is successful

Read this app's specific [upgrade documentation](https://github.com/YunoHost-Apps/jsoncrack_ynh/wiki/How-to-apply-upstream-upgrades-to-this-package) for more information.
