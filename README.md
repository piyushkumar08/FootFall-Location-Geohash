# FootFall-Location-Geohash

* Identification of the FootFalls through mobile location points in 100m radius of locations given in ['location.xlsx'](https://github.com/piyushkumar08/FootFall-Location-Geohash/blob/main/location.xlsx).

* The mobile location data points are given in the ['footfalls.xlsx'](https://github.com/piyushkumar08/FootFall-Location-Geohash/blob/main/footfalls.xlsx) file.

## Installation
- Add the excel files to your SQL server database
- And just execute the code
- Software used: [Microsoft SQL Server Management Studio](https://www.microsoft.com/en-in/sql-server/sql-server-downloads)

## Result
   Click [here](https://github.com/piyushkumar08/FootFall-Location-Geohash/blob/main/Result_footfall.csv) to see the result. It is in CSV format.
   
## Credits
* The `geohash_bit`, `geohash_base32` and `geohash_base32_index` functions were implemented using nowelium's [geohash-mysql-func](https://github.com/nowelium/geohash-mysql-func/blob/master/geohash.sql) as a reference
* The `geohash_encode` and `geohash_decode` functions were implemented using davetroy's [geohash-js](https://github.com/davetroy/geohash-js) and vdurante's [geohash-function](https://github.com/vdurante/sql-server-geohash-functions/blob/master/geohash.sql) as a reference

