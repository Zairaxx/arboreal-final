# arboreal-final

Krav för G
Du uppfyller alla krav från Individuell examination 1.
Du har implementerat egna media queries så att din hemsida anpassar sig för mobil, tablet samt desktop.
Du väljer själv vilka breakpoints du använder dig utav. I din README.md som ska ligga i projektet ska du motivera valet av breakpoints, vad var det som gjorde att du valde precis det värdet för att ändra strukturen på sidan?
Du beskriver också vilket responsivt mönster du har utgått ifrån och varför det var ett bra val för sidan. This is responsive: patterns
Du har förbättrat din hemsida utifrån den feedback du fick från föregående inlämning samt skrivit ner vad du har ändrat för att möta denna feedback alternativt motiverat varför du inte har ändrat utefter återkopplingen du fick. Denna reflektion skrivs ner i din README.md.
Krav för VG
Du använder dig av fallbacks för äldre browsers så att din sida fungerar väl på även äldre browsers.
Du har testat sidan i flera olika browsers och sidan har ett konsekvent beteende och design: Safari, Chrome, Firefox, Microsoft Edge samt Internet Explorer 11 (viss variation får förekomma men inga större fel ska synas).
Du använder dig utav feature queries för hantera fall där vissa egenskaper inte stödjs.
Du använder dig utav vendor prefixing på de egenskaper som behöver detta. Se: shouldiprefix.com.
Din sida fungerar väl på på både Android samt iOS.

Feedback:

Hej Brandon.

Nu har jag kollat genom din Arboreal uppgift. 
Jag vill bara påpeka att allt kanske inte är så smidigt formulerat av mig, detta är som sagt bara sett från min synvinkel. :slightly_smiling_face: Lite stressad för allt man ska hinna med.

Bra att du har fått med uppgiftens innehåll och att navlänkarna fungerar fint. 

Här kommer mina tips och synpunkter:

Färg och form.
Det är väldigt mycket som händer på sidan så att använda färre bakgrundsmotiv, kanske 1 av motiven som man använder tillsammans med bakgrundsfärg skulle kunna ge ett luftigare mer lättläsligt intryck.
Med 1 eller 2 bakgrundsfärger till brödtext samt att använda en och samma färg på text, ev med  komplementerande färgval i rubriker.

HTML
Stundtals svårt att se vart divarna börjar och slutar.
Eventuellt skulle en del av divarna kunna bytas ut till semantisk HTML
som <article><section><header><main><footer>

Kontaktformuläret.
HTML  labels saknas i kontaktformuläret.
Input type “text” på telefonnummer bör vara “number”.
Lägga till placeholder samt Id (input).

Footer
Länka Ikonerna till sociala medier sidorna.

Övrigt
Validering av HTML och CSS saknas.

CSS
Bra att du har hållt dig till klasser/ taggar.
Använda samma måttenheter så långt det går (px,em)


Väldigt intressant att titta på någon annans kod. Nu är ju detta enbart mina tankar om din Arboreal uppgift.

Brandons kommentar:

Grymt bra feedback, jag uppdaterade min uppgift med samtliga punkter förutom att lägga input type="number" på telefonnummer, då
det medföljer en scroll för att scrolla igenom siffror, vilket inte var nödvändigt på denna sida.

