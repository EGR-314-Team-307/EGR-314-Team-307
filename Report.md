---
Report:
---
<h1 align="center">
Fire Extinguisher Sentry
</h1>
<p align="center">
Februrary 27, 2024
</p>
<p align="center">
Arizona State University
</p>
<p align="center">
Dr. Nichols
</p>
<p align="center">
Team 307
</p>
<p align="center">
Moksh Goel
</p>
<p align="center">
Andrew Headley
</p>
<p align="center">
Ethan Young
</p>
<p align="center">
Nathan Vairora
</p>




# [Team Organization](./TeamOrg.md)

When our team formed, we joined together to decide what the goals of this project would entail. From our discussion, we highlighted certain aspects that we deemed important to accomplish within the scope of the class. These ideals include:


- Demonstrate proficiency in core engineering principles
- Enhance leadership skills within our team
- Become proficient in understanding user needs
- Gain practical experience in embedded systems
- Develop team problem-solving skills and open communication


After brainstorming our shared expectations for the project, we summarized our collective thoughts into a product mission statement that encapsulates what we hope to achieve with this venture:

To create a usable, viable product that is relatively unique and allows a measure of automation to be brought to the crop-growing process. As well as providing an appropriate level of challenge for each team member, and meeting the EGR 314 course requirements. 


# [User Needs, Benchmarking, and Requirements](./UserNeeds.md)


## VOC Benchmarking
The first couple of searches, as well as the fourth and fifth searches, focused on existing monitoring systems that used a variety of different sensors. The third search focused on the automation aspect, where consumers could set the product to run in their absence The sixth search focused on an automated fire suppression system.
## Search 1: “plant moisture reader”

**Selected Product:**

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/8d111a90-2d4a-4182-ad0a-4a97c1994408)

- Figure 1: 3-In-1 Soil Meter with Moisture, PH, and Light Meter for Indoor/Outdoor Gardens
- Price: $12.99
- Vendor: Home Depot
- Description: This product was designed to detect moisture, pH, and sunlight. The product is great for testing in lawns, gardens, greenhouses, and homes because it is designed for indoor and outdoor use.

**Table 1: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “I wasn’t sure I would be able to manage this tool purposefully, but it’s easy to use and the information it yields does not require an “expert’s” interpretation. I am grateful to have this handy, multi-purpose meter to help me improve my gardening results.” | The device should be easy to use. (Explicit) |
| “It was easy to use and inexpensive. Don’t have to guess anymore.” | The device should be a reasonable price. (Explicit) |
| “As far as I can tell it’s working well. Easy to read and appears to be accurate. Best of all, no assembly required.” | The device should be pre-assembled. (Explicit) |

**Table 2: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “Did not register even when used on different soils.” | The device should work on different soil types. (Explicit) |
| “Same problem as all the other reviews, ph meter just doesn't work...” | The device should function as intended. (Explicit) |
| “It died after using it 3 times. You can’t change the battery” | Battery-powered devices need to be accessible to replace/recharge. (Explicit) |

## Search 2: “plant monitor kit”

**Selected Product:**

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/e93a931a-0015-4050-8f73-611688bb34fd)


- Figure 2: ALMOND Automatic Irrigation DIY Kit, 4Pcs Capacitive Soil Moisture Sensor+4Pcs 1 Channel 5V Relay Module + 4Pcs Water Pump + 4Pcs 1M Vinyl Tubing for Arduino Moisture Detection Garden Watering
- Price: $16.98
- Vendor: Amazon
- Description: This product is an automatic watering system kit. The components in the kit include a soil moisture sensor, water pumps, and a relay module.

**Table 3: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “Works great. Maybe a bit lacking in terms of instructions but will be compatible with most tutorials when googling "Arduino watering system". Sensitivity of the moisture sensors isn't great. Wet to dry is about 250-450 on the analog read, but it's good enough to work reliably.” | The device needs to have clear instructions for the user. (Explicit) |
| “Worked well with Arduino. -1 star because it included only one type of wiring connection. My MKR 1010 IOT carrier Rev 2 was not compatible with them.” | The device should be compatible with the intended components. (Explicit) |

**Table 4: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “None of the sensors changed output when in air, dirt, or water and the one pump I tested, leaked behind the pump housing. I realize these are cheap pumps but they shouldn’t leak in that spot. Just bad design. They were returned with a note in the box.” | The device shall have quality components. (Explicit) |
| “The relay would not turn off when the soil was moist. I queried experts on a couple of electronics forums and scoured numerous YouTube videos. Two major problems came to light: the first is a design / manufacturing problem with the V2 capacitive board where sloppy masking leads to an 80+% defect rate that causes the moisture sensor to respond way too slowly to moisture changes; the second is the relay - according to the experienced electronics professionals I asked, the triggering voltage is flawed.” | The design of the device should be efficient. (Latent) |

## Search 3: “Automatic plant watering system”

**Selected Product:**

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/47cc990c-1042-4652-a101-45072ebe5600)

- Figure 3: RAINPOINT WiFi Automatic Watering System For Indoor Potted Plants, DIY Drip Irrigation Kit Remotely Control Auto/Manual/Delay Watering Mode via APP, Automatic Self-Watering Irrigation System with Pump
- Price: $69.99
- Vendor: Amazon
- Description: App-controlled irrigation system that can use environmental information like local temperature, humidity, and sun position to know when to water house plants, but a timer can also be set instead.

**Table 5: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “The standout feature of this watering system is its Wi-Fi connectivity. Once set up and connected to the dedicated app, you can control the watering schedule and duration remotely. This is a game-changer for those with busy schedules or frequent travelers. You can ensure your plants are watered at just the right times without being physically present, which is a huge time-saver…The drip irrigation mechanism provides consistent and targeted watering, preventing overwatering or underwatering, which can be common pitfalls in plant care. It helps to maintain optimal soil moisture levels, promoting healthy root development and overall plant well-being.” | The device should be remotely operable. (Explicit) |
| “I like that it can run every set number of days/hours rather than specific days of the week if that makes sense. This way I can water every other day, every 2 days etc. Their other wifi timers could use this feature! This being said, there is no way to have it run at a specific time that you set. I wish I could have it run at 7 in the morning without having to be awake to start it... I wish that it had a different type of watering system as an option. How it works is that it injects the water 3 inches or so down to the root which is OK, but it seems too localized, especially if it's a larger plant. It might be better to moisten more of the soil. I get that a sprinkler might not make sense for indoor use because it could get water everywhere, but a porous or fabric "soaking hose" or something similar would be a good option to have so that it can soak more of the soil from the top without shooting water everywhere.” | The device should have various options for setting timers. (Explicit) The device should be adaptable to provide different levels of watering depending on user needs. (Explicit) |

**Table 6: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “I have never written this type of review before but my experience leads me to believe that this timer could have pumped 16 quarts of water all over the floor, because, when pumping water it changed from wifi to manual without my making a different setting. When this happened, wifi was pumping water as set but about half way through the wifi pumping time, the manual light lit up suddenly. I had not touched the timer. I sat and watched. I had a stopwatch running so I could determine if the timer would shut off at the time I had it set. It did not turn off at 4 minutes 22 seconds ( the setting) . Instead it kept pumping water. If I had not been sitting there monitoring the timer it may have just continued to pump water until it was all gone, all 16 quarts of it, and had a huge water overflow on the floor. My advice: if you buy this timer, check these things a) does it maintain the wifi connection. This one did not and it was not my 2.4 G wifi signal. b) Check to see if the timer starts at the time you have it set for, c) then with a stopwatch check to see if it stops pumping the water as set. Would I advise you to buy this brand...nope. I will say this positively: I called them 4 times to ask questions and they were good about answering my questions. They indicated that maybe the timer was faulty. Fat lot of good | -


## Search 4: “Plant Monitor Soil Test Kit”

**Selected Product:**

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/c8f740c2-57d0-497d-81b0-e7be01de0af7)

- Figure 4: WANFEI Plant Monitor Soil Test Kit, Flower Care Soil Tester SmartPlant Tracker Intelligent Sensor Plants Detector Bluetooth Monitor for Light Moisture Fertility Temperature Level for iOS and Android
- Price: $29.99
- Vendor: Amazon
- Description: 4 in 1 Intelligent Sensor --- Provides information on soil moisture, fertility level, temperature, and light intensity --- The Grow nursing home is an intelligent sensor designed to be planted in an indoor pot.

**Table 7: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “I've had one of these a month now, and just got a second one. I am using these with Home Assistant, and an ESPHome bluetooth proxy device to send the data to Home Assistant. In HA I set up notifications to let me know when to water the plants. I will update this in case one breaks or anything. So far after a month, the first one still says 100% battery left. A little pricey, but now I can "remember" to water the plants much better with the HA notifications.” | Sends constant data such as notifications. (Explicit) Could be more cost efficient. (Explicit) |
| “I hope this thing is accurate because I love the app and the ease of use. It seems super accurate for sunlight and water because I can test that. The fertility of the soil is the best feature and seems to be working. It showed a low fertility and I started adding fertilizer and the numbers went up. I have yet to hit the range for soil fertility mark so I hope it is right because I am jacking up the fertilizer. But so far I really like this product. Great app and if it is as accurate as it seems so far it is the missing ingredient to my planter gardens!” | Needs to provide accurate information of the product. (Explicit) |
| “After almost 3 weeks of using this I can say that it was a great purchase! I connected my Strelitzia to a self watering pump and I was always wondering if I'm giving it too much water or too little or too often/not often enough. It clearly shows the current soil humidity, light and soil fertility + air temperature. It even shows a nice chart of the historical data on a daily or weekly graph. Would definitely recommend it to anyone unsure of their plant's conditions over time!” | The device is automated providing further comfort to the user. (Latent) |

**Table 8: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “Sensor reports 10-13% moisture while absolutely drenched after rain. Completely unhelpful. Have this configured in Home Assistant. The illuminance values systematically show higher values than my personal weather station, but at least are directionally correct. Temperature sensor actually seems at least somewhat accurate.” | Information and data provided should be accurate. (Explicit) |
| “Bought two for my plants to follow the directions and wasn't able to connect to the app because it keeps crashing. I have tried on my android phone and tablet multiple times . Even tried taking the battery out to see if it syncs to Bluetooth after replacing the battery. The device shows up on the Bluetooth setting but said I need an app to connect so I did download the flower app twice and still no success. Bad app” | The app interface and processing should be accurate and easy to use. (Explicit) |
| “I started to be suspicious of the readings when I realized that after using this device on ten different plants, they all came back with 35 to 45% moist levels. I then compare the readings of this product against another product that I have been using for a while, but the bad part is that you need to wait 10 minutes for the reading to be accurate. The difference between the two was unbelievable! We are talking about 10 in my old, slow device vs 45 on this WANFEI or another 35 in WANFEI vs 85 in reading the old sensor. The thing is that as soon as I put my finger on the plant that was reading 85 on my old sensor, I realized how wet the soil was. (a lot).” | The data being collected should be accurate. (Explicit) |

## Search 5: “electronic water monitor for plant”

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/e857681b-5bda-4768-8eb9-55dc0537b93c)

**Selected Product:**
- Figure 5: ECO WITT WH0291 Soil Moisture Tester Plant Soil Moisture Sensor Meter with Digital LCD Display
- Price: $36.99
- Vendor: Amazon.com
- Description: The soil moisture meter offers easy plant care, swiftly measures soil moisture with a clear digital LCD display. Used indoors or outdoors, it's waterproof and adaptable. Customize moisture levels with the custom mode for various soil types.

**Table 9: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “I have about ten fruit trees and 10 blackberry plants. I had them for 3 years and they have come to a large size. You really need to manage the water levels to get the best and best fruit. I jumped in head down this year with all the correct fertilizers and oils the plants need but, when it comes to the water or moisture of the soil it looks dry on the first inch or so but then where the roots are it's wet and you over water. I looked for months on the best products to just have the water level happen automatically each day as needed. I already collect 3300 gallons of rain water from my house so the water has all the natural chemicals needed. I have a pressure pump system to supply my mini sprayers but now how wet is the soil.??? I read up all the descriptions of how to set up and use this system and found next to nothing else then call them if you buy the units and need help. I did not want to waste my time with someone that may not work but I took a chance and I am glad I did. THEY COULDN'T be easier to pair and install. You simply hook the receiver to your wifi in settings then download their app next, put a battery in the soil unit, wait 30 seconds and the sending units are seen by the app automatically. I WISH other systems were this easy so you can't make a mistake. Buy these product the are outstanding in every way, attached are some screen shots you can check the soil from location you happen to be at and for me it just press that zone button and my plants are done, I only have to manually press the water button for that zone if the soil is behind dry even after the automatic cycles. GREAT product and , oh by the I own a worldwide computer computer and know a GREAT product on the technology side and this rates the highest on ease of setup and results.” | Needs to be an automated system effortlessly manages water levels (Explicit) |
| “I have about 24+ of these in my home. I use it to track some of my rarer houseplants and I have a dashboard that shows my moisture at all times. I was really stressed and always checking my plants before, but with this I have a much better handle of the plants in my home.” | Needs to provide peace of mind by accurately monitoring plants (Latent) |
| “This works surprisingly well! I started out with one to test and am up to 7 so far. The moisture reading corresponds pretty well to when plants start wilting. It's different for each plant type but is consistent for the same plant, so is great for knowing when to water, especially if you're not around to see the leaves starting to droop. There is a green cap hidden under the cardboard in the box that holds the sensor in place!!! They probably mention it in the instructions, but who needs instructions, you just put the battery in and the sensor automatically shows up in the ecowatt app for your weather station in less than a minute. The green cap goes over the battery compartment to make it waterproof. It's unnecessarily tight, but I guess that's a good thing.” | Needs to be accurate and an easy set up (Explicit) |

**Table 10: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “Worked great, after calibrating correctly, for 4 months. The probe is still sending a signal, the station is still receiving it, but the set button on the station no longer works to recalibrate after its first battery change. Waiting to hear from Ecowitt about the 1 year warranty.” | Needs to be open source (Explicit) |
| “Was great but now the phone and PC application no longer works due to server changes by Ecowitt. Currently, they are completely useless.” | Needs to be open source (Explicit) |
| “I bought 11 of these over the past year to monitor my plants outdoors and so far 4 have stopped working. The little red light flashes as expected to indicate the battery still works but they stopped communicating with both of my gateway receivers. The receivers are still showing data for the few sensors I have left so I know it is not a problem with those. I tried resetting the receivers and changing the batteries for the affected sensors, but still no luck. The sensors seem to be well sealed too as I don't see any sign of moisture build up inside the battery compartment. I contacted the company and they kindly sent me 2 replacements for the first two that died but since then another 2 have died.” | Needs to be modular for easy repairs(Explicit) |

## Search 6: “Automatic Fire Extinguisher”

**Selected Product:**

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/4d01349b-ca81-457a-bfed-280f8c4dbd52)

- Figure 4: JOSEOZSTA Automatic Fire Extinguisher-Car Fire Extinguisher 
- Price: $39.99
- Vendor: Amazon
- Description: Joseozsta Automatic Fire Extinguisher is full-automatic,when it's trigger device catch fire, it will start working in 2-3 seconds,and fire extinguishing only less than 9 seconds

**Table 11: 4-5 Star Review Positive Comments**

| Voice of the Customer | Related Customer Need           |
|-----------------------|---------------------------------|
| “the product was inexpensive when compared to the competition. Good transaction.” | The product should be competitive to the market (Explicit). |
| “Merchandise is in excellent condition. Thank you for a great deal, I really appreciate it. ” | Ensure the product is in excellent condition (Explicit). |
| “I bought 2 of these unit to install in the back of a large RV propane/electric absorption fridge just in case there is ever a fire back there. Gives me peace of mind and hopefully they will never be used and if so they work as advertised” | The product should work as advertised (Explicit). |

**Table 12: 1-2 Star Review Negative Comments**

| Voice of the Customer | Related Customer Need            |
|-----------------------|---------------------------------|
| “I threw it in my car once it came in and a week later, my son got a hold of a lighter and started a flame that caught our backseat while driving. I pulled over immediately and pulled the extinguisher out, but it didn’t work at all.” | The product should be easy to operate (Latent). |

## Organize: Figure 2: Jamboard of User Needs
Once each product's reviews had be evaluated for user needs, the team organized those needs into groupings of similarity. Six themes were then identified and labeled as categories, as seen in Table 11. Then taking into account the product reviews, the team weighed these categories by importance. 

**Table 13: Categorized and Ranked User Needs**

| Category    | Meta Statement                                             | Importance ★ |
|-------------|------------------------------------------------------------|---------------|
| Functionality | The product needs to function as intended.                | ★★★★★       |
| Design        | The product needs to have a quality design.               | ★★★★         |
| Quality       | All materials should be high quality.                     | ★★★          |
| Durability    | The product needs to be durable.                          | ★★★          |
| Safety        | The product needs to safely interact.                     | ★★★          |
| Accessibility | The product needs to be available.                        | ★★★          |

## Use Cases

### User Story #1: Sarah
Sarah, a busy professional, relies on a smart plant waterer to keep her indoor plants thriving amidst her hectic schedule. With customized watering schedules and real-time monitoring, the device ensures each plant receives the precise amount of hydration it needs, sparing Sarah the worry of wilted foliage. Through remote control via a mobile app, Sarah can nurture her indoor garden effortlessly, enjoying the lush greenery that enriches her living space.

### User Story #2: John
In a suburban garden, John installs an automatic plant cover to safeguard his delicate flowers from frost during chilly nights. As temperatures drop, the sensor-equipped cover detects the cold and swiftly unfurls, cocooning the plants in warmth until the weather improves. John can rest easy knowing his garden is shielded from harm, allowing his flowers to bloom undisturbed even in the coldest of nights.

## Aspects
The categories identified in Table 13 and their associated importances then guided the development of requirements necessary to meet user needs. These aspects will be used as litmus tests during the course of the development of the prototype. As each subsytem is developed, it will be checked against these aspects to verify if the subsystem satisfies them or not. In the event that the subsystem does not staisfy the aspect, it will be reworked until it does. Further, when each subsystem is integrated into the final project, an overall verification test will be performed, to see if the final prototype meets or exceeds the requirements. If the integrated system fails, then it will be reworked until it succeeds.
1. **Product Design**
   - 1.1 The design will emphasize user-friendliness.
   - 1.2 The design will be as portable as possible.
   - 1.3 The design will have various sizes.
   - 1.4 The design will be durable.

2. **Functionality**
   - 2.1 The product will be rechargeable.
   - 2.2 The product will have a motor actuator.

3. **Interactivity**
   - 3.1 The product will be designed to prevent accidental use.

4. **Adaptive Intelligence**
   - 4.1 The product will turn off if not used for more than 60 minutes to save energy.
   - 4.2 The device will be able to recognize touch and prevent injury by conforming to in-the-way objects.

5. **Customization**
   - 5.1 The product shall offer multiple size options.

6. **Manufacturing**
   - 6.1 The total BOM cost price of the product shall be <$200.
   - 6.2 The construction of the product must be easy enough to understand to where a non-engineer can fix it if it were to be broken.
   - 6.3 The product will be manufactured so that the parts stay in place during use.
   - 6.4 Functioning of the device shall be easy to check by the manufacturer.
   - 6.5 The product shall be designed to consist of the minimum possible amount of parts.

7. **Regulations**
   - 7.1 At least 2 analog sensors.
   - 7.2 At least 1 motor/linear actuator with bidirectional control ability.
   - 7.3 The product will run on 3.3V system logic-level voltage.
   - 7.4 The dimensions of the custom circuit board will not exceed 100mm x 100mm.



# [Design Ideation](./DesignIdeation.md)


During the design ideation phase, the team created a Jamboard and proceeded to put up any idea that came to mind, be it a phrase that sparked a thought, or an explicit statement saying what the idea was. No thought was dismissed outright, no matter how outlandish it may have seemed. Due to the space available on Jamboard, as well as the readability of the sticky note function, the ideas had to be boiled down to a handful of words. This helped the ideas stay at a vague enough level that each team member could use them as inspiration and go their own ways with it. The downside to this method was that some ideas sounded like rephrasings of others, so some discussion had to happen in order to justify keeping all or some of similar ideas. 
## Generate Ideas
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/91f41a39-f1df-48e3-a80d-fac1992e7646)

### Sort Ideas
After the ideas were gathered, they were then sorted into project ideas and features. The team also identified prior to starting this that a focus on plant cultivation or care was an ideal concept based on the project scenario, so a third category was added to collect the ideas and features.

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/5bbc9d27-40f7-44a4-a943-0cf3fc0eac2b)

#### Design 1: Plant Frost Shield
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/ecce3bb7-61b1-4caf-8cc8-0aa35cedc910)

During the winter, plant owners cover their plants to protect them from the freezing temperatures. Our design concept supports the health of a plant during extreme cold conditions by automatically covering the plants when it's too cold, based on readings of moisture and temperature. The sides of the design will be covered as well and are not covered for modeling purposes.

#### Design 2: Automated Plant Watering System
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/53ed1c7a-626a-40bc-9b41-e607c79f2e76)

This automated plant watering system would use a timing system, moisture and temperature sensors, and two motors to manage the watering needs of a user’s shelf of plants. The sensor data would be used to determine the best times for watering, so the user can get feedback about the efficacy of whatever time intervals they use. The sensor information and watering status would be transmitted via WiFi to the user’s device so they can monitor it remotely. The watering head would move on rails back and forth so it can water the plants, then move out of the way so the user doesn’t obscure their plants. The system would include an emergency stop, both a manual one and an automated one, to avoid dumping the user’s entire water supply into the plants.

#### Design 3: Water Sensor Management Network
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/757f6a3e-4170-4c0a-b5f7-36c9ee9f8bbf)

The Water Sensor Management Network is an advanced and comprehensive system designed to monitor and manage the percentage of water in the soil and the water quality across various environments. Using moisture sensor technologies and interconnected data infrastructure, this network provides real-time insights into water conditions, ensuring efficient resource management and environmental sustainability.

#### Design 4: Fire Extinguisher Sentry
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/baa90fdc-6884-4ba5-b803-2480c5c28e21)

This automated fire extinguisher operates by utilizing a light sensor and temperature detector to identify fires swiftly. Once a fire is detected, it activates a motor that moves the extinguisher into position and triggers its operation, swiftly suppressing the flames and mitigating potential damage.

# Updated Selected Design
At the beginning of the design process, the team focused primarily on automating plant care while users were away. This route was taken due to uncertainty in the feasibility of other project ideas. This led to some dissatisfaction in the team that the project would be something to be proud of, and so the team consulted with one of the teaching assistants for the course. After expressing their thoughts, the teaching assistant indicated that one of the more popular ideas that the team had set aside in the belief that it would not be possible would actually be doable if the scope was limited properly. This is what led the team to pivot the project idea away from automated plant care to an automated fire extinguisher system. This new project would incorporate some of the same needs and requirements, albeit with a change in sensors for the individual subsystems. 

# [Block Diagram](./BlockDiagram.md)

Prior to component selection, a block diagram was constructed to get a general idea of how each component would need to connect to each other to function. This also informed the team on how many pins might be required on the microcontroller, as well as potential power requirements for each component. Each team member took charge of a part of the subsystem, with the member being responsible for the microcontroller and also taking on the power subsystem.

Andrew Headley: Microcontroller
</p>
Nathan Vairora: Humidity Sensor
</p>
Ethan Young: Motor Actuator
</p>
Moksh Goel: Tempurature Sensor
</p>

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/41125720-531c-42b5-95a9-c4d859ac19be)

# [Component Selection](./ComponentSelection.md)

## Motor
FIT0492-B


$11.90

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/6c857586-6925-407b-90ce-849e6142946f)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Datasheet     | More expensive than alternative options      |
| High Torque                   |  |
| 12V           |                    |
| Decent Supply from Digikey        |                            |
| High quality and performance         


Rationale:
This motor was selected primarily for its higher torque output. It is one of the more expensive options and requires a separate 12V power rail, however, the torque was of higher priority.

## Motor Driver
IFX9201SGAUMA1


$4.00

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/b26c9aee-ac05-4806-9a77-5eb1991cbf39)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Higher current output of 6A per channel     | More expensive than alternative options      |
| Optimal temperature range                   |  |
| Includes Datasheet           |                    |
| Higher Supply Voltage        |                            |

Rationale:
This motor driver was selected for its compatibility with the chosen motor. It is also more expensive than other options found, but the compatibility was of greater importance.

## Switching Voltage Regulator
LM25085QMYX/NOPB

$2.38

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/d99d0ba9-f987-4c8d-868b-a6baa99783b1)


| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Includes Datasheet     | Support circuitry required      |
| Adjustable output voltage                   | Multiple resistors, capacitors, and inductors |
|  Typical application circuit to follow         |                    |
| Supply voltage between 4.5V and 42V        |                            |

Rationale:
This voltage regulator was selected due to the supporting circuitry for a typical application being relatively simpler than the other options. Adjusting the circuitry to output 3.3V also appeared straightforward, with multiple equations provided and all of the components required available as surface mount options.

## Light Sensor
SENSOR OPT AMBIENT 4CHIPLED


$1.20

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/06b560dd-659e-45a5-ab1b-9158c3f684cf)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| 2.4V-3.6V    | Weight not included     |
| Inexpensive                   |  |
| Wide Temperature Range        |                    |
| Includes Datasheet       |                            |

Rationale: 
This sensor was selected due to its smaller number of pins for an easier soldering experience, the communication via I2C, and the wide operating temperature range. It was also less expensive than other options.

## Heat Sensor
ZTP-148SRC1


$1.97

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/4029b698-6089-4951-9b92-ad0cbe879ca1)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Cost Effective     | 4 pin output      |
| Includes Datasheet                  | Non surface mount |
| Analog Output          |                    |
| Working Temperature -20°C ~ 100°C        |                            |
| Long distance         

Rationale:
This heat sensor was selected for its range of operating temperatures and ability to detect changes in heat at longer distances. This would assist in getting a better direction when detecting a fire.

## Battery
EN22


$2.61

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/70c055f0-398e-4db0-9058-c90d0bd07800)

| Pros                                           | Cons                                             |
|------------------------------------------------|--------------------------------------------------|
| Includes Datasheet    | Non rechargeable     |
| 9V                   |  |
| Inexpensive        |                    |

Rationale:
This battery was selected with the input voltage requirements for the voltage regulator in mind. It can provide an appropriate voltage level for the regulator to step down to 3.3V.

# [Microcontroller Selection](./MicrocontrollerSelection.md)
For the choice of microcontrollers, the team identified three potential candidates: the PIC18F14Q40, the PIC16F18855, and the PIC24FJ32GP202. Then the chips were compared to each other to see which would be the best option based on the project requirements, primarily power requirements, number of SPI, I2C, and UART pins, and overall number of pins. With these criteria, the PIC24FJ32GP202 chip was selected. 

|                                  | PIC Option 1 | PIC Option 2 | PIC Option 3 |
|----------------------------------|--------------|--------------|--------------|
| Part Number                      | PIC18F14Q40  | PIC16F18855  | PIC24FJ32GP202 |
| Production Unit Cost             | $1.23        | $1.56        | $1.29        |
| Supply Voltage Range             | 1.8V-5.5V    | 1.8V-5.5V    | 2.0V-3.6V    |
| Absolute Maximum Current for entire IC | 350mA  | 250 mA       | 150 mA       |
| Maximum GPIO Pin Current (Source/Sink) | +/- 50mA | +/- 50 mA | +/-18 mA |
| 8-bit or 16-bit Architecture    | 8-bit        | 8-bit        | 16-bit       |
| Available IC Packages / Footprints | 20-Pin PDIP, 20-Pin SOIC, 20-Pin SSOP | 28-pin (S)PDIP, SOIC, SSOP, QFN (6x6), UQFN(4x4) | 28-Pin QFN, UQFN 28-Pin SOIC, SSOP, 36-Pin UQFN, 48-Pin UQFN, TQFP |
| Supports External Interrupts?   | Yes          | Yes          | Yes          |
| In-System Programming Capability and Type | No     | Yes, Serial | Yes, Serial |
| Works with MPLAB® X Integrated Development Environment (IDE)? | Yes | Yes | Yes |
| Works with Microchip Code Configurator? | Yes | Yes (?) | Yes |

|                           | PIC Option 1 | PIC Option 2 | PIC Option 3 |
|---------------------------|--------------|--------------|--------------|
| How many GPIO Pins?       | 6+           | 18           | 25           |
| Built-in ADC? How many?   | 1+           | 1            | 24           |
| Built-in Hardware PWM?    | 1+           | 3            | 2            |
| Built-in I2C? SPI? How many? | 1+SPI, 1+I2C | 2 SPI, 1 I2C | 2 SPI, 2 I2C |
| Built-in UART? How many?  | 2+UART       | 3 USART      | 0 UART, 1 USART (?) |
#### Overall Pros

1. PIC Option 1: 3UART, Multiple PWMs
2. PIC Option 2: Multiple ADCs, 2 SPI and 2 I2C, 2 PWM, A lot of options for pins
3. PIC Option 3: Multiple ADCs, 2 SPI and 2 I2C, 5 PWM, A lot of options for pins

#### Overall Cons

1. PIC Option 1: Few ADCs, Less I2C
2. PIC Option 2: More pins to solder, Expensive dev board, A lot of options for pins
3. PIC Option 3: More pins to solder, Expensive dev board, A lot of options for pins

#### Ranking

1. PIC Option 3
2. PIC Option 1
3. PIC Option 2

### Final Microcontroller Choice: PIC24FJ32GP202

# [Hardware Proposal](./HardwareProposal.md)
With the selected microcontroller and components, the team put together a wiring schematic for each subsystem, taking into account any supplementary circuitry needed. The microcontroller required a switching voltage regulator that could take a 9V source and output a regulated 3.3V. This would also supply power to the subsystems. With the light and heat sensors, the team believes that is enough to determine the location of a simulated fire, as well as the motor being capable of rotating a simple actuator to aim a fire extinguisher towards that fire. The following image is the current circuit schematic of each subsystem.

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/c47b7918-99d1-4399-a098-f9fec08382e0)


# [Software Proposal](./SoftwareProposal.md)
The flow through the software code needed to be developed once the components were selected. To do this, the team identified the different coding requirements for the sensors and the microcontroller. The sensors require I2C for communicating with the microcontroller, and the motor driver requires SPI. When the system powers on, the system needs to initialize with the appropriate setup for the two different types of serial communication. Once the communication methods have been initialized, the sensors will be enabled, then the motor, and then the ESP32 module. At this point, the system will start reading the output of the sensors while comparing those outputs to baseline values in order to determine if the prototype is facing a fire or not. If the sensor values are determined to indicate a fire, the system state will be changed, and the motor will be told to move whilst still reading the sensor outputs. Once the greatest value output by the sensors has been reached, the motor will be told to stop. If the sensors continue to indicate a fire, the motor will stay at that position; if the sensors indicate the fire has been extinguished, the motor will move back to its origin position and the state of the system will be changed back to monitoring for a fire. Each time there is a system state change, the system will output an update via the ESP32 module. The following figures represent the logic flow of the system:

## Main Control Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/e8977080-a0ea-4625-8662-15950e93150b)

## Initialize System Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/3c740c02-d770-4db7-ab2a-244abe82b3cd)

## Refresh Display Loop
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/33398161-3451-4edb-936a-da8b52467630)

## Temperature Sensor
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/044100e1-f5a2-42b4-85fa-c809a926ba0c)

## Light Sensor
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/2b5f275a-1eef-4787-a6f6-808dd52d7363)

## Motor System
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/14ac5112-8339-4841-be09-6d4fa16d9104)


# Appendix A: Team Organization Charter

## Communication Channels

**Table 1: Team Member Communication Modes**

| Name | First Choice Communication    |  Second Choice Communication  | Third Choice Communication  |
|------|-------------------------------|-------------------------------|-----------------------------|
| Andrew | Discord | Text | Email |
| Moksh  | Discord | Text | Email |
| Ethan  | Discord | Text | Email |
|Nathan  | Discord | Text | Email |

## Communication Procedures
We have a discord server set up for daily communication. If there isn't a response or we need a rapid response we would text or call them. If they are completely unresponsive we would email them as a last resort before bringing it to the professor.

## Meeting Schedule
When possible, class time will be used as the primary weekly meetings. Subsequent meetings and their modality will be determined by necessity, however, the following times have been identified as when the majority of team members will be available:
- Tuesday - 1 pm-6 pm
- Wednesday - 2 pm-5 pm
- Thursday - 2 pm-6 pm
  
## Meeting Coordination
- We will discuss during class whether or not we need to meet in person or through Discord for the week. 
- If we need to edit the meeting hours, we will reference the meeting schedule highlighted above and make necessary adjustments.
- The preferred format of meetings is virtual, but when necessary, we will meet in the Peralta lab in person.
  
## Roles and Responsibilities

| Role                   | Duties                                                                                   |
|------------------------|-----------------------------------------------------------------------------------------|
| Meeting leader - Ethan Young | Schedules team meetings, runs each meeting, turns in assignments                          |
| Meeting recorder - Andrew Headley | Takes minutes of each team meeting, including attendance, and records action items and to whom they are assigned |
| Assignment leader - Moksh Goel | Coordinates the team’s work on a given assignment to Canvas before the due date           |
| Project monitor - Nathan Vairora | Tracks the team’s progress relative to the project schedule (Gantt chart) and keeps team members apprised of deadlines and project status |

## Specifications:
- Roles will change every three assignments
- Roles will rotate in order, beginning with each member choosing their role
- If a team member is falling behind in their responsibilities, provided other members are up to date on their work, they can help out the team member who is struggling
- If the three other team members feel one person isn't a good fit for a role, they can let the person know and the team member can be assigned a different role.
- Team activities and milestones will be tracked via Canvas submissions and in-person progress checkpoints
- Team members will be assigned technical responsibilities based on their talents and comfortability in different fields
  
## Team Coordination & Accountability
- In team meetings, the leader will talk about upcoming deadlines, and we'll figure out when and how to finish each task.
Once three team members agree, an assignment is good to submit.
- If someone gets feedback on a design, they can share it on Discord. Then, we can all talk about what to do next.
- If a team member isn't doing well, we'll help them with extra meetings and study sessions.
- If someone stops trying, we might have to issue a pink slip.
  
## Team 307 Signatures

Ethan Young


Nathan Vairora


Moksh Goel


Andrew Headley

# Appendix B: Bill of Materials
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/101139470/94e54736-0637-490f-be47-feb6c223853f)

# Appendix C: Power Budget
![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/9287dce2-0f18-4053-837f-ed472c647bbe)

![image](https://github.com/EGR-314-Team-307/EGR-314-Team-307/assets/156955314/00c3ac5a-e286-4a0f-92c1-867ce1242d73)

