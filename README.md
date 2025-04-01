# LangSMS - Anonymous SMS Sender

LangSMS is an advanced SMS spoofing tool that allows you to send anonymous messages securely using VPN and Tor networks.

## Features

- 🔹 Send anonymous SMS messages
- 🔹 Supports VPN-based identity masking
- 🔹 Tor network integration for anonymity
- 🔹 Multi-number bulk SMS sending
- 🔹 Advanced error handling
- 🔹 Cool and modern terminal UI

## Installation

### Prerequisites

- Kali Linux or any Linux OS
- Python 3 installed
- OpenVPN (for VPN support)
- Tor (optional for additional anonymity)

### Clone the Repository

```sh
git clone https://github.com/renatochuck/langsms.git
cd langsms
```

### Install Dependencies

```sh
pip install -r requirements.txt
```

## Usage

### Send a Single SMS
```sh
python3 langsms.py
```
Then, follow the on-screen instructions to send an SMS.

### Send Multiple SMS (Requires VPN Configurations)
```sh
python3 langsms.py
```
Choose option 2 and enter the required details.

## VPN Integration
LangSMS supports ProtonVPN for increased security.
To use VPN, store your credentials in a text file and provide the path to your `.ovpn` configuration files.

## License

This project is for educational purposes only. The developer is not responsible for any misuse of this tool.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Contact

- GitHub: [LangSMS Repository](https://github.com/renatochuck/langsms)

