# Wazo modify Mail configuration 

If you want modify the SMTP parameters to your personal parameters with Mailjet.

This script do:

* Auto-generated edited file /etc/xivo/common.conf
* Generated file /etc/mailname
* And insert to database.

# Wazo version

Wazo version >= 19.12

# Installation

Connect to your stack and get the root.

    apt install wazo-plugind-cli
    wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-smtp-mailjet"

# Usage

    wazo-smtp-mailjet

Read instruction into dialog box
