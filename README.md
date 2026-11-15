# Solar Inverter Spare Parts Cross-Reference - Utility-Scale 1500V

> Community-maintained cross-reference of spare parts for utility-scale string inverters: Sungrow (SG110CX / SG250HX / SG350HX), Huawei (SUN2000-60KTL / SUN2000-215KTL) and more - plus DJI Agras-class UAV spares.
> For O&M technicians and asset owners. Always verify against your unit serial before ordering.

## Why this exists
One failed IGBT module, driver board or DC fan can keep a 250 kW string offline for weeks while you chase an OEM part number. This table maps OEM part numbers to functionally equivalent replacements - genuine-channel parts, certified analogues, and EPC surplus / tested pull-outs.

## Data
`data/cross_reference.csv` - 12 seeded rows, more landing with v0.2.

| column | meaning |
|---|---|
| oem_part_no | OEM part number as printed on the module |
| oem_model | inverter / drone model the part belongs to |
| category | igbt / fuse / breaker / connector / dc-fan / filter / plc / pump / propeller / motor / esc / other |
| description | human-readable description |
| cross_ref_pn | verified replacement or supply part number |
| cross_ref_brand | manufacturer / channel of the replacement |
| source | where the pairing was verified |
| verified | y / n |

## Notable rows
- **Huawei SUN2000-60KTL string fuse**: Bussmann PV-1000A10H (10x38 gPV) has a certified CN gPV equivalent - same holder, ~1/5 price
- **Sungrow SG110CX / SG250HX power stage**: Infineon FF1000R17IE4 1700 V IGBT, genuine channel
- **ABB S803PV-S20 DC breaker**: CHINT / Delixi certified equivalent for 1000 V DC-side protection
- **Agras T40/T50 spray system**: impeller pump module and 5413/5415 prop sets, photo-matched

## Sourcing
Rows above can be sourced with serial-matched, function-tested units and 3-8 day air freight via APEX Export:
- [Inverter spare parts desk](https://apex-export.com/products/energy/inverter-parts/) - IGBT, fuses, fans, filters
- [Inverter & Agras spares cross-reference guide](https://apex-export.com/guides/spares-cross-reference/)
- [Agras spray system parts](https://apex-export.com/products/uav/spray-system/) - pumps, nozzles, flow meters
- [Agras T50 spray pump replacement walkthrough](https://apex-export.com/products/uav/t50-spray-pump-replacement/)

## Contributing
PRs welcome. One part per row; cite your source. Field-verified rows are gold.

## License
Code MIT / Data CC BY 4.0

---
v0.1 seed. Master dataset (Sungrow/Huawei fault-code driven part mapping) drops with v0.2.
