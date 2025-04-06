HomeAssistant Pollen Monitor
============================

Overview
--------
This project integrates [ATMO](https://map.atmo-france.org/) pollen level data into Home Assistant. The data is retrieved from a remote API and parsed to display pollen levels from various trees and plants on a custom dashboard. The dashboard is built using a custom Mushroom card integration to visually represent pollen concentration levels.

Features
--------
- Retrieves pollen data every 6 hours from a specified API endpoint.
- Displays pollen levels for different types such as Aulne, Bouleau, Olivier, Graminées, Armoise, and Ambroisie.
- Uses custom templates for visual indicators based on pollen concentration.
- Custom card layout supports color-coded icons for intuitive monitoring.

Installation
------------
1. Clone the repository.
2. Copy the content of sensors-pollen-configuration.yaml into your configuration.yaml file.
3. Install the Mushroom integration from HACS.
4. Restart Home Assistant.
5. Navigate to your dashboard and add the sensors.
6. Create a Mushroom card and paste the content of mushroom-cards.yaml into the card's code.

Usage
-----
After installation, navigate to your Home Assistant dashboard to view the pollen levels for Paris. The sensors will update automatically based on the scan interval defined in the configuration. You can also change the API URL in the configuration if you wish to monitor pollen levels for a different location.
