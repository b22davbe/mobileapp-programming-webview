
# Rapport
Inläming 2: WebView

Först så forkades och klonades projektet ifrån github. Efter det byttes namnet på appen till "Davidsappeliappapp".
Därefter aktiverades internet till appen som visas i kodsnutten här under:
```
<uses-permission android:name="android.permission.INTERNET"/>
```
Sedan byttes TextView ut mot WebView där WebView har fått ett eget ID.
Det skapades också en variabel: myWebView som initieras när programmet startar.
Därefter lokaliseras WebView-elementet med ID:t som tidigare skapats.
Sedan skapades en ny WebViewClient som länkas ihop med WebView som i kodsnutten nedan:
```
myWebView.setWebViewClient(new WebViewClient());
```
Efter det så tilläts javascript in i WebViewClient.
Sedan gjordes en html-fil fylld med endast lorem ipsum text och till slut 
så implementerades det så att his.se dyker upp om man klickar på external webpage
och man kommer till html-sidan med lorem ipsum text om man klickar på internal webpage.



Bilder läggs i samma mapp som markdown-filen.

![](extern.png);
![](intern.png);

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
