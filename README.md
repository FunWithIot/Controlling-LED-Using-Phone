# Controlling-LED-Using-Phone
Control Led using any device on the same wifi connection using the esp-8266 module.

• In the Setup phase Connect the NodeMcu with The Wifi Access Point Using given Credentials
hardcoded into the code.

• Once connected the nodemcu will be assigned an DHCP ip. Connect to the serial port and write the Ip
address.

• Start a Server on Any Port.

• Next Write the Html Webpage on the serial connection. On accessing givenIp:Given Port will let you see
the particular webpage.

• In the loop phase we constantly listen for response and based on data received using get method parse the
url To get the response and then based on the response set the Voltage of Control Pin High or Low.
