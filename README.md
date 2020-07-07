# Riksdagen
Container for different things conncted with Wikidata <-> and the Swedish Parliamen
## Jupyter Notebooks
innehåller kod och data som hämtats
* [SOU](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20SOU.ipynb) ([en](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20Motioner-en.ipynb))
  * Linköping [Swedish Government Official Reports (SOU) 1922 - 2019 (up to 2020:29)](https://ep.liu.se/databases/sou/)
* [SFS](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20SFS.ipynb)
* [KU anmälningar](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20KU-anm%C3%A4lningar.ipynb)
* [Ledamöter](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20ledam%C3%B6ter.ipynb)
* [Dokumenttyper](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokumenttyper.ipynb)
* [Motioner](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20Motioner.ipynb)
* [Betänknande](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20Kommitt%C3%A9direktiv.ipynb)
* [Direktiv](https://github.com/salgo60/open-data-examples/blob/master/Riksdagens%20dokument%20Kommitt%C3%A9direktiv.ipynb)
* Skriftliga frågor 
* Interporlationer
# Links
* Wikipedia/Wikidata
  * [Wikidata:WikiProject_Sweden/Swedish_Riksdag_documents](https://www.wikidata.org/wiki/Wikidata:WikiProject_Sweden/Swedish_Riksdag_documents)
  * [Diskussion:Lista_över_svenska_riksdagar](https://sv.wikipedia.org/wiki/Diskussion:Lista_%C3%B6ver_svenska_riksdagar)
  * [Wikidata:WikiProject_every_politician/Sweden](https://www.wikidata.org/wiki/Wikidata:WikiProject_every_politician/Sweden)
* Properties
  * [Riksdagens person-id P1214](https://www.wikidata.org/wiki/Property:P1214)
  * [Riksdagen person guid P8388](https://www.wikidata.org/wiki/Property:P8388)
  * Draft Proposal [Swedish Riksdag document](https://www.wikidata.org/wiki/Wikidata:Property_proposal/Swedish_Riksdag_document)
* GITHUB
  * [tmtmtmtm/sweden-riksdag-api-current](https://github.com/tmtmtmtm/sweden-riksdag-api-current) did some uploading cleaning....
     * [twitter Tony Bowden](https://twitter.com/tmtm)
  * [Reicher/RiksdagenPythonAPI](https://github.com/Reicher/RiksdagenPythonAPI)
  * [ErikBjare/MyRiksdag](https://github.com/ErikBjare/MyRiksdag)
  * [Riksdagskollen](https://github.com/axelca/riksdagskollen) [web](https://rikskoll.netlify.app/)
  * [Mandatkollen](https://github.com/Iteam1337/mandatkollen)
  * [OAndell/Riksdagskollen](https://github.com/OAndell/Riksdagskollen) 
  * [jonwarghed/RostRecept](https://github.com/jonwarghed/RostRecept) a little program that interacts with Riksdagens API to find what your riksdagsman voted for
  * [github.com/ragulin/mds-riksdagen](https://github.com/ragulin/mds-riksdagen) [MDS](https://en.wikipedia.org/wiki/Multidimensional_scaling) visualizations of the swedish parliament
  * [Citizen Intelligence Agency](https://github.com/Hack23/cia) "Tracking politicians like bugs. Citizen Intelligence Agency is independent and non-partisan voluntary project....Visualize political activity in Sweden, present key performance indicators and metadata for the actors on national level."
* Telegram "Wikidata Sverige"
* Live sessions
  * Jan Ainali is doing SPARQL searching on Swedish Riksdags (OM) members - [Wikipedia Weekly Network - LIVE Wikidata editing #10](https://www.youtube.com/watch?v=q2iTKemFrq4)
# Other projects 
* [Parline](https://data.ipu.org/)
* openparliament.tv
  * [Proposal](https://openparliament.tv/proposal)
    * [tweet](https://twitter.com/OpenHypervideo/status/1270285255107399685)
* [www.politicindex.de](https://www.politicindex.de/) - [video](https://www.youtube.com/watch?v=OzwCqMdXHjs&feature=youtu.be)

# ShEx
<a name="ShEx"></a>
* [sheXer](http://shexer.weso.es/) / [rdfshape](http://rdfshape.weso.es) 
 * [wikishape](http://wikishape.weso.es/) [GITHUB](https://github.com/weso/wikishape/issues)
* [WikiProject Schemas/Tutorial](https://www.wikidata.org/wiki/Wikidata:WikiProject_Schemas/Tutorial)
## Draft queries for session
* Query to be used for [building ShEx](https://w.wiki/W56)
* Query [that gives 349](https://w.wiki/W54) and should be validated
### Questions
1. can we set range dates for start dat pq:P580 > [Q18332247](https://www.wikidata.org/wiki/Q18332247) "2018 Swedish general election"
