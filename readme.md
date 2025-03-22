Forked from [Github keychron/qmk_firmware](https://github.com/Keychron/qmk_firmware)
Changes are based on the `wireless_playground` branch

# walruskhan keychron Q0 Max and Q1 max
- [Q1 Max](https://keychron.co.nz/products/keychron-q1-max-qmk-via-wireless-custom-mechanical-keyboard?_pos=2&_psq=q1+max&_ss=e&_v=1.0)
- [Q0 MAX](https://keychron.co.nz/products/keychron-q0-max-qmk-custom-number-pad)

# Usage
```bash
> qmk compile -kb keychron/q1_max/ansi_encoder -km walruskhan
> qmk flash -kb keychron/q1_max/ansi_encoder -km walruskhan
```

# Changes:
- Renamed 'Mac' and 'Win' layers to 'WUMBO' and 'mini' respectively
  - 'WUMBO' layer is for development/office work
  - 'mini' layer is for gaming (e.g. no auto shift or macros)
- Auto Shift on 'WUMBO' layer

# Issues:
- auto shift is not disabled on mini layer