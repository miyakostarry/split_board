# split_board -44keys 

So this is my 44-key split keyboard project. It has two separate halves, with 22 keys on each side.

I'm designing the PCB in KiCad and still figuring out a few things, so some components might change later. This is basically where the project stands right now.

BATMAN STYLE 
<img width="931" height="477" alt="Screenshot 2026-11-09 101216" src="https://github.com/user-attachments/assets/3e6637f2-3ab5-44bd-bf0f-d4308245c08e" />

<img width="1087" height="691" alt="Screenshot 2026-11-09 101611" src="https://github.com/user-attachments/assets/c5086124-5a8b-4190-a01a-e77d9e7401d1" />


## Battery

I'm planning to use normal rechargeable 3.7V LiPo batteries.

Probably around 500–800mAh for each half, but I haven't finalized the capacity yet. It will also depend on how much space is available inside the case.

## Battery sensing

I might add battery-voltage sensing later using two resistors and an ADC pin on the XIAO.

This isn't necessary for the keyboard to work, so I'm not buying those components right now.

## Switches and footprints

Currently I'm using Kailh Choc V1 switches because I want to keep the keyboard low-profile.

BUT I might change the switches in the future depending on availability and price.

So the footprints aren't necessarily final. If I switch to something like Choc V2, Gateron Low Profile or regular MX switches, I'll need to update the footprints in KiCad and check that the new switches actually fit the PCB.

I also need to make sure the hot-swap sockets match the switches.

## A few things I still need to figure out

- Final key layout and keycap sizes
- Whether I'll add RGB lighting
- Final switch and socket choice

## Important note

This project is still a work in progress. I'm keeping this README updated as I make changes, so the parts listed here are my current plan, not necessarily the final components I'll order.

For now, the main goal is to get the circuit and PCB design working properly before manufacturing anything.
