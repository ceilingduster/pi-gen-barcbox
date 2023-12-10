# pi-gen for BARCBox Project

Uses pi-gen from https://github.com/RPi-Distro/pi-gen

For build, use a config file like:
``
export DEPLOY_ZIP=1
export ENABLE_SSH=1
export FIRST_USER_NAME=barcbox
export FIRST_USER_PASS=barcbox
export IMG_NAME=barcboxos
export KEYBOARD_KEYMAP=US
export KEYBOARD_LAYOUT="English (US)"
export LOCALE_DEFAULT=en_US.UTF-8
export PI_GEN_RELEASE=BARCBoxOS
export TARGET_HOSTNAME=barcbox
export TIMEZONE_DEFAULT=America/Toronto
export DISABLE_FIRST_BOOT_USER_RENAME=1
``
