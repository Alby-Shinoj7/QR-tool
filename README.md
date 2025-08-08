# QR-tool

## Req
- Python 3
- Packages: Flask, qrcode[pil]

Install it:
```bash
pip install Flask qrcode[pil]
```

##  how to run
1. Generate the QR code:
   ```bash
   python generate_qr.py
   ```
   This produces `qr_code.png`.
2. Start the Flask appli:
   ```bash
   python app.py
   ```
   The site is served at `http://127.0.0.1:5000/`.
3. Scan `qr_code.png` with a mobile device connected to the same machine. Adjust the URL in `generate_qr.py` to your network IP 

```if you want other devices on the network to access the simulation.```

## Disclaimer
This tool is for educational purposes only. It does not capture or transmit any real data.
