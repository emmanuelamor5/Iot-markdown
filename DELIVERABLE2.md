# Embedded Systems & IoT
## Prototypes of Embedded Devices
**Group 10**

---

## 1. Group Members


| Name | Student ID | Role in this Deliverable |
|---|---|---|
| Jesse Richard and Ryan Arkadie | 159287, 168052| _e.g. Physical prototype (a), wiring & testing_ |
| Derrick Kibet and Emmanuel Ochieng | 169651, 169765 | _e.g. Physical prototype (b), documentation_ |
| Joe Karogo and Matthew Wachira | 167141, 151733 | _e.g. Wokwi simulations (a) and (c)_ |
| Jarvis Getenga | 169888 | _e.g. Sensor calibration, IDE output capture_ |

**Evidence of groupwork:**

![Group photo](media/group_photo.jpg)


---

## 2. Overview of Architectures

Per the Deliverable 2 brief, our group produced the required minimum of 4 prototypes:

| Architecture | Description | Prototype Type |
|---|---|---|
| (a) | ESP32 + MQ-5 + DHT22 + LCD | **Physical** and **Simulated** (both required) |
| (b) | ESP32 (MQ-5) ↔ ESP32 (DHT22), interfaced directly | **Physical** |
| (c) | ESP32 (DHT22) → Relay → ESP32 (MQ-5) | **Simulated** |

(b) and (c) are interchangeable per the brief; our group built (b) physically and (c) as a simulation.

---

## 3. Architecture (a): ESP32 + MQ-5 + DHT22 + LCD

### 3.1 Physical Prototype

![Physical prototype (a)](media/4aphysical 1.jpeg)
![Physical prototype (a) - alternate angle](media/4aphysical 2.jpeg)

**IDE Output:**

![IDE output (a)](media/4aIDE simulated.jpeg)


### 3.2 Simulated Prototype

**Wokwi Project Link:** [https://wokwi.com/projects/467286122843350017](https://wokwi.com/projects/467286122843350017)


![Simulated prototype (a)](media/4a Wokwi simulated.png)

---

## 4. Architecture (b): ESP32 (MQ-5) ↔ ESP32 (DHT22)

### 4.1 Physical Prototype


![Physical prototype (b)](media/4bphysical 1.jpeg)
![Physical prototype (b) - alternate angle](media/4bphysical 2.jpeg)

**IDE Output:**

![IDE output (b)](media/4bIDE simulated.jpeg)

---

## 5. Architecture (c): ESP32 (DHT22) → Relay → ESP32 (MQ-5)

### 5.1 Simulated Prototype

**Wokwi Project Link:** [https://wokwi.com/projects/467156925257896961](https://wokwi.com/projects/467156925257896961)


![Simulated prototype (c)](media/4c Wokwi simulated.png)



---

## 6. Issues Encountered and Resolutions

- **Problem:** For architecture (a), we were unable to display any output on the LCD.
- **Solutions explored:** We checked the wiring and suspected that the connections were either not transmitting enough voltage or that the LCD module had failed completely. We tried to resolve the issue during the available time, but we could not fully fix it before submission.
- **Recommendation / resolution:** Although the LCD did not display as expected, the IDE serial monitor produced meaningful output and confirmed that the program logic was working. This suggests the issue was most likely hardware-related and should be revisited by rechecking the wiring, power supply, and LCD module.

---

## 7. Repository Structure

```
/Iot-markdown
│
├── DELIVERABLE2.md           # this document
├── media/                    # all images referenced above
│   ├── 4a Wokwi simulated.png
│   ├── 4aIDE simulated.jpeg
│   ├── 4aphysical 1.jpeg
│   ├── 4aphysical 2.jpeg
│   ├── 4bIDE simulated.jpeg
│   ├── 4bphysical 1.jpeg
│   ├── 4bphysical 2.jpeg
│   └── 4c Wokwi simulated.png

```