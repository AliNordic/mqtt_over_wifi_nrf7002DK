# MQTT over Wi-Fi on the nRF7002DK

This is a sample nRF Connect SDK application for the nRF7002 DK that demonistrate the use of the provisioning service and running MQTT over Wi-Fi.

The sample uses the prvisinoing service to allow you to securely connect the nRF7002 DK to your Wi-Fi network using the the nRF Wi-Fi Provisioner mobile app.
Once connection to the internent is established, the nRF7002 DK will act as an MQTT client, connects to an MQTT broker, and establish bidirectional communication over Wi-Fi
with another MQTT client connected to the same broker. Through this connection, you can control the LEDs and monitor the buttons on the nRF7002 DK. 

How to use:

1.  Flash the demo application to your board nRF7002 DK.
    1.1 Option A: Build from source code
    1.2 Option B: Flash the binary files in /hex

2.  Provision the nRF7002 DK to your access point/route:

    2.1 Install the nRF Wi-Fi Provisioner mobile app on your smartphone or tablet.

    2.2 Select your Wi-Fi network from the list of available Wi-Fi networks and enter your Wi-Fi network password (access point/router password)..

3.  Connect to the nRF7002 DK over MQTT using another MQTT client.

More details can be found on this blog post: 
