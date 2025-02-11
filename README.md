# Multi-CAST Teop

## How to cite

If you use these data please cite
- the original source
  > Mosel, Ulrike & Schnell, Stefan. 2021. Multi-CAST Teop. In Haig, Geoffrey & Schnell, Stefan (eds.), Multi-CAST: Multilingual corpus of annotated spoken texts. Version 2101. Bamberg: University of Bamberg. (multicast.aspra.uni-bamberg.de/#teop) (date accessed)
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

![](cldf/media/image.jpg)

## Description


**Teop** ([teop1238](https://glottolog.org/resource/languoid/id/teop1238)) is a Western Oceanic language spoken on Bougainville Island, Papua New Guinea. The texts, all traditional narratives, were recorded by Ulrike Mosel and Enoch Horai Magum over the course of a [language documentation project](http://dobes.mpi.nl/projects/teop/) (principal investigator: Ulrike Mosel) funded by the Volkswagen Foundation (grant no. II 77 973). Details on the project can be found online at [the DOBES webpage](http://dobes.mpi.nl/projects/teop/).

A sketch grammar of Teop ([Mosel & Thiesen 2007](Source#cldf:mosel.thiesen2007)) and additional materials are also available there, and an online dictionary (*[A multifunctional Teop-English dictionary](https://dictionaria.clld.org/contributions/teop)*, [Mosel 2019](Source#cldf:mosel2019)) can be found [here](https://dictionaria.clld.org/contributions/teop). The texts were annotated for Multi-CAST by Ulrike Mosel and Stefan Schnell; referent indexing with RefIND was added in 2019 by Ulrike Mosel, Stefan Schnell, and Maria Vollmer.

The Multi-CAST Teop texts (version 2207) also constitute a part of the [Teop data set](https://doreco.huma-num.fr/languages/teop1238) in [DoReCo](https://doreco.huma-num.fr/), which has been time-aligned at the phone level.

This dataset is licensed under a CC-BY-4.0 license

Available online at https://multicast.aspra.uni-bamberg.de/#teop


```geojson
{
    "type": "FeatureCollection",
    "features": [
        {
            "type": "Feature",
            "geometry": {
                "type": "Point",
                "coordinates": [
                    154.971,
                    -5.67474
                ]
            }
        },
        {
            "type": "Feature",
            "geometry": {
                "type": "Polygon",
                "coordinates": [
                    [
                        [
                            149.971,
                            -0.6747399999999999
                        ],
                        [
                            159.971,
                            -0.6747399999999999
                        ],
                        [
                            159.971,
                            -10.67474
                        ],
                        [
                            149.971,
                            -10.67474
                        ],
                        [
                            149.971,
                            -0.6747399999999999
                        ]
                    ]
                ]
            }
        }
    ]
}
```



## Corpus counts

Only a small number of basic GRAID symbols are counted:

*Function symbols*
- ⟨0⟩ zero
- ⟨pro⟩ definite pronoun
- ⟨np⟩ full noun phrase
- ⟨other⟩ form not further specified

*Person/Animacy symbols*
- ⟨.1⟩ first person
- ⟨.2⟩ second person
- ⟨.h⟩ third person, human
- ⟨.d⟩ third person, anthropomorphic
- ø third person, non-human

*Function symbols*
- ⟨:s⟩ subject of an intransitive clause
- ⟨:a⟩ subject of a transitive clause
- ⟨:ncs⟩ non-canonical subject
- ⟨:p⟩ direct object
- ⟨:obl⟩ oblique argument
- ⟨:g⟩ goal argument
- ⟨:l⟩ locational argument
- ⟨:pred⟩ predicate
- ⟨:poss⟩ possessive
- ⟨:other⟩ function not further specified

Only basic categories are listed; categories represented by complex symbols with additional
specifiers (e.g. ⟨dem_pro⟩ ‘demonstrative pronoun’) have been subsumed under the more basic
category (e.g. ⟨pro⟩ ‘definite pronoun’). Please refer to the annotation notes for this corpus for
information on all annotated categories, including those not listed here.

| GRAID | ⟨:s⟩ | ⟨:a⟩ | ⟨:ncs⟩ | ⟨:p⟩ | ⟨:obl⟩ | ⟨:g⟩ | ⟨:l⟩ | ⟨:pred⟩ | ⟨:poss⟩ | ⟨:other⟩ | totals |
|:--------------|-------:|-------:|---------:|-------:|---------:|-------:|-------:|----------:|----------:|-----------:|---------:|
| **⟨0.1⟩** | 3 | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 4 |
| **⟨0.2⟩** | 20 | 15 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 35 |
| **⟨0.h⟩** | 188 | 90 | 0 | 44 | 0 | 0 | 0 | 0 | 0 | 0 | 322 |
| **⟨0.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨0⟩** | 51 | 6 | 0 | 54 | 2 | 0 | 0 | 0 | 0 | 0 | 113 |
| **⟨pro.1⟩** | 61 | 64 | 0 | 4 | 0 | 0 | 0 | 2 | 24 | 0 | 155 |
| **⟨pro.2⟩** | 24 | 24 | 0 | 6 | 0 | 0 | 1 | 1 | 17 | 0 | 73 |
| **⟨pro.h⟩** | 143 | 163 | 0 | 55 | 0 | 0 | 0 | 1 | 116 | 1 | 479 |
| **⟨pro.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨pro⟩** | 30 | 3 | 0 | 38 | 4 | 0 | 3 | 1 | 36 | 4 | 119 |
| **⟨np.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np.h⟩** | 121 | 55 | 0 | 53 | 8 | 1 | 0 | 38 | 21 | 1 | 298 |
| **⟨np.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨np⟩** | 67 | 7 | 0 | 186 | 8 | 44 | 63 | 49 | 40 | 50 | 514 |
| **⟨other.1⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.2⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other.h⟩** | 1 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 1 |
| **⟨other.d⟩** | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| **⟨other⟩** | 0 | 0 | 0 | 0 | 6 | 8 | 2 | 130 | 0 | 0 | 146 |
| | 709 | 428 | 0 | 440 | 28 | 53 | 69 | 222 | 254 | 56 | 2259 |


**Clause boundaries**

| GRAID | count |
|:-----------|--------:|
| **⟨##⟩** | 1080 |
| **⟨#⟩** | 223 |
| **totals** | 1303 |



## Corpus metadata

- [Annotation notes](cldf/media/annotation-notes.pdf)
- [Metadata](cldf/media/metadata.pdf)
- [Translated texts](cldf/media/translated-texts.pdf)


## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [TextCorpus](https://github.com/cldf/cldf/tree/master/modules/TextCorpus) at [cldf/TextCorpus-metadata.json](cldf/TextCorpus-metadata.json)