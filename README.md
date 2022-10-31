# Neochromium, other operating systems on mangaged Chromebooks


## What is Neochromium?

Neochromium is a chain of exploits in the ChromeOS firmware to allow for installation of custom firmware, which can boot both a managed ChromeOS environment and other operating systems from a USB, allowing it to be invisible to administrator without directly checking the firmware.

## Why use Neochromium?

First of all, it is hideable. Since you can boot into enrolled ChromeOS, you still have a place where you can do work and be managed. However, you can boot from a USB to make it so no one can boot unless they have a USB, which is unlikely.  
Second, other operating systems offer more things to do. You can install software, code, browse the internet, do whatever you want with your chosen OS, either Linux or Windows.

## How would I do this exploit?

Well, I haven't worked out the kinks yet. There's still some stuff to do, but the general process is to downgrade ChromeOS through recovery, use a exploit to get a bash shell, use a script to unenroll the Chromebook, activate developer mode, flash a custom firmware to the Chromebook, get out of developer mode, then reenroll the Chromebook.

## Can this be patched?

Nope. If it does you can just recover back. Even if Google removed downgrading, it would cause more harm than good.

## What OS's can I boot?

As long as you can load it on USB and it's supported for your Chromebook hardware, you can boot it. The best one would be Arch Linux, as it is great in general and it has unoffical ARM versions.

## When will you put specific instructions?

When I get this concept working.
