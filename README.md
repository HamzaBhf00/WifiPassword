# How to show Wifi Password 👀

The command **netsh wlan show profile** is used to list all the Wi-Fi profiles that are stored on your computer. This includes the name of the network, the security type, and the password (if it is saved).
To use this command, open a Command Prompt window as administrator. Then, type the following command and press Enter:

```netsh wlan show profile```

## Example:
![wifi](https://github.com/HamzaBhf00/WifiPassword/assets/93322506/0ded3ead-5f56-4dcc-9004-8a092e3bda93)


This will list all the Wi-Fi profiles that are stored on your computer. The output of this command will vary depending on the number of Wi-Fi profiles that you have saved.
For each Wi-Fi profile, the output will include the following information:
- Profile name: The name of the Wi-Fi network.
- SSID: The Service Set Identifier (SSID) of the Wi-Fi network. This is the name that you see when you are scanning for Wi-Fi networks.
- Security type: The security type of the Wi-Fi network. This can be WEP, WPA, WPA2, or WPA3.
- Key Content: The password for the Wi-Fi network. This will only be displayed if the **key=clear** parameter is used.

If you want to see the password for a particular Wi-Fi network, you can use the following command:

```netsh wlan show profile name="Wi-Fi name" key=clear```

Replace Wi-Fi name with the name of the Wi-Fi network that you want to see the password for.

## Example:
![wifid](https://github.com/HamzaBhf00/WifiPassword/assets/93322506/293d4df6-1f63-40d2-86dd-3ceef58d2059)

> Note: Note that this command will only work if you have saved the password for the Wi-Fi network in your computer. If you have not saved the password, you will not be able to see it using this command.
