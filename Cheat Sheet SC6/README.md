# Safety Code 6 (SC6) Cheat Sheet

## What is Safety Code 6?

- Health Canada's RF exposure standard.
- Sets limits for human exposure to radio frequency (RF) energy.
- Covers frequencies from 3 kHz to 300 GHz.
- Applies to:
  - Cell towers
  - 4G/LTE
  - 5G
  - Wi-Fi
  - Broadcast antennas
  - Microwave links
  - Public safety radio systems

**Goal:** Ensure RF exposure remains below safe limits.

## Key Definitions

| Term | Meaning |
| --- | --- |
| RF | Radio Frequency |
| EMF | Electromagnetic Field |
| SC6 | Safety Code 6 |
| EIRP | Effective Isotropic Radiated Power |
| SAR | Specific Absorption Rate |
| AGL | Above Ground Level |
| dBi | Antenna Gain Unit |
| W/m² | Power Density Unit |

## RF Fundamentals

### RF

Electromagnetic energy used for wireless communication.

Examples:

- Cellular networks
- Wi-Fi
- Bluetooth
- Radio systems

### EMF

An Electromagnetic Field consisting of:

- Electric fields
- Magnetic fields

### RF Radiation

- Non-ionising radiation
- Does not ionise atoms like X-rays or gamma rays

## Common Cellular Frequencies

| Service | Frequency |
| --- | --- |
| LTE 700 | 698–806 MHz |
| Cellular 850 | 824–894 MHz |
| PCS | 1900 MHz |
| AWS | 1700/2100 MHz |
| LTE / 5G | 2600 MHz |
| 5G NR | 3500 MHz |

## Important Antenna Terms

### Antenna Gain

How effectively an antenna focuses RF energy.

**Example:** 17 dBi

### Azimuth

Direction the antenna points.

- 0° = North
- 90° = East
- 180° = South
- 270° = West

### Mechanical Tilt

Physical downward antenna angle.

**Example:** 4°

### Electrical Tilt

Electronic adjustment of the antenna beam.

**Example:** 6°

### EIRP

Effective radiated power after accounting for antenna gain and losses.

**Higher EIRP = higher potential RF exposure.**

## Power Density

Measures RF energy over an area.

**Unit:** W/m²

### Common Results

| Exposure | Meaning |
| --- | --- |
| 25% | Well below limit |
| 50% | Half the limit |
| 75% | Below limit |
| 100% | At the limit |
| 120% | Exceeds limit |

### Formula

```text
S = P ÷ A
```

Where:

- **S** = Power Density
- **P** = Power
- **A** = Area

## SAR

**Specific Absorption Rate** measures RF energy absorbed by the body.

**Unit:** W/kg

## Controlled vs Uncontrolled Areas

### Uncontrolled Environment

Public access areas:

- Sidewalks
- Streets
- Parking lots
- Public rooftops

More restrictive exposure limits apply.

### Controlled Environment

Areas restricted to trained personnel:

- Tower platforms
- Restricted rooftops
- Equipment compounds
- Maintenance areas

Higher occupational limits may apply.

## Near Field vs Far Field

| Near Field | Far Field |
| --- | --- |
| Close to antenna | Far from antenna |
| Complex behaviour | Predictable behaviour |
| Detailed modelling required | Simpler calculations |
| Exposure changes rapidly | Easier exposure estimates |

## Multiple Source Assessments

All RF sources must be considered together.

**Example:**

| Source | Contribution |
| --- | ---: |
| Bell | 30% |
| Rogers | 25% |
| TELUS | 18% |
| Public Safety | 12% |
| **Total** | **85%** |

**85% = compliant (below 100%).**

## SC6 Review Process

1. Collect site data
2. Review antenna parameters
3. Perform RF modelling
4. Calculate exposure levels
5. Compare against SC6 limits
6. Determine compliance
7. Recommend mitigation
8. Issue final report

## Typical RF Report Inputs

| Parameter | Example |
| --- | --- |
| Antenna Height | 35 m AGL |
| Transmit Power | 40 W |
| Antenna Gain | 17 dBi |
| Mechanical Tilt | 4° |
| Electrical Tilt | 6° |
| Frequencies | 700, 850, 1900, 3500 MHz |

## Common Compliance Issues

### Public Exposure Too High

Possible solutions:

- Antenna relocation
- Power reduction
- Increased setback distances

### Worker Exposure Concerns

Possible solutions:

- Restricted access
- Safe work procedures
- RF awareness training

### Rooftop Exposure Issues

Possible solutions:

- Safety barriers
- Restricted zones
- Warning signs
- Locked access

## RF Safety Signage

- **Notice:** RF equipment is present.
- **Warning:** Elevated RF exposure may exist.
- **Danger:** Exposure limits may be exceeded.

## Example Assessments

### Rooftop Site

| Location | Exposure |
| --- | ---: |
| Sidewalk | 1% |
| Adjacent Roof | 8% |
| Front of Antenna | 165% |

**Assessment:**

- Sidewalk → Compliant
- Adjacent roof → Compliant
- Front of antenna → Non-compliant

**Actions:**

- Restrict access
- Install signage
- Create controlled areas

### Worker Access Example

**Exposure:**

- 140% Public Limit
- 40% Controlled Limit

**Assessment:**

- Not suitable for public access
- May be acceptable for trained workers

## Frequently Asked Questions

### Is 5G covered by SC6?

Yes.

### What does 100% SC6 mean?

Exposure equals the allowable limit.

### What does “compliant” mean?

Exposure is below the applicable SC6 limit.

### Why use percentages?

To easily compare exposure against the allowable limit.

### Why does antenna tilt matter?

It changes where RF energy is directed and affects exposure levels.

## Common RF Compliance Software

### EMF Visual

- SC6 assessments
- Rooftop studies
- Tower studies
- Power density calculations

### iBwave

- Indoor wireless systems
- DAS design
- Coverage prediction

### EDX SignalPro

- RF propagation
- Coverage analysis
- Interference analysis

### Atoll

- LTE planning
- 5G planning
- Sector analysis

## SC6 Analyst Quick Summary

An SC6 analyst:

- ✅ Reviews site drawings and antenna data
- ✅ Reviews RF exposure reports
- ✅ Confirms compliance with SC6 limits
- ✅ Evaluates cumulative exposure
- ✅ Identifies problem areas
- ✅ Recommends mitigation measures
- ✅ Supports final compliance reporting

## Remember

- **100% SC6 = At the limit**
- **Less than 100% = Compliant**
- **Greater than 100% = Non-compliant / requires further review**
