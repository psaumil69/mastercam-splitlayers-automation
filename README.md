# Mastercam Z‑Layer Automation (NET‑Hook)

A streamlined Mastercam NET‑Hook that automatically applies Z‑offsets to selected geometry layers.  
Designed to eliminate repetitive CAM work and produce fast, consistent results.

---

## Article & Background

This project is based on a workflow described in my Medium article:  
https://medium.com/@ps29/automating-z-level-layer-offsets-in-mastercam-a-net-hook-method-that-saved-hours-of-repetitive-wor-b5f3bea5a3ba

The article explains the motivation, the problem solved, and the practical benefits of automating Z‑level layer offsets in Mastercam.

---

## Latest Release  
Download the compiled tool here:  
https://github.com/psaumil69/mastercam-splitlayers-automation/releases/latest

Includes:

• SplitLayers.dll (NET‑Hook)  
• SplitLayers.ft (function table)  
• TestFile.mcam (optional sample)

---

## Installation  
This NET-Hook Add-In works on Mastercam 2022+ 
1. Download DLL + FT from the release  
2. Copy both files into your Mastercam folder: C:\Program Files\Mastercam 202X\chooks\
3. Restart Mastercam  
4. Launch the hook from:  
   Add‑Ins → NET‑Hook menu

More details in docs/install.md

---

## Usage Overview  
1. Open a Mastercam file  
2. Run the SplitLayers NET‑Hook  
3. Select target layers  
4. Enter Z‑offset  
5. Apply → verify → done

More info in docs/overview.md

---

## Features  
• Automates Z‑layer offsets  
• Eliminates repetitive manual edits  
• Reduces human error  
• Configuration‑friendly  
• Lightweight, fast, no setup needed  
• No source code required — compiled DLL only

---

## Documentation  
• docs/overview.md  
• docs/install.md  

---

## License & Legal  
• Documentation: MIT License (LICENSE)  
• DLL: Covered by EULA (EULA.md)  
• Not affiliated with CNC Software, LLC  
• Mastercam® is a registered trademark of CNC Software, LLC

---

## Support
If this tool helps your workflow, consider starring the repo!  
If you run into issues or have feature suggestions, feel free to open an Issue on GitHub.
