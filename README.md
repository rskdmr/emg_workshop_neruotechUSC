# Arduino EMG Code and Workshop from NeurotechUSC and USC IEEE
**This tutorial was taken from DroneBot Workshop's YouTube linked [here](https://www.youtube.com/watch?v=wMVL3d2dN9U&ab_channel=DroneBotWorkshop).**

Items Used:
1. Arduino Uno [link](https://www.amazon.com/ELEGOO-Board-ATmega328P-ATMEGA16U2-Compliant/dp/B01EWOE0UU/ref=asc_df_B01EWOE0UU/?tag=hyprod-20&linkCode=df0&hvadid=309751315916&hvpos=&hvnetw=g&hvrand=10817911768631456663&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9030933&hvtargid=pla-455309014075&psc=1&mcid=4ed5986a9fd03eba946a83adced9204e&tag=&ref=&adgrpid=67183599252&hvpone=&hvptwo=&hvadid=309751315916&hvpos=&hvnetw=g&hvrand=10817911768631456663&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9030933&hvtargid=pla-455309014075&gclid=CjwKCAiAqY6tBhAtEiwAHeRopa_ENvNNe7FMIbpYzbx08hMex9FLcPC1LhkiMIrP74lUQcIlZ3dCDxoCUCoQAvD_BwE)
2. Generic Muscle Electric Sensor Module [link](https://www.amazon.com/gp/product/B0CJ7FMSP4/ref=ppx_yo_dt_b_asin_image_o01_s00?ie=UTF8&psc=1)
3. Male to Female Jumper Wires
4. Red Dot Electrodes


### Set up:
1. Connect the Arduino to your laptop using the USB-A to USB-B cable. If required, use a USB-C to USB-A adapter.
2. Wire the EMG sensor to the Arduino GND and A0 pins. Use M-F jumper wires.
3. Connect the EMG sensor to the power supply via the breadboard. Use M-F jumper wires.
4. Connect the electrodes to the EMG sensor.
5. Start up the Arduino IDE and connect to the Arduino board.
6. Attach the electrodes to the muscle. One for ground and two to measure the potential difference.
7. Put your code in the IDE and upload it to the Arduino.
8. Open the serial monitor or serial plotter to visualize the sensor readings.


### Takeaways: 
1. Replicate the results multiple times.
  - It took us hours to figure out why the setup worked only sometimes and why we couldn't replicate the same results during the presentation
2. If you pay for cheap products, you'll get cheap results.
  - As students, we spent as little as possible on materials to save on club funds. As a result, the EMG module didn't work as best as it could, with some of the capacitors getting fried when hooked up to the DC power supply

### Further Experimentation/Ideas: 
- Use EMG to create a muscle-activated prosthetic using servo motors and 3D printing
- Muscle-controlled input for game input (e.g. Pong, Chrome No Internet Game, etc.)
- Muscle controlled cars

### Images:
**Electrode Placement**
![IMG_9848](https://github.com/rskdmr/emg_sketch_code/assets/120705369/198fa13d-a8c0-4d9d-b3fd-487859486df5)
![IMG_9847](https://github.com/rskdmr/emg_sketch_code/assets/120705369/c88e1206-2967-46d9-8327-b2211953aec1)

**Arduino Pin Placement**
![IMG_9846](https://github.com/rskdmr/emg_sketch_code/assets/120705369/5863f65f-265a-430f-86ba-5e0d59e63f94)
**EMG Module Pin Placement**
![IMG_9845](https://github.com/rskdmr/emg_sketch_code/assets/120705369/d3ee5a4c-de7e-491b-aaee-0713cef5fd67)
**Whole Scale Set Up**
![IMG_9844](https://github.com/rskdmr/emg_sketch_code/assets/120705369/a44a8f0a-7942-4be7-97e6-8b612c91e708)

**No Muscle Activity**
<img width="799" alt="Screenshot 2023-11-08 at 3 50 50 PM" src="https://github.com/rskdmr/emg_workshop_neruotechUSC/assets/120705369/3812ece9-17b4-4d79-8137-92cb8144b944">

**Muscle Spikes**
<img width="796" alt="Screenshot 2023-11-07 at 6 54 40 PM" src="https://github.com/rskdmr/emg_workshop_neruotechUSC/assets/120705369/adbfe563-8f79-465e-a0dc-4fa10e9a1387">



