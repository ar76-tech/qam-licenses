# QAM CRM PPF licences

Signed licence codes read by every QAM CRM PPF program every hour (`licensing.check_online`).
Each file is `<id>.txt`, where the id is a hash of the shop's request code; its content is one code signed with the
vendor's private key, which never leaves the vendor's PC. A code cannot be changed or made without that key, and no
shop's name or phone number is kept here.

Files are written by `license_tools/vendor_panel.py` on the vendor's PC. Do not edit them by hand.
