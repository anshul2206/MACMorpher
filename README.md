# MACMorpher

A Python-based command-line tool to spoof or change the MAC (Media Access Control) address of your network interface on Unix/Linux systems.

---

## 🔧 Installation

You can download the script directly or clone the Git repository:

```bash
git clone https://github.com/anshul2206/MACMorpher.git
cd macchanger
```

Ensure Python 3 is installed and make the script executable (optional):

```bash
chmod +x Macchanger.py
```

---

## 🧰 Requirements

- Python 3.x
- `ifconfig` tool (usually part of `net-tools`)
- Root/sudo privileges

---

## ▶️ Usage

To change your MAC address, use:

```bash
sudo python3 Macchanger.py -i [interface] -m [new_mac_address]
```

### 📌 Examples

Change the MAC address of `eth0`:

```bash
sudo python3 Macchanger.py -i eth0 -m 00:11:22:33:44:55
```

View help options:

```bash
python3 Macchanger.py --help
```

---

## 💡 Sample Output

```text
Current MAC :aa:bb:cc:dd:ee:ff
[+] Changing MAC address for eth0 to 00:11:22:33:44:55
[+] MAC address is successfully changed to 00:11:22:33:44:55
```

---

## ⚠️ Notes

- This tool **only works on Linux/Unix** systems.
- Use responsibly. Changing MAC addresses can interfere with network access and violate some policies.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👤 Author

Developed by **Your Name**  
GitHub: [@anshul2206](https://github.com/anshul2206)
