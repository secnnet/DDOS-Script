# PyDDoS

PyDDoS is a Python-based tool for conducting Distributed Denial of Service (DDoS) attacks. It provides different attack methods such as SYN flood, HTTP request flood, and slowloris attack.

## Features

- SYN flood attack: Sends a high volume of TCP SYN packets to overwhelm the target system's resources.
- HTTP request flood: Sends a large number of HTTP requests to exhaust the target server's resources.
- Slowloris attack: Keeps multiple connections to the target server open with partial HTTP requests, preventing it from serving legitimate clients.

## Prerequisites

- Python 3.x
- Requests library (`pip install requests`)
- Colorama library (`pip install colorama`)
- Termcolor library (`pip install termcolor`)

## Usage

To launch an attack, run the `pyddos.py` script with the following command-line arguments:

python pyddos.py -d <target> -p <port> -T <threads> -Pyslow


Replace the `<target>`, `<port>`, and `<threads>` with the appropriate values for your attack. You can choose between the `-Pyslow`, `-Request`, or `-Synflood` options to select the attack type.

For more details on the available options, run the script with the `-h` or `--help` flag.

## Disclaimer

Please use this tool responsibly and with proper authorization. Conducting DDoS attacks without permission is illegal and unethical. The author of this tool is not responsible for any misuse or damage caused by using this tool.

## License

This project is licensed under the [MIT License](LICENSE).

## Contributions

Contributions to the project are welcome. If you encounter any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Contact

For any inquiries or feedback, please contact [your_email@example.com](mailto:your_email@example.com).

