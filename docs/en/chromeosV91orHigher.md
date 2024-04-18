# 1. Creating a recovery disk

If your device is in [this list](../meetHardwareDevices.md) download on Chrome [this extension](https://chrome.google.com/webstore/detail/meet-compute-system-recov/odkacekibiibhidpiopcmgbgebkeoced) for Meet Compute Systems, otherwise use [this one](https://chrome.google.com/webstore/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm) for generic ChromeOS devices.

Open the extension, connect the USB drive and follow the instructions on screen to create a recovery USB drive.

# 2. System recovery

> [!IMPORTANT]
> Before continuing, remove **all** USB devices from the Chromebox except a keyboard. Also disconnect the device from internet.

Follow the [official steps](https://support.google.com/a/answer/10562922?hl=en#zippy=%2Cstep-enter-recovery-mode) from Google to reinstall ChromeOS, starting from `Step 2: Enter recovery mode`.

When ChromeOS is completely reinstalled you'll be greeted with the welcome screen:

![welcome screen](../images/welcome_new.png)

**Do not continue with the setup**, instead turn off the device from the menu in the bottom right.

## 2.1. Enabling developer mode

Enter recovery mode again by pressing and keeping pressed the recovery button, then turn the device on. When you see the recovery screen, press `Ctrl + D` to activate developer mode, then press the recovery button to restart the device.

> [!IMPORTANT]
> If after the restart you're immediately prompted with a screen asking you to return to a protected mode, press `Confirm`. The Chromebox will reboot into ChromeOS.
>
> Make sure that the device is no longer managed ([deprovision](./index.md#deprovisioning) it), there is no account signed in and then reach this screen **without continuing** with the setup:
> 
> ![sign in options](../images/sign_in_options.png)
> 
> Turn off the device from the menu in the bottom right, then retry enabling developer mode.

