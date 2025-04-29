# Compteur Binaire Hexa pour Blender 🎨💻

Welcome to the **Compteur Binaire Hexa pour Blender** repository! This project features a Python script designed for Blender, enabling procedural animation of a counter that translates decimal values into binary and hexadecimal formats. 

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview

The **Compteur Binaire Hexa pour Blender** project serves as a practical tool for artists and developers interested in animation and programming within Blender. This script provides a unique way to visualize numbers by translating decimal values into both binary and hexadecimal formats, making it an excellent resource for educational purposes or creative projects.

![Blender Animation](https://example.com/blender-animation.png)

## Features

- **Procedural Animation**: Create dynamic animations directly in Blender.
- **Decimal to Binary Conversion**: Easily convert decimal numbers to binary format.
- **Decimal to Hexadecimal Conversion**: Translate decimal numbers into hexadecimal format.
- **User-Friendly Interface**: Designed to be intuitive for both beginners and experienced users.
- **Customizable Parameters**: Adjust settings to fit your animation needs.

## Installation

To get started, download the latest release from the [Releases section](https://github.com/KhorYuanSiang12/Compteur-Binaire-Hexa-pour-Blender/releases). You will find a `.zip` file that contains the necessary scripts and resources. 

Once downloaded, follow these steps:

1. **Extract the Files**: Unzip the downloaded file to a directory of your choice.
2. **Open Blender**: Launch Blender on your computer.
3. **Load the Script**: Go to `Text Editor` in Blender, open the extracted Python script, and run it.
4. **Adjust Settings**: Customize the parameters as needed.

## Usage

Using the **Compteur Binaire Hexa pour Blender** is straightforward. Here’s a simple guide:

1. **Open the Script**: Load the Python script in Blender’s Text Editor.
2. **Set the Starting Value**: Define the starting decimal value for your counter.
3. **Run the Animation**: Execute the script to start the animation. You will see the counter transitioning through decimal, binary, and hexadecimal representations.

### Example Code

Here’s a snippet to illustrate how to set up the counter:

```python
import bpy

# Function to animate the counter
def animate_counter(start_value, end_value):
    for value in range(start_value, end_value + 1):
        binary_value = bin(value)[2:]  # Convert to binary
        hex_value = hex(value)[2:]      # Convert to hexadecimal
        # Update your Blender object here
        print(f'Decimal: {value}, Binary: {binary_value}, Hexadecimal: {hex_value}')

animate_counter(0, 255)
```

## Demo

For a visual demonstration of the counter in action, check out the video on [YouTube](https://www.youtube.com/your-demo-video). 

![Demo Video](https://img.youtube.com/vi/your-video-id/0.jpg)

## Contributing

We welcome contributions from the community! If you would like to help improve this project, please follow these steps:

1. **Fork the Repository**: Click the "Fork" button at the top right of this page.
2. **Create a Branch**: Use a descriptive name for your branch.
3. **Make Your Changes**: Implement your feature or fix a bug.
4. **Submit a Pull Request**: Provide a clear description of your changes.

Please ensure your code adheres to our coding standards and passes all tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, feel free to reach out:

- **Email**: your-email@example.com
- **GitHub**: [KhorYuanSiang12](https://github.com/KhorYuanSiang12)

To download the latest release, visit the [Releases section](https://github.com/KhorYuanSiang12/Compteur-Binaire-Hexa-pour-Blender/releases).

Thank you for your interest in the **Compteur Binaire Hexa pour Blender**! We hope you find this project useful and inspiring. Happy animating!