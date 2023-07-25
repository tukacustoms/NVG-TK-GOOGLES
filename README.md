# NVG-TK-GOOGLES
This is a new product of 3d printed night vision googles for airsoft use!, afordable and functional parts

# NVG-TK-GOOGLES science behind them

for this project at first we need to know how to see in dark enviroments with technology, for human eye the wavelength is called visible spectrum wich is the range of wavelengths that human eye can sjee; wich is between 380 and 700 nanometers, for an common night vision googles the wavelenght used is infrared light wich has between 780nm and 1mm so that wavelenght human eye coudnt see.

to overcome the wavelenght problem, digital cameras cam pick up infrared light, but it has a catch, most of the digital cameras from the factory has an filter for infrared light, this filter are mean to increase the overal image quality, but in this project will have some solutions to make it dont be necessary to make any modifications to the digital camera

https://pt.aliexpress.com/item/1005004223144753.html?_t=pvid%3A9ecd82ac-5747-4eb7-bf66-0b2aad1abbbd&afTraceInfo=1005004223144753__pc__pcBridgePPC__xxxxxx__1690228233&spm=a2g0o.ppclist.product.mainProduct&gatewayAdapt=glo2bra

# hardware choisses 

# solution 1

at first the project have some features based on the https://www.youtube.com/watch?v=MthrbR4_UAk&t=500s project.

wich uses fpv high resolution on night time video cameras and uses them with an tft with adapter display, those displays are mean to reproduce in real time videos catched by the digital camera

https://www.adafruit.com/product/911

https://pt.aliexpress.com/item/32820081956.html?spm=a2g0o.productlist.main.7.79fa7a2eKG9bhZ&algo_pvid=ba2699eb-73fe-4e81-912d-6e965fe0a0f0&algo_exp_id=ba2699eb-73fe-4e81-912d-6e965fe0a0f0-3&pdp_npi=3%40dis%21BRL%21179.17%21129.0%21%21%2135.71%21%21%40210213b716902268491321269d077e%2110000007610455813%21sea%21BR%213124747279&curPageLogUid=0kWpS1jqqGdU#nav-review

unfortunaly they are quite expensive option still and a bit hard to find them.

problem of this project idea is that they arent using the main feature of the night vision googles, the infrared lighting, but still a functional product, because the fpv camera choosed can cait 0.01 lux lightening of the enviroment.
second problem is that the price of the fpv camera, the final product will be quite expensive by multiplying everything by 4.

# solution 2

after searching for a while, asking about a camera already without ir filter, found some options to use that they are already made for night vision wich makes the overal project with same functionality as intended

https://pt.aliexpress.com/item/1005005338137609.html?spm=a2g0o.productlist.main.15.7ae414631x433U&algo_pvid=4b931d3a-d59c-426e-8473-9e1e93f62575&aem_p4p_detail=202307241308272014997737209960001745738&algo_exp_id=4b931d3a-d59c-426e-8473-9e1e93f62575-7&pdp_npi=3%40dis%21BRL%21241.40%21156.91%21%21%21345.84%21%21%4021227bf916902293079494648d0bdf%2112000032662752561%21sea%21BR%213124747279&curPageLogUid=DhVBPfh4VJDW&search_p4p_id=202307241308272014997737209960001745738_8

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/6a0864f8-a852-4783-93d7-4e615a0da388)

this first option has the overal capabilities for ir sensitivity and use for the analog tft display of the project

uses 640*480/30fps
110mA-280mA current power usage
5v power supply
68 °,80 °,90 °,100 °, 120 °, 150 °, 170 ° lenses options

for this option has the great pcb format with mounting holes to use on the overal project
has a low distortion lenses to choose from wich is great for the project, since the ngv already has a panoramic functionality, using a wide and istorted lenses angle gonna afect the overal performance while using it 
the just 2 minor disaventages
the price, is the greater price of them all with almost same capabilities but still is a great option
doesnt come with led built in, but it has its good advantages too

# hardware studies

after further study and analysing options with different price ranges and documentations were found out 2 options that can be satisfied by using the IR sensitivity for the night vision theory

https://pt.aliexpress.com/item/1005005736297543.html?spm=a2g0o.store_pc_allProduct.8148356.72.492c7808lG1pfg&pdp_npi=3%40dis%21BRL%21R%24%20100%2C35%21R%24%20100%2C35%21%21%21%21%21%402103205216902294463534572e062d%2112000034161150747%21sh%21BR%213124747279

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/9ad65086-853d-4c71-a6b2-2bde5d9ec13b)


this first one has from 94 degree to 190 degree lenses of field of view, but in this project we gonna focus on  the 94 because we gonna have 4 digital cameras for the panoramic view of the NVG. another feature that this digital camera has is the hability to automaticly changes from day light to night and already hasj a built in 6 IR led to illuminate and help the overal view in the dark.

has module size 38mm by 38mm by 24.60mm
has fixed focus
need 5V supply wich is great and comes from the usb bus power
for this nvg the best image transfer to use is between 640 by 480 with 30 fps since the frame hate is extremely important for the airsoft use

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/e0ed5d04-c573-4402-bf00-17ff5b59f775)

and a plus is that on the pcb has some mounting holes that can be used to fix the digital camera in place, since the sizes are perfect for the use, this option is the main digital camera to use on the project

another option to use with ir sensitivity is the 

https://pt.aliexpress.com/item/1005005444124395.html?gatewayAdapt=glo2bra

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/475247b8-ee2b-405d-baff-d86463ab8024)

it is a smaller size and more budget price with 50 and 80 degree lenses, wich probably gonna use the 80 degree version, but for testing we could use 50 degree to see overal performance

has module size 25mm by 12mm by 6mm
fixed focus
works with 5V supply same as past examples
mas power usage is 500mW wich is great for longer periods of usage or smaller batteries
has 2 options to test for the overal resolution one is 640x480 30FPS wich isj great and another is 320x240 128FPS wich is another great option buut image quality is gonna be poorer for the high fps

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/c235ab53-5e9c-495f-804f-4b30c8b40370)

has just slight 2 desaventages but those can be solved easily
one is the overal pcb format, its rectangular and smaller size makes te hole mounts a bit treackier to work with, but in further studies gonna be modeled by metric documentation and be work with
and the second one is that wont came with ir led built in, wich is good and bad, bad because need to make a separated circuit to add them that would cause an slight bigger power usage, and good because can work out with ir led independetly making if greater in performance and more designs to use.

# tft displays

getting on addafruit site the price is a little bit expensive to work with, making usj to search for another solution to find a substitute for it, is more than the price, is for the overal availability of the tft display that has analog driversj built in
after a while wasj found them with great price range, wich can use 2 inches display to use with the lenses

https://pt.aliexpress.com/item/1005004380216204.html?gatewayAdapt=glo2bra

![image](https://github.com/tukacustoms/NVG-TK-GOOGLES/assets/115516996/9fb5a2c2-dcb2-4f11-a7bb-a4088f1f1489)


it works from range of 3v to 15v wich isj a great range to use including making it paralel to the digital cameras
uses 0,5w maximum power usage
and has 4:3 ratio
