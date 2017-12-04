# nvram

Apple stores boot configuration and firmware settings in non-volatile
RAM which can be manipulated and viewed with the `/usr/sbin/nvram`
program.

Starting in 2016 they decided to configure MacBooks to automatically
boot when the lid is open. I don't like this and thankfully it's easy
to fix.

## How to Use

You can use a textfile containing "name value" value strings for
setting variables.

__Disable autoboot__

`nvram -f disable-autoboot`

__Enable autoboot__

`nvram -f enable-autoboot`
