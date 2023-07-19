Recon Script

This is a simple bash script designed to automate a basic reconnaissance workflow. It includes tasks such as harvesting subdomains, probing for alive domains, checking for possible subdomain takeovers, scanning for open ports, scraping wayback data, and more.
Prerequisites

The script uses the following tools:

    assetfinder
    httprobe
    subjack
    nmap
    waybackurls

These tools must be installed and correctly configured on your system for the script to work.
Usage

bash

./recon.sh [url]

Replace [url] with the target URL. The script will create a directory structure under the URL name, in which it will save all output and logs.
Directory Structure

The script will create the following directory structure:
[URL]
└── recon
    ├── httprobe
    ├── scans
    ├── potential_takeovers
    └── wayback
        ├── params
        └── extensions

Contribution

If you wish to contribute to developing this script, feel free to create a pull request. Any and all contributions are welcome.
Disclaimer

This script is meant for educational and ethical use only. Do not use it for illegal activities. The author does not accept any responsibility for any misuse of this script.
License

This project is licensed under the terms of the MIT license. See the LICENSE file for details.
