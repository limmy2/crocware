### New changes
* SubGHz: External CC1101 support (by @quen0n | PR #307) - [How to connect](https://github.com/quen0n/flipperzero-ext-cc1101)
* SubGHz: Fix GUI receiver bug - When keyboard is locked and popup appears it now shows bottom text correctly
* Plugins: Added movement interval in mouse_jiggler USB & BLE (by @DocKuro | PR #303)
* Plugins: Solitaire and Blackjack now affect Flipper's level (by @teeebor | PR #305)
* Plugins -> Updated **ProtoView** [(by antirez)](https://github.com/antirez/protoview)
* Plugins -> Updated **UniTemp** [(by quen0n)](https://github.com/quen0n/unitemp-flipperzero)
* Infrared: Update universal remote assets (by @amec0e) (PR #306)
* NFC: Remove invalid keys from mf classic dict (Fixes #304)
* GUI: Custom font set function (by @LTVA1) - [Link](https://github.com/LTVA1/flipperzero-firmware-wPlugins/tree/patch-custom-font)
* OFW: FreeRTOS: update to 10.5.1
* OFW: NFC: fix creating MF Classic tags from "Add Manually" menu (BCC calulation and ATQA/SAK writing)
* OFW: Print card CID in storage info
* OFW: Add support for `GUI-CTRL` in bad_usb
* OFW: Furi: getter for current thread stdout write callback 
* OFW: LF-RFID: add CRC calculation to paradox protocol
* OFW: WS: add protocol LaCrosse-TX (TFA Dostmann) 
* OFW: Assets: correct MicroSD card pinout in service animations
* OFW: Furi: make `furi_is_irq_context` public
* OFW: debug apps: made runnable as .faps; sdk: resolved additional APIs in use by faps 
* OFW: NFC: change from int8_t to uint8_t
* OFW: NFC: add MIFARE MINI support
* OFW: emv: parse track1&2 equivalent data
* OFW: nfc: Fix sector reads when one block is unreadable for MIFARE Classic
* OFW: nfc: Fix crash when using debug PCAP trace
* OFW: ELF-loader: wait for notification to complete on app exit

#### [🎲 Download latest extra apps pack](https://download-directory.github.io/?url=https://github.com/xMasterX/unleashed-extra-pack/tree/main/apps)

[-> How to install firmware](https://github.com/DarkFlippers/unleashed-firmware/blob/dev/documentation/HowToInstall.md)

[-> Download qFlipper (official link)](https://flipperzero.one/update)

## Please support development of my project on Patreon, but also the Unleashed project with one of the listed methods below. Most the changes listed above have been added into RM.
* Boosty: https://boosty.to/mmxdev
* Ko-Fi: https://ko-fi.com/masterx
* cloudtips (only RU payments accepted): https://pay.cloudtips.ru/p/7b3e9d65
* YooMoney (only RU payments accepted): https://yoomoney.ru/fundraise/XA49mgQLPA0.221209
* USDT(TRC20): `TSXcitMSnWXUFqiUfEXrTVpVewXy2cYhrs`
* BCH: `qquxfyzntuqufy2dx0hrfr4sndp0tucvky4sw8qyu3`
* ETH/BSC/ERC20-Tokens: `darkflippers.eth` (or `0xFebF1bBc8229418FF2408C07AF6Afa49152fEc6a`)
* BTC: `bc1q0np836jk9jwr4dd7p6qv66d04vamtqkxrecck9`
* DOGE: `D6R6gYgBn5LwTNmPyvAQR6bZ9EtGgFCpvv`
* LTC: `ltc1q3ex4ejkl0xpx3znwrmth4lyuadr5qgv8tmq8z9`
* XMR (Monero): `41xUz92suUu1u5Mu4qkrcs52gtfpu9rnZRdBpCJ244KRHf6xXSvVFevdf2cnjS7RAeYr5hn9MsEfxKoFDRSctFjG5fv1Mhn`
* TON: `EQCOqcnYkvzOZUV_9bPE_8oTbOrOF03MnF-VcJyjisTZmpGf`

### Thanks to Unleashed sponsors:
callmezimbra, Quen0n, MERRON, grvpvl (lvpvrg), art_col, ThurstonWaffles, Moneron, UterGrooll, LUCFER, Northpirate, zloepuzo, T.Rat, Alexey B., ionelife, ...
and all other great people who supported our project and me (xMasterX), thanks to you all!

**Note: To avoid issues with .dfu, prefer installing using .tgz with qFlipper, web updater or by self update package, all needed assets will be installed**

**Recommended option - Web Updater**

What means `n` or `e` in - `flipper-z-f7-update-(version)(n / e).tgz` ? - `n` means this build comes without our custom animations, only official flipper animations, 
`e` means build has extra apps pack preinstalled

Self-update package (update from microSD) - `flipper-z-f7-update-(version).zip` or download `.tgz` for mobile app / qFlipper


