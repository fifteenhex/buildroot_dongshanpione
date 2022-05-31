# buildroot_dongshanpione

![status-badge](https://woodpecker.thingy.jp/api/badges/fifteenhex/buildroot_dongshanpione/status.svg)


## Overlay configuration

- lcd0 - This is for `100ask-lcd0` connected to the dongshanpi one.
- ili9341 - This is for a ili9341 display connected to SPI (probably via the carrier board..).
  - Use `DRM_PANEL_ILITEK_ILI9341` as the driver, that's the only one of the 3 that is tested.
