
# Type: inv_fieldData_pub




URI: [neon:InvFieldDataPub](https://data.neonscience.org/InvFieldDataPub)


![img](http://yuml.me/diagram/nofunky;dir:TB/class/[InvFieldDataPub&#124;uid:string%20%3F;domainID:string%20%3F;siteID:string%20%3F;remarks:string%20%3F;recordedBy:string%20%3F;eventID:string%20%3F;decimalLatitude:double%20%3F;decimalLongitude:double%20%3F;geodeticDatum:string%20%3F;coordinateUncertainty:double%20%3F;elevation:double%20%3F;elevationUncertainty:double%20%3F;sampleID:string%20%3F;collectDate:time%20%3F;startDate:time%20%3F;samplingProtocolVersion:string%20%3F;collectedBy:string%20%3F;habitatType:string%20%3F;benthicArea:double%20%3F;samplerType:string%20%3F;substratumSizeClass:string%20%3F;ponarDepth:double%20%3F;snagLength:double%20%3F;snagDiameter:double%20%3F;sampleCode:string%20%3F;dataQF:string%20%3F;geneticSampleID:string%20%3F;aquaticSiteType:string%20%3F;geneticSampleCode:string%20%3F;samplingImpractical:string%20%3F;namedLocation:string%20%3F;dnaSnagDiameter:double%20%3F;dnaSnagLength:double%20%3F])

## Attributes


### Own

 * [aquaticSiteType](aquaticSiteType.md)  <sub>OPT</sub>
    * Description: Type of aquatic site, includes lake, river or stream
    * range: [String](types/String.md)
 * [benthicArea](benthicArea.md)  <sub>OPT</sub>
    * Description: Area of the benthos sampled
    * range: [Double](types/Double.md)
 * [collectDate](collectDate.md)  <sub>OPT</sub>
    * Description: Date of the collection event
    * range: [Time](types/Time.md)
 * [collectedBy](collectedBy.md)  <sub>OPT</sub>
    * Description: An identifier for the technician who collected the sample or specimen
    * range: [String](types/String.md)
 * [coordinateUncertainty](coordinateUncertainty.md)  <sub>OPT</sub>
    * Description: The horizontal distance (in meters) from the given decimalLatitude and decimalLongitude describing the smallest circle containing the whole of the Location. Zero is not a valid value for this term
    * range: [Double](types/Double.md)
 * [dataQF](dataQF.md)  <sub>OPT</sub>
    * Description: Data quality flag
    * range: [String](types/String.md)
 * [decimalLatitude](decimalLatitude.md)  <sub>OPT</sub>
    * Description: The geographic latitude (in decimal degrees, WGS84) of the geographic center of the reference area
    * range: [Double](types/Double.md)
 * [decimalLongitude](decimalLongitude.md)  <sub>OPT</sub>
    * Description: The geographic longitude (in decimal degrees, WGS84) of the geographic center of the reference area
    * range: [Double](types/Double.md)
 * [dnaSnagDiameter](dnaSnagDiameter.md)  <sub>OPT</sub>
    * Description: Diameter of snag sampled for DNA
    * range: [Double](types/Double.md)
 * [dnaSnagLength](dnaSnagLength.md)  <sub>OPT</sub>
    * Description: Length of snag sampled for DNA
    * range: [Double](types/Double.md)
 * [domainID](domainID.md)  <sub>OPT</sub>
    * Description: Unique identifier of the NEON domain
    * range: [String](types/String.md)
 * [elevation](elevation.md)  <sub>OPT</sub>
    * Description: Elevation (in meters) above sea level
    * range: [Double](types/Double.md)
 * [elevationUncertainty](elevationUncertainty.md)  <sub>OPT</sub>
    * Description: Uncertainty in elevation values (in meters)
    * range: [Double](types/Double.md)
 * [eventID](eventID.md)  <sub>OPT</sub>
    * Description: An identifier for the set of information associated with the event, which includes information about the place and time of the event
    * range: [String](types/String.md)
 * [geneticSampleCode](geneticSampleCode.md)  <sub>OPT</sub>
    * Description: Barcode of a genetic sample
    * range: [String](types/String.md)
 * [geneticSampleID](geneticSampleID.md)  <sub>OPT</sub>
    * Description: Identifier for the genetic sample
    * range: [String](types/String.md)
 * [geodeticDatum](geodeticDatum.md)  <sub>OPT</sub>
    * Description: Model used to measure horizontal position on the earth
    * range: [String](types/String.md)
 * [habitatType](habitatType.md)  <sub>OPT</sub>
    * Description: Habitat type sampled
    * range: [String](types/String.md)
 * [namedLocation](namedLocation.md)  <sub>OPT</sub>
    * Description: Name of the measurement location in the NEON database
    * range: [String](types/String.md)
 * [ponarDepth](ponarDepth.md)  <sub>OPT</sub>
    * Description: Depth of petite ponar sample
    * range: [Double](types/Double.md)
 * [recordedBy](recordedBy.md)  <sub>OPT</sub>
    * Description: An identifier for the technician who recorded the data
    * range: [String](types/String.md)
 * [remarks](remarks.md)  <sub>OPT</sub>
    * Description: Technician notes; free text comments accompanying the record
    * range: [String](types/String.md)
 * [sampleCode](sampleCode.md)  <sub>OPT</sub>
    * Description: Barcode of a sample
    * range: [String](types/String.md)
 * [sampleID](sampleID.md)  <sub>OPT</sub>
    * Description: Identifier for sample
    * range: [String](types/String.md)
 * [samplerType](samplerType.md)  <sub>OPT</sub>
    * Description: Type of sampler used to collect the sample
    * range: [String](types/String.md)
 * [samplingImpractical](samplingImpractical.md)  <sub>OPT</sub>
    * Description: Samples and/or measurements were not collected due to the indicated circumstance
    * range: [String](types/String.md)
 * [samplingProtocolVersion](samplingProtocolVersion.md)  <sub>OPT</sub>
    * Description: The NEON document number and version where detailed information regarding the sampling method used is available; format NEON.DOC.######vX
    * range: [String](types/String.md)
 * [siteID](siteID.md)  <sub>OPT</sub>
    * Description: NEON site code
    * range: [String](types/String.md)
 * [snagDiameter](snagDiameter.md)  <sub>OPT</sub>
    * Description: Diameter of snag sampled
    * range: [Double](types/Double.md)
 * [snagLength](snagLength.md)  <sub>OPT</sub>
    * Description: Length of snag sampled
    * range: [Double](types/Double.md)
 * [startDate](startDate.md)  <sub>OPT</sub>
    * Description: The start date-time or interval during which an event occurred
    * range: [Time](types/Time.md)
 * [substratumSizeClass](substratumSizeClass.md)  <sub>OPT</sub>
    * Description: Size class of the substratum sampled
    * range: [String](types/String.md)
 * [uid](uid.md)  <sub>OPT</sub>
    * Description: Unique ID within NEON database; an identifier for the record
    * range: [String](types/String.md)

## Other properties

|  |  |  |
| --- | --- | --- |
| **Mappings:** | | neon:inv_fieldData_pub |
| **In Subsets:** | | DP1.20126.001 |
|  | | DP1.20120.001 |

