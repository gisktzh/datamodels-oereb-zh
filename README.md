# datamodels-oereb-zh
Dies sind die Interlis Datenmodelle, welche im ÖREB-Kataster des Kantons Zürich verwendet werden. Die Modelle sind nach Themen (Nutzungsplanung, Abstandslinien, Grundwasser, Gewässerraum) aufgegliedert. Die Ablage ist wie folgt organisiert:
- \<Thema\>\_ZH\_Master\_\<Version\>.ili: Dies ist das Master-Modell in Interlis2. Von diesem werden die anderen Modelle abgeleitet.
- \<Thema\>\_ZH\_Transfer\_\<Version\>.ili: Dies ist das Transfermodell, in welchem die OEREB-Daten abgegeben werden.
- \<Thema\>\_ZH\_IL1-Abgeleitet\_\<Version\>.ili: Dies war die initiale ili1-Ableitung des Master-Modelles. Hat keine Relevanz mehr.
- implementation/\<Modell\>-[PROJ|PROTOKOLL|RG].ili: Dies sind die in GeosPro implementierten Modelle fuer projektierte, protokollierte und rechtsgueltige Daten (ev. veraltet)

Die Modelle der zweiten Version (*_V2.ili) werden voraussichtlich im Q4/2015 aktiv geschaltet. Dann werden auch die Implementations-Modelle upgedatet.