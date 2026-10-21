# 3D Printed Enclosure: Custom 12 Key OLED Stream Deck 

This directory contains the CAD file for a case for custom 12-key PCB with an integrated medium sized OLED display. 

The entire enclosure was modeled in Onshape

---

## Case
<img width="1778" height="948" alt="image" src="https://github.com/user-attachments/assets/6aa021e0-eab5-4976-9e79-4c29d9eff31f" />
<img width="1681" height="825" alt="image" src="https://github.com/user-attachments/assets/5a48203e-75de-4db6-b1b7-743177d09b1f" />

###  The Lid
I started with the custom PCB and made sure the lid would fit, each key is left 14mm x 14 mm space
*   **Key Switch Tolerances:** The 12 key cutouts were modeled to fit standard mechanical switches
*   **OLED Screen:** The medium sized OLED screen has a place to be mounted
*   Modeled to sit flush with the PCB layout

### The Body 
Once the lid is done I made the body
*  I referenced part of a body for another CAD I made a while ago, so it was not difficult for me know know the wall thickness and general shape relatively. (Sorry I wasn't clear in my first version of this README, I did not borrow the body dimensions from that design it was the specific dimensions to fit my desk)
*  The main body fits with the lid


### Form Factor
The case is designed to fit on my desk
*   The height fits between the space between the bottom of my monitor and the desk surface. 
*   The front of the case is tilted so it is easier to click the keys and see the OLED screen


  **I would recommend using PLA for 3D printing, print both pieces with their widest, flattest external faces flat against the build plate and support is not needed** 


## Printing Instructions

1. Get the STL files for each part
2. Open in your slicer 
3. Orient each piece with its widest flattest face down on the build 
   plate
4. No supports needed
5. Recommended settings:
   - Material: PLA
   - Layer height: 0.2mm
   - Infill: 15-20%
   - Wall count: 3

## Assembly

1. Print both the lid and body
2. Insert mechanical switches into the 12 cutouts on the lid 
3. Mount the OLED screen into its cutout
4. Place the PCB into the body
5. Connect the switches and screen to the PCB
6. Put the lid onto the body

## Files

| File | Description |
|------|-------------|
| `lid.step` | Top piece with key and screen cutouts |
| `body.step` | Bottom piece that holds the PCB |
