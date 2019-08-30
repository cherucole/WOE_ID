This zip file contains data produced by the Yahoo! Geo Technologies group. 
The zip file consists of
 
- a set of 4 data files (.tsv)
- a license file (licence.txt)
- readme.txt

This is a stand-alone, platform independent data provision with no prerequisites.

Following is the layout of each data file:

filename: geoplanet_places_7.4.0.tsv 

- 6 fields
  * WOEID			- primary "place" key
  * ISO Country Code		- according to ISO 3166-1 region code
  * Preferred "Normal" Name	- in local language or english
  * Language Code of Name	- according to ISO 639-2 standard
  * PlaceType Code		- code indicating place category
  * Parent ID			- WOEID of direct parent feature


filename: geoplanet_aliases_7.4.0.tsv

- 4 fields
  * WOEID		- primary "place" key
  * Name		- alternative name of place
  * NameType		- descriptor for name
  * LanguageCode	- language of name as per ISO 639-2 standard


filename: geoplanet_adjacencies_7.4.0.tsv

- 4 fields
  *Place WOEID
  *Place ISO Code
  *Neighbor WOEID
  *Neighbor ISO Code


filename: geoplanet_changes_7.4.0.tsv

- 3 fields
  *Deleted WOEID
  *Replacement WOEID
  *Data Version