# LEE-TOOLS 💥⚡ (Network Stresser)

Một Tool DDoS cơ bản, được mình nghiên cứu từ rất lâu rồi. Tuy không còn tác dụng với các Server Minecraft hiện nay, nhưng nó cũng là một phần kỷ niệm và ký ức trong suốt quá trình tiếp cận tựa game Minecraft 🎤✨

## Features 🎉

- 📡 **Attack Methods:**:

 - **LAYER 7**
  - `cfb` - Bypass Cloudflare Attack
  - `pxcfb` - Bypass Cloudflare Attack With Proxy
  - `cfreq` - Bypass Cloudflare UAM, CAPTCHA, BFM (request)
  - `cfsoc` - Bypass Cloudflare UAM, CAPTCHA, BFM (socket)
  - `pxsky` - Bypass Google Project Shield, Vshield, DDoS Guard Free, CF NoSec With Proxy
  - `sky` - Sky method without proxy
  - `http2` - HTTP 2.0 Request Attack
  - `pxhttp2` - HTTP 2.0 Request Attack With Proxy
  - `get` - Get Request Attack
  - `post` - Post Request Attack
  - `head` - Head Request Attack
  - `pps` - Only GET / HTTP/1.1
  - `spoof` - HTTP Spoof Socket Attack
  - `pxspoof` - HTTP Spoof Socket Attack With Proxy
  - `soc` - Socket Attack
  - `pxraw` - Proxy Request Attack 
  - `pxsoc` - Proxy Socket Attack

 - **LAYER 4**
  - `udp` - UDP Attack
  - `tcp` - TCP Attack

 - **TOOLS**
  - `geoip` - Geo IP Address Lookup
  - `dns` - Classic DNS Lookup
  - `subnet` - Subnet IP Address Lookup

## Setup 🛠️

### Prerequisites 📦

Make sure you have the following installed:

- install python.org
- install python3 from Microsoft Store

### Development Mode 🔧

1. Install the required dependencies:

   ```setup.py
   open file setup.py 
   ```
   ```pip
   press 0 to do the install on pip 
   ```
   ```pip3
   press 1 to do the install on pip3
   ```

   ```install setuptools
   python -m pip install setuptools
   ```

2. Run the tool in development mode:

   ```bash
   - cd (tools directory)
   - python main.py
   ```

---

## Usage ⚙️

Once the server is up and running, you can interact with it via the frontend:

1. **Start Attack**:
   - Set up the attack parameters: target URL,IPADDRESS, attack method (HTTP Flood, SOC, TCP, etc...), packet size, duration, and delay.

2. **Stop Attack**:
   - When the time is set, the attack in progress will automatically end.
   - If you want to make an emergency stop, press Ctrl + Z

### Example Request

layer7 > cfb
```json
{
  "URL": "http://example.com",
  "THREAD": "90000",
  "TIME": 120,
}
```

## Adding Proxy

Go to the ``proxy.txt`` file and add the proxy ip you have.

## Contributing 💖

Feel free, this source is completely free, your only contribution is to share interesting ideas and I will try to develop them! 😄

---


## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Disclaimer 🚨

Please note that this project is for educational purposes only and should not be used for malicious purposes.

---

### (｡♥‿♥｡) Happy Hacking 💖🎶
