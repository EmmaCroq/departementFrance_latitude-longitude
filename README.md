# departementFrance_latitude-longitude
Import SQL -> 96 Departement de France avec la longitude et la latitude de leur chef-lieu 

## English / French

This document is to be imported into the table of your database which contains the columns: "name", "postcode" and "position".

The position is made with the "ST_GeomFromText ()" method which first takes a point with longitude and latitude (X / Y) then its SRID. For a geographical position it is 4326.

This document does not take into account the departments Overseas Territories.


.
.
.



Ce document est à importer dans la table de votre base de données qui contient les colonnes : "nom", "codepostal" and "position".

La position se fait avec la méthode "ST_GeomFromText()" qui prend en premier un point avec longitude et latitude (X/Y) puis son SRID. Pour une position géographique il s'agit  de 4326.

Ce document ne prend pas en compte les départements d'Outre-Mer.

