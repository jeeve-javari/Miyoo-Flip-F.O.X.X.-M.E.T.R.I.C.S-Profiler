# Miyoo Flip Hardware Profiler

A lightweight hardware profiling script designed for the Miyoo Flip console to monitor CPU, GPU, RAM, and power metrics in real time. This tool is useful for performance analysis, debugging, and optimizing your handheld experience.

---

## Features

- **Real-time Monitoring**: Tracks CPU frequency, GPU load, RAM usage, and battery metrics.
- **Comprehensive Logs**: Automatically generates logs with timestamps.
- **Customizable**: Adjust parameters like log location and rotation size.
- **Minimal Impact**: Designed to run in the background with minimal resource usage.

---

## Prerequisites

1. A Miyoo Flip console.
2. Access to an SD card reader for transferring files.
3. Basic knowledge of handling Linux-based systems.

---

## Installation

### Step 1: Transfer the Script

1. Download the script from this repository:
   - [Download hardware_profiler.sh](./hardware_profiler.sh)
2. Insert your Miyoo Flip’s SD card into your PC. Alternatively, use USB Mass Storage mode to access the SD card.
3. Copy the `hardware_profiler.sh` script to the following location:
   - **Path**: `/mnt/sdcard/app/miyoo355/`

---

### Step 2: Make the Script Executable

1. Insert the SD card back into the Miyoo Flip.
2. Connect the Miyoo Flip to your PC using **USB Mass Storage** mode.
3. Navigate to the script and press A. You'll get two options in chinese. The first one is to view the file, and the second one is to execute it.
	Choose the second one.
4. The Miyoo will kick you out of the file commander app and the profiler will be running in the background. Whenever you want to view the logfile,
	just navigate back to /mnt/sdcard/app/miyoo355/` and it will be inside the `/profiler_logs` folder. 
---

## Troubleshooting

### Common Issues

1. No logs are generated:
	-Ensure the script is executable.
	-Check that the log directory exists and has write permissions.
2. Metrics are missing or inaccurate:
	-Verify the profiler paths inside the script.
	-Ensure the correct firmware is installed.
3. No Tracking currently for SOC metrics
   -The script is not equipped to track SOC runtime metrics.
   - The correct filepath is still unknown.
  
## Contribution

Contributions are welcome! If you'd like to improve the profiler, feel free to open issues or submit pull requests. 
You can also submit your logs and other info here: https://forms.gle/mZ7Qt2mQwEqiZqoz6 I'll do my best to analyze the data and come up with a sort of community performance profile on the device. 
## License

This project is licensed under the MIT License. See the LICENSE file for more details.
 ## Contact
 
 For questions or suggestions, reach out via GitHub issues or connect with me on my YouTube channel: The Silicon Foxx.

