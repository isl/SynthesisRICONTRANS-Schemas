# Synthesis RICONTRANS - Entity Documentation Schemas

This repository contains the documentation schemas of the entity types used by Synthesis RICONTRANS. 

**Synthesis RICONTRANS** is a web-based application for the collaborative and controlled documentation of data and knowledge related to *Art History* research. It is based on and extends [Synthesis-Core](https://www.ics.forth.gr/isl/synthesis-core), an information system for the scientific and administrative documentation of cultural entities which makes use of [FIMS](https://github.com/isl/FIMS), an open-source system suitable for documenting, recording and managing XML files stored in an XML database.

**Synthesis RICONTRANS** has been designed and configured considering the research needs of the [RICONTRANS](https://ricontrans-project.eu/) project, whose research focus is the Russian religious artefacts brought from Russia to the Balkans after the 16th century and which are now preserved in churches, monasteries or museums. 

The repository provides the documentation schemas (in XSD format) of the below types of entities:
* **Objects**  - The documentation fields are organised in the following categories:
Object Identity (indicative fields: code, name, originator of reference, collection, category, basic material(s), main object image), Detailed Object Description (indicative fields: other object names, measurements, object decoration, inscriptions, stamps, locations, photographic documentation), Object History (historical events, use, acquisition), References (source references, bibliographic references, other related materials), Card Identity (scientific supervisor, scientific associates).
* **Object Trasnfers** - Allows documenting information about transfers of objects. Indicative fields: transfer name/title, transfer date, transferred object, from location, to location, description, transfer purpose, person(s) involved, based on (link to source(s), source passage(s), bibliography).
* **Routes** - Allows grouping a set of object transfers based on a particular object, type of objects, or other criteria. Indicative fields: route name, object transfers, creation information (author, date).
* **Archival Sources** - Allows documenting information about archival sources used to obtain information about an entity of interest (e.g., about an object, object transfer, historical figure, etc.). Indicative fields: title, subject area, short description, category, type, collection, series, file, language.
* **Books** -  Allows documenting information about (old) books used to obtain information about an entity of interest. Indicative fields: title, author(s), type, subject area, repository, language, publisher, publication date.
* **Newspapers and Periodicals/Reviews** - Allows documenting information about (old) newspapers and periodical/reviews. Indicative fields: title, type, subject area, author, language, editor, publisher, publication date.
* **Oral History Sources** - Allows documenting information about oral history sources, like an oral testimony or interview. Indicative fields: title, subject area, description, language, interview date, interviewer, interviewee.
* **Web Sources** - Allows documenting information about web sources providing historical information about one or more entities of interest. Indicative fields: URI, web page title, subject area, content language, text.
* **Bibliography** - Allows documenting information about bibliographic references related to the project. Indicative fields: type, title, author(s), publisher, publication date/place, conference title, volume and issue number, language.
* **Source Passages** - Allows documenting information about a specific source passage that provides important information for an entity of interest (e.g.,
an object transfer). Indicative fields: title, subject area, topic, origin (source or bibliography), source passage text, translation, commentary. 
* **Collection of Source Passages** - Allows grouping a set of source passages, e.g., based on an object, source, etc. Indicative fields: title, subject, short description, source passage(s).
* **Researcher Comments** - Allows documenting information about research results, e.g., the findings of observing the inscriptions of an icon. Indicative fields: researcher, title, about (object, transfer, route, historical figure), description, date, based on (type of research), conclusion, property of analysis, outcome of analysis, method of analysis, date of analysis.
* **Historical Figures** - Allows documenting information about historical persons, like a bishop, patriarch, etc. Indicative fields: name, role, service, birth place, ethnicity, life period, activity period, references
* **Historical Events** - Allows documenting information about historical events, such as a prince reception, an archbishop ordination, or the erection of a church. Indicative fields: name, time of event, location, description, references.
* **Collections** - Allows documenting information about collections of objects, e.g., museum collections. Indicative fields: code number, subject, originator of reference, description.
* **Locations** - Allows documenting information about locations, such as cities, villages, monasteries, churches and museums. Indicative fields: name, location type, geopolitical hierarchy, coordinates.
* **Persons** - Allows documenting information about persons (not historical), such as the researchers participating in the project, a photographer, etc. Indicative fields: name, name in native language, role, member of, description.
* **Organizations** - Allows documenting information about organisations, such as museums, libraries, ephorates, etc. Indicative fields: name, type, pursuit (field), location, contact information, description.
* **Digital Objects** - Allows documenting metadata information about the uploaded digital objects like photos. Indicative fields: title, type, short description, file, rights, creation date, creator.

### Acknowledgements ###

This work has received funding from the European Union's Horizon 2020 research and innovation programme under i) the European Research Council (ERC) grant agreement No 818791 ([Project RICONTRANS](https://ricontrans-project.eu/)), and ii) the Marie Sklodowska-Curie grant agreement No 890861 ([Project ReKnow](https://reknow.ics.forth.gr/)).

