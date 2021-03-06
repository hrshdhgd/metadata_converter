
# Type: rea_plateauMeasurementFieldData_in




URI: [neon:ReaPlateauMeasurementFieldDataIn](https://data.neonscience.org/ReaPlateauMeasurementFieldDataIn)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[ReaPlateauMeasurementFieldDataIn&#124;uid:string%20%3F;remarks:string%20%3F;collectDate:time%20%3F;stationID:string%20%3F;waterTemp:double%20%3F;startDate:time%20%3F;fulcrumVersion:string%20%3F;platformInfo:string%20%3F;plateauFieldDataQF:string%20%3F;specificConductanceRep1:double%20%3F;specificConductanceRep2:double%20%3F;specificConductanceRep3:double%20%3F;specificConductanceRep4:double%20%3F;specificConductanceRep5:double%20%3F])

## Attributes


### Own

 * [collectDate](collectDate.md)  <sub>OPT</sub>
    * Description: Date of the collection event
    * range: [Time](types/Time.md)
 * [fulcrumVersion](fulcrumVersion.md)  <sub>OPT</sub>
    * Description: Version of the Fulcrum application used during data entry
    * range: [String](types/String.md)
 * [plateauFieldDataQF](plateauFieldDataQF.md)  <sub>OPT</sub>
    * Description: Data quality flag for plateau field data
    * range: [String](types/String.md)
 * [platformInfo](platformInfo.md)  <sub>OPT</sub>
    * Description: Operating System and browser information (where applicable) of computer used during data entry
    * range: [String](types/String.md)
 * [remarks](remarks.md)  <sub>OPT</sub>
    * Description: Technician notes; free text comments accompanying the record
    * range: [String](types/String.md)
 * [specificConductanceRep1](specificConductanceRep1.md)  <sub>OPT</sub>
    * Description: Conductivity auto-corrected to 25 degrees C measurement replicate 1
    * range: [Double](types/Double.md)
 * [specificConductanceRep2](specificConductanceRep2.md)  <sub>OPT</sub>
    * Description: Conductivity auto-corrected to 25 degrees C measurement replicate 2
    * range: [Double](types/Double.md)
 * [specificConductanceRep3](specificConductanceRep3.md)  <sub>OPT</sub>
    * Description: Conductivity auto-corrected to 25 degrees C measurement replicate 3
    * range: [Double](types/Double.md)
 * [specificConductanceRep4](specificConductanceRep4.md)  <sub>OPT</sub>
    * Description: Conductivity auto-corrected to 25 degrees C measurement replicate 4
    * range: [Double](types/Double.md)
 * [specificConductanceRep5](specificConductanceRep5.md)  <sub>OPT</sub>
    * Description: Conductivity auto-corrected to 25 degrees C measurement replicate 5
    * range: [Double](types/Double.md)
 * [startDate](startDate.md)  <sub>OPT</sub>
    * Description: The start date-time or interval during which an event occurred
    * range: [Time](types/Time.md)
 * [stationID](stationID.md)  <sub>OPT</sub>
    * Description: Identifier for station where sample was collected
    * range: [String](types/String.md)
 * [uid](uid.md)  <sub>OPT</sub>
    * Description: Unique ID within NEON database; an identifier for the record
    * range: [String](types/String.md)
 * [waterTemp](waterTemp.md)  <sub>OPT</sub>
    * Description: Temperature of water (C)
    * range: [Double](types/Double.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | neon:rea_plateauMeasurementFieldData_in |
| **In Subsets:** | | DP0.20190.001 |

