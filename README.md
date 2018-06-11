# The Joy of Automation

------------------


## TODO:

- [ ] NODEMCUs:
    - [ ] Bag Neopixel Ring w. DHT11
    - [ ] Neopixel Strip (for desk)
    - [ ] Soil Moisture Sensor
    - [ ] Paper Signal for Temperature (Arrow)
    - [ ] Paper Signal for Weather (Umbrella)
- [ ] Raspberry Pis:
    - [ ] (Zero) Access Point + OLED Screen
    - [ ] SenseHat
    - [ ] PiFaceCAD (?) 
- [ ] Tasker
    - [ ] SMS with "Temperature" or "Humidity". Check Node-1 and respond with sms.
    - [ ] SMS With "Plants". Check moisture and respond with sms.
    - [ ] AutoVoice with "Temperature" or "Humidity". Check Node-1 and respond.
    - [ ] Autovoice with "water" and "plants". Check Node 3 and respond.
- [ ] Reveal Presentation
    - [ ] Show popular IoT projects.
        - [ ] [Dog Feeder](https://www.youtube.com/watch?v=vS6s9sN6Sq0)
        - [ ] [Smart Mirror]()
        - [ ] [Book Shelf LEDs]()

# Weather API Query

    http://api.openweathermap.org/data/2.5/forecast?id=1277333&appid=0f0337272dc3b00d7ab0076a26c13406


    a = urequest.get("http://api.openweathermap.org/data/2.5/weather?id=1277333&appid=0f0337272dc3b00d7ab0076a26c13406"]
    weather = "{} x {}".format( a.json()["weather"]["main"], a.json()["weather"]["description"].title())