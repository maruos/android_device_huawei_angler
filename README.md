# Maru OS on the Nexus 6P

## Vendor files

Maru uses [android-prepare-vendor](https://github.com/anestisb/android-prepare-vendor) to generate a complete vendor tree for angler, including `vendor.img`. This allows you to flash your build without having to first flash the latest stock image. If your build hangs on the Google boot logo, please ensure that you have generated a complete vendor tree with android-prepare-vendor.

If you want to use an alternative method of obtaining the vendor files that does not generate `vendor.img`, see this [PR](https://github.com/maruos/android_device_lge_bullhead/pull/1) for an easy workaround.

## Contributing

See the [main Maru OS repository](https://github.com/maruos/maruos) for more
info.

## License

[Apache 2.0](https://github.com/maruos/maruos/blob/master/LICENSE)
