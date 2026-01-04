
![Image Alt](https://github.com/AsadAhmad-1337/Whatsapp-call-ip-grabber/blob/f8fda739d687e0df83aad7d121f36488491f18b7/thumb.png)
# Whatsapp-call-ip-grabber
This script is a real-time WhatsApp STUN traffic analyzer that identifies the receiving end’s public IP during a call, performs geolocation, logs results to an HTML file with embedded maps and auto detects call start/stop.

# Requirements

# Operating System: 

  Windows 7/10/11

# Application:

  WhatsApp Desktop Application 

# External Tools:

  Wireshark installed with TShark CLI: make sure that your default path is C:\Program Files\Wireshark\tshark.exe.

# Network:

  Wi-Fi or Etherenet

# Features
  
# ✦︎ Live STUN Packet Monitoring:

Captures only STUN traffic on the specified interface (Wi-Fi by default).

Filters out private IPs and known Meta-owned IP ranges.

# ✦︎ Public IP Detection:

Focuses on the receiving party’s public IP.

Tracks timestamps to detect activity and inactivity.

# ✦︎ Call Start/Stop Detection:

Detects when the call starts based on first STUN packet.

Detects call end after configurable inactivity threshold (CALL_INACTIVITY_THRESHOLD seconds).

# ✦︎ Geolocation Lookup:

City, Country, ISP, Latitude, Longitude.

Excludes Meta/Facebook-owned ISPs info logging.

# ✦︎ HTML Logging:

Creates Whatsapp_ip_detection_report.html file.

Columns include Time, IP, ISP, Location, Map.

Interactive embedded Google Maps.

Clickable coordinates under the map for direct Google Maps link.

# ✦︎ Terminal Output:

Prints target candidate details in real-time.

Displays IP, ISP, location, coordinates.

Notifies of call start and call end.

# ✦︎ Robustness:

Terminates TShark subprocess and closes HTML table properly. 
  


