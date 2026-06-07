# STRYFE - 3D Printed 5" Optimized Topology FPV Drone

A fully 3D-printable 5" FPV freestyle drone frame, designed in Fusion 360 using generative/topology optimization tools to maximize strength while minimizing weight. I Built to fit on smaller 3D printers. It is printable on printers 120mm+ by 120mm+! I printed it on my BambuLabs A1 mini. This is my first drone build, so I'd really appreciate any feedback on printables. 

> Inspired by [ProgrammaDan's Dragonfly FPV Drone](https://github.com/ProgrammaDan/dragonfly-fpv)

![STRYFE Drone](https://media.printables.com/media/prints/9b428b4d-6d27-4a04-9593-dd2b8c355b26/images/13094430_08ceb360-3932-4702-aa62-4419b648f1d7_38318fb2-0a32-4e03-b4ae-40f70655bf1a/thumbs/cover/1200x630/jpg/img_4558.jpg)

## Test Flight

**[Watch it fly on YouTube](https://youtube.com/shorts/oiSVrfM4jPY?si=SMwh-cmVWzysh2-i)**

## Features

- Designed with Fusion 360's Generative Design tools for an optimized topology frame. It's supposed to be stronger, but I mainly just like how cool it looks. 
- Splits into parts that fit on smaller 3D printers (no large bed required)
- Integrated prop guards and landing gear
- Camera mount
- Velcro battery strap routing built into the frame
- Compatible with standard 30.5×30.5mm FC/ESC stacks
- Clean wire routing channels through each arm

## Bill of Materials

| Part | Link |
|------|------|
| FC/ESC Stack | [SoloGood F405 55A (ICM42688P, 30.5×30.5mm, 2–6S)](https://www.amazon.com/dp/B0CWNPZZXV) |
| Motors | [MAD BSC 2207.5 2100KV (N52H, 6S compatible)](https://www.amazon.com/dp/B0FMRCY18R) |
| Props | [HQProp 5X4.8X3 V1S 5048 3-Blade (4× CW / 4× CCW)](https://www.amazon.com/dp/B0CTY3V3GD) |
| Battery | [OVONIC 14.8V 120C 1500mAh 4S LiPo w/ XT60 (2-pack)](https://www.amazon.com/dp/B09CTS2KY6) |
| ELRS Receiver | [Amazon](https://www.amazon.com/dp/B0FJFL51RV) |
| Charger | [ISDT PD60S 60W 6A XT60 Balance Charger](https://www.amazon.com/dp/B08F7C1T2T) |
| Camera/VTX | [AKK KC03 800TVL + 600mW VTX Combo](https://www.amazon.com/dp/B01N48QUIP) |
| Goggles | [Speedybee 5.8G 40CH FPV Goggles](https://www.amazon.com/dp/B0CDLPG247) |

**Hardware:** 12mm M3 screws (×24), M3 nuts (×4), 8mm M4 screws (×16), Velcro strip, double-sided tape or M2 screws and nuts

**Filament:** ~200g CF-PETG

## Print Settings

| Setting | Value |
|---------|-------|
| Material | CF-PETG (recommended) |
| Walls | 3 |
| Infill | 35% |
| Supports | Yes. It is required for prop guards and landing gear base |

## Build Instructions

1. **Bottom plate arms** attach the bottom plate to each arm using 8× M4 screws
2. **Camera mount** screw the camera into the camera mount using 2× M2 screws, then mount to the frame with 2× M3 screws
3. **FC stack** mount using 4× M3 screws with rubber grommets for vibration isolation
4. **Wire routing** thread motor wires through the channels in each arm
5. **Motors, prop guards, landing gear** screw into place
6. **Soldering** solder motors, VTX, ELRS receiver, power leads, and capacitor to the stack (cut leads to length as needed; refer to Amazon listing wiring diagrams)
7. **Battery strap** thread the Velcro strip through the two top slits
8. **Top plate** secure with 8× M4 screws and 2× M3 screws
9. **Betaflight setup** connect to Betaflight, verify motor order and spin direction, then configure rates, modes, and filters
10. **First flight** strap in your battery and fly!

## How It Works

The frame geometry was generated using Fusion 360's Generative Design feature, which runs stress simulations to find the most efficient material distribution for a given set of loads. Instead of designing the arms manually, I defined the mounting points, obstacle geometry, and expected force directions. I then let the the solver generate a design that is 3D printable. I ended up running around 10+ simulations because the solver would generate me branches that looked too thin to 3D print reliably. 

## Credits

- Inspired by [ProgrammaDan's Dragonfly FPV Drone](https://github.com/ProgrammaDan/dragonfly-fpv)
- Arms designed in Autodesk Fusion 360
- Frame designed in Onshape (the best CAD software)
