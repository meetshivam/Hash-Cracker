# 🔐 Hash Cracker – Python-based Brute Force Password Recovery Tool

**Hash Cracker** is a Python-powered tool that recovers original human-readable passwords from encrypted hash values using **brute-force techniques**.  
It’s built for **educational**, **ethical hacking**, and **security testing** purposes to demonstrate how weak passwords can be cracked using computational methods.

---

## ⚙️ Supported Hash Algorithms

- **MD5**
- **SHA1**
- **SHA224**
- **SHA256**
- **SHA384**
- **SHA512**
- **SHA3_224**
- **SHA3_256**
- **SHA3_384**
- **SHA3_512**

---

## 🚀 Features

- 🔁 Multi-algorithm hash cracking  
- ⚡ Brute-force engine with customizable character sets  
- 🧵 Multi-threaded execution for better performance  
- 🧠 Educational example of cryptographic weakness in weak passwords  
- 💻 Simple and clean Command-Line Interface (CLI)

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/hash-cracker.git
   cd hash-cracker
````

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the tool:

   ```bash
   python hash_cracker.py
   ```

---

## 💡 Usage

You can run the script and provide:

* The **hash value**
* The **algorithm** (e.g., `md5`, `sha256`, etc.)
* The **maximum password length** or **custom charset** (if configured)

Example:

```bash
python hash_cracker.py --hash 5d41402abc4b2a76b9719d911017c592 --algo md5
```

**Output:**

```
✅ Hash cracked successfully!
🔓 Plaintext password: hello
```

---

## 🧰 Requirements

* Python 3.8+
* `hashlib`
* `itertools`
* `tqdm`
* `argparse`

---

## ⚠️ Disclaimer

This project is developed **strictly for educational and ethical purposes**.
Use it **only** on hashes you **own** or have **explicit permission** to test.

