
<div align="center">

<h1>Design Phase Locked Loop 100MHz Circuit With CMOS 130nm Technology (LTSPICE)</h1>
</div>

**Block diagram of PLL**


![image](https://github.com/trong420/pll/assets/90754954/d6bc4fe4-8550-4429-8803-8a4a6f729901)


**1. PFD - Phase Frequency Detector** 

- Schematic DFF

![image](https://github.com/trong420/pll/assets/90754954/4cab92ea-54e0-4a4b-a788-659aa8c1380c)

- Simulation DFF

![image](https://github.com/trong420/pll/assets/90754954/aa5d06ee-20c6-4984-bfff-ca14e96c1860)

- Schematic PFD

![image](https://github.com/trong420/pll/assets/90754954/9de4c38d-c68b-4ada-bd4a-7d01aaadfb8b)

- Simulation PFD with Input phase advance

![image](https://github.com/trong420/pll/assets/90754954/4bee8237-04b5-4306-99b8-96d96b9ab4a6)

- Simulation PFD with VCO phase advance

![image](https://github.com/trong420/pll/assets/90754954/f856c4c1-5539-4b8c-a54c-6f9ff100b962)

- Simulation PFD with the same phase

![image](https://github.com/trong420/pll/assets/90754954/6952c969-97d4-45d8-8493-34653f1f24e6)


**2. Charge Pump and Filter** 

- Schematic

![image](https://github.com/trong420/pll/assets/90754954/92ce12f3-da92-4350-8db8-ba7c45bc446c)


- Simulation

![image](https://github.com/trong420/pll/assets/90754954/38ec9d5f-af16-42c9-9f10-c09a54deb98a)


**3. VCO - Voltage Controlled Oscillator** 

- Schematic

![image](https://github.com/trong420/pll/assets/90754954/4fefe4a0-22a5-468e-b0bf-9600235f1e2c)


- Simulation

![image](https://github.com/trong420/pll/assets/90754954/fb03636e-8b7a-44ee-8044-6e16d186ba82)


**4. Frequency Divider** 

- Schematic

![image](https://github.com/trong420/pll/assets/90754954/d0098378-0c50-405b-9f0a-6da2dd8cb831)


- Simulation

![image](https://github.com/trong420/pll/assets/90754954/5d4f1f94-9300-407f-9d15-c6e34aa451ae)


**5. PLL - Simulation At 3.125 MHz** 

- Schematic


![image](https://github.com/trong420/pll/assets/90754954/112a515f-bc4c-4630-9d5e-bb72b78f739c)


- Simulation

![image](https://github.com/trong420/pll/assets/90754954/46754122-8377-44e2-b121-6d237ee6b796)

- After simulation, the PLL has achieved a stable frequency of 97 MHz


![image](https://github.com/trong420/pll/assets/90754954/e37c04e7-75d9-4b4c-8a1c-eb3f2651db43)



