# Setting a Static IP on MacOS

!!! Note
    This guide was made using MacOS Sonoma (version 14.3). Your screens may vary from these screenshots, depending on what version of MacOS you are using.

1. Click the wireless symbol in the top right of your screen to open the Wi-Fi menu.
2. Click **Wi-Fi settings** at the bottom of the Wi-Fi menu.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/macos/1_2_wifi_menu.png)

3. Connect to the lighting or sound control network you want to use, and then click on the **Details** button to the right of the current wireless network.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/macos/3_settings_details.png)

4. In the left menu, select **TCP/IP**, and then click on the **Configure IPv4** dropdown menu.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/macos/4_dhcp_dropdown.png)

5. In the dropdown menu, select the **Manually** option.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/macos/5_manually_dropdown.png)

6. Set a manual IP address in the proper range of your equipment (typically for lighting systems, this IP address is going to start with `10.101.125.xxx`, but you can check the IP address of your lighting or sound console, and set the IP to be in the same range - the first two sets of numbers should be the same, and the third set of numbers will typically be `125`.)  
      1.  !!! Warning
        If you are connecting multiple devices to the network (more than one iPad, phone, computer, etc, you **must** make sure that each device has a unique IP address. i.e., the last set of numbers must be unique for each device. If your first device is set to `10.101.125.101`, then you could set additional devices to use IPs `10.101.125.102`, `.103`, etc.)

7. Set the Subnet mask to `255.255.0.0`.
8. Leave Router blank, or leave the value that was already in the box.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/macos/6_static_ip_7_subnet_8_router.png)

9. Click **OK** at the bottom of the screen to save.