# Setting a Static IP on Windows

!!! Note
    This guide was made using Windows 11 Pro. Your screens may vary from these screenshots, depending on what version of Windows you are using.

1. Open your **Settings** app from the Start menu, and select **Network & internet** in the left column.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/1_network_internet_settings.png)

2. From the Network and internet settings screen, ensure **Wi-Fi** is turned **on**, and the click on the **Wi-Fi** block to enter WiFi settings.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/2_wifi_settings.png)

3. Click on **Show Available Networks** to view all available WiFi networks, and connect to the sound or lighting control network. 
4. Click on **[Network Name] properties** to change the settings for that specific network.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/3_connect_to_network_4_properties.png)

5. Set the Network profile type to **Private network**.
6. Scroll down to **IP assignment** and click on **Edit**.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/5_private_network_6_edit_ip.png)

7. In the **Edit network IP settings**, click on the dropdown menu and choose **Manual**.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/7_manual_ip.png)

8. Turn **On** the slider for **IPv4**. (IPv6 can remain turned off.)  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/8_enable_ipv4.png)

9. Set a manual IP address in the proper range of your equipment (typically for lighting systems, this IP address is going to start with `10.101.125.xxx`, but you can check the IP address of your lighting or sound console, and set the IP to be in the same range - the first two sets of numbers should be the same, and the third set of numbers will typically be `125`.)  
      1.  !!! Warning
        If you are connecting multiple devices to the network (more than one iPad, phone, computer, etc, you **must** make sure that each device has a unique IP address. i.e., the last set of numbers must be unique for each device. If your first device is set to `10.101.125.101`, then you could set additional devices to use IPs `10.101.125.102`, `.103`, etc.)

10. Set the Subnet Mask to `255.255.0.0`.
11. Leave Gateway and Preferred DNS blank, or leave the value that was already in the box.
12. Click the **Save** button at the bottom.  
![](https://ksl-kb.b-cdn.net/static-ip-tutorial/windows/9-11_set_ip_subnet_gw_12_save.png)