# Solar Inverter Spare Parts Cross-Reference - Utility-Scale 1500V

> Community-maintained cross-reference of spare parts for utility-scale string inverters: Sungrow (SG110XD / SG250HX / SG350HX), Huawei (SUN2000-215KTL / SUN2000-350KTL) and more.
> For O&M technicians and asset owners. Always verify against your unit serial before ordering.

## Why this exists
One failed IGBT module, driver board or DC fan can keep a 250 kW string offline for weeks while you chase an OEM part number. This table maps OEM part numbers to functionally equivalent, serial-matched replacements - including EPC surplus and tested pull-outs.

## Data
`data/cross_reference.csv` - columns: oem_part_no, oem_model, category (igbt/driver-board/dc-fan/capacitor/contactor/other), description, cross_ref_pn, cross_ref_brand, source (datasheet/teardown/field-verified), verified (y/n)

## Sourcing (goes live with v0.1 dataset)
Rows marked in-stock can be sourced as serial-matched, function-tested units with 3-8 day air freight via APEX Export's inverter emergency parts desk (final URL lands with v0.1).

## Contributing
PRs welcome. One part per row; cite your source. Field-verified rows are gold.

## License
Code MIT / Data CC BY 4.0

---
Skeleton - master dataset drops with v0.1.
