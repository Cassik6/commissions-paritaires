This repo serves as a way to download about 4000 Pdf containing joint commissions (commissions paritaires) ranging from jan 2018 to febr 2020.

# Why 

# What
this repo is containing
- a json file (jc.json). Each of it's json object contains a route to each pdf (documentLink field)
- venv folder containing the needed virtual envirement if you wish to run the code yourself.
- data folder containing all the pdfs
- jc_dowload_script.py file script to download all the pdfs

the json object looks like this:

{
        "jcId": 1000000,
        "jcFr": "COMMISSION PARITAIRE AUXILIAIRE POUR OUVRIERS",
        "jcNl": "AANVULLEND PARITAIR COMITE VOOR DE WERKLIEDEN",
        "titleFr": "La procédure de mise en uvre et les conditions d'octroi d'un régime de chômage avec complément d'entreprise - travail de nuit, métier lourd (2021-2022).",
        "titleNl": "Procedure van tenuitvoerlegging en van de voorwaarden voor de toekenning betreffende het stelsel van werkloosheid met bedrijfstoeslag - nachtarbeid, zwaar beroep (2021-2022).",
        "themesFr": [
            "RÉGIME DE CHÔMAGE AVEC COMPLÉMENT D'ENTREPRISE (RCC)"
        ],
        "themesNl": [
            "STELSEL VAN WERKLOOSHEID MET BEDRIJFSTOESLAG (SWT)"
        ],
        "signatureDate": "2019-11-13T11:00:00.000+0000",
        "validityDate": "2022-12-31T11:00:00.000+0000",
        "depositDate": "2019-11-27T11:00:00.000+0000",
        "recordDate": "2020-02-04T11:00:00.000+0000",
        "depositRegistrationDate": "2020-02-04T11:00:00.000+0000",
        "depositNumber": 156733,
        "enforced": true,
        "royalDecreeDate": null,
        "noticeDepositMBDate": "2020-02-17T11:00:00.000+0000",
        "publicationRoyalDecreeDate": null,
        "correctedDate": null,
        "documentLink": "100/100-2019-014748.pdf",
        "documentSize": "455 Kb",
        "scopeFr": null,
        "scopeNl": null,
        "noScopeFr": null,
        "noScopeNl": null
    }

# How
Note that the pdf files are already downloaded, but the code is still provided so you could do it yourself if need be.

1. Install 




