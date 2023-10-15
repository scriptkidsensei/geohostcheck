# Geohostcheck
 
### Geohostcheck is a powerful host status checker with proxy support.
 
FREE and OPEN-SOURCE!
 
## Features 
 
- Check the status of hosts with different protocols.
 
- Use proxy servers for checking.
  
- Highly customizable with user agents.
 *Instant automatic user agent changes if proxy or request is banned
   
- Easy to use and robust.
  
- If you don't have a proxy list, geohc will automatically search and download it from the internet.
 


## Screenshots
 
![Header](https://github.com/scriptkidsensei/GeoHostCheck/assets/55909183/fea0a2eb-905e-4858-b2a7-17d3d8222ea1)
 
#### Protocol Choice
 
![DeepinScreenshot_select-area_20231015171230](https://github.com/scriptkidsensei/GeoHostCheck/assets/55909183/f762db56-8b76-4e62-a833-f0edad1e6601)
 
![Screenshot 2](https://github.com/scriptkidsensei/GeoHostCheck/assets/55909183/a78db6dd-6a6a-47d7-9dd2-cf8df0f505e9)
 
#### User-agent
 
![Screenshot 3](https://github.com/scriptkidsensei/GeoHostCheck/assets/55909183/f64187de-c789-4cd8-9824-20e79b3dc024)
 
#### Automatic proxy list installer!
 
![Screenshot 4](https://github.com/scriptkidsensei/GeoHostCheck/assets/55909183/523e67ac-26a0-473e-bb1d-70e734ef3976)
 
 
 
 ### Support Protocols 
 
 *Line : 449*
 
```python

if protocol == "ICMP":
#imcp proxy ping code...
 
 elif protocol == "UDP":
 send_udp_packet(target_ip, udp_port, protocol, proxy_address)
 elif protocol == "DNS":
 send_tls_request_to_dns(target_ip, tls_port, protocol, proxy_address, user_agent)
 elif protocol == "TCP":
 send_tcp_request(target_ip, tcp_port, protocol, proxy_address, user_agent)
 elif protocol == "TLS":
 send_tls_request(target_ip, tls_port, protocol, proxy_address, user_agent)
```
 
### Support Proxy types
 
```python
# Supports all proxy types
```
 
### User-Agents 
 
*Line : 26*
 
```python
user_agents = [
 "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/58.0.3029.110 Safari/537.36",
 "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Firefox/52.0 Safari/537.36",
 "Mozilla/5.0 (Linux; Android 5.1.1; ASUS_X00BD) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/85.0.4183.101 Mobile Safari/537.36"
 "Mozilla/5.0 (Linux; Android 9; SM-A530W) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.101 Mobile Safari/537.36"
 "Mozilla/5.0 (Linux; Android 5.0; SM-N900) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.106 Mobile Safari/537.36"
 "Mozilla/5.0 (Linux; Android 11; SM-N770F Build/RP1A.200720.012; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/91.0.4472.101 Mobile Safari/537.36"
 "Mozilla/5.0 (Linux; Android 7.0; LGMP450) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/83.0.4103.101 Mobile Safari/537.36"
 "Dalvik/2.1.0 (Linux; U; Android 8.1.0; GOME 2018X38A Build/O11019)"
 "Mozilla/5.0 (iPhone; CPU iPhone OS 14_2 like Mac OS X) AppleWebKit/605.1.15 (KHTML, like Gecko) GSA/129.0.336390422 Mobile/15E148 Safari/604.1"
 "Mozilla/5.0 (Linux; Android 9; SM-A102U) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/89.0.4389.86 Mobile Safari/537.36"
 "Mozilla/5.0 (Linux; Android 9; SM-N976N) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/78.0.3904.90 Mobile Safari/537.36"
 "Dalvik/1.6.0 (Linux; U; Android 8.1.0; E100 Build/KOT49H)"
]
```
 
## Installation
 
You can install Geohostcheck by cloning this repository:
 
```shell
git clone https://github.com/scriptkidsensei/GeoHostCheck.git
 
```
 
```shell
pip3 install -r requirements.txt
sudo python3 geohc.py
```
 
 
It took me a lot of effort to make this python script. Please star this repo :D
