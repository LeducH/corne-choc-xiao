# Corne with choc switches and Xiao PCB

Here are gerber files that you can use. Simply drag and drop the provided gerber zip file into JLCPCB. For those interested in partial PCBA, I've furnished both a BOM and CPL with details for the diodes and battery connector.

---

**UPDATE (05/20/23)**

For those not using PCBA, it's imperative to ensure that the diode markers align with the square through-hole connection. It's not catastrophic if you orient them differently, but you'll need to tweak the firmware to account for the inversion. I've made available a generic firmware, derived from the provided startup files, that shifts from `col2row` to `row2col`.

---

SVG files are available for import into Fusion 360. This allows you to draft a sketch as a starting point for designing a case. These SVGs are extracted from the PCB Edge Cuts.

## **Edit Log:**

- **04/14/23**: Updated the ZMK starter files to be compatible with the latest ZMK versions.
- **04/09/23**: Added links to parts and images.
- **03/12/23**: Incorporated ZMK starter files. Place these in the `boards/shields` directory of your ZMK branch and update the `build.yml` accordingly.

## **Resources and Links:**

- **Build Guidance Images**: [View here](https://imgur.com/a/QKp5wG5)
- **Power Switches**: [Available on Amazon](https://www.amazon.com/gp/product/B0826XVZ8M/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
- **XIAO BLE**: [Available on Seeedstudio](https://www.seeedstudio.com/Seeed-XIAO-BLE-nRF52840-p-5201.html)
- **Batteries**: [Available on Amazon](https://www.amazon.com/HAC-006-BPJMX-C0-Battery-Nintendo-HAC-015-Controller/dp/B08L3FWXS4/ref=sr_1_4?crid=2YZOVGUSZ9RTX&keywords=HAC-006&qid=1679153921&s=electronics&sprefix=hac-006%2Celectronics%2C110&sr=1-4)
- **Nice!View**: [Check it out here](https://typeractive.xyz/products/nice-view)
- **Mill-Max Pins (Used on Nice!View)**: [Available on Digikey](https://www.digikey.com/en/products/detail/mill-max-manufacturing-corp/3320-0-00-15-00-00-03-0/4147392?s=N4IgTCBcDaIKIBECMSDMAWAtAOQSAugL5A)
- **Low Profile Sockets (For Nice!View)**: [Available on Digikey](https://www.digikey.com/en/products/detail/aries-electronics/40-0518-10/261892)

If you encounter any challenges, the [ZMK Discord](https://zmk.dev/) community is always ready to help.

