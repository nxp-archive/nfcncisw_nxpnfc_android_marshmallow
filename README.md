# nxpnfc_android_marshmallow

This repository contains the files allowing to patch 6.0.1 Marshmallow version of AOSP source in order to add support for NXP-NCI NFC controllers (PN7120, PN7150) to an Android based system.
It only applies to Marshmallow Android versions (for other releases see appropriate repository: https://wiki.codeaurora.org/xwiki/bin/NCI+NFC+Controller+SW+resources/).

Information about NXP NFC Controller can be found on [NXP website](http://www.nxp.com/products/identification_and_security/nfc_and_reader_ics/nfc_controller_solutions/#overview).

Further details about the stack and integration guidelines [here](https://www.nxp.com/docs/en/application-note/AN11690.pdf).

Release version
---------------
 * R1.3: Repositories moved from Github to CodeAurora
 * R1.2: Updated with PN7150 AGC debug and P2P active mode fixes
 * R1.1: Updated with HCE fix
 * R1.0: Initial release based on NFC_NCIHALx_AR3C.4.5.0_M_OpnSrc
