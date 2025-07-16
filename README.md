# Arduino Micro Sui SDK

A lightweight Arduino library for interacting with the Sui blockchain.

## Appreciation

This Arduino package is based on the excellent work of the original Micro Sui SDK creators. We extend our gratitude to the original development team for their foundational work that made this Arduino adaptation possible.

**Original Repository**: https://github.com/MicroSui/microsui-lib
**Documentation**: https://docs.microsui.com/docs/getting-started

## Installation

### Method 1: Arduino Library Manager (Recommended)

1. Open Arduino IDE
2. Go to **Sketch** → **Include Library** → **Manage Libraries**
3. Search for "Micro Sui SDK"
4. Click **Install**

### Method 2: Manual Installation

1. Download the latest release from the [releases page](https://github.com/Emmybrown775/microsui-arduino/releases)
2. Extract the ZIP file
3. Copy the extracted folder to your Arduino libraries directory:
   - **Windows**: `Documents\Arduino\libraries\`
   - **macOS**: `~/Documents/Arduino/libraries/`
   - **Linux**: `~/Arduino/libraries/`
4. Restart Arduino IDE

### Method 3: Git Clone

```bash
cd ~/Documents/Arduino/libraries/
git clone https://github.com/Emmybrown775/microsui-arduino.git
```

## Usage

Include the library in your Arduino sketch:

```cpp
extern "C" {
 #include <MicroSui.h>
}
```
