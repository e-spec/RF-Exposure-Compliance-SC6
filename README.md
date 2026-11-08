# RF Exposure Compliance Theory and Practice
## Safety Code 6 (SC6) Guide for Cellular Site Assessment and Compliance Review

## Purpose

This guide provides the theoretical foundations and practical knowledge required to understand, evaluate, and review Safety Code 6 (SC6) compliance assessments for cellular and wireless communication sites.

### Intended Audience

- RF Compliance Analysts
- RF Engineers
- Telecommunications Engineers

### Topics Covered

- Safety Code 6 fundamentals
- RF exposure theory
- Cellular site compliance assessments
- Exposure calculations and interpretation
- Controlled and uncontrolled environments
- Common compliance issues
- Mitigation strategies
- Real-world examples
- Frequently Asked Questions (FAQ)

---

# Why Is It Called Safety Code 6?

Safety Code 6 (SC6) is one of several safety codes published by Health Canada.

The number "6" is simply the identifier assigned to the code that addresses human exposure to radiofrequency electromagnetic fields (RF-EMF). It is not related to:

- RF frequencies
- Cellular technologies
- Exposure limits
- 5G
- Telecommunications generations

SC6 establishes limits for human exposure to RF energy in the frequency range of **3 kHz to 300 GHz**, including:

- Cellular networks
- Wi-Fi
- Microwave systems
- Radio communications
- Satellite systems
- Emerging wireless technologies

---

# What Is Safety Code 6?

Safety Code 6 is Health Canada's guideline for limiting human exposure to radiofrequency electromagnetic fields.

It is the primary standard used in Canada to evaluate RF exposure from:

- Cellular base stations
- 4G LTE systems
- 5G systems
- Wi-Fi access points
- Broadcast antennas
- Microwave links
- Public safety radio systems

The goal of SC6 is to ensure RF exposure remains below levels known to produce adverse health effects.

---

# What Does an SC6 Analyst Do?

An SC6 analyst typically performs the following activities.

## Review Site Documentation

- Tower drawings
- Rooftop drawings
- Antenna schedules
- Construction packages
- Equipment inventories

## Evaluate RF Exposure Reports

- Power density results
- SAR references
- Exposure percentages
- Public exposure zones
- Worker exposure zones

## Determine Compliance

Verify whether exposure levels remain below applicable Safety Code 6 limits.

## Recommend Mitigation Measures

If exposure exceeds limits, recommendations may include:

- Physical barriers
- Safety signage
- Access restrictions
- Antenna relocation
- Antenna reorientation
- Power reduction
- Controlled-access procedures

---

# RF Fundamentals

## What Is RF?

RF (Radio Frequency) refers to electromagnetic energy used for wireless communication systems.

Examples include:

- Cellular networks
- Wi-Fi
- Bluetooth
- Microwave communication
- Radio transmission
- Television broadcasting

## What Is EMF?

EMF stands for Electromagnetic Field. An EMF consists of electric fields and magnetic fields. Radiofrequency energy is a type of EMF.

## What Is RF Radiation?

RF radiation is classified as **non-ionising radiation**. Unlike X-rays or gamma rays, RF energy does not have enough energy to ionise atoms or molecules.

Common RF sources include:

- Cellular towers
- Wi-Fi routers
- Radio transmitters

---

# Common Cellular Frequencies

| Service | Typical frequency |
| --- | --- |
| LTE 700 | 698–806 MHz |
| Cellular 850 | 824–894 MHz |
| PCS | 1900 MHz |
| AWS | 1700/2100 MHz |
| LTE/5G | 2600 MHz |
| 5G NR | 3500 MHz |

---

# Cellular Site Fundamentals

## Antenna Gain

Gain measures how effectively an antenna focuses RF energy. It is commonly expressed in dBi.

**Example:** 17 dBi

Higher gain generally means energy is concentrated more efficiently in specific directions.

## Azimuth

Azimuth refers to the compass direction an antenna faces.

- 0° = North
- 90° = East
- 180° = South
- 270° = West

## Mechanical Tilt

Mechanical tilt is the physical downward angle applied to an antenna.

**Example:** 4°

## Electrical Tilt

Electrical tilt is electronic beam steering performed within the antenna.

**Example:** 6°

Adjusting electrical tilt can significantly affect RF exposure patterns.

## EIRP

Effective Isotropic Radiated Power (EIRP) represents the effective radiated power after accounting for antenna gain and system losses. Higher EIRP generally produces larger RF exposure zones.

## Power Density

Power density is one of the most important concepts in SC6 assessments. It measures RF power distributed over a specific area.

**Unit:** W/m² (watts per square metre)

Compliance reports often display results as percentages of the SC6 limit. For example, **25% SC6** means the exposure equals 25% of the applicable limit.

## SAR (Specific Absorption Rate)

SAR measures how much RF energy is absorbed by body tissue.

**Unit:** W/kg

For cellular base-station and rooftop assessments, power-density-based evaluations are generally encountered more frequently than SAR calculations.

---

# Controlled vs Uncontrolled Environments

## Uncontrolled Environment

Areas accessible to the public.

Examples:

- Sidewalks
- Parking lots
- Streets
- Public rooftops

Exposure limits are more restrictive.

## Controlled Environment

Areas accessible only to trained personnel who are aware of RF hazards.

Examples:

- Tower platforms
- Restricted rooftops
- Maintenance areas
- Equipment compounds

Higher occupational exposure limits may apply in controlled environments.

---

# Near Field vs Far Field

## Near Field

The region close to an antenna.

Characteristics:

- Complex field behaviour
- Exposure may vary rapidly
- Often requires detailed modelling

## Far Field

The region sufficiently distant from an antenna.

Characteristics:

- More predictable behaviour
- Simpler calculations
- Easier exposure estimation

---

# Multiple Source Assessments

Most telecommunications sites contain more than one RF source. Examples include:

- Bell
- Rogers
- TELUS
- Public safety systems
- Microwave links

Safety Code 6 evaluates total exposure from all sources combined.

For example, contributions of 30%, 25%, 18%, and 12% produce a combined exposure of **85%** when expressed as applicable exposure-limit percentages. The assessment must account for the relevant sources and applicable limits.

---

# Compliance Review Methodology

A typical SC6 workflow is:

1. Collect site data
2. Review antenna parameters
3. Perform RF modelling
4. Calculate exposure percentages
5. Compare against SC6 limits
6. Determine compliance
7. Develop recommendations
8. Issue the final report

## Typical Inputs Found in RF Reports

| Input | Example |
| --- | --- |
| Antenna height | 35 m AGL (above ground level) |
| Transmit power | 40 W |
| Antenna gain | 17 dBi |
| Mechanical tilt | 4° |
| Electrical tilt | 6° |
| Frequencies | 700, 850, 1900, and 3500 MHz |

---

# Common Compliance Issues

## Public Exposure Exceeds Limits

Possible mitigation measures:

- Antenna relocation
- Power reduction
- Increased setback distance

## Worker Exposure Concerns

Possible mitigation measures:

- Restricted-access areas
- Worker procedures
- RF awareness training

## Rooftop Exposure Issues

Possible mitigation measures:

- Safety barriers
- Restricted-access zones
- Warning signage
- Locked access points

---

# RF Safety Signage

SC6 compliance reviews often involve safety-signage recommendations.

- **Notice:** Indicates RF equipment is present.
- **Warning:** Indicates elevated RF exposure levels.
- **Danger:** Indicates severe RF hazards where exposure limits may be exceeded.

---

# Real-World Examples

## Example 1: Rooftop Site

### Scenario

Three cellular sectors are installed on a downtown rooftop.

### Simulation Results

| Location | Exposure |
| --- | ---: |
| Sidewalk | 1% SC6 |
| Adjacent roof | 8% SC6 |
| In front of antenna | 165% SC6 |

### Assessment

- Sidewalk: Compliant
- Adjacent roof: Compliant
- In front of antenna: Non-compliant

### Recommendations

- Restrict access
- Install signage
- Establish controlled areas
- Create maintenance procedures

## Example 2: Multi-Carrier Tower

### Scenario

A tower hosts Bell, Rogers, TELUS, and public safety radio systems.

### Individual Contributions

| System | Exposure contribution |
| --- | ---: |
| Bell | 30% |
| Rogers | 25% |
| TELUS | 18% |
| Public safety | 12% |
| **Total** | **85%** |

### Assessment

The site remains compliant because the cumulative exposure is below 100%, assuming the reported contributions are calculated against the applicable limits and combined using the appropriate assessment method.

## Example 3: Worker Access

### Scenario

A technician must access a rooftop near operating antennas.

### Calculated Exposure

- 140% of the public limit
- 40% of the controlled-environment limit

### Assessment

The area is unsuitable for unrestricted public access. It may be acceptable under controlled-access procedures when the applicable occupational limits and required safety controls are satisfied.

---

# Frequently Asked Questions (FAQ)

## Is 5G covered by SC6?

Yes. Safety Code 6 covers frequencies from 3 kHz to 300 GHz, which includes frequencies used for 5G systems.

## What does 100% SC6 mean?

It means the exposure equals the applicable limit.

- 50% = Half the limit
- 75% = Three quarters of the limit
- 100% = At the limit
- 120% = Exceeds the limit

## What does “compliant” mean?

A location is compliant when calculated or measured exposure remains below the applicable SC6 limits.

## Why are results shown as percentages?

Percentages provide an easy way to compare exposure levels against applicable limits.

## What is the difference between EIRP and transmit power?

Transmit power is the power leaving the radio equipment. EIRP accounts for transmit power, antenna gain, and system losses. It represents the effective radiated power of the antenna system.

## Why does antenna tilt matter?

Tilt changes where RF energy is directed. Changing tilt can improve coverage, reduce rooftop exposure, or reduce exposure on nearby buildings.

## What is usually reviewed in a compliance report?

Typical review items include:

- Frequencies
- Antenna gains
- Antenna heights
- Transmit powers
- Azimuths
- Mechanical tilt
- Electrical tilt
- Exposure calculations
- Public exposure areas
- Occupational exposure areas
- Compliance conclusions

---

# Quick Reference Cheat Sheet

## Key Formula

Power density:

**S = P / A**

Where:

- **S** = power density
- **P** = power
- **A** = area

## Key Terms

| Term | Meaning |
| --- | --- |
| RF | Radio Frequency |
| EMF | Electromagnetic Field |
| SAR | Specific Absorption Rate |
| EIRP | Effective Isotropic Radiated Power |
| SC6 | Safety Code 6 |
| AGL | Above Ground Level |
| dBi | Antenna gain reference unit |
| W/m² | Power density unit |

---

# RF Modelling and Compliance Software

Safety Code 6 compliance assessments are typically supported by specialised RF modelling and prediction software.

These tools help engineers and compliance analysts:

- Model RF fields around antennas
- Predict exposure levels
- Determine compliance boundaries
- Identify controlled-access areas
- Evaluate cumulative exposure from multiple transmitters
- Generate compliance reports

## EMF Visual

One of the widely used RF compliance tools in North America.

Capabilities include:

- Safety Code 6 assessments
- FCC assessments
- Power density calculations
- Rooftop studies
- Tower studies
- Multi-carrier assessments
- Compliance-boundary generation

Many Canadian RF compliance reports are generated using EMF Visual or similar software.

## iBwave

Primarily used for wireless network design and propagation modelling.

Common applications include:

- Indoor cellular systems
- DAS systems
- Coverage prediction
- Network planning

## EDX SignalPro

Commonly used for:

- RF propagation studies
- Coverage analysis
- Interference analysis
- Wireless network planning

Some organizations also use it to support RF exposure evaluations.

## Atoll

Widely used cellular network planning software.

Common applications include:

- LTE design
- 5G design
- Sector analysis
- Coverage analysis

Exposure assessments may use data exported from Atoll models.

## In-House Modelling Tools

Many consulting firms and wireless carriers use proprietary spreadsheets, GIS tools, and internal modelling platforms alongside commercial RF software.

## What an SC6 Analyst Typically Does with the Software

In most RF compliance roles, the analyst is not developing the software itself. Common responsibilities include:

- Importing site designs
- Verifying antenna data
- Reviewing modelling assumptions
- Validating transmit power levels
- Reviewing calculated exposure maps
- Checking compliance boundaries
- Verifying cumulative exposure calculations
- Generating final reports
- Recommending mitigation measures

Understanding the assumptions, inputs, and interpretation of the results is essential for performing accurate and defensible Safety Code 6 compliance assessments.
