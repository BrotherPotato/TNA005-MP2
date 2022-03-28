Kort beskrivning av USPS-databasen med handskrivna siffror. 

> load uspsDigits 

Load kommandot i Matlab ger 4 variabler: 

testAns 	2007 x 1 	Facit för testsiffrorna
testDigits	16 x 16 x 2007 	Testsiffror, varje “skiva” i 3-D arrayen är en siffra 
trainAns	7291 x 1 	Facit för träningssiffror 
trainDigits	16 x 16 x 7291	Träningssiffror, varje “skiva” i 3-D arrayen är en siffra

För att visualisera en given siffra använd funktionen ima.m

> ima(A)

där A är en (endast en) siffra, t.ex. A = testDigits(:,:,3) ger den tredje siffra in testmängden. 