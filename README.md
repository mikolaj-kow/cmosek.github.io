
So I've started to write down useful projects because my browser's tabs eats a lot of RAM

If you find anything useful - it's yours

## Security

[Security]

### Hardware 

- [PoisonTap](https://github.com/samyk/poisontap)

### Modern Web



#### Crypto - scanners

##### TLS
- [SSLLabs CLI](https://github.com/ssllabs/ssllabs-scan/)

###### Certificate Transparency
- [Cert Search](https://crt.sh/)
- [Cert Spotter](https://github.com/SSLMate/certspotter)

##### CSP
- [CSP Evaluator](https://csp-evaluator.withgoogle.com/)

### Mail

- [Sender Score](https://www.senderscore.org/)

#### SPF
- [SPF Explained](https://blog.returnpath.com/how-to-explain-spf-in-plain-english/)
- [SPF Creation](https://blog.returnpath.com/protecting-your-brand-from-phishing-how-to-create-your-spf-record/)

#### DKIM
- [DKIM Explained](https://blog.returnpath.com/how-to-explain-dkim-in-plain-english-2/)
- [DKIM Creation](https://blog.returnpath.com/protecting-your-brand-from-phishing-how-to-create-a-dkim-record/)

#### DMARC
- [DMARC Explained](https://blog.returnpath.com/how-to-explain-dmarc-in-plain-english/)
- [DMARC Creation](https://blog.returnpath.com/build-your-dmarc-record-in-15-minutes-v2/)

### DDoS
- [BlackArch](https://blackarch.org/dos.html) various tools

## Home Automation

### Sonoff
- [Tasmota](https://github.com/arendst/Sonoff-Tasmota) - Sonoff firmware with MQTT and OTA
- [ESPurna](https://bitbucket.org/xoseperez/espurna) - ESP8266 firmware
- [Sonoff SC Hack](http://tinkerman.cat/itead-studio-sonoff-sc-revisited/)
- [Sonoff TH10/16 Mod](http://tinkerman.cat/sonoff-th10-th16-sensors-displays-actuators/) - GPIO4/14
- [Sonoff POW](http://tinkerman.cat/the-sonoff-pow/) + Sensor [HLW8012](http://tinkerman.cat/hlw8012-ic-new-sonoff-pow/)

### MGMT software
- [MongooseOS](https://mongoose-os.com/) - an OS + SDK for IoT
- [Blynk](https://www.blynk.cc/) mobile app + [local server](http://docs.blynk.cc/#blynk-server)
- [Huginn](https://github.com/huginn/huginn) ITFFT opensource alternative (rule-based automation engine)
- [Trigger Happy](https://github.com/foxmask/django-th)

### LED Strips

#### Lightbulb
- [Sonoff B1](http://tinkerman.cat/sonoff-b1-lights-and-shades/)
- [AiLight](http://tinkerman.cat/ailight-hackable-rgbw-light-bulb/)

#### Addresable LED Strips
- [FastLED GitHub](https://github.com/FastLED/FastLED) + [FastLED Webpage](http://fastled.io/) - framework for LED operations
- nice comparation of [LED Chipsets/Drivers](https://github.com/FastLED/FastLED/wiki/Overview) 

#### Music controlled LED
- MC [LED in jar](http://natural-nerd.com/music-reactive-light/)
- [Effect Lib](https://github.com/scottlawsonbc/audio-reactive-led-strip) + [Project Assembly](https://github.com/xNNism/rpi_led_visualizer)

#### Ambilight LED
- [Hyperion Tutorial](https://hyperion-project.org/threads/raspberry-pi-3-mediacenter-hyperion-ambilight-no-soldering.77/)
- [Video Grabber](http://raspberry-at-home.com/video-grabber-for-raspberry-pi/)s comparision 
- [STK1160 vs UTV007](https://hyperion-project.org/threads/comparison-fushicai-utv007-vs-stk1160.194/)
- [LightBerry](http://lightberry.eu/) - commercial

### TRV's

- [OpenTRV](https://github.com/opentrv)
- [DYI TRV](http://www.instructables.com/id/Smart-Radiator-Valve-With-Home-Assistant/)
- [Xavax/HT100BT/Comet](http://torsten-traenkner.de/wissen/smarthome/heizung.php) research
- [OpenHR20](https://github.com/OpenHR20/OpenHR20) lib
- [EQ3-BT](https://github.com/rytilahti/python-eq3bt) lib and cli intrface

### Air quality monitoring
- [Overview](http://vair-monitor.com/2017/01/19/measuring-dust-levels-measure-part-23/), sensors segment's and tech
- Sensors [Overview and comparision](http://aqicn.org/sensor/)
- PPD42 Sensor + [teardown](http://takingspace.org/wp-content/uploads/ShinyeiPPD42NS_Deconstruction_TracyAllen.pdf) 
- Sensors [comparision](http://www.takingspace.org/make-your-own-aircasting-particle-monitor/)
- [Making Sense](https://github.com/waagsociety/making-sensor/raw/master/sensor_kit/doc/Sensor_Kit_doc.pdf) - 
- [DustDuino](http://dustduino.org/)
- [Sharp GP2Y1010AU0F implementation](http://www.howmuchsnow.com/arduino/airquality/)
- [GP2 Test](http://www.ti.com/lit/ug/tidub65c/tidub65c.pdf) by Texas Instruments
- [PPD42NS implementation](http://www.howmuchsnow.com/arduino/airquality/grovedust/)
- [SEN0177](https://www.dfrobot.com/wiki/index.php/PM2.5_laser_dust_sensor_SKU:SEN0177)
- [PMS5003](https://ourairquality.org/index.php/build-an-air-quality-monitor/) build
- [Paper](http://aqicn.org/aqicn/doc/a-low-cost-instrument-for-environmental-particulate-analysis-based-on-optical-scattering.pdf), [paper2](https://www.atmos-meas-tech-discuss.net/amt-2015-331/amt-2015-331.pdf), [paper3](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4569398/)
- [vThings](http://vair-monitor.com/2017/01/06/vthings-co2-and-dust-monitor-v3/) internal build
- [AQ-SPEC](http://www.aqmd.gov/aq-spec/evaluations/summary) sensors evaluation
- [Bachelor Thesis](https://cdn.hackaday.io/files/21912937483008/Thomas_Portable_Air_Quality.pdf) on Air Quality Monitoring
- [explanation](https://www.thebeijinger.com/blog/2016/01/02/which-iaq-monitor-should-i-buy) why you should calibrate sensors

#### Polish stuff
- [Kraków](http://www.krakow-zdroj.pl/) - amatorska stacja SDS011 i PMS1003 - z numeryczną korekcją wilgoci metodą [regresji nieliniowej](https://www.facebook.com/KrakowZdroj/posts/1551991205093317) 
- [Niepołomnice](http://www.powietrze.info/about.html) - amatorska stacja - SDS021 i PMS7003

- polish http://nettemp.pl/forum/viewtopic.php?f=19&t=569

### Sensors
- [HX711](https://github.com/bogde/HX711) - Weight Sensor
- [Hygrometer](http://www.kandrsmith.org/RJS/Misc/Hygrometers/calib_many.html) comparision

### Misc
- [OpenEnergyMonitor](https://openenergymonitor.org/)
- [Noduino](https://sbstjn.com/noduino/) - JavaScript and Node.js Framework for accessing basic Arduino controls from Web Applications
- Sleep as Android [Tasker plugin](https://sleep.urbandroid.org/documentation/tutorials/tasker/), [API](https://sleep.urbandroid.org/documentation/developer-api/intents-and-content-providers/)+[Intents2MQTT](https://play.google.com/store/apps/details?id=pixento.nl.broadcasttomqtt), [IFTTT plugin](https://sleep.urbandroid.org/documentation/integration/ifttt/)

## Mobile / Android

- [EFIDroid](http://efidroid.org/) - open UEFI Android bootloader + [msm8996 bug](https://github.com/efidroid/projectmanagement/issues/89)
