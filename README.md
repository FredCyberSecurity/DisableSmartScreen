# Temporarily Disable "Smart Screen For Microsoft Edge" in Reputation-Based Protection

Under Reputation-Based Protection in Windows Security, you can see that "Check Apps and Files" and "Smart Screen For Microsoft Edge" are ON, the toggles are grayed out, and these settings are managed by your administrator. This means that, as a user, you should not be able to modify these settings, which is common in enterprise setups.

I have discovered a clever method to temporarily disable these options, even though they are managed by the enterprise administrator, AND this requires NO administrative privileges on the client.

Open the Reputation-Based Protection window.
1. Insert a USB drive into a USB port.
2. Eject the USB drive.
3. Keep the window open and wait, for as long as it takes.
4. You will get the option to toggle and turn off "Smart Screen For Microsoft Edge."
5. The toggle becomes temporarily accessible, allowing users to disable "Smart Screen For Microsoft Edge." While the policy eventually re-syncs and re-enables the setting, there is a window of opportunity (a few seconds or minutes) during which users can exploit this temporary state for potentially malicious activity.

This works 4 out of 10 times, in my experience.

See the video for proof of concept (PoC).
(The video is in Norwegian)



https://github.com/user-attachments/assets/9293a787-cf39-44e5-a898-6f6af6af9d8a

