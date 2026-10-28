# US Residential Electrical, Solar PV, Battery Backup & Generator Sizing Formulas (NEC Reference)

A practical open reference of governing electrical engineering equations, National Electrical Code (NEC / NFPA 70) continuous-load derating factors, motor inrush surge multipliers, and battery depth-of-discharge (DoD) models used across [CalcMyPower.com](https://calcmypower.com/).

Explore the complete interactive tool suite on the [CalcMyPower Calculators Directory](https://calcmypower.com/calculators).

## Live Interactive Engineering Calculators (15 Tools)

All interactive implementations below run 100% client-side with transparent formulas and worked residential and RV scenarios:

### Appliance Energy & Utility Billing
* [Electricity Usage Calculator: Appliance kWh & Cost Estimator](https://calcmypower.com/electricity-use-calculator): Compute daily, monthly, and annual kilowatt-hour consumption from appliance running watts and operating duty cycles.
* [Electricity Cost Calculator: Monthly Utility Bill Estimator](https://calcmypower.com/electricity-cost-calculator): Model effective tiered utility rates, volumetric kWh charges, fixed meter fees, and seasonal fuel riders.

### Backup Generators & Outage Planning
* [Generator Size Calculator: Running & Surge Wattage Chart](https://calcmypower.com/generator-size-calculator): Size portable inverter, dual-fuel, and whole-house standby generators with single-motor starting surge deltas and 25% continuous headroom.
* [Generator Fuel Consumption Calculator (Gasoline, Propane & Diesel Gal/Hr)](https://calcmypower.com/generator-fuel-consumption-calculator): Estimate fuel burn rates in gallons per hour, runtimes per tank, and operating costs across 25%, 50%, 75%, and 100% electrical loads.

### Battery Banks, Inverters & UPS Runtime
* [Battery Capacity Calculator: Amp Hours & Watt Hours](https://calcmypower.com/battery-capacity-calculator): Size 12V, 24V, and 48V battery banks with chemistry-specific depth of discharge (LiFePO4 vs AGM lead-acid) and series-parallel wiring.
* [UPS Runtime Calculator: Battery Backup Time](https://calcmypower.com/ups-battery-backup-calculator): Calculate uninterruptible power supply reserve runtime for home office PCs, WiFi routers, CPAP medical units, and network switches.
* [Inverter Size Calculator (Continuous Watts & Surge VA Rating)](https://calcmypower.com/inverter-size-calculator): Determine continuous inverter wattage, motor surge margins, DC battery cable gauge (AWG), and fuse ratings.

### Circuit Amperage, Wattage & Voltage Drop (NEC Article 210 & 240)
* [Watts to Amps Calculator: Convert W to A Fast](https://calcmypower.com/watts-to-amps-calculator): Convert real power to current across DC, 120V/240V single-phase AC, and balanced 3-phase circuits with NEC conductor ampacity tables.
* [Amps to Watts Calculator: Convert A to W Fast](https://calcmypower.com/amps-to-watts-calculator): Convert circuit amperage to continuous real power with 80% thermal safety breaker limits.
* [Voltage Drop Calculator: Wire Gauge & Distance](https://calcmypower.com/voltage-drop-calculator): Calculate conductor voltage drop and percentage loss for copper and aluminum wire runs across NEC 3% branch circuit limits.
* [Three-Phase Power Calculator (kW, kVA, kVAR & Line Current)](https://calcmypower.com/three-phase-power-calculator): Solve balanced 208V, 240V, and 480V delta/wye circuits for real power, apparent power, reactive power, and power factor.

### Solar PV Array & Charge Controller Sizing (NEC Article 690)
* [Solar System Size Calculator (Array kW & Panel Count)](https://calcmypower.com/solar-system-size-calculator): Calculate required rooftop PV array kilowatt capacity, module count, and roof surface area from annual kWh utility consumption and regional peak sun hours (PSH).
* [Solar Charge Controller Calculator (MPPT vs PWM Amps & Cold Voc Check)](https://calcmypower.com/solar-charge-controller-calculator): Size MPPT and PWM charge controllers with NEC 125% continuous output current and sub-zero open-circuit voltage (Voc) temperature corrections.
* [Solar Battery Bank Sizing Calculator (Days of Autonomy & DoD)](https://calcmypower.com/solar-battery-calculator): Size off-grid solar storage banks in kWh and Amp-hours across multi-day weather autonomy periods.
* [Solar Panel Tilt Angle Calculator (Latitude & Seasonal Optimization)](https://calcmypower.com/solar-panel-tilt-calculator): Calculate true south tilt angles for fixed, seasonal, and roof pitch orientations based on geographical latitude.

## Authoritative Sizing Guides & Reference Manuals (10 Guides)

* [What Size Generator Do I Need to Run My House?](https://calcmypower.com/what-size-generator-do-i-need-for-my-house): Comprehensive sizing methodology based on essential circuits and motor locked-rotor amps rather than misleading square footage approximations.
* [What Size Generator Do I Need to Run a Refrigerator?](https://calcmypower.com/what-size-generator-to-run-a-refrigerator): Compressor surge benchmarks, starting delta watts, and simultaneous outage circuit planning.
* [What Does Ah Mean on a Battery? Amp-Hours Explained](https://calcmypower.com/what-does-ah-mean-on-a-battery): Electrical charge definition, conversion from Ah to Watt-hours (Wh), Peukert effect, and discharge ratings (C-rate).
* [What Is a Watt-Hour (Wh)? Watts vs. Watt-Hours Explained](https://calcmypower.com/what-is-a-watt-hour): Instantaneous power (Watts) vs accumulated energy (Watt-hours) and utility meter billing fundamentals.
* [How Long Will a 100Ah Battery Last? 12V Appliance Runtime Guide](https://calcmypower.com/how-long-will-a-100ah-battery-last): Real-world runtime benchmarks for LiFePO4 and lead-acid deep cycle batteries powering refrigerators, CPAP machines, and TVs.
* [Solar Panels in Series vs Parallel: Wiring, Voltage & Current Explained](https://calcmypower.com/solar-panels-series-vs-parallel): High-voltage series stringing vs high-current parallel array tradeoffs, MPPT window matching, and shading resistance.
* [How Much Energy Does a Solar Panel Produce? 400W Panel Examples](https://calcmypower.com/how-much-energy-does-a-solar-panel-produce): Realistic daily and monthly kilowatt-hour yields across summer and winter irradiance profiles.
* [How Many Amp Hours Do I Need for a Battery Bank?](https://calcmypower.com/how-many-amp-hours-do-i-need): Step-by-step battery bank sizing formula accounting for daily load profiles, system voltage, autonomy days, and chemistry DoD limits.
* [How Long Does It Take to Charge a Battery with Solar Panels?](https://calcmypower.com/how-long-does-it-take-to-charge-a-battery-with-solar-panels): MPPT charge efficiency, solar array wattage, battery state-of-charge curves, and solar irradiance math.
* [How Many Watts on a 15-Amp or 20-Amp Circuit? Continuous Limits & Sizing](https://calcmypower.com/how-many-watts-can-a-15-amp-or-20-amp-circuit-handle): Continuous load thresholds, NEC 80% breaker rules, 14 AWG vs 12 AWG copper wire ampacities, and high-wattage appliance budgeting.

## Governing Equations & Engineering Reference

### 1. NEC 125% Continuous Load Rule (NEC 210.20(A))

Branch-circuit overcurrent protection devices (circuit breakers and fuses) must be sized for 100% of non-continuous loads plus 125% of continuous loads (loads operating for 3 hours or longer):

```text
I_continuous_max = I_breaker_rating * 0.80
P_continuous_safe = V_circuit * I_breaker_rating * 0.80 * Power_Factor
I_breaker_required = I_continuous_load * 1.25
```

Standard Residential Overcurrent Limits (120V / 240V Single Phase, Unity PF):
* 15A @ 120V (14 AWG Cu): 1,800W Maximum Surge | 1,440W Continuous Safe Limit
* 20A @ 120V (12 AWG Cu): 2,400W Maximum Surge | 1,920W Continuous Safe Limit
* 30A @ 240V (10 AWG Cu): 7,200W Maximum Surge | 5,760W Continuous Safe Limit
* 50A @ 240V (6 AWG Cu): 12,000W Maximum Surge | 9,600W Continuous Safe Limit
* 200A @ 240V Main Service: 48,000W Maximum Surge | 38,400W Continuous Safe Limit

### 2. Motor Starting Inrush Surge & Generator Sizing (NEC Article 430)

Single-phase induction motor compressors draw 3x to 6x full-load operating current during locked-rotor startup:

```text
P_starting_delta = P_starting_peak - P_running
P_running_total = Sum(P_running_i)
P_surge_max_delta = Max(P_starting_delta_i)
P_generator_required = (P_running_total + P_surge_max_delta) * 1.25
```

The 1.25 multiplier ensures the generator alternator operates within its continuous sweet spot (70% to 80% capacity) rather than running in thermal overload.

### 3. Battery Usable Energy & Inverter Runtime

Battery capacity rated in Amp-hours (Ah) must be converted to nominal Watt-hours (Wh) and derated by usable Depth of Discharge (DoD) and DC-to-AC inverter conversion efficiency:

```text
E_nominal_Wh = V_nominal_DC * Capacity_Ah
E_usable_Wh = E_nominal_Wh * DoD_factor * Inverter_Efficiency
Runtime_Hours = E_usable_Wh / P_AC_load_watts
```

Depth of Discharge (DoD) & Efficiency baselines:
* Lithium Iron Phosphate (LiFePO4): 90% to 95% DoD, 90% to 95% Inverter Efficiency
* Sealed Lead-Acid / AGM / Gel: 50% DoD, 80% to 85% Inverter Efficiency
* Flooded Lead-Acid: 50% DoD, 75% to 80% Inverter Efficiency (subject to Peukert capacity loss at high C-rates)

### 4. Solar PV Array & MPPT Charge Controller Sizing (NEC Article 690)

Charge controller output current rating must handle continuous solar generation plus the mandatory NEC 125% safety margin:

```text
I_controller_nominal = P_array_STC / V_battery_nominal
I_controller_planning = I_controller_nominal * 1.25
```

Cold-Weather Open-Circuit Voltage Correction (NEC 690.7):
```text
Voc_cold = Voc_STC * [1 + Alpha_Voc * (T_min_record - 25)]
```
Where Alpha_Voc is the manufacturer temperature coefficient in percentage or volts per degree Celsius (typically -0.28%/C to -0.35%/C), and T_min_record is the lowest historical ambient temperature.

### 5. Voltage Drop Formulation (Ohm's Law & Conductor Resistivity)

To comply with NEC Informational Note 210.19(A) recommending maximum 3% branch voltage drop and 5% combined feeder/branch voltage drop:

Single-Phase AC / DC:
```text
VD = 2 * I * (Length_ft / 1000) * R_conductor_per_1000ft
```

Balanced Three-Phase AC:
```text
VD = sqrt(3) * I * (Length_ft / 1000) * R_conductor_per_1000ft
VD_percentage = (VD / V_source) * 100
```

Where R_conductor is the DC or AC resistance from NEC Chapter 9, Table 8 (solid/stranded uncoated copper or aluminum).

## Citation & Standards

All formulations and derating methodologies are grounded in the following technical standards:
* NFPA 70: National Electrical Code (NEC), Articles 210 (Branch Circuits), 220 (Branch-Circuit, Feeder, and Service Load Calculations), 240 (Overcurrent Protection), 430 (Motors), and 690 (Solar Photovoltaic Systems).
* IEEE Standard 1013: IEEE Recommended Practice for Sizing Lead-Acid Batteries for Stand-Alone Photovoltaic Systems.
* NREL: National Renewable Energy Laboratory PVWatts Irradiance Models.
* U.S. Energy Information Administration (EIA) Residential Electricity Average Rates.

Maintained by [CalcMyPower](https://calcmypower.com/) for engineers, electricians, solar installers, and homeowners.
