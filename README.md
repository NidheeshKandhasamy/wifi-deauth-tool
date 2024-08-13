# Wi-Fi Deauthentication Tool

This Bash script provides a set of functionalities for managing Wi-Fi networks, including scanning, selecting networks, and deauthenticating clients. It is designed for educational and legitimate penetration testing purposes.

## Features

- **Scan for Wi-Fi Networks**: Scan and list available Wi-Fi networks.
- **Select a Wi-Fi Network**: Monitor a specific Wi-Fi network by its BSSID and channel.
- **Deauthenticate a Client**: Send deauthentication packets to a specific client on a network.
- **Deauthenticate All Clients**: Send deauthentication packets to all clients on a network.
- **Check Wi-Fi Adapter Status**: Display the status of the Wi-Fi adapter.
- **Change Wi-Fi Adapter Interface Name**: Change the name of the Wi-Fi adapter interface.

## Disclaimer

1. This tool is provided for educational purposes only. It should not be used for illegal activities.
2. Only use it for legitimate penetration testing and security research purposes and on network devices that you own or have permission to test.
3. By using this tool, you agree that you will not engage in any unauthorized or illegal activities.
4. The author is not responsible for any damages or liabilities caused by the use or misuse of this tool.
5. Use this tool at your own risk and ensure compliance with applicable laws and obtain necessary permissions.

## Requirements

- **Aircrack-ng Suite**: Includes `airodump-ng`, `aireplay-ng`, and other tools.
- **iwconfig**: For checking Wi-Fi adapter status.
- **Bash**: The script is intended to be run in a Unix-like environment with Bash.

## Setup and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/NidheeshKandhasamy/wifi-deauth-tool.git

## Script Overview
display_menu()
Displays the main menu with options for the user.

scan_wifi()
Scans for available Wi-Fi networks using airodump-ng.

select_wifi()
Allows the user to select a specific Wi-Fi network for monitoring.

deauth_client()
Sends deauthentication packets to a specified client.

deauth_all_clients()
Sends deauthentication packets to all clients on a specified network.

check_wifi()
Displays the status of the Wi-Fi adapter.

change_interface()
Allows changing the Wi-Fi adapter interface name.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
Specify the license under which the project is distributed.
