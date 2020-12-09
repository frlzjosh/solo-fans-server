- I have created a home automation service that will read temperature data and will turn on a fan in the event it get's too hot in your room. 
- I would say 95% of it is working because I am not succesfully streaming this temperature data to my back-end service. I am able to successfully read the arduino sensor data, however I am having an asynchronous issue when reading the streamed data as opposed to reading the mock data I am generating and feeding to my client and using to toggle my fan.
- My biggest issue was finding a reliable source to use to utlize MQTT on my ARDUINO Nano 33 IOT embedded device. It is a new device and there are just so many brokers, libraries, and workflow to incorporate MQTT to an embedded device.
- Another issue I faced was getting socket.io to work in my front-end. For some reason the current version isn't fully supported and it took my a full day to find out that I needed to downgrade.
- I love using Medium articles to help me get started with stuff, direct documentation for the front-end API's I used were also very useful, and I used YouTube most of the time for most things Arduino related.
- I purchased an Arduino NANO 33 IOT so I can have access to wifi, solder tool, and solder iron
- I would say I spent about at leat 60 hours on this whole project including research and development in my back-end and front-end
- I am the only person that worked on this application.