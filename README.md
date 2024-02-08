# Mini-Project-1

Tobias Carlsen - cph-tc183@cphbusiness.dk

Christian Kortsen - cph-cc283@cphbusiness.dk

Daniel Trelborg - cph-dh216@cphbusiness.dk

Simone Toft Hansen - cph-sh575@cphbusiness.dk


Vi har valgt at bruge en .CSV fil om biler, en .JSON fil om Indiske firmaers stock data, og en .XLSX om youtube kanal statistikker.


# Description
Vi starter med at importe pandas, numpy og seaborn.

Vi valgte filer og ingestede dem ind i vores kode.

Derefter kiggede vi den rå data igennem, og cleanede det som vi syntes skulle cleanes.

Særligt var vi nødt til at lave en funktion der kunne lave tal strings med M og K om til floats.

Derefter anonymiserede vi bla. Youtube-kanalernes navne ved hjælp af Faker, som vi også importerede og ændrede dets lokation til Portugal - så alle navnene blev lavet om.

Derefter visualiserede vi dataen først med outliers og derefter uden, så vi kunne se medianen og første og tredje quartiles.

Vi lavede en bar-graf.

Herefter brugte vi corr() funktionen til at finde korrelationen mellem alle vores numeriske værdier.

Vi fandt derefter ud af at der var stor korrelation, mellem likes og views, 0.94.

Til sidst lavede vi nogle bins for Average Likes til vores Youtube data., som indeholdte low, mid og high, som vi også smed ind i en bar-graf.
