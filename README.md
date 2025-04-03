# Tinker WriterDeck

Tinker Writer Deck

Converts any 64-bit PC (amd64) based laptop into a writer deck, or a device solely designed around distraction free writing.

Website: https://tinker.sh

## Instructions:

Install a "headless" (or Desktop Environment Free) version of Debian 12.10 "Bookworm": https://www.debian.org/releases/bookworm/

When installing debian, use:
- username: author
- password: password

Install the following programs:
- sudo apt install tilde
- sudo apt install tmux
- sudo apt install udiskie
- sudo apt install network-manager

Upload, chmod +x, and run the following script:
https://github.com/tinkersec/tinkerwriterdeck/blob/main/initialConfig.sh

Then disconnect from wifi and enjoy.

Security Note: For password-protected Full Disk Encryption, please configure during installation of Debian.

Without Full Disk Encryption, please consider that:
- No password is required to log into the writer deck.
- No password is required to run at sudo or root privileges.
- Do not store anything on the Writer Deck that you would not want others to read if they got physical access to the device.
- Treat it like a diary that you would lock up in a box to prevent your brother from reading.
- Save any sensitive documents on a USB to move off of the writer deck and store separately in a secure fashion, then delete from the Writer Deck and USB afterwards.
