# custom-keyboard
Hi, I am building a custom keyboard for the HackClub Keeb project. Huge thanks to HackClub for giving me this opportunity to finally bring this idea to life.

For the past ~4 months, my laptop keyboard has had broken G and H keys. The replacement was very expensive, and typing on it became really frustrating. This project is my way of solving that problem while also learning PCB design and embedded systems.

Thanks again to HackClub for giving me a platform where I can express myself and build something useful instead of just dealing with a broken keyboard.

Design Overview

My design is fairly simple and practical.

I am using a Raspberry Pi Pico as the main controller.
The keyboard layout is based on Cool84.
I have also added support for an RGB LED strip, which I plan to connect later for lighting effects.
Keyboard Layout:
<img width="831" height="323" alt="image" src="https://github.com/user-attachments/assets/503acaf3-7bab-4445-9021-a472adb7a67f" />

PCB Design Process
1. Keyboard Matrix Design

First, I created the switch matrix for the keyboard.

<img width="975" height="545" alt="image" src="https://github.com/user-attachments/assets/7c7167b6-5809-4889-b82d-c6de0860a801" />

2. RGB Strip Connection

Then I designed the connections for the RGB LED strip.

<img width="975" height="413" alt="image" src="https://github.com/user-attachments/assets/081902cf-332e-4d42-a672-5c04b60d25ce" />
3. Full Pico Integration

After that, I connected everything to the Raspberry Pi Pico.

<img width="548" height="600" alt="image" src="https://github.com/user-attachments/assets/6cfe3836-293e-4113-bdc9-ef8c7036c58b" />

PCB Assembly (Most Challenging Part)

The hardest part of this project was assembling everything properly in the PCB editor.

In my first design, I made many mistakes:

Forgot to add mounting holes
Placed the Pico on the wrong side
Messed up multiple nets and connections

After a lot of trial and error, I finally managed to create a clean design with no major errors.

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/d4a5079f-1a97-4944-bf85-ddd8f62bf1ae" />
Final PCB

Here is the final PCB design:

<img width="1315" height="712" alt="image" src="https://github.com/user-attachments/assets/25b1020b-9f11-4b37-9dab-28ea5c39eb1c" />
Case Design

Next, I started working on the case. Compared to the PCB, this part was easier because the design is simple.

The case has:

Bottom plate
Side walls
Space for a clear top sheet (for aesthetics and protection)
<img width="1918" height="1078" alt="image" src="https://github.com/user-attachments/assets/9d75d974-e94b-4cb9-84d9-8640b6a23059" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/0c03263f-6f97-4121-800a-7ff114b571e7" />

Final Note

This project has been a big learning experience for me in PCB design, embedded systems, and hardware development. I made mistakes, fixed them, and learned a lot through the process.

Note on writing:
English is not my first language. I used ChatGPT only to improve the grammar and structure of this README. All ideas, design work, PCB development, and project decisions were done by me without AI assistance.
