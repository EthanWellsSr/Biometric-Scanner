# Parts List

Running list of hardware for the Biometric Locking Box. Status: **Have** / **Ordered** / **Need** / **TBD**.

Wiring: [docs/wiring-diagram.png](docs/wiring-diagram.png) · pinout tables in the [README](README.md#wiring).

| Component | Qty | Purpose | Status | Price (USD) | Date Purchased | Purchased By | Link |
|---|---|---|---|---|---|---|---|
| Arduino Uno (Rev3) | 1 | Main controller — runs the fingerprint matching sketch and drives the relay | Have | — | — | — | |
| Geekworm transparent protective case for Arduino Uno R3 | 1 | Protects the Arduino board while leaving its USB, power, and header connections accessible | Have | $5.00 | 2025-11-05 | Ethan Wells | [Amazon](https://www.amazon.com/dp/B01C8500L8) |
| Optical fingerprint sensor module (Adafruit-compatible, e.g. R305/ZFM-20) | 1 | Enrolls and matches fingerprints over TTL serial (57600 baud, D2/D3) | Have | — | — | — | |
| 5 V single-channel relay module | 1 | Switches 12 V to the solenoid from Arduino D4 (active LOW) | Have | — | — | — | |
| 12 V DC locking solenoid | 1 | Lock mechanism — retracts to open the box on a fingerprint match | Have | — | — | — | |
| 12 V DC AC-DC power adapter | 1 | Main power for the Arduino (VIN) and the solenoid | Have | — | — | — | |
| DC barrel jack adapter (female, screw terminal) | 1 | Splits 12 V from the adapter to the Arduino and relay/solenoid circuit | Have | — | — | — | |
| Rechargeable battery pack | 1 | Backup power so the sensor and lock work during outages | Have | — | — | — | |
| Breadboard | 1 | Prototyping and power distribution | Have | — | — | — | |
| Jumper wires | 1 set | Connections between sensor, relay, solenoid, and Arduino | Have | — | — | — | |
| USB A-to-B cable | 1 | Upload the sketch and view the serial monitor | Have | — | — | — | |
| Enclosure / box | 1 | Secure storage box housing the lock and electronics | Have | — | — | — | |
| **Running total (priced items only)** | | | | **$5.00** | | | |

Pricing may vary depending on current market; prices listed are item prices at the time of purchase, before tax. The Arduino case was listed at $5.90 when rechecked on 2026-09-24. The [Project Analysis Paper](Project%20Analysis%20Paper.pdf) puts the final build cost at about $85 (estimate was about $100).
