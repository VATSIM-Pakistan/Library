# Karachi Aerodrome Guide (OPKC)

## 1. Aerodrome Information

| Item                        | Information             |
| --------------------------- | ----------------------- |
| Location                    | Karachi, Pakistan       |
| ICAO / IATA                 | OPKC / KHI              |
| Coordinates                 | N24° 54.5', E067° 09.8' |
| Elevation                   | 100 ft                  |
| Transition Altitude / Level | 3000 ft / FL050         |

---

## 1.2 Communication Information

| Position         | Callsign  | Frequency |
| ---------------- | --------- | --------- |
| Karachi ATIS     | OPKC_ATIS | 126.700   |
| Karachi Ground   | OPKC_GND  | 121.600   |
| Karachi Tower    | OPKC_TWR  | 118.300   |
| Karachi Approach | OPKC_APP  | 125.500   |

---

## 1.3 Navigational Aids

| Instrument      | Identifier | Frequency |
| --------------- | ---------- | --------- |
| ILS/DME RWY 25L | IQA        | 109.7     |
| ILS/DME RWY 25R | IKC        | 110.1     |
| VOR             | KC         | 112.1     |
| NDB             | KC         | 271       |

---

## 1.4 Runways

### Characteristics

| Runway | True/Magnetic Bearing | Dimensions        |
| ------ | --------------------- | ----------------- |
| 25L    | 254/250               | 11155 ft × 148 ft |
| 25R    | 254/250               | 10499 ft × 151 ft |
| 07L    | 074/070               | 11155 ft × 148 ft |
| 07R    | 074/070               | 10499 ft × 151 ft |

### Takeoff Distances

| Runway | Intersection  | TORA   | ASDA   |
| ------ | ------------- | ------ | ------ |
| 25L    | Full Distance | 3400 m | 3400 m |
| 25L    | F             | 3000 m | 3000 m |
| 25R    | Full Distance | 3500 m | 3500 m |
| 25R    | F             | 2900 m | 2900 m |
| 07R    | Full Distance | 3400 m | 3400 m |
| 07R    | A             | 2900 m | 2900 m |
| 07L    | Full Distance | 3500 m | 3500 m |

---

# 2. Departure Clearance Procedures

Ground Movement Control (GMC) is responsible for validating routes and providing IFR clearance to departing aircraft. The controller shall assign the correct departure procedure based on the first point filed in the flight plan.

Where the flight plan contains an invalid route, level, or departure procedure, GMC shall ensure the error is corrected before clearance is issued.

---

## 2.1 Requesting ATC Clearance

Pilots are expected to report the following on first contact before requesting ATC clearance:

1. Callsign
2. Stand number
3. Destination
4. Current ATIS letter
5. Requested flight level

---

## 2.2 Receiving ATC Clearance

An ATC clearance shall contain the following:

1. Callsign
2. Destination
3. Departure procedure / Radar Vectors / SID / Airway
4. Runway in use
5. Initial flight level
6. Assigned SSR code

### Example

```text
Pilot: Karachi Ground, PIA300 at stand 12, destination Islamabad, requested level FL390, we have information C, requesting ATC clearance.

Controller: PIA300, Karachi Ground, cleared to destination Islamabad enroute J112, BADUL1D departure, RWY 25L in use, initially climb and maintain FL070, expect higher enroute, squawk on departure 3642.

Pilot: Cleared to destination enroute J112 via the BADUL1D departure, RWY 25L, climb initially FL070, squawk 3642, PIA300.

Controller: PIA300, readback is correct, information C is current, report ready for push and start.
```

> **Note:** QNH must be provided during taxi instructions.

### Example

```text
Controller: PIA300, taxi to holding point RWY 25L via M,E,H, QNH 1013.
```

---

## 2.3 Departure Procedures

### 2.3.1 RNAV Instrument Departures

Karachi generally uses RNAV SIDs for departures and these are preferred. Certain non-RNAV SIDs may also be used, particularly for eastbound departures or during RWY 07 operations.

Commonly used RNAV SIDs:

1. BADUL1D
2. MELOM1F
3. MELOM1H
4. DANGI1D
5. NIROL1C

---

### 2.3.2 Omni-directional Departures

When a pilot is unable to fly a SID, an omni-directional departure may be assigned. Aircraft can expect radar vectors to the first waypoint filed in the flight plan.

During takeoff clearance, Tower shall assign an initial heading. Further vectors will then be issued by Approach.

### Example ATC Clearance

```text
Pilot: Karachi Ground As-salamu alaykum, PIA300, stand 18, POB 112, requested level 370, request IFR clearance to Lahore, we are unable to accept SID.

Controller: PIA300, cleared to destination via the omni-directional departure, RWY 25L in use, initially climb and maintain FL070, squawk 3642.
```

### Example Takeoff Clearance

```text
Controller: PIA300, after departure turn right heading 010, surface winds 260 degrees 08 knots, RWY 25L, cleared for takeoff.
```

---

## 2.4 Runway Change

At Karachi, the primary runway in use is RWY 25L. However, if wind conditions favor RWY 07 operations with wind speeds exceeding 8 knots, the active runway may be changed.

Aircraft already cleared shall receive updated clearances reflecting the revised runway and SID.

### Example

```text
Controller: PIA300, runway has been changed. ATC clearance available, report ready to copy.

Pilot: Ready to copy clearance, PIA300.

Controller: PIA300 re-cleared to destination via the BADUL3B departure, RWY 07R in use, initially climb to FL070, squawk 3642.
```

---

## 2.5 VFR Aircraft

### 2.5.1 General

VFR operations at OPKC are permitted subject to ATC clearance and prevailing traffic conditions. Due to high IFR traffic volume at Jinnah International Airport, VFR aircraft may be delayed, rerouted, or subject to altitude restrictions.

All VFR aircraft shall maintain continuous two-way radio communication with ATC while operating within controlled airspace.

---

### 2.5.2 Airspace Classification

The airspace surrounding OPKC is controlled airspace.

Therefore:

* VFR flights require explicit ATC clearance before entry.
* Standard VFR “see and avoid” principles apply.
* ATC shall provide separation from IFR traffic where possible.
* Pilots remain responsible for maintaining vigilance for other traffic.

---

### 2.5.3 VFR Entry and Exit Procedures

VFR aircraft shall use designated reporting points when entering or exiting the Karachi CTR.

Pilots must report:

1. Position
2. Altitude
3. Intentions

ATC may assign:

1. Specific routing
2. Altitude restrictions
3. Holding instructions if required

---

### 2.5.4 Circuit Procedures

Standard traffic circuits at OPKC are conducted as follows unless otherwise instructed:

| Item              | Information                                        |
| ----------------- | -------------------------------------------------- |
| Circuit Altitude  | Typically 1000 ft AGL                              |
| Circuit Direction | Left-hand or right-hand depending on runway in use |
| Joining Procedure | Overhead join or as instructed by ATC              |

Pilots shall:

1. Report joining, downwind, base, and final
2. Maintain spacing from preceding traffic
3. Be prepared for extended circuits during busy traffic periods

---

# 3. Ground Movement Procedures

Ground Movement Controller (GMC) is responsible for all aircraft movements on aerodrome movement areas except runways and associated taxiways.

Departing aircraft are provided pushback and taxi instructions. Arriving aircraft are assigned stands and taxi routes.

For intersection departure requests, Ground Controller shall coordinate with Tower before approval.

---

## 3.1 Pushback Procedures

Aircraft requesting pushback without displaying the assigned transponder code shall remain on stand until the correct squawk is set.

Pushback or ground movement shall not be authorized until compliance is confirmed.

Depending on stand allocation, aircraft shall receive a specific pushback direction.

---

### 3.1.2 Coordination Requirement

Where pushback affects taxiway flow or sequencing, Ground Controller shall coordinate appropriately with adjacent positions.

---

## 3.2 Taxi Procedures

### 3.2.1 Departure Taxi Clearance

* Aircraft shall receive taxi instructions to the appropriate holding point after pushback and engine start.
* Taxi routes shall be issued in full where necessary.
* Pilots shall read back all taxi instructions.

---

### 3.2.2 Taxi Route Management

* Taxi instructions shall prioritize efficiency and safety.
* Intermediate holding points may be used to regulate traffic.
* Aircraft shall exercise caution at intersections and give way when instructed.

---

### 3.2.3 Runway Coordination and Holding Points

* Aircraft shall not enter holding points without Tower clearance.
* GMC shall hand aircraft to Tower at appropriate positions to avoid unnecessary stopping.

---

### 3.2.4 Taxiways for RWY 25L / 25R

| Stands | Taxiways for RWY 25L | Taxiways for RWY 25R |
| ------ | -------------------- | -------------------- |
| 11–14  | M,E,H                | M,E,G                |
| 16–23  | N,E,H                | N,E,G                |
| 25–28  | P,E,H                | P,E,G                |

---

### 3.2.5 Taxiways for RWY 07R / 07L

| Stands | Taxiways for RWY 07R | Taxiways for RWY 07L |
| ------ | -------------------- | -------------------- |
| 11–14  | M,E                  | M,E,Q                |
| 16–23  | N,E                  | N,E,Q                |
| 25–28  | P,E                  | P,E,Q                |

---

## 3.3 Stand Allocation Procedure

### Main Jinnah Terminal

| Stand Range  | Usage                 |
| ------------ | --------------------- |
| Stands 11–18 | Domestic Flights      |
| Stands 21–28 | International Flights |

---

### 3.3.1 Restrictions

* Stands 14, 16, 23, 24, and 25 are certified for heavy aircraft operations.
* Remaining stands support medium to light aircraft.
* Stands 11, 18, 21, and 28 are remote stands without direct boarding infrastructure.

---

## 3.4 Handoff Procedures

Transfer of control between ATS units shall ensure continuous separation and situational awareness.

Controllers shall not issue clearances beyond their area of responsibility without coordination.

Aircraft may be instructed to hold at suitable intermediate points when required.

---

# 4. Aerodrome Procedures

The Aerodrome Controller (ADC) is responsible for all movements on active runways and associated taxiways.

ADC shall ensure safe and efficient IFR arrival and departure separation while also coordinating IFR and VFR operations within the control zone.

---

## 4.2 Preferred Runways

Due to ILS capability and runway length, RWY 25L is the preferred runway.

When wind conditions require a runway change combined with wind changes greater than 8 knots, RWY 07R becomes the preferred runway.

---

## 4.3 Departure Procedures

### 4.3.1 Line-up Clearance

Aircraft handed over to Tower may be cleared to line up once the runway is confirmed clear.

### Example

```text
Controller: PIA300, via Holding Point H, line up and wait RWY 25L.
```

### Conditional Line-up Clearance

```text
Controller: PIA300, behind departing company A320, line up and wait RWY 25L behind.
```

---

### 4.3.2 Takeoff Clearance

Aircraft shall be cleared for takeoff once separation standards are met.

### Example

```text
Controller: PIA300, surface winds 260 degrees 10 knots, RWY 25L, cleared for takeoff.
```

---

### 4.3.3 Separation Requirements

* IFR departures shall comply with standard IFR separation minima.
* Enhanced wake turbulence separation (eWTS) shall be applied where applicable.
* Aircraft on the same SID shall generally receive a minimum spacing of two minutes unless reduced separation is permitted.
* VFR departures may be cleared maintaining visual separation where appropriate.

---

### 4.3.4 Departure Handoff Procedure

Aircraft shall normally be handed to Approach after becoming airborne and reaching 1000 ft AGL.

### Example

```text
Controller: PIA300, airborne time 17, contact Karachi Approach 125.500.
```

---

### 4.3.5 Omni-directional Departures

Aircraft conducting omni-directional departures may receive heading assignments after departure to assist with sequencing and terrain separation.

### Example

```text
Controller: PIA300, after departure fly heading 270, maintain altitude 2000 ft, wind 280 degrees 6 knots, RWY 25L, cleared for takeoff.
```

---

### 4.3.6 Rejecting a Departure

Aircraft may be instructed to reject takeoff where required to prevent unsafe situations.

### Example

```text
Controller: PIA300, cancel takeoff clearance, stop immediately, I say again, stop immediately.
```

---

## 4.4 Arrival Procedures

While Approach primarily manages arrival separation, ADC shall ensure separation is maintained until the preceding aircraft crosses the threshold safely.

---

### 4.4.1 Speed Restriction

ADC may issue speed control instructions to maintain arrival spacing.

### Example

```text
Controller: PIA300, surface winds 270 degrees 08 knots, RWY 25L, continue approach number 2, reduce to minimum approach speed for separation.
```

---

### 4.4.2 Visual Separation

Aircraft without Mode C or VFR aircraft may be instructed to maintain visual separation.

---

### 4.4.3 Go-around Instruction

Controllers may issue go-around instructions where landing is no longer suitable.

### Example

```text
Controller: PIA300, go around, I say again, go around, acknowledge going around.

Pilot: PIA300 going around.

Controller: PIA300, continue missed approach procedure, contact Karachi Approach 125.500.
```

---

### 4.4.4 Arrival Taxi Procedure

After vacating the runway, aircraft shall receive taxi instructions and be transferred to Ground once fully clear of the runway environment.

---

## 4.5 VFR Procedures

ADC is responsible for managing all VFR traffic within the control zone.

---

### 4.5.1 VFR Departures

Once ready and traffic conditions permit, VFR aircraft shall be cleared for departure in an orderly sequence.

Aircraft shall report when leaving the control zone.

---

### 4.5.2 VFR Traffic in Circuit

At Karachi, circuit operations are conducted north of the airfield.

Aircraft shall:

* Enter downwind as instructed
* State intentions
* Expect orbit instructions during IFR arrival sequencing where required

Once orbiting is no longer required, ADC shall issue base turn instructions followed by landing or touch-and-go clearance.

---

### 4.5.3 VFR Arrivals

Inbound VFR aircraft shall establish contact with ADC before entering the control zone.

ADC shall issue:

* Joining instructions
* Circuit direction
* Circuit altitude
* Runway in use
* Traffic information
* Sequencing requirements

Pilots shall remain outside controlled airspace until clearance to enter has been issued.
