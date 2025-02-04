# CloudWorks

CloudWorks is a Windows application designed to adjust display settings to achieve optimal resolution and color accuracy. The application checks the current screen resolution and color depth, and makes adjustments to ensure the best possible display quality.

## Features

- Automatically detects current screen resolution and color depth.
- Adjusts resolution to 1920x1080 if the current setting is not optimal.
- Checks if the color depth is at least 32 bits (not fully implemented in this version).

## Prerequisites

- Windows operating system.
- Python 3.x installed on your system.

## Installation

1. Clone the repository to your local machine.
   ```bash
   git clone https://github.com/yourusername/cloudworks.git
   cd cloudworks
   ```

2. Make sure you have Python installed and added to your PATH.

## Usage

Run the application using the following command in your terminal or command prompt:

```bash
python cloudworks.py
```

Note: The application requires administrative privileges to change display settings. Make sure to run your terminal or command prompt with admin rights.

## Limitations

- The application currently only supports changing the resolution to 1920x1080.
- Changing color depth is not implemented in this version.
- Only supported on Windows operating systems.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Disclaimer

This software is provided "as-is" without any warranties. Use it at your own risk.