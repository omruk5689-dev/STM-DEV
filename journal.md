# Project Journal

| Project Name | Time Taken | Software Used |
|---|---|---|
| STM32-DEV | 4 hours | EasyEDA Pro |

## Entry: Schematic & PCB Design

**Hours 1–2: Schematic Design**
<img width="772" height="317" alt="Screenshot 2026-09-14 000835" src="https://github.com/user-attachments/assets/7c2cc38d-970d-49a1-921c-9f1658c43db4" />
<img width="715" height="356" alt="Screenshot 2026-09-14 000931" src="https://github.com/user-attachments/assets/e8de7277-4d91-4d86-94af-7e02739fec59" />
<img width="720" height="375" alt="Screenshot 2026-09-14 000944" src="https://github.com/user-attachments/assets/b6640ac7-9705-4c0a-85c2-0b67163d8dba" />

I've already put the schematic together from the start. The USB-C connector is placed first because this will be the entry point where power and data will enter the board. I connected it correctly with everything necessary like CC lines, VBUS and D+/D- lines to the MCU pins.

After that, I connected the MCU itself to everything. I inserted the STM32F103C8T6 microcontroller and started wiring it with the rest of the components present on the board – the power supply, the oscillator, the reset circuit, the boot selection pins and etc. After adding the MCU on the schematic, I added the part of the oscillator consisting of the main 8 MHz oscillator and the timing 32.768 kHz crystal with their load capacitors.

In two hours, I've managed to complete the most important part of the schematic.

**Hours 3–4: PCB Routing & Layout**
<img width="761" height="333" alt="Screenshot 2026-09-14 001028" src="https://github.com/user-attachments/assets/789090f8-2378-4e94-89c3-537c0f3f35f8" />

Switched over to the PCB side for the second half of the session. Placed all the components on the board and started routing traces using EasyEDA Pro's auto-router to get a clean, precise layout without spending hours doing it all by hand. Kept an eye on the routing as it went to make sure everything landed where it needed to, then went back through and tidied up any traces that needed a manual touch.

By the end of the four hours, the board had gone from a blank schematic to a fully placed and routed PCB layout — a solid stopping point for the day

.<img width="527" height="261" alt="Screenshot 2026-09-14 001014" src="https://github.com/user-attachments/assets/3b970176-2211-4190-90ed-111e812299b9" />
<img width="2160" height="845" alt="PCB_PCB1_2026-09-13" src="https://github.com/user-attachments/assets/8e7e58f0-aebe-4993-9235-f81b088e2817" />
