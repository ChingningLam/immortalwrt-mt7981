**Chinese** | [教程](https://p3terx.com/archives/build-openwrt-with-github-actions.html)

# cudy tr3000 v1 256mb 
openclash ua3f usb网络共享友好

# Actions-OpenWrt

编译自 https://github.com/padavanonly/immortalwrt-mt798x-6.6 兼容 Cudy Tr3000 新 flash

若你想关闭 USB 供电执行命令

```bash
echo 0 > /sys/class/gpio/modem_power/value
```

恢复供电执行命令

```bash
echo 1 > /sys/class/gpio/modem_power/value
```

集成第三方软件包:
- [OpenClash](https://github.com/vernesong/OpenClash)
- [ua3f](https://github.com/SunBK201/UA3F)
- [Bandix](https://github.com/timsaya/luci-app-bandix)
- [luci-theme-aurora](https://github.com/eamonxg/luci-theme-aurora)
- luci-app-upnp
- kmod-usb-net-cdc-ether
- kmod-usb-net-rndis


## Credits

- [Microsoft Azure](https://azure.microsoft.com)
- [GitHub Actions](https://github.com/features/actions)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [coolsnowwolf/lede](https://github.com/coolsnowwolf/lede)
- [Mikubill/transfer](https://github.com/Mikubill/transfer)
- [softprops/action-gh-release](https://github.com/softprops/action-gh-release)
- [Mattraks/delete-workflow-runs](https://github.com/Mattraks/delete-workflow-runs)
- [dev-drprasad/delete-older-releases](https://github.com/dev-drprasad/delete-older-releases)
- [peter-evans/repository-dispatch](https://github.com/peter-evans/repository-dispatch)

## License

[MIT](https://github.com/P3TERX/Actions-OpenWrt/blob/main/LICENSE) © [**P3TERX**](https://p3terx.com)
