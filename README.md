☕⚡ KaffeeSATS

## Bitcoin-Powered Coffee Machines

**Pay with Lightning. Drink Coffee.**

KaffeeSATS is an open-source project that transforms standard coffee machines into Bitcoin-powered vending systems using the Lightning Network.

The project currently includes two different implementations.

---

# Version 1: Offline Bitcoin Switch

### Offline Lightning PIN System

Hardware:

* Sunton ESP32-3248S035 Smart Display
* LNbits Offline Bitcoin Switch
* Internal Relay Interface
* Bosch Tassimo Coffee Machine

How it works:

1. Scan Lightning invoice
2. Pay with any Lightning wallet
3. Receive a secret PIN
4. Enter PIN on the display
5. Relay activates
6. Press coffee button
7. Coffee brewing starts

Advantages:

* Works without permanent internet connection
* No external controller required
* Great demonstration of the LNbits Offline Bitcoin Switch

---

# Version 2: Online ZapBox Edition

### Lightning & Bolt Card Enabled

Hardware:

* ZapBox Compact
* LNbits
* Internal 5V Relay
* Bosch Tassimo Coffee Machine

How it works:

1. Scan QR Code
   or
   Tap NFC Bolt Card
2. Lightning payment is processed
3. ZapBox outputs a 5V trigger signal
4. Internal relay enables the machine
5. User presses the brew button
6. Coffee brewing starts

Advantages:

* Instant user experience
* NFC Bolt Card support
* Simple payment flow
* Perfect for conferences and public demonstrations

---

# Comparison

| Feature             | Offline Switch | ZapBox   |
| ------------------- | -------------- | -------- |
| Lightning QR        | ✅              | ✅        |
| NFC Bolt Card       | ❌              | ✅        |
| Secret PIN          | ✅              | ❌        |
| Sunton Display      | ✅              | Optional |
| ZapBox              | ❌              | ✅        |
| Offline Operation   | ✅              | ❌        |
| Conference Friendly | ✅              | ✅        |

---

# Why KaffeeSATS?

Bitcoin is often difficult to explain.

Coffee is not.

KaffeeSATS demonstrates Bitcoin and the Lightning Network through a real-world interaction that everyone understands.

Pay.
Press.
Enjoy.

---

# Open Source

This project is released under the MIT License.

Feel free to fork, improve and build your own Bitcoin-powered coffee machine.
!!!!! Thank you to Axel for the amazing work (Zapbox & Offline Switch) & LNBits !!!!!
---

# KaffeeSATS

### Pay With Lightning. Drink Coffee.
