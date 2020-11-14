# mqtt_flexiweigh

A weighbridge Management Software that reads data from from a scale using rs232 serial cable.
The whole idea is to build a client switch written using tkinter(graphic user interface), pyserial 
for reading data from the scale, paho_mqtt for sending data to the mqtt broker and a django rest api 
server is created to listen at the broker and as the whole company erp
