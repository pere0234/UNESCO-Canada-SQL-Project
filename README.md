# A Relational Database Listing UNESCO World Heritage Sites in Canada
* Tools: SQL, PostGreSQL
* Abstract: 
  *  As part of an initiative to foster sustainable tourism, Destination Canada, 
      a leading marketing and research organization, 
      requests a listing of all UNESCO world heritage sites within Canada. 
        Organized by province, the listing is also structured by type of site: cultural, natural, and mixed. 
        
 * Business Rules:
  * Canadian Province
    * A province is unique and individual. 
    * A province's name, capital city, and population, among other details is maintained.
    * All Canadian provinces are listed.
    * A province may have many UNESCO sites.
    * A province may not have any sites. 
    * A site must belong to one province.
   
  * Cultural Site
    * A list of cultural sites is maintained in the database. They include such items as historic buildings, works of art, archaeological sites, libraries, and museums.
    * Each site is listed by site ID, province, name, and location coordinates.
  
  * Natural Site
    * A list of natural sites is maintained in the database. They include those that contain elements of both natural and cultural significance. 
    * Each site is listed by site ID, province, name, and location coordinates.
  
 * Mixed Site
    * A list of natural sites is maintained in the database. They include those that contain elements of both natural and cultural significance. 
    * Each site is listed by site ID, province, name, and location coordinates.

![image](https://user-images.githubusercontent.com/77496752/117150391-1c7b5600-ad86-11eb-89e2-8699e811d188.png)
