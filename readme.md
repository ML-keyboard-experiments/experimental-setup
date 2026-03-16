# For latency and power consumption measurements
[](/docs/setup.svg)
## 1. Setup: TOTEM (1)
1. Switch to branch `master`
2. Flash on both devices: `settings_reset-xiao_ble__zmk-zmk.uf2`
3. TOTEM (right half): `totem_peripheral-xiao_ble__zmk-zmk.uf2`
4. Matrix testing board: `totem_central-xiao_ble__zmk-zmk.uf2`

## 2. Setup: TOTEM (2)
1. Flash on both devices: `settings_reset-xiao_ble__zmk-zmk.uf2`
2. TOTEM (right half): `totem_central-xiao_ble__zmk-zmk.uf2`
3. Matrix testing board: `totem_peripheral-xiao_ble__zmk-zmk.uf2`

## 3. Setup: TOTEM with Dongle
1. Switch to branch `dongle`
2. Flash on all 3 devices: `settings_reset-xiao_ble__zmk-zmk.uf2`
3. TOTEM (right half): `totem_right-xiao_ble__zmk-zmk.uf2`
4. Matrix testing board: `totem_left-xiao_ble__zmk-zmk.uf2`
5. Seeed XIAO: `totem_dongle-xiao_ble__zmk-zmk.uf2`