# Windows boot manager

[![Windows boot manager](red2.png)](https://github.com/digishare/windows-boot-manager)

Windows Boot Manager loads from the volume boot code, which is part of the volume boot record. It helps your Windows 10, Windows 8, Windows 7, or Windows Vista operating system start.


## Where Is Windows Boot Manager Located?

Configuration data required for Boot Manager rests in the Boot Configuration Data store, a registry-like database that replaced the boot.ini file used in older versions of Windows like Windows XP.

The BOOTMGR file itself is both read-only and hidden. It is located in the root directory of the partition marked as Active in Disk Management. On most Windows computers, this partition is labeled as System Reserved and doesn't obtain a drive letter.


## Can You Disable Windows Boot Manager?

You cannot remove the Windows Boot Manager. However, you can reduce the time that it waits for you to answer which operating system you want to start by choosing the default operating system and then lowering the timeout time, basically skipping the Windows Boot Manager altogether.

1. Open Administrative Tools, which is accessible through the System and Security link in Control Panel.

2. Open System Configuration.

3. Select the Boot tab on the System Configuration window that opens.

4. Choose the operating system you want to always boot to.

5. Adjust the Timeout time to the lowest possible time, in seconds, which is probably 3

6. Choose OK or Apply to save the changes.

7. Boot manager should appear to be disabled.
