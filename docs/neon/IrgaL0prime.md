
# Type: irga_L0prime




URI: [neon:IrgaL0prime](https://data.neonscience.org/IrgaL0prime)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[IrgaL0prime&#124;idx:integer%20%3F;diag:integer%20%3F;tempBloc:double%20%3F;tempCellIn:double%20%3F;tempCellOut:double%20%3F;presAtmBox:double%20%3F;presGageCell:double%20%3F;pwrH2OSamp:double%20%3F;pwrH2ORef:double%20%3F;asrpH2O:double%20%3F;rhoMoleH2O:double%20%3F;fdMoleH2O:double%20%3F;pwrCO2Samp:double%20%3F;pwrCO2Ref:double%20%3F;asrpCO2:double%20%3F;rhoMoleCO2:double%20%3F;fdMoleCO2:double%20%3F;diag2:integer%20%3F;poteCool:double%20%3F;ssiCO2:double%20%3F;ssiH2O:double%20%3F;tempMean:string%20%3F;presSum:string%20%3F;qfIrgaHead:integer%20%3F;qfIrgaTempOut:integer%20%3F;qfIrgaTempIn:integer%20%3F;qfIrgaAux:integer%20%3F;qfIrgaPres:integer%20%3F;qfIrgaChop:integer%20%3F;qfIrgaDetc:integer%20%3F;qfIrgaPll:integer%20%3F;qfIrgaSync:integer%20%3F;qfIrgaAgc:integer%20%3F])

## Attributes


### Own

 * [asrpCO2](asrpCO2.md)  <sub>OPT</sub>
    * Description: Electromagnetic absorptance (asrp) in the carbondioxide (CO2) absorption band
    * range: [Double](types/Double.md)
 * [asrpH2O](asrpH2O.md)  <sub>OPT</sub>
    * Description: Electromagnetic absorptance (asrp) in the water vapor (H2O) absorption band
    * range: [Double](types/Double.md)
 * [diag](diag.md)  <sub>OPT</sub>
    * Description: Diagnostic value (diag), output as a 32 bit integer Bit assignment according to NEONDOC000807 (L0 prime processing ATBD)
    * range: [Integer](types/Integer.md)
 * [diag2](diag2.md)  <sub>OPT</sub>
    * Description: Diagnostic value (diag) number 2 (2; sync clocks)
    * range: [Integer](types/Integer.md)
 * [fdMoleCO2](fdMoleCO2.md)  <sub>OPT</sub>
    * Description: Dry mole fraction (fd) on molar basis (Mole) of carbondioxide (CO2), synonymous with mixing ratio
    * range: [Double](types/Double.md)
 * [fdMoleH2O](fdMoleH2O.md)  <sub>OPT</sub>
    * Description: Dry mole fraction (fd) on molar basis (Mole) of water vapor (H2O), synonymous with mixing ratio
    * range: [Double](types/Double.md)
 * [idx](idx.md)  <sub>OPT</sub>
    * Description: Index value (idx)
    * range: [Integer](types/Integer.md)
 * [poteCool](poteCool.md)  <sub>OPT</sub>
    * Description: Electric potential (pote) at the cooler (Cool)
    * range: [Double](types/Double.md)
 * [presAtmBox](presAtmBox.md)  <sub>OPT</sub>
    * Description: Pressure (pres), measured as atmospheric (Atm) pressure of the control box (Box), synonymous with absolute pressure or total pressure (at sea level the standard atmospheric pressure is 101.325 kPa)
    * range: [Double](types/Double.md)
 * [presGageCell](presGageCell.md)  <sub>OPT</sub>
    * Description: Pressure (pres), measured as differential against ambient pressure, synonymous with gage (Gage) pressure (at sea level the gage pressure equals total pressure minus 101.325 kPa), between the optical cell (Cell) and the control box
    * range: [Double](types/Double.md)
 * [presSum](presSum.md)  <sub>OPT</sub>
    * Description: Total pressure (LI-7550 box pressure + head pressure)
    * range: [String](types/String.md)
 * [pwrCO2Ref](pwrCO2Ref.md)  <sub>OPT</sub>
    * Description: Power (pwr) of the carbondioxide (CO2) signal in the absorption band used for reference (Ref)
    * range: [Double](types/Double.md)
 * [pwrCO2Samp](pwrCO2Samp.md)  <sub>OPT</sub>
    * Description: Power (pwr) of the carbondioxide (CO2) signal in the absorption band used for sampling (Samp)
    * range: [Double](types/Double.md)
 * [pwrH2ORef](pwrH2ORef.md)  <sub>OPT</sub>
    * Description: Power (pwr) of the water vapor (H2O) signal in the absorption band used for reference (Ref)
    * range: [Double](types/Double.md)
 * [pwrH2OSamp](pwrH2OSamp.md)  <sub>OPT</sub>
    * Description: Power (pwr) of the water vapor (H2O) signal in the absorption band used for sampling (Samp)
    * range: [Double](types/Double.md)
 * [qfIrgaAgc](qfIrgaAgc.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL10: AGC)
    * range: [Integer](types/Integer.md)
 * [qfIrgaAux](qfIrgaAux.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL04: Aux input)
    * range: [Integer](types/Integer.md)
 * [qfIrgaChop](qfIrgaChop.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL06: Chopper)
    * range: [Integer](types/Integer.md)
 * [qfIrgaDetc](qfIrgaDetc.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL07: Detector)
    * range: [Integer](types/Integer.md)
 * [qfIrgaHead](qfIrgaHead.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL01: Head detect)
    * range: [Integer](types/Integer.md)
 * [qfIrgaPll](qfIrgaPll.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL08: PLL)
    * range: [Integer](types/Integer.md)
 * [qfIrgaPres](qfIrgaPres.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL05: Differential pressure)
    * range: [Integer](types/Integer.md)
 * [qfIrgaSync](qfIrgaSync.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL09: Sync)
    * range: [Integer](types/Integer.md)
 * [qfIrgaTempIn](qfIrgaTempIn.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL03: Inlet temperature)
    * range: [Integer](types/Integer.md)
 * [qfIrgaTempOut](qfIrgaTempOut.md)  <sub>OPT</sub>
    * Description: Sensor flag (fL02: Outlet temperature)
    * range: [Integer](types/Integer.md)
 * [rhoMoleCO2](rhoMoleCO2.md)  <sub>OPT</sub>
    * Description: Density (rho) on molar basis (Mole) of carbondioxide (CO2), synonymous with number density
    * range: [Double](types/Double.md)
 * [rhoMoleH2O](rhoMoleH2O.md)  <sub>OPT</sub>
    * Description: Density (rho) on molar basis (Mole) of water vapor (H2O), synonymous with number density
    * range: [Double](types/Double.md)
 * [ssiCO2](ssiCO2.md)  <sub>OPT</sub>
    * Description: Signal strength indicator (ssi) for the carbondioxide (CO2) absorption band
    * range: [Double](types/Double.md)
 * [ssiH2O](ssiH2O.md)  <sub>OPT</sub>
    * Description: Signal strength indicator (ssi) for the water vapor (H2O) absorption band
    * range: [Double](types/Double.md)
 * [tempBloc](tempBloc.md)  <sub>OPT</sub>
    * Description: Temperature (temp) of the instrument block (Bloc)
    * range: [Double](types/Double.md)
 * [tempCellIn](tempCellIn.md)  <sub>OPT</sub>
    * Description: Temperature (temp) of the optical cell (Cell) inlet (In) thermocouple
    * range: [Double](types/Double.md)
 * [tempCellOut](tempCellOut.md)  <sub>OPT</sub>
    * Description: Temperature (temp) of the optical cell (Cell) outlet (Out) thermocouple
    * range: [Double](types/Double.md)
 * [tempMean](tempMean.md)  <sub>OPT</sub>
    * Description: Cell temperature (weighted average of head inlet and outlet temperature)
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | neon:irga_L0prime |
| **In Subsets:** | | IP0.00016.001 |

