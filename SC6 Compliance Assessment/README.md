# Safety Code 6 (SC6) RF Exposure Compliance Assessment

## Overview

This repository contains reference material describing a typical Safety Code 6 (SC6) RF exposure compliance assessment process used for wireless telecommunications infrastructure, including macro sites, rooftop installations, small cells, fixed wireless systems, and 4G/5G deployments.

The objective of an SC6 assessment is to verify that radiofrequency (RF) exposure levels remain below the limits established by Health Canada's Safety Code 6 standard.

## What is Safety Code 6?

Safety Code 6 (SC6) is Health Canada's standard for human exposure to radiofrequency (RF) electromagnetic fields in the frequency range from 3 kHz to 300 GHz. It establishes exposure limits designed to protect the public and workers from known adverse health effects associated with RF energy.

The “6” in Safety Code 6 is simply the document number within a series of Health Canada safety codes. It does not represent a frequency, power level, or technical RF parameter.

## RF Fundamentals

### RF (Radio Frequency)

RF is electromagnetic energy used for wireless communications.

Examples include:

- Cellular networks (4G/5G)
- Wi-Fi
- Bluetooth
- Public safety radio
- Broadcast systems
- Microwave links

### EMF (Electromagnetic Field)

An electromagnetic field consists of electric fields and magnetic fields. RF energy is a form of EMF.

### RF Radiation

RF communication systems produce non-ionizing radiation: energy that does not ionize atoms like X-rays or gamma rays.

## Assessment Workflow

```text
Receive Assessment Request
        ↓
Collect Site Information
        ↓
Validate Site Documentation
        ↓
Information Complete?
        ↓
Review Antenna Parameters
        ↓
Define Assessment Areas
        ↓
Perform RF Modelling
        ↓
Calculate Exposure Levels
        ↓
Aggregate Multiple RF Sources
        ↓
Compare Against SC6 Limits
        ↓
Compliant?
        ↓
Issue Report
```

## Phase 1 – Information Collection

The assessment begins by gathering all information required to accurately model RF exposure levels.

### Site Data

- Site ID
- Site name
- Site address
- GPS coordinates
- Rooftop or tower classification
- Site drawings
- Elevation information

### Antenna Data

- Manufacturer
- Antenna model
- Number of sectors
- Antenna height (AGL)
- Antenna gain (dBi)
- Azimuth
- Mechanical tilt
- Electrical tilt

### RF System Data

- Frequency bands
- LTE carriers
- 5G NR carriers
- Public safety systems
- Fixed wireless systems
- Broadcast systems

### Transmission Data

- Transmit power
- EIRP
- MIMO configuration
- Carrier aggregation configuration

### Information Validation

Before starting RF modelling, the analyst confirms all required inputs are available.

#### Validation checklist

**Site information**

- [x] Site drawings available
- [x] Antenna locations identified
- [x] Building dimensions available
- [x] Access areas identified

**RF information**

- [x] Antenna models available
- [x] Power levels available
- [x] Frequency assignments available
- [x] Existing RF systems identified

If information is missing:

1. Identify missing data.
2. Request clarification.
3. Obtain updated documentation.
4. Repeat the validation process.

## Phase 2 – Technical Review

### Antenna Parameter Review

| Parameter | Purpose |
| --- | --- |
| Height | RF propagation analysis |
| Gain | Exposure calculations |
| Azimuth | RF direction |
| Mechanical tilt | Beam positioning |
| Electrical tilt | Beam shaping |
| Frequency | Exposure calculations |
| EIRP | Power density calculations |

## Phase 3 – Define Assessment Areas

Exposure calculations are performed at locations where people may be present.

### Public areas

- Sidewalks
- Streets
- Parking lots
- Adjacent properties
- Accessible rooftops

### Occupational areas

- Tower platforms
- Equipment compounds
- Maintenance zones
- Restricted rooftops

## Phase 4 – RF Modelling

RF modelling estimates exposure levels around the site.

Typical software may include:

- EMF Visual
- Atoll
- EDX SignalPro
- Proprietary engineering tools

Outputs include:

- Power density
- Exposure contours
- Compliance boundaries
- Exposure percentages

## Phase 5 – Exposure Calculations

Exposure is evaluated for:

- **Public exposure:** More restrictive limits apply.
- **Occupational exposure:** Applies to trained workers operating in controlled environments.

Results are typically expressed as:

| Exposure level | Assessment |
| --- | --- |
| < 100% | Compliant |
| = 100% | At regulatory limit |
| > 100% | Non-compliant |

### SC6 Exposure Limits by Frequency (Interview Quick Reference)

For wireless infrastructure assessments, results are often reported as a percentage of the applicable Safety Code 6 limit.

```text
% SC6 = (Calculated Power Density / SC6 Limit) × 100
```

Therefore, 100% SC6 means the maximum allowable exposure level for that frequency.

#### Typical public exposure limits

| Frequency band | Approx. 100% SC6 limit |
| --- | ---: |
| 700 MHz | 4.7 W/m² |
| 850 MHz | 5.7 W/m² |
| 1900 MHz | 10 W/m² |
| 2100 MHz | 10 W/m² |
| 2600 MHz | 10 W/m² |
| 3500 MHz | 10 W/m² |

#### Example – 2100 MHz

| Power density | SC6 percentage |
| ---: | ---: |
| 2.5 W/m² | 25% |
| 5.0 W/m² | 50% |
| 7.5 W/m² | 75% |
| 10.0 W/m² | 100% |
| 12.0 W/m² | 120% |

### What Does 75% SC6 Mean?

A result of 75% means the calculated RF exposure is 75% of the maximum allowable Safety Code 6 limit. The location is compliant because it remains below 100%.

### Why Does the SC6 Limit Change With Frequency?

RF energy interacts differently with the human body at different frequencies. For this reason, Safety Code 6 establishes frequency-dependent exposure limits.

### Power Density vs. SAR

**Power density** measures RF energy present in an area.

- Unit: W/m²
- Used for cell towers, rooftop sites, small cells, broadcast systems, and fixed wireless installations

**SAR (Specific Absorption Rate)** measures RF energy absorbed by human tissue.

- Unit: W/kg
- Used for mobile phones, tablets, wearables, and devices operating close to the body

**Easy way to remember:** Power density is RF energy outside the body; SAR is RF energy absorbed inside the body.

Most SC6 rooftop and tower assessments use power density rather than SAR.

## Phase 6 – Multiple Source Assessment

Where multiple RF systems exist, all exposure sources must be combined.

Examples include Bell, Rogers, TELUS, public safety radio, broadcast systems, and microwave links. The combined exposure percentage is compared against the applicable SC6 limit.

### Example

| Source | Exposure contribution |
| --- | ---: |
| Bell | 30% |
| Rogers | 25% |
| TELUS | 15% |
| Public safety | 10% |
| **Total** | **80%** |

**Result:** 80% SC6 = compliant.

## Compliance Decision

### Exposure ≤ 100%

The site is considered compliant. Proceed to final calculations, report preparation, and compliance certification.

### Exposure > 100%

Mitigation measures must be evaluated.

## Mitigation Assessment Process

### Step 1 – Determine Root Cause

#### High transmit power

Examples: LTE carrier additions, 5G overlays, or excessive EIRP.

Mitigations:

- Reduce power
- Traffic balancing
- Network redesign

#### Antenna orientation issues

Examples: improper azimuth or excessive main beam exposure.

Mitigations:

- Adjust azimuth
- Modify electrical tilt
- Modify mechanical tilt

#### Insufficient separation distance

Examples: a public walkway near an antenna or a rooftop access path in the RF beam.

Mitigations:

- Increase setback distance
- Relocate access route
- Restrict public access

#### Antenna placement issues

Examples: an antenna mounted too low or facing an occupied area.

Mitigations:

- Relocate antenna
- Increase mounting height
- Change mounting structure

#### Multi-carrier exposure

Examples: a shared tower or shared rooftop.

Mitigations:

- Coordinate with co-located operators
- Reassess combined EIRP
- Reconfigure the RF environment

### Administrative Controls

Where engineering controls are not sufficient, administrative controls may be implemented. Examples include:

- RF warning signs
- RF notice signs
- Controlled access zones
- Locked gates
- Restricted rooftop access
- Physical barriers
- Safe work procedures
- RF awareness training

### Final Assessment Cycle

```text
Identify Issue
      ↓
Select Mitigation
      ↓
Implement Changes
      ↓
Recalculate Exposure
      ↓
Exposure ≤ 100%?
      ↓
YES → Issue Report

NO  → Repeat Mitigation Process
```

## Final Deliverables

A typical SC6 report includes:

- Site description
- Antenna inventory
- Technical parameters
- RF modelling assumptions
- Exposure calculations
- Compliance assessment
- Mitigation recommendations
- Site diagrams
- Compliance statement

## SC6 Analyst Responsibilities

An SC6 analyst typically:

- Reviews site documentation
- Reviews antenna configurations
- Validates RF inputs
- Performs RF exposure assessments
- Evaluates cumulative RF exposure
- Identifies compliance risks
- Develops mitigation recommendations
- Produces final compliance reports

## Quick Summary

An SC6 assessment verifies that RF exposure levels from wireless infrastructure remain below Safety Code 6 limits.

The process involves:

1. Collecting and validating site data.
2. Reviewing antenna parameters and RF system information.
3. Performing RF modelling.
4. Calculating exposure levels and cumulative exposure.
5. Comparing results against applicable SC6 limits.
6. Identifying mitigation measures if exposure exceeds limits.
7. Issuing the final compliance report.

### Key Interview Takeaways

- 100% SC6 means exposure equals the allowable limit.
- Less than 100% is compliant.
- Greater than 100% requires mitigation or further review.
- Power density (W/m²) is the primary metric used for towers and rooftop studies.
- SAR (W/kg) is primarily used for devices operating close to the body.
- Multiple RF sources must always be evaluated cumulatively.
- RF analysts focus heavily on antenna height, gain, azimuth, tilts, EIRP, and frequency when performing SC6 assessments.
