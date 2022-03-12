# SLI_Galnet
## SLI Galnet, the Galician wordnet

|File|Size|Description|
|----|-----|-------| 
|SLI_Galnet_LMF_3.0.29.tar.gz|1.8M|_SLI Galnet_ --the Galician wordnet-- at version 3.0.29 (http://sli.uvigo.gal/galnet) in LMF (Lexical Markup Framework) format (http://globalwordnet.github.io/schemas/WN-LMF-1.0.dtd)|    
|SLI_Galnet_RDF_3.0.29.tar.gz|169M|_SLI Galnet_, the Galician wordnet, at version 3.0.29 (http://sli.uvigo.gal/galnet) in RDF (Resource Description Framework) format. This distribution includes linked multilingual lexical data for Galician, Catalan, Basque, Spanish, Portuguese and English, and integrates ontological knowledge from Extended WordNet Domains, Adimen-SUMO, Top Ontology and Galnet Epinonyms|

These resources are made available under the terms of Creative Commons Attribution 4.0 International Public License (CC BY 4.0) (which you can find at https://creativecommons.org/licenses/by/4.0/), and are distributed without any warranty.

Information and contact: Xavier Gómez Guinovart (xgg2021@gmail.com)

***
## Note

**SLI_Galnet_RDF_3.0.29.tar.gz** has been split into 25MB parts with the _split_ command:

```console
$ split -b 25M -d SLI_Galnet_RDF_3.0.29.tar.gz SLI_Galnet_RDF_3.0.29.tar.gz.part
```

To rejoin these parts, you can use the _cat_ command:

```console
$ cat SLI_Galnet_RDF_3.0.29.tar.gz.part* > SLI_Galnet_RDF_3.0.29.tar.gz
```
