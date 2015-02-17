# datamodels-oereb-zh
Dies sind die Interlis Datenmodelle, welche im ÖREB-Kataster des Kantons Zürich verwendet werden. Die Modelle sind nach Themen (Nutzungsplanung, Abstandslinien, Grundwasser) aufgegliedert. Die Ablage ist wie folgt organisiert:
- \<Thema\>\_IL2_ZH\_\<Version\>.ili: Dies ist das Master-Modell in Interlis2. Von diesem werden die anderen Modelle abgeleitet.
- \<Thema\>\_IL1_ZH_\<Version\>.ili: Das aus dem Interlis2 - Modell abgeleitete Interlis1-Modell. Dies ist ein Zwischenprodukt.
- \<Thema\>\_Transfer_ZH\_\<Version\>.ili: Dies ist das Transfermodell, in welchem die OEREB-Daten abgegeben werden.
- implementation/\<Modell\>-[PROJ|PROTOKOLL|RG].ili: Dies sind die in GeosPro implementierten Modelle fuer projektierte, protokollierte und rechtsgueltige Daten.
