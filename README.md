
# darkboss1bd-pdf-payload-injection-tool

This tool automates the process of modifying a PDF to inject a custom JavaScript payload for testing purposes. It is designed to assist penetration testers in crafting proof-of-concept exploits for scenarios involving darkboss1bd-pdf-payload-injection-tool payloads embedded in PDF files.


## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/darkboss1bd/darkboss1bd-pdf-payload-injection-tool.git
   cd darkboss1bd-pdf-payload-injection-tool
   ```

2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure `qpdf` is installed on your system:
   ```bash
   sudo apt install qpdf
   ```

---

## Usage

1. Run the tool:
   ```bash
   python3 darkboss1bd-pdf-payload-injection-tool.py
   ```

2. Enter your custom JavaScript payload when prompted:
   ```plaintext
   Enter your JavaScript payload (e.g., injection: which would reflect alert('injection');
   ```

3. Upon success, the modified PDF will be saved in the current directory:
   ```plaintext
   Success! Your modified PDF is saved as: final-officefile.pdf
   ```

---

## Requirements

- Python 3.x
- `qpdf` (command-line tool)
- Python libraries:
  - `requests`
  - `termcolor`

Install missing libraries using:
```bash
pip install requests termcolor
```

---

## Disclaimer

This tool is intended for educational and authorized penetration testing purposes only. The creator assumes no responsibility for any misuse or damage caused by this tool.

---

## Contributing

Feel free to fork this repository and submit pull requests for improvements or additional features.

---

## License

All rights preserved for my Gf. 
