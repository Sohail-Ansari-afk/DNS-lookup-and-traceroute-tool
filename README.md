# 🌐 DNS Lookup & Traceroute Tool (Python CLI)

A command-line tool to perform 🔍 DNS lookups, 🚀 traceroutes, and 📶 latency checks using Python, `socket`, and `scapy`.

---

## ⚙️ Features

- 🔎 DNS Lookup (Domain → IP)
- 🛰️ Traceroute to visualize hop paths
- 📈 ICMP-based Ping/Latency checks
- 🧪 Command-line based, no GUI required

---

## 📦 Requirements

- Python 3.x
- `scapy` package

Install `scapy` with:

```bash
pip install scapy
````

---

## ▶️ How to Run

1. 💾 Save the script as:

   ```
   DNS Lookup and Traceroute Tool.py
   ```

2. 🧠 Open terminal or command prompt.

3. Run the script using:

   ```bash
   python "DNS Lookup and Traceroute Tool.py"
   ```

4. 🖊️ Enter a domain when prompted:

   ```
   Enter a domain name (e.g., google.com):
   ```

5. You’ll get:

   * ✅ DNS Resolution Result
   * 📶 Ping Results (with latency in ms)
   * 🌐 Traceroute Output (each hop and its response time)

---

## 🔐 Example Output

```bash
Enter a domain name (e.g., google.com): google.com
[DNS] google.com resolves to 142.250.195.14

[Latency Check]
Ping 1: 142.250.195.14 - 22.34 ms
Ping 2: 142.250.195.14 - 20.18 ms
Ping 3: 142.250.195.14 - 21.76 ms
Ping 4: 142.250.195.14 - 22.10 ms

Average Latency: 21.60 ms

[Traceroute]
1: 192.168.0.1 (3.25 ms)
2: 10.0.0.1 (10.12 ms)
3: 142.250.195.14 (21.76 ms)
Traceroute complete.
```

---

## 📝 Notes

* Make sure you **run as Administrator/root** if traceroute doesn't work (some systems restrict ICMP packets).
* For educational and diagnostic use 📚
* Avoid excessive pinging of public domains 🌍

---

## 📌 Author

Built with ⚙️ `socket`, 💥 `scapy`, and ❤️ Python.

---

Happy Networking! 🛰️🔧🌍


