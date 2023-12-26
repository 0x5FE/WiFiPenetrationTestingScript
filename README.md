# Wi-FiPenetrationTesting

- Its purpose is to automate various tasks involved in testing the security of a Wi-Fi network and to be tested directly on windows without using virtualization or kalilinux.

      Attempts brute-force attacks on the target AP.
      Performs WEP key cracking using Aircrack-ng.
      Performs WPA/WPA2 key cracking using Aircrack-ng.
      exploit_vulns Function:
      Tests for vulnerabilities in the target AP.
      Executes a WPS attack using Reaver.
      Performs a WPA2 downgrade attack using Aircrack-ng.
      generate_report Function:
      Generates a penetration testing report.
      Uses Aircrack-ng to create a report based on the captured data.
  
  **- This script is for educational and testing purposes only. Unauthorized access to networks is illegal and unethical.**

# Prerequisites

 - ***Windows***
- ***Wireless Interface:*** Ensure that the appropriate wireless interface is specified in the script (default is wlan0). Replace it with the correct interface name.
  
- ***Target Access Point (AP):*** Specify the MAC address of the target AP in the target_ap variable.


# Usage

- Open the script in a text editor.
- Set the appropriate values for the interface and target_ap variables.
- Save the changes.
- Execute the script with elevated privileges ***(Run as Administrator).***

# Notes

- Ensure that the required Wi-Fi penetration testing tools ***(airodump-ng, aircrack-ng, reaver.exe)*** are installed and available in ***the system's PATH.***

- The script assumes the presence of a wordlist ***file named wordlist.txt*** for password cracking. Ensure it exists in the script's directory.

# Disclaimer

- The authors of this script are not responsible for any misuse, damage, or unauthorized access resulting from the use of this script. Use it responsibly and in compliance with applicable laws and regulations.
