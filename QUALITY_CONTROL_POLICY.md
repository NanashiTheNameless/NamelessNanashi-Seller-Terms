# Quality Control and Testing Policy

**Effective date:** November 24, 2026

This policy explains how **NamelessNanashi** inspects and tests items before they ship. Please read it alongside our [Terms of Service](TERMS_OF_SERVICE.md) and [Refund and Return Policy](REFUND_AND_RETURN_POLICY.md). Those policies, any written agreement we both accept, and your rights under applicable law control warranties, returns, and refunds; this policy does not limit them.

## 1. Hubs and Electronics

Before a hub ships, we:

- **Erase the board's flash memory** so nothing from manufacturing or earlier use remains.
- **Flash the firmware**, verify it against its checksum, and confirm the hub boots and responds.
- **Test Wi-Fi:** confirm the hub broadcasts its `OpenShock-` setup access point in a fresh Wi-Fi scan.
- **Test RF:** have the hub send sound, vibrate, and stop commands, and confirm each one is received by a separate RF receiver.
- **Factory reset the hub** after testing, so it arrives with no saved settings and is ready for first-time setup.

Testing is done with our open-source [OpenShock AutoFlasher](https://github.com/NanashiTheNameless/OpenShock-AutoFlasher). A hub that fails any test is repaired and retested until it passes all of them; a hub that cannot be repaired does not ship.

## 2. Printed Parts

3D-printed cases and parts are inspected for print defects and fit before they are assembled or packed.

## 3. Final Packing Inspection

Each order is checked against what was ordered before it is sealed and shipped.

## 4. QC Passed Sticker

Every unit that passes quality control is marked with a holographic **QC Passed** sticker. If your unit arrived without one, please contact us.

## 5. What Testing Does and Does Not Cover

Testing confirms an item worked when it left us. It cannot account for damage in transit, your network or power setup, third-party software or services such as OpenShock, or use that does not follow the instructions. Passing our tests is not a warranty; the [Limited Hardware Warranty](REFUND_AND_RETURN_POLICY.md) and applicable law cover problems after delivery.

## 6. If Something Is Wrong

If an item arrives damaged, faulty, or incorrect, contact us as soon as possible with your order number, a description of the problem, and photos where helpful. The [Refund and Return Policy](REFUND_AND_RETURN_POLICY.md) explains time limits, exchanges, and refunds.

## 7. Changes to This Policy

We may update this policy as our process changes. Every change is recorded in this repository's history.
