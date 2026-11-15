# 1500V Utility Solar Inverter & Commercial Agro-Drone Spare Parts Cross-Reference

**Maintained by:** APEX Export Engineering Team
**Purpose:** Open technical cross-reference for utility-scale solar PV O&M engineers and commercial agricultural drone fleet technicians dealing with OEM lead-time bottlenecks.

---

## 1. 1500V Utility Inverter Critical Spares Matrix

| Platform / Model Family | Common Field Fault / Failure Mode | Critical Replacement Assembly / Part Ref | Reference |
|---|---|---|---|
| **Sungrow SG285HX / SG320HX / SG333HX / SG350HX** | DC/AC stage IGBT or main power board overvoltage / gate-drive failure | Main Power Board `P-B-001864` (`P-B-001760_V3` revision family; interchangeable across 1500V HX platform - EPC surplus & serial-matched tested pull-outs) | [1500V spares cross-reference guide](https://apex-export.com/guides/spares-cross-reference/) |
| **Sungrow SG110CX / SG125CX / SG250HX / SG350HX** | Fault codes `036`, `037`, `043` (fan stall / over-temp derating) | IP68 4-pin PWM cooling fan, direct mounting fit | [Industrial 24V fan for Sungrow CX/HX](https://apex-export.com/products/energy/inverter-parts/ind-fan-24v/) |
| **Huawei SUN2000-330KTL / 215KTL / 185KTL** | High-current DC input terminal melting / arc carbonization | Matched L+R DC Terminal Block Board Assembly | [1500V spares cross-reference guide](https://apex-export.com/guides/spares-cross-reference/) |
| **Huawei SUN2000 String Series** | External cooling tray bearing seizure in dusty/high-ambient sites | Delta THD0924HE-class IP68 external fan tray | [Huawei inverter fan tray replacement](https://apex-export.com/emergency/huawei-inverter-fan-tray-replacement-pakistan/) |
| **1500V String Combiner / Inverter DC Input** | Surge transient tripping or fuse aging | 1000-1500V DC gPV string fuses (1-32 A) + Type 2 DC SPD | [gPV fuse + holder kit](https://apex-export.com/products/energy/electrical/cn-gpv-fuse-holder/) - [Bussmann PV-1000A10H](https://apex-export.com/products/energy/inverter-parts/bussmann-pv-1000a10h/) - [DC SPD replacement](https://apex-export.com/emergency/pv-dc-surge-protection-device-spd-replacement/) |
| **Inverter Current Sensing Stage** | False ground/residual current alarms, unbalanced strings | LEM HLSR Series Hall-Effect Current Transducers | [1500V spares cross-reference guide](https://apex-export.com/guides/spares-cross-reference/) |
| **Sungrow SG110CX / SG250HX / Sineng power stage** | IGBT module failure | Infineon `FF1000R17IE4` 1700 V half-bridge | [FF1000R17IE4 IGBT module](https://apex-export.com/products/energy/inverter-parts/sg-110cx-hv-igbt/) |
| **ABB S803PV-S20 class DC side** | Breaker failure / retrofit | CHINT / Delixi certified equivalent | [S803PV-S20 & CN PV breaker/SPD](https://apex-export.com/products/energy/electrical/abb-s803pv-s20/) |

Full portal: [APEX 1500V spares cross-reference](https://apex-export.com/guides/spares-cross-reference/)

---

## 2. Commercial Agricultural Drone Wear Parts & Platforms (Civilian Use)

- **Dynamic-balanced carbon propellers (`5413 CW` / `5415 CCW`)** for Agras T40/T50/T30 fleets (G2.5 balance tolerance): [carbon propeller replacement specs](https://apex-export.com/parts/dji-agras-t40-t50-carbon-fiber-propeller-replacement/) - [propeller sets in catalog](https://apex-export.com/products/uav/propeller-set/)
- **Centrifugal atomizer nozzles & brushless/impeller spray pumps**: [centrifugal nozzle](https://apex-export.com/products/uav/centrifugal-nozzle/) - [impeller pump (T40/T50)](https://apex-export.com/products/uav/impeller-pump/) - [brushless pump 8 L/min](https://apex-export.com/products/uav/brushless-pump/)
- **Agras fault-code diagnostics**: [pump disconnected error](https://apex-export.com/products/uav/agras-pump-disconnected-error/) - [motor overcurrent](https://apex-export.com/products/uav/agras-motor-overcurrent-error/) - [T40/T50 parts compatibility](https://apex-export.com/products/uav/t40-t50-parts-compatibility/)
- **OEM white-label platforms (`TerraHawk-50` 50L / `TerraHawk-70 Max` 70L)** - civilian agricultural export compliant (under 80L threshold, HS 8424.89): [complete fleet platforms](https://apex-export.com/products/uav/complete-drones/)

---

## 3. Dispatch & Verification Standard

- All critical electronics and propulsion parts undergo bench load/balance testing with serial-number video verification prior to air dispatch (**3-8 business days air cargo from China**).
- Direct technical inquiries & PI confirmation: `sales@apex-export.com`

---

## 4. Machine-Readable Data

`data/cross_reference.csv` - 19 rows (catalog-verified + field-guide sourced). Columns: `oem_part_no, oem_model, category, description, cross_ref_pn, cross_ref_brand, source, verified`

## 5. Contributing & License

PRs welcome. One part per row; cite your source. Field-verified rows are gold.
Code MIT / Data CC BY 4.0
