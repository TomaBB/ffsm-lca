version 2.2.2
========================

Public version

Includes all data delivered until 1 June 2014. Only the trade fraction data (import & export fractions) are from the version 2.1 database.

Trade linking and balancing to a mimumum sum of absolute deviation between requested column and row headers and calculated row and column headers is about 1E-6 million Euro. 

Industry by Industry, fixed product sales assumption, coefficient form


Updates
=======
- Reduced resolution of the energy extensions in mrFDMaterials annd mrMaterials


Format of the files
===================

Text between double quotes
Delimiter tab character
EOL windows format
In the "types_version2.2.2.xls" the full description of all classifications is given including the order of all the classifications.


Pecularities
============

In the emission files there is a row for every substance combined with the air compartment as well as the water compartment while in many cases there are no data available.


Sizes (rows x columns) of the matrices in the files
===================================================

mrIOT (7826 x 7827)
row 1: text, CountryCode
row 2: text, IndustryTypename
column 1: text, CountryCode
column 2: text, IndustryTypeName
column 3: text, UnitCode

mrFinalDemand 7826 x 339
row 1: text, CountryCode
row 2: text, FinalDemandTypeName
column 1: text, CountryCode
column 2: text, IndustryTypeName
column 3: text, UnitCode

mrFactorInputs 21 x 7826
row 1: text, CountryCode
row 2: text, IndustryTypeName
column 1: text, FactorInputTypeName
column 2: text, UnitCode

mrEmissions 172 x 7827
row 1: text, CountryCode
row 2: IndustryTypeName
column 1: text, SubstanceName
column 2: text, CompartmentName
column 3: text, UnitCode

mrResources 17 x 7827
row 1: text, CountryCode
row 2: text, IndustryTypeName
column 1: text, ExtractionTypeName
column 2: text, CompartmentName
column 3: text, UnitCode

mrMaterials 286 x 7826
row 1: text, CountryCode
row 2: text, IndustryTypeNames
column 1: text, PhysicalTypeName
column 2: text, UnitCode

mrFDEmissions 172 x 339
row 1: text, CountryCode
row 2: text, FinalDemandTypeName
column 1: text, SubstanceName
column 2: text, CompartmentName
column 3: text, UnitCode

mrFDMaterials 286 x 338
row 1: text, CountryCode
row 2: text, FinalDemandTypeCode
column 1: text, PhysicalTypeName
column 2: text, UnitCode







