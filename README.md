# WhatsApp Collapsible Sidebars — fork

Fork of [WhatsApp Collapsible Sidebars](https://greasyfork.org/en/scripts/584118-whatsapp-collapsible-sidebars) by JackMBurch (original by imxitiz), GPLv3.

## Changes from v1.2

- The chat-list caret now follows the edge while you drag the resize handle. In v1.2 it stayed at the old width until the window was resized.
- The carets hide when a WhatsApp popover (emoji/GIF picker, menu, dialog) covers them, and clicks pass through to it. In v1.2 they floated on top of the picker.

## Install

With Violentmonkey or Tampermonkey: [whatsapp-collapsible-sidebars.user.js](https://raw.githubusercontent.com/kriskhaira/whatsapp-collapsible-sidebars/main/whatsapp-collapsible-sidebars.user.js). Turn off the Greasy Fork version so the two don't both run.

The fix has been reported upstream; once a fixed upstream version is out, switch back to it.
