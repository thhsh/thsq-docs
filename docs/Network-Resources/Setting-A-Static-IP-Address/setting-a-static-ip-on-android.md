# Setting a Static IP on Android

!!! Note
    This guide was made using Android 13 on a Google Pixel. Your screens may vary from these screenshots, depending on what version of Android and what model of device you are using.

1. Open your Wi-Fi/Network settings and tap on the lighting or sound control network you want to use.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/android/1_choose_network.png)

2. Enter the password for the Wi-Fi network, **do not click OK, Save, or Connect**.
3. Tap **Advanced Options** at the bottom of the password screen.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/android/2_enter_password_3_advanced_options.png)

4. In the advanced settings screen, tap on the **IP Settings** dropdown. (Probably currently shows DHCP.)  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/android/4_ip_settings_dhcp_dropdown.png)

5. In the dropdown that appears, select **Static**.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/android/5_static_dropdown.png)

6. Set a manual IP address in the proper range of your equipment (typically for lighting systems, this IP address is going to start with `10.101.125.xxx`, but you can check the IP address of your lighting or sound console, and set the IP to be in the same range - the first two sets of numbers should be the same, and the third set of numbers will typically be `125`.)  
      1.  !!! Warning
        If you are connecting multiple devices to the network (more than one iPad, phone, computer, etc, you **must** make sure that each device has a unique IP address. i.e., the last set of numbers must be unique for each device. If your first device is set to `10.101.125.101`, then you could set additional devices to use IPs `10.101.125.102`, `.103`, etc.)
7. Set the Gateway to `10.101.125.1`.
8. Set the Network prefix length to `16`. (On some devices, if you are asked for a Subnet mask, that should be set to `255.255.0.0`.)
9. If you are required to enter DNS 1 and/or DNS 2 settings, set DNS 1 to `8.8.8.8` and DNS 2 to `1.1.1.1`.
10. Tap the **Connect** button in the bottom right.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/android/6_static_ip_7_gw_8_subnet_9_dns_10_connect.png)
