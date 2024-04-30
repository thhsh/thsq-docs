# Setting a Static IP on iOS/iPadOS

!!! Note
    This guide was made using iOS 17.3. Your screens may vary from these screenshots, depending on what version of iOS you are using.

1. Open your **Settings** app, and select **Wi-Fi** near the top of the menu.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/ios/1_wifi_settings.png)

2. Connect to the lighting or sound control network you want to use.
3. Once the network shows at the top, tap on the :octicons-info-16: symbol to the right of the network name.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/ios/2_connect_to_network_3_details_button.png)

4. From the network settings screen, scroll down and tap on **Configure IP**.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/ios/4_configure_ip_menu.png)

5. Change the setting on this page from Automatic to **Manual**.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/ios/5_manual_ip.png)

6. Set a manual IP address in the proper range of your equipment (typically for lighting systems, this IP address is going to start with `10.101.125.xxx`, but you can check the IP address of your lighting or sound console, and set the IP to be in the same range - the first two sets of numbers should be the same, and the third set of numbers will typically be `125`.)  
      1.  !!! Warning
        If you are connecting multiple devices to the network (more than one iPad, phone, computer, etc, you **must** make sure that each device has a unique IP address. i.e., the last set of numbers must be unique for each device. If your first device is set to `10.101.125.101`, then you could set additional devices to use IPs `10.101.125.102`, `.103`, etc.)

7. Set the Subnet Mask to `255.255.0.0`.
8. Leave Router blank.
9. Tap **Save** in the top right of the screen.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/ios/6_static_ip_7_subnet_8_router_9_save.png)