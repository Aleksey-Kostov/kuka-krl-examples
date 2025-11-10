# KUKA KRL Examples

This repository contains KUKA Robot Language (KRL) files for a robot program that performs a **grab and drop** operation.  
The project is structured to keep the main program, configuration, and data files organized.

## Project Structure

kuka-krl-examples/
├── main.crc # Main program
├── grab_drop.dat # Grab & drop positions
├── config.dat # Robot/tool configuration

## Usage

1. Load all files to your KUKA controller or simulator.
2. Configure robot settings in `config.dat`.
3. Run `main.crc`.
4. Test in simulation first for safety.
