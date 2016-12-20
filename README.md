The Museum of Modern Art (MoMA) Exhibition and Staff Histories
===================

## Exhibition Index Dataset
The Museum of Modern Art (MoMA) opened in 1929 with its first exhibition [Cézanne, Gauguin, Seurat, Van Gogh](https://www.moma.org/calendar/exhibitions/1767) [MoMA Exh. #1, November 7–December 7, 1929]. Since that time the Museum has presented more than 2,500 exhibitions of artworks from all moments of art history and all corners of the globe. While the Museum’s focus has been on all forms of art and design from Post-impressionism into the 21st century, exhibitions have also included paintings by Italian Renaissance masters, historic sculptures and textiles from Africa and Oceania, pottery and implements from Native American communities, and European and American folk and outsider art. 

The exhibition index dataset was compiled by a project team from the [MoMA Archives](https://www.moma.org/research-and-learning/research-resources/archives/index) as part of their work to preserve, describe, and open to the public over 22,000 folders of exhibition records dating from 1929 to 1989 from its registrar and curatorial departments. The Exhibition History Project was generously funded by the Leon Levy Foundation, which has also committed to underwriting further work on this dataset and the processing of additional records from 1990 to 2000 over the next three years. Not yet included in the dataset are the thousands of film series presented by MoMA’s Department of Film over its 80-year history. Those records will be added in a future phase of the project, as will a history of performance art at MoMA and MoMA PS1 and exhibitions at MoMA PS1.  
 
This research dataset lists 1,788 exhibitions, representing all of the known exhibitions held at the museum from 1929 through 1989. All known curators and organizers, artists and other participants are listed for each exhibition. A total of 11,550 constituents are represented in this dataset, approximately 5,900 of them not currently represented in MoMA’s permanent collection of artworks.
 
### The fields are as follows:
Field Name | Type           | Description  | Example
-----------------------|----------------|--------------------------|------------
ExhibitionID          | Number   |A unique number that identifies exhibitions within the Museum’s collection database. | 2999
ExhibitionNumber          | String         |A unique alphanumeric string assigned to each exhibition by the Museum for internal use since exhibition #1 in 1929. | 30b
ExhibitionTitle | String  | The formal full title of the exhibition. | Summer Exhibition: Gauguin Woodcuts and Watercolors
ExhibitionCitationDate| String  |  Bracketed text display of exhibition number and opening and closing dates. This string should follow the italicized exhibition title in all academic citations, to adequately differentiate referenced exhibitions.  |[MoMA Exh. #30b, July 10–September 30, 1933]
ExhibitionBeginDate   | Date         | The opening date of an exhibition when known. | 7/10/1933
ExhibitionEndDate | Date        | The closing date of an exhibition when known.  | 9/30/1933
ExhibitionSortOrder | Number  | A unique number provided to order exhibitions by the exhibition number, as in traditional MoMA recordkeeping, rather than by date. |37
ExhibitionURL          | String     | Web address for the exhibition on MoMA.org. | moma.org/calendar/exhibitions/1912 
ExhibitionRole          | String     | Role of each constituent in the exhibition. Includes Artist, Curator, Arranger, Designer, Preparer, Installer and Competition Judge. | Curator
ExhibitionRoleinPressRelease          | String     | Role of each constituent in the exhibition as expressed in the press release. | Director
ConstituentID      | Number  | A unique number that identifies constituents within the Museum’s collection database. |  2098
ConstituentType             | String       | Type of constituent, usually Individual or Institution (organization)| Individual
DisplayName      | String         |  The full proper reading format of a constituent name. | Paul Gauguin
AlphaSort           | String         | The form of the constituent name for correct alphabetization.  | Gauguin Paul
FirstName            | String      | The individual’s first name, when known. | Alfred
MiddleName             | String    | The individual’s middle name or initial, when known. | H.
LastName          | String         | The individual’s last name, when known. | Barr
Suffix                | String         |  The individual’s name suffix, when present.    | Jr.
Institution        | String         |  Additional name field for Institutions.  | Miller Furniture Co., Herman
Nationality         | String         |  Accepted country of identification, often distinct from country of origin. | French
ConstituentBeginDate | Number | Birth year of an individual or an institution’s year of origin. | 1848
ConstituentEndDate | Number | Death year of an individual or an institution’s year of termination. | 1903
ArtistBio | String | Text display of nationality with birth and death years. | French, 1848–1903
Gender | String | Gender identification of an individual. | Female
VIAFID | Number | Unique identifier from the Virtual International Authority File (VIAF) | 27064953
WikidataID | String | Unique identifier from Wikidata, Wikipedia, and other Wikimedia resources. | Q37693
ULANID | Number | Unique identifier from the Getty Research Institute’s Union List of Artist Names (ULAN). | 500011421
ConstituentURL | String | Web address for the artist on MoMA.org. | moma.org/artists/2098 



## Museum Directors and Department Heads Dataset
The staff history dataset contains a list of all directors of the Museum and department heads of individual curatorial departments since its founding in 1929. In its nascency the Museum's administration was so small that separate departments did not exist as such. For instance, while the Museum conducted registrarial activities from the very beginning, only in 1932 was a staff member, Alice E. Mallete, designated as Registrar. Likewise, though MoMA began its permanent collection of prints and drawings in 1929 and received its first painting in 1930, the official conception of the Department of Painting and Sculpture is of uncertain date and it did not have the position of chief curator or director until 1940. Specific position titles are mostly omitted from this dataset as these often changed and an individual might be a curator or chief curator, acting director or director, while still always being the top-ranked position within the department. Further notes on the history of individual departments are below.
 
### Department of Painting and Sculpture (1929–present)
The official founding date of this curatorial department as a distinct unit is uncertain; the name Department of Painting and Sculpture is first seen among Museum records around 1940. In 1947 the Museum reorganized the administration of the department. Alfred H. Barr, Jr. was named "Director of Museum Collections" in which he was in charge of supervising all the Museum's acquisitions, personally responsible for painting and sculpture acquisitions and, as phrased in the press release, responsible for the "planning, organization, care and use (including publications and display) of the Collections as a whole." Other departments were placed under Barr's supervision but remained largely independent. Dorothy C. Miller, already serving as Acting Director of Painting and Sculpture upon James Johnson Sweeney's departure, remained in that now-redefined role until 1949. Miller and the Directors who followed her during Barr's tenure are sometimes referred to as the Directors of Painting and Sculpture Exhibitions to distinguish them from Barr's role as Director of Museum Collections.
 
### Department of Architecture (1932–1949) </br> Department of Industrial Design (1940–1948) </br> Department of Architecture and Design (1949–present)
Renamed the Department of Architecture and Industrial Art in 1935, returning to simply the Department of Architecture in 1940 when Industrial Design was made independent. For a brief time during Philip L. Goodwin's tenure as "Chairman" of the Department lead curators were designated as Directors and are thus included in the dataset. The current Department of Architecture and Design was created when the Departments of Architecture and Industrial Design merged in 1949.
 
### Department of Film (1935–present)
Founded as the Film Library, became the Department of Film in 1966, renamed the Department of Film and Video in 1994, renamed the Department Film and Media in 2001, and most recently renamed the Department of Film in 2006 after the creation of the new stand-alone Department of Media. Note that Iris Barry was the Department's first curator and was in many ways considered the de facto department head from 1935 as John E. Abbott had several executive roles at the Museum.
 
### Department of Photography (1940–present)
In the summer of 1929 Alfred H. Barr, Jr. included a department devoted to photography in the multi-departmental plan for the Museum which he was asked to present to the Trustees. But the department did not actually exist until 1940. It was the first department of photography in a museum devoted to twentieth-century art.  	
 
### Department of Dance and Theater Design (1944–1948)
In 1939 the Dance Archives was established as a part of the Museum Library to provide a home for a specialized research collection for the study of dance donated by Lincoln Kirstein. Paul Magriel was the Dance Archives' first librarian. In 1944 the Dance Archives was promoted to the status of a curatorial department with George Amberg as its curator. The department was dissolved in 1948 due to the Museum’s rising operating costs.

### Department of Drawings and Prints (1960–1969) </br> Department of Prints and Illustrated Books (1969–2013) </br> Department of Drawings (1971–2013) </br> Department of Drawings and Prints (2013–present)
The Department of Drawings and Prints began in 1960 under the aegis of Museum Collections and only became an independent department in 1966. The Department of Prints and Illustrated Books was created in 1969 to provide autonomy for prints while responsibility for drawings reverted to the Department of Painting and Sculpture until 1971. The current Department of Drawings and Prints was formed after the merger of the Department of Prints and Illustrated Books and the Department of Drawings in 2013.
 
### Chief Curator at Large (1993–present)
Senior curatorial position unattached to a curatorial department.
 
### Department of Media and Performance Art (2006–present)
Split off from the Department of Film as the Department of Media and renamed Media and Performance Art in 2009.
 
### Fields in the staff history dataset are as follows:
Field Name | Type           | Description  | Example
-----------------------|----------------|--------------------------|------------
DepartmentFullName          | String   |The full name of the institution or the curatorial department. | Department of Architecture
DepartmentBeginYear  | Number  | The year the department was created.  | 1932
DepartmentEndYear | Number | The year the department closed or merged with another. | 1949
ConstituentID | Number | A unique number that identifies individuals within the Museum’s collection database. | 16292
DisplayName | String | The full proper reading format of a name. | Philip L. Goodwin
PositionNote | String | Note to clarify the title of department head. | as Chairman
PositionBeginDate | Number | Year the individual was named to the position. | 1935
PositionEndDate | Number | Year the individual stepped down from the position. | 1948
ConstituentType | String | Type of constituent, usually Individual or Institution (organization) | Individual
AlphaSort | String | The form of the name for alphabetization by last name.  | Goodwin Philip L.
FirstName | String | The individual’s first name, when known. | Philip
MiddleName | String | The individual’s middle name or initial, when known | L.
LastName | String | The individual’s last name, when known | Goodwin
Suffix | String | The individual’s name suffix, when present | Jr.
Nationality | String | Accepted country of identification, often distinct from country of origin | American
ConstituentBeginDate | Number | Birth year of an individual or an institution’s year of origin | 1885
ConstituentEndDate | Number | Death year of an individual or an institution’s year of termination | 1958
ArtistBio | String | Text display of nationality with birth and death years | American, 1885–1958
Gender | String | Gender identity of an individual | Male
VIAFID | Number | Unique identifier from the Virtual International Authority File (VIAF) | 107308378
WikidataID | String |  Unique identifier from Wikidata, Wikipedia, and other Wikimedia resources | Q21289656
ULANID | Number | Unique identifier from the Getty Research Institute’s Union List of Artists Names (ULAN) | 500002438

At this time, both datasets are available in CSV format, encoded in UTF-8. While UTF-8 is the standard for multilingual character encodings, it is not correctly interpreted by Excel on a Mac. Users of Excel on a Mac can convert the UTF-8 to UTF-16 so the file can be imported correctly. 
 
These datasets are placed in the public domain using a [CC0 License](https://creativecommons.org/publicdomain/zero/1.0/).


### Research in progress
This data is provided “as is” for research purposes and you use this data at your own risk. While we believe this list of exhibitions is complete within its data range, many curators and participants have not yet been identified and work is ongoing. MoMA offers the datasets "as-is" and makes no representations or warranties of any kind. We plan to update the datasets with new and revised information on a regular basis. You are advised to regularly update your copy of the datasets to ensure you are using the best available information.
 
### Pull requests
Because these datasets are generated from our internal database, we do not accept pull requests. If you have identified errors or have extra information to share, please email us at [digital@moma.org](mailto:digital@moma.org). 

### Give attribution to MoMA
MoMA requests that you actively acknowledge and give attribution to MoMA wherever possible. If you use the dataset for a publication, please cite it using the digital object identifier [![DOI](https://zenodo.org/badge/67644440.svg)](https://zenodo.org/badge/latestdoi/67644440). Attribution supports efforts to release other data. It also reduces the amount of “orphaned data”, helping retain links to authoritative sources. 

### Do not misrepresent the dataset
Do not mislead others or misrepresent the dataset or its source. You must not use MoMA’s trademarks or otherwise claim or imply that MoMA endorses you or your use of the dataset. 

Whenever you transform, translate or otherwise modify the dataset, you must make it clear that the resulting information has been modified. If you enrich or otherwise modify the dataset, consider publishing the derived dataset without reuse restrictions.

The writers of these guidelines thank the [Tate](http://www.tate.org.uk/), [Cooper-Hewitt](http://www.cooperhewitt.org/),  [Europeana](http://www.europeana.eu/), and the [Carnegie Museum of Art](http://www.cmoa.org/). 



