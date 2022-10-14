---
  title: Coordination
---

--8<-- "includes/abbreviations.md"

### Auto Release

"Next" Coordination is a procedure where the SY TWR controller gives a heads-up to the SY TCU controller about an impending departure. The SY TCU controller will respond by assigning a heading to the aircraft, for the SY TWR controller to pass on with their takeoff clearance.

!!! example
    SY TWR -> SY TCU: "Next, ABC"  
    SY TCU -> SY TWR: "ABC, Heading 030"  
    SY TWR -> SY TCU: "Heading 030, ABC"  
    SY TWR -> ABC: "ABC, Assigned heading right 030, Runway 34R, Cleared for Takeoff"  
    ABC -> SY TWR: "Right heading 030, Runway 34R, Cleared for Takeoff"  
    `AIP GEN 3.4 6.16.6`

"Next" Coordination to SY TCU is additionally required for:  
    a) Departures to YSBK  
    b) Jets departing 16L via WOL, except during SODPROPS  
    c) after a go-around, the next departure from that runway

The SY TCU controller can suspend/resume Auto Release at any time, with the concurrence of SY TWR.

"Next" Coordination to SY TCU is not required for aircraft assigned a **Procedural SID** and the Standard Assignable Level.

#### Standard Assignable Departure Headings

Aircraft that have been assigned the **Radar SID** must be assigned a heading on departure. “Next” coordination is not required to the SY TCU controller when the departing aircraft has been assigned the standard assignable level, and has been cleared via the headings listed below:

| Runway | Jet | Non-Jet 
| ----------------- | -------------- | ---------------- |
| 07                | 070         | 020, 110       |
| 16L                | 125          | 125 (RWY 25 in use), 090 (RWY 25 not in use) |
| 16R               | 170         | 210         |
| 25                | 300, 240          | 020, 210, 240 |
| 34L                | 290          | 230 |
| 34R                | 030, 070          | 350 |

!!! information
    Where multiple standard assignable headings are available, assign the heading most suitable for the aircraft's direction of flight

#### Standard Assignable Departure Levels

Jets: `A050`
Non-jets: `A030`

### Ground Operations
As per this (link) diagram, ADC has Responsibility of the Runways, meaning SMC must always coordinate with ADC to allow aircraft to cross runways whilst taxiing. SMC may request, or ADC may elect, to release certain runways to the SMC controller, so they may let aircraft cross the runway without coordination (For example, Releasing runway 07/25 to SMC whilst PROPS are in progress.) This Release may also be cancelled at the controller's discretion.