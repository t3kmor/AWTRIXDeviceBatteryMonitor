# AWTRIX 3 Device Battery Monitor 

This Home Assistant blueprint allows you to create a battery percentage display for your AWTRIX 3 (formerly AWTRIX Light) device. It leverages data available in Home Assistant to show the battery level of your phone or tablet. 

[AWTRIX Flows](https://flows.blueforcer.de/flow/XBJpOq0Zorzw)

## Features

+ **Compatibility**: This blueprint is designed to work seamlessly with AWTRIX 3.
+ **Dynamic Charging Icon**: The charging icon changes based on whether the device is charging or not.
+ **Customizable Text**: You can choose the text to display alongside the battery percentage.
+ **Scroll speed text**: You can choose the scroll speed of the displayed text.
+ **Battery Percentage Display**: Toggle the visibility of the battery percentage text.
+ **Color Customization**:
    - Choose the color of the progress bar based on the battery level.
    - Set the background color of the progress bar.

## Installation
### Import button
Import this blueprint to Home Assistant with "**Import blueprint**" button.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Ft3kmor%2FAWTRIXDeviceBatteryMonitor)

### Import from URL 

To install this blueprint in your Home Assistant instance, follow these steps:

1. Open your Home Assistant instance.
2. Navigate to the "Configuration" panel.
3. Click on "Blueprints".
4. Click on "Import Blueprint" and paste the URL to this GitHub repository.
5. Find the blueprint in the list of available blueprints and click "Install".
6. Configure the blueprint according to your preferences.
7. Click "Save".

### Import from file

1. Download the blueprint file.
2. In Home Assistant, navigate to **Configuration > Blueprints**.
3. Click on **Import Blueprint** and upload the downloaded blueprint file.
4. Create an automation using this blueprint and configure the necessary parameters.

## Usage

1. Create an automation using this blueprint.
2. Customize the blueprint parameters:
    - **AWTRIX Device**: Select your AWTRIX device.
    - **AWTRIX Application name**: Select an unique app name.
    - **Device**: Select your device.
    - **Text to display**: Enter the text you want to display.
    - **Show percentage**: Toggle the percentage of battery after text set above.
    - **Set progress bar color**: Set progress bar color by battery percentage.
    - **Background Color**: Pick the background color for the progress bar.
    - **Duration**: Set how long text is displayed
    - **Text Case**: Set the text case (uppercase, lowercase, or as entered).
    - **Icon Behavior**: Choose how the icon behaves.
3. Save your automation and voilà!

### Several devices
If you need to display the battery level of several devices, simply create an automation for each device using the blueprint.

## Screenshot
![51dcsqdqd1414656](https://github.com/t3kmor/AWTRIXDeviceBatteryMonitor/assets/121339563/fbadfb74-c04f-4c72-95ec-295ff065a6af)


## TODO
- [ ] Change text color
- [ ] Add option to make text rainbow-colored
- [ ] Change position of battery percentage relative to text
