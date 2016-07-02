# Unterschied Web Site – Web App

Ergebnisse der Hausaufgabe auf den 1. Juli 2016.

## Anmerkungen Josef

Zuallererst muss ich gestehen, dass ich die Aufgabe mit gewissen Hintergedanken gestellt habe. Über den Begriff «Web App» herrscht in der Fachwelt nämlich keinen Konsens. So wird er besipielsweise von Verfechtern des *Progressive Enhancement* in Frage gestellt. Je nachdem wen man fragt, erhält man stark abweichende Definitionen des Begriffs und so würde ich ihn nicht zur Fachterminologie rechnen, sondern eher als Vehikel für Ideologien bezeichnen, vielleicht sogar als hohle Floskel mit dem Zweck, die schale Luft in Sitzungszimmern mit dem Duft von Innovation aufzufrischen.

Das Nachdenken über die Frage, wie sich Web Sites und Apps unterscheiden, ob sie sich abgesehen von ihrer technischen Grundlage überhaupt unterscheiden und ob man Zwischenstufen definieren soll, halte ich aber für durchaus sinnvoll.

Wichtiger als die Unterscheidung zwischen App, Web App und Web Site ist jene zwischen *native* und *web*. Ersteres bedeutet immer die Abhängigkeit von einem Betriebssystem und wahrscheinlich auch von einem zentralisierten Vertrieb (App Store) und dessen Geschäftsbedingungen. Argumente für oder gegen «Native» haben auch eine politische Dimension, die man nicht ausser Acht lassen sollte.

Eine wichtige Entwicklung, die gegenwärtig stattfindet, ist die Möglichkeit, dass eine Web Site über einen sogenannten *Service Worker* im Hintergrund verfügen kann: Das ist ein Script, das bestimmte Funktionen ermöglicht, die bisher Native Apps vorbehalten waren. Dazu gehören u.a. das Funktionieren ohne Verbindung zum Internet, das Laden von Daten im Hintergrund (ohne dass die Web Site im Browser geöffnet ist), das Erhalten von Push-Nachrichten und die Verwendung der *Geolocation*.

*Es folgen die Resultate der Recherche. Ich habe mir teilweise kleine Änderungen erlaubt, um Begriffe anzugleichen, etwa «Web Site» statt «Webseite». Wo es mir notwendig erschien, habe ich Anmerkungen angefügt.*

### Weiterführende Lektüre

* [Why Britain banned web apps](https://www.instapaper.com/read/733226787)
* [Maybe we could tone down the JavaScript](https://eev.ee/blog/2016/03/06/maybe-we-could-tone-down-the-javascript/)
* [Jeremy Keith – Regressive Web Apps](https://adactio.com/journal/10708) 

## Mischa Kreis

### Unterschied zwischen Web Site und Web App

Meine Kommentare sind _kursiv_. Gewisse Stellen aus Quellen sind **fett** hervorgehoben, da ich entweder darauf bezug nehme, oder sie mir als wichtig erscheinen.

#### Wikipedia

[Web Application:](https://en.wikipedia.org/wiki/Web_application) […]The general **distinction between an interactive web site of any kind and a "web application" is unclear.** Web sites most likely to be referred to as "web applications" are those which have **similar functionality to a desktop software application** […]

[Website](https://en.wikipedia.org/wiki/Website) […] A website, also written as web site,[1] is a collection of related web pages, including multimedia content, […]

_Wabseiten können Webapplikationen enthalten. Das umgekehrte wäre dann bei nativen Apps möglich [(Hybrid apps embed a mobile web site inside a native app, […])](https://en.wikipedia.org/wiki/Web_application)._

#### Stack Overflow

[Aus der Konversation:](http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application)

**Websites are primarily informational**. In this sense, http://cnn.com and http://php.net are websites, not web applications.

**Web applications primarily allow the user to perform actions.** Google Analytics, gmail, and jslint are web applications.

**They are not entirely exclusive.** A university website likely gives information such as location, tuition rates, programs available, etc; it will likely have web applications that allow teachers to manage grades and course materials, applications for students to register for and withdraw from courses, etc.

#### Difference btw	

[Difference Between Web Application and Website:](http://www.differencebtw.com/difference-between-web-application-and-website/)

_Die Angaben hier erscheinen mir etwas zwiespältig:_ 

[…]
Following are some main differences between web application and website:

* **Web application is the part of website.** It is itself not a complete website. While website is that complete product, which you see on your browser.
* Web application functions and tasks are much higher and complex than website. Website just shows the collected data and information in an order on a page. **Web application actually maintains the whole website.**

_Anders ausgedrückt würde das heissen, eine Webseite besteht nur dank einer Web Applikation, welche «die Webseite verwaltet»? Das ist doch Unsinn, eine Webseite kann ja auch nur aus einem einzigen HTML-Dokument bestehen; wo ist denn da die Applikation?_  

* Website is a source of information while web application works interactively.

 _Auch hier gibt es die zweifelhafte Differenzierung mittels des Begriffs der Interaktion: wieso ist die Benutzung einer Webseite keine Interaktion?_

* Website works on a web browser while web application runs and used separately on computer.

_Stimmt das? Ich denke nicht; drum heisst es doch auch Web Applikation und nicht Desktop Applikation … ? Der Verfasser widerspricht sich da ja selbst – beim ersten Punkt seht sogar: «Web application is the part of a website.»_

* Developing a website is more easy and low cost project in compare to developing website application. Different platforms are required to develop website application.

_Naja, nicht sehr informativ._

* Website is easily ascertainable through any operating system and device. Just insert the URL and get the desired result. While in website application first you have to download and install it to make it useful.

_Tatsächlich? Ist es nicht so, dass für beide ein Browser benötigt wird; deshalb auch der Unterschied zwischen Web Applikation und Desktop Applikation (s.o.)._

#### Twitter
_Scheint wohl allgemein nicht ganz klar zu sein:_

[Jen Simmons:](https://twitter.com/jensimmons/status/739505357790302208) **In a world where the web is divided in two — web apps vs web sites** — where does a newspaper content ‘native’ app fit if it moves to the web?

[Jen Simmons:](https://twitter.com/jensimmons/status/739507974113251329) I ask these questions because **I sincerely want to understand what we collectively mean when we say: that’s not a website, that’s a web app**

_Frau Simmons scheint über die Unterscheidung auch im Unklaren zu sein_

[Sibylle Weber:](https://twitter.com/sibweber/status/739696003901751296)
@jensimmons To me: **web app = tool**, used to complete a task. **website = information**, standalone or wrapper for app (i.e. store)

[Adam Hill](https://twitter.com/adshill/status/739512244711624704) @jensimmons a web “app" is an application, **it requires interaction (login, update etc.)** a web "site" is the one way provision of pages.

_Wenn ich auf einer x-beliebigen Seite die Menünavigation bediene (was ja wohl überall vorhanden ist), ist das dann keine «Interaktion»?_

[John Allsopp:](https://twitter.com/johnallsopp/status/739727517938941953) @adshill @jensimmons **what's the purpose of the distinction?**

[John Allsopp:](https://twitter.com/johnallsopp/status/739727517938941953) I'm not sure it's a case of needing them to be distinct. But **if it's unclear, they do need to be defined.**

_Zur letzter Aussage fügt der Herr allerdings keine Erläuterung hinzu._


#### Erklärungsversuch

_Grundlegend scheint mir die Erläuterung mit Google- oder Apple-Produkten nachvollziehbar: im Browser können Präsentationen oder Tabellen quasi von Grund auf erstellt werden – durch den Input des Users (diese so entstandenen Files sind wiederum auf den entsprechenden Desktop-Applikationen weiterverwendbar – was aber nicht Teil der Definition ist; aber dem Verständnis hilfreich ist). Grundsätzlich können mit Web-Applikationen Dinge entstehen, **die nur mit der Eingabe des Users erst möglich sind**. Bei einer Webseite «konsumiert» der User lediglich. Und um beim Beispiel Google zu bleiben: bei einer Sucheingabe interagiere ich zwar ebenso; doch entsteht dabei nichts neues (zumindest nichts, was ich als User beeinflussen kann) – ich erhalte lediglich eine Liste von Inhalten die es bereits gibt._

## Peter Motter

Die Diskussion wurde im Web offenbar um 2013 intensiv geführt und hat sich seither beruhigt (Beispiele: [Stackoverflow] [1], [Vision Mobile Blog] [2] ). Ich vermute, die Unterscheidung hat u.a. an Bedeutung eingebüßt durch das Aufkommen des responsiven Ansatzes, der das Design für mobile Geräte nicht mehr isoliert betrachtet.

Ich bin auf (härtere) *technische* und (weichere) *inhaltlich-funktionelle Unterscheidungskriterien* gestoßen.

### Technische Merkmale einer Web App

+ **Single-Page-Design** – im [HTML-Seminar] [3] wird der Trend, komplette Websites in Einzeldateien zusammenzufassen, um sie dann ausschnittweise darzustellen, mit dem Vorteil kürzerer Latenzzeiten beim Laden der Web App erklärt. Mobile User haben dadurch, wie beim Download einer nativen App, nur eine einmalige Wartezeit.
+ **Einbindung der Geräte-Hardware** (Geolocation, Kamera,...)
+ **Offline funktionsfähig** mit automatischer Synchronisierung
+ **Komplexes User Interface** mit visuellen Anklängen an native Apps und das UI des Geräts und Unterdrückung der browsereigenen Navigationstools

### Inhatlich-funktionelle Unterschiede

+ Web-Site wird tendenziell passiv konsumiert und zeigt im Wesentlichen allen Besuchern die gleichen Inhalte an (**"read-only"**) 
+ Web-App verarbeitet individuellen **User-Input**
+ Web-App fokussiert auf die schnelle **Erledigung abgegrenzter, spezifischer Aufgaben**, die früher eine installierbare, somit plattformabhängige Software erfordert hätten 
	
[1]: http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application	"Stackoverflow"
[2]: http://www.visionmobile.com/blog/2013/07/web-sites-vs-web-apps-what-the-experts-think/	"Vision Mobile Blog"
[3]: http://www.html-seminar.de/unterschied-seitenaufbau-fuer-mobiles-www.htm	"HTML-Seminar"

## Fabienne Koller

Eine Webseite wird von ihrem Inhalt (klassische Informationen) definiert, eine Web App wird durch ihre Interaktion mit ihren Usern definiert ([Stackoverflow.com, Antwort in einem Chat](http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application)).  Bei einer Webseite steht auf der Nutzerseite das Konsumieren des Inhalts im Vordergrund, bei einer Web App das «Mitgestalten» (Visionmobile.com).
«Eine Web App ist auch eine Webseite technisch gesehen, wichtig ist aber dass der User viel interagiert und z.Bsp. Arbeit erledigen kann. Klassische Informationen im Web = Webseite. Genau Grenzen zwischen Website und Web App gibt es aber nicht. Facebook hat beides: Viele Infos (Website) und auch viele Nutzer Interaktionen (Web App).» (Dave, Kollege, Programmierer).

## Regi Müller

### Web-Apps sind:

– im Browser aufrufbar, Geräteunabhängig
– müssen nicht auf dem Gerät installiert werden (gegenüber App)
– hat meistens einen Service- oder Lösungsgedanken
– Interaktion mit dem Nutzer (z.B. einen Anruf, E-Mail abrufen, ein Taxi finden, integrierte Kamera …)
– kann den Inhalt dem Nutzer anpassen (z.B. Anfrage von Daten)
– Inhalt kann durch den Nutzer angepasst werden
– mehr Aktions- als Informationsorientiert
– können Offline verwendet werden, werden aktualisiert, sobald man online geht (HTML5) *Anm. das Stichwort hierzu ist «service worker»*

### Quellen:

- [stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application](http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application) 
- [www.visionmobile.com/blog/2013/07/web-sites-vs-web-apps-what-the-experts-think/](http://www.visionmobile.com/blog/2013/07/web-sites-vs-web-apps-what-the-experts-think/) 
- [www.das-webjournal.com/mobilemarketing/unterschied-app-mobile-webseite.htm](http://www.das-webjournal.com/mobilemarketing/unterschied-app-mobile-webseite.htm) 
- [www.adextra.de/blog/2012/08/app-webapp-oder-mobile-website/](http://www.adextra.de/blog/2012/08/app-webapp-oder-mobile-website/)

## Silvio Demuth

A website might just be static content. A web site is a collection of documents that are accessed via the internet through a web browser. Web sites can also contain web applications, which allow visitors to complete online tasks such as: Search, View, Buy, Checkout, and Pay.

A website is a set of related web pages typically served from a single web domain. A website is hosted on at least one web server, accessible via a network such as the Internet or a private local area network through an Internet address known as a uniform resource locator (URL). All publicly accessible websites collectively constitute the World Wide Web.

Web applications primarily allow the user to perform actions.

A web application would have dynamic content. A web application may be a part of a whole website.

A web application is a software program which a user accesses over an internal network, or via the internet through a web browser.

A web application is a web site that does more than displaying content, it has a business logic. It’s intended for user interactions, performing actual business functions. Compared to web sites, i.e. blogs and news sites, web apps provide a richer user experience.

All modern websites are web applications, including CMS's.

- [stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application](http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application)
- [lionandpanda.com/website-vs-web-application-whats-the-difference/](https://lionandpanda.com/website-vs-web-application-whats-the-difference/)

## Beni Hefti

[praegnanz.de/weblog/mobile-website-oder-web-app](https://praegnanz.de/weblog/mobile-website-oder-web-app)

Soll eine Mobile Website mehr als «App» dargestellt werden oder als «Website». Mit Beispiel.

[www.analog.de/mobile-website-responsive-design-web-app-native-app/](http://www.analog.de/mobile-website-responsive-design-web-app-native-app/)

Tolle Übersicht zu den Begriffen!

## Unterschied Website und App

[www.billiger-telefonieren.de/mobilfunk/unterschied-website-app_201375.html](http://www.billiger-telefonieren.de/mobilfunk/unterschied-website-app_201375.html)

Link komisch, aber alles einfach erklärt.

#### +

* kann auf Kamera oder GPS zugreifen
* Barcodes können mit einem App gescannt werden und Produkt wir direkt im App angezeigt > z.B. für Shopping
* Push-Nachrichten können angezeigt werden > Websites können dies nur eingeschränkt.
* App speichert Daten lokal, was einen Geschwindigkeitsvorteil ist oder ein Offline-Modus kann auch möglich sein, was keine Verbindung zum Internet nötig macht.
* Werden die Apps aus offiziellen Stores genutzt sind diese in der Regel sicherer als eine Website.

#### –

* Mobile persönliche Daten werden von den Apps gesammelt > Was damit geschieht ist nicht immer klar.

## Vanessa Savi

### Web App

Eine Webanwendung (auch Webapplikation oder kurz Web-App) ist ein Anwendungsprogramm nach dem Client-Server-Modell. Zur Kommunikation zwischen Webclient und Webserver wird i.d.R. das HTTP-Protokoll eingesetzt.
Der serverseitige Anteil einer Webanwendung liegt auf einem Webserver. Über eine Internet- oder eine Intranetverbindung kann die Webanwendung *auf dem Webserver aufgerufen und der Webclient im Webbrowser* geladen werden.

### Web Site

Als Webseite (eine Wortzusammensetzung aus Web und Seite), Webdokument, Internetseite oder kurz Seite wird ein Dokument als Bestandteil eines Angebotes oder einer Website im World Wide Web bezeichnet, das mit einem Browser unter Angabe eines Uniform Resource Locators (URL) abgerufen und von einem Webserver angeboten werden kann. In diesem Zusammenhang wird auch von einer HTML-Seite oder einem HTML-Dokument gesprochen.

#### Quelle

[de.wikipedia.org/wiki/Webseite](https://de.wikipedia.org/wiki/Webseite)

### Web Apps vs. klassische Website: Unterschiede im Seitenaufbau

Es gibt einen sehr wichtigen Unterschied zwischen den klassischen Internetseiten und Inhalten für den mobilen Bereich mit Handy und Tablets. *Wir haben ein Geschwindigkeitsproblem bei der Übertragung der Inhalte für mobile Geräte.*

Wer unterwegs gesurft ist, merkt deutlich den Geschwindigkeitsunterschied. Und das erst in zweiter Linie wegen der Bandbreite (sprich Übertragung von Dateimenge) – es liegt oft an den Latenzzeiten. Diese «Antwortzeit», sprich die Zeitspanne zwischen Absenden einer Anforderung und der Antwort (Request) beträgt als Beispiel mit DSL 25 Millisekunden – mobil dagegen 500 Millisekunden (nur als Beispiel, die Zahlen können je nach Anbindung variieren). Und 500 Millisekunden sind eine halbe Sekunde und wenn wir mehr als einen Request haben, dann steigt die benötigte Gesamtzeit schmerzhaft an. Daher versucht man so wenig einzelne Dateien wie möglich zu übertragen und Inhalte zusammenzufassen.

Dies ist sehr wichtig für das Verständnis von Anwendungen für mobile Geräte wie Handys und Tablets. Grundprinzip ist also, dass wir wegen meistens mangelnder Bandbreite und schlechter Latenzzeiten bei mobilen Geräten so wenige Dateien wie möglich über die «Leitung» übertragen und diese klein halten. So wird i.d.R. auch die komplette Anwendung in 1 Datei gepackt und beim ersten Mal übertragen. Das hat den Vorteil, dass der Benutzer nicht jedes Mal warten muss, wenn er mit der Anwendung interagiert sondern nur einmal am Anfang – und diese Daten können auch im Cache des mobilen Devices gespeichert werden.

#### Quelle
[http://www.html-seminar.de/unterschied-seitenaufbau-fuer-mobiles-www.htm](http://www.html-seminar.de/unterschied-seitenaufbau-fuer-mobiles-www.htm)

## Carmen Zanin

ne Native App wird als App für ein bestimmtes Betriebssystem programmiert und über den App-Store vertrieben.
Eine Web-App ist im Prinzip eine Website (HTML 5), die auf mobilen Endgeräten aber aussieht, wie eine App.

Ich denke der grösste Unterschied ist die Programmierung. Eine Web App wird einmal programmiert und kann auf allen Devices abgespielt werden. Für die Native App braucht es für Android eine Version und für iOs eine.

Es ist sicher wichtig, dass man sich ganz klar darüber ist, wie genau die Anwendung genutzt wird. Je nachdem ist die eine Version sinnvoller als die Andere.

### Vorteile Native App

- Direkter Zugriff auf Hardware wie Kamera, GPS, Kalender etc.
- Direkte Grafikprogrammierung für die Endgeräte
- Einfache Installation und Speicherung auf dem Homebildschirm
- kann hohe Datenmengen speichern
- kann Pushmitteilungen senden
- Werbeeffekt durch Verkauf im App Store
- kann offline genutzt werden

### Nachteile Native App

- Verkauf durch Apple, Aktualisierung langsamer, 30% an Apple (Abhängigkeit), muss über den Store aktualisiert werden
- zwei verschiedene Programmierungen, macht sie teurer

*Anm. Interessanter Artikel zum Thema: [Lessons From Five Years in Mobile News Apps: #1 Don’t have a news app.](https://medium.com/swlh/lessons-from-five-years-in-mobile-news-apps-1-don-t-have-a-news-app-c46939195389#.kj9l5krz9) – es geht zwar um News-Apps, die Einsichten lassen sich aber auf andere Kategorien übertragen.*

### Vorteile Web App

- muss nur einmal programmiert werden, günstiger
- kann laufend aktualisiert werden, ohne App-Store-Zulassung sind Updates sehr schnell aktualisiert
- können auch auf dem Homescreen als Apps dargestellt werden

### Nachteile Web App

- langsamer, da vom Netz abhängig
- erschwerte intuitive Nutzung
- es können höchstens 5MB Datenmengen gespeichert werden

Doch mittlerweile gibt es ja bereits Hybrid Apps … die die Vorteile von beiden Varianten nutzen wollen. Doch, wenn ich das richtig recherchiert habe, dann sind diese Apps wiederum erst für sehr spezifische Inhalte sinnvoll, da sie doch einige Bugs haben.

## Daniela Spühler

### Websites

Eine Website wird direkt über den Browser aufgerufen und kann somit von jedem internetfähigen Endgerät genutzt werden. Dies hat den Vorteil, dass ein zusätzlicher Download zur Nutzung der Website entfällt. Aufgrund der Sichtbarkeit für Suchmaschinen können die Inhalte der Website gefunden werden und erreichen meist eine höhere Reichweite als bspw. native Apps. Ein weiterer Vorteil der mobilen Website ist die verhältnismässig kostengünstige Umsetzung. Im Gegensatz zu einer nativen App ist eine Anpassung der Inhalte im Nachhineinin der Regel ohne speziellen externen Zulassungsprozess (wie z.B.  im App-Store) möglich und somit schnell umsetzbar.

Ein Nachteil der Website ist zum einen jedoch, dass immer zwingend eine Internetverbindung bestehen muss, um auf die Website-Inhalte zugreifen zu können. Zum anderen kann über eine mobilen Anpassung der Website noch nicht auf alle Hardware-Funktionalitäten des mobilen Endgeräts, wie bspw. Kamera oder GPS-Funktion, zugegriffen werden.

*Das wird sich in Zukunft ändern, Stichwort «Service Worker».*

### Webapp

Bei einer Web Application handelt es sich um eine Website, die sich in ihrem „Look and Feel“ stark an einer native App orientiert. Allerdings wird sie, wie eine Website direkt über den Browser aufgerufen. Somit entfällt ein zusätzlicher Download zur Nutzung der Webinhalte hier ebenfalls. Ein gelungenes Beispiel einer solchen Web Application stellt die Seite von Facebook dar, die der native App bereits sehr nahe kommt.

![](https://trakken.de/trakkblog/wp-content/uploads/2014/04/tblog_grafik_04_03apr.jpg)

Ein weiterer Vorteil liegt darin, dass für die Web App nur eine Anwendung programmiert werden muss, die alle mobilen Endgeräte bedient. Allerdings kann auch sie nur bedingt auf bestimmte Hardware- Funktionalitäten zugreifen. Auch der Vertriebsweg gestaltet sich etwas schwieriger. Die Existenz muss über bestimmte Schnittstellen publik gemacht werden, sodass der User bei seiner Internetrecherche auf seinem Smartphone oder Tablet automatisch auf eine solche Web App geleitet wird. Die Nutzung ist ausschließlich über einer bestehende Online-Verbindung möglich. Bestimmte Änderungen oder Updates der Webinhalte sind wiederum schnell und ohne große Probleme für alle mobilen Endgeräte umsetzbar.

![](https://trakken.de/trakkblog/wp-content/uploads/2014/04/tblog_grafik_06_03apr.jpg)

#### Links

- [Web Sites vs. Web Apps: What the experts think](http://www.visionmobile.com/blog/2013/07/websites-vs-web-apps-what-the-experts-think/)
- [Vor- und Nachteile von mobilen Websites und Apps](https://www.trakken.de/insights/vor-und-nachteile-von-mobilen-websites-und-apps/)

## Tina Tanner

### Web App

Ziel: Responsive Ansicht der Webseite

#### +

- keine Vorgaben beim Interface Design, Corporate Design der Firma kann besser umgesetzt werden
- läuft Platformunabhängig (Android, WebOS und Windows Phone 7) Multi-Channel-fähige-Anwendungen kann auf beliebigen Endgeräten betrieben werden mit dem vorhanden Webbrowser
(– Möglichkeit der Redaktionellen Betreuung)
- Änderungen müssen nur auf der Webseite vorgenommen werden, geringere Wartungskosten
- Sicherheit: Lücken können sofort behoben werden

#### -

– Hardware-Komponenten wie zum Beispiel Kamera oder Mikrofon können nicht angesprochen werden
– die Interaktivität leidet bei langsamer Internetverbindung, Datenübertragungsgeschwindigkeit spielt eine Rolle
– Übertragungs-Gebühren (besonders Roaming-Gebühren im Ausland) Storage-Technik Cachetspeicher mit 5-10 MB nur für kleine Datenmengen hilfreich.
– keine Offlinebenutzung möglich, man muss immer mit dem Webserver verbunden sein

### Native App

Ziel: Man kann etwas MACHEN mit der App. (*Anm. lässt sich auch mit «Web App», z.B. Google Docs, oder?*)

#### +

+ Hardware-Komponenten wie zum Beispiel Kamera oder Mikrofon können angesprochen werden
+ Änderungen müssen zusätzlich zum Web separat angepasst werden, höhere Wartungskosten

#### -
– vorgegebenes Interface Design
– muss auf jede Platform individuell angepasst werden. (mehr gestalterischer Aufwand, teurer)
– Sicherheit: Sicherheitslückenanfällig

Die Entscheidung für eine Web- oder eine Mobile-App ist gebunden an den Zweck.
Die Abwägung von Faktoren wie Designansprüche, Entwicklungs- und Wartungsaufwand (Plattformabhängigkeit/Sicherheit & Update) und die daraus resultierenden Kosten spielen eine Rolle. Ebenfalls sind Überlegungen zur Verwendung von Hardwarekomponenten (Kamera & Mikrofon), Wichtigkeit der Internetverbindung beim Gebrauch der App und die Übertragungsgebürenkosten für den Endbenutzer sind in Betracht zu ziehen.

### Links

[praegnanz.de/weblog/mobile-website-oder-web-app](https://praegnanz.de/weblog/mobile-website-oder-web-app)
[de.wikipedia.org/wiki/Webanwendung](https://de.wikipedia.org/wiki/Webanwendung) 

## Thea Sautter

### Unterschiede

- die Nutzungsumstände und die Bedienungsparadigmen sind anders
- Eine App ist ein Programm

### Vorteile von mobilen WebSites

*Anm. als* mobile Web Site *bezeichent man in der Regel eine Variante einer Web Site, die für die Anzeige auf kleinen Bildschirmen optimiert ist und die unter einem anderen Pfad auf dem Server abgelegt ist, als die eigentliche Web Site. Wird die Web Site auf einem Mobiltelefon aufgerufen, wird man auf die* mobile Web Site *umgeleitet. Diese Art Web Site ist mit dem Aufkommen von* Responsive Web Design *weitgehend obsolet geworden.*

- es existieren keine Guidelines, der Seitenaufbau ist flexibler
- geräteunabhängig, muss nicht auf jedes Mobile-OS Gerät angepasst werden, damit reduzieren sich die Entwicklerkosten deutlich
- individuelleres Erscheinungsbild, eine freier gestaltete mobile Website ann das Corporate Design einer Firma besser berücksichtigen
- über den Webbrowser eines mobilen Endgerätes abrufbar
- leichter zu warten und erweiterbar
- üblicherweise von Suchmaschinen auffindbar, wird indiziert
- Updates können schneller veröffentlicht werden
- Nachrichten können redaktionell gewichtet und geteasert werden
- lautes Vorlesen ist möglich

### Nachteile von mobilen Websites

- schlechtere Performance
- kein Zugriff auf native Gerätefunktionalitäten möglich

### Vorteile von Web Apps

*Anm. Nicht sicher, ob hier der Begriff «Web App» mit «native» verwechselt wurde?*

- ist als erweiterter Funktionsumfang zum Gerät zu sehen
- Funktionen sind im Vordergrund (wichtig)
- schnelle Auffindbarkeit von Information möglich
- einfache Menupunkte, Buttons und Listen (zeitbasiert oder alphabetisch geordnet)
- müssen nicht betreut werden, datenbankgestützt (*Anm. betreut werden muss alles. Eine Datenbank ist keine zwingende Voraussetzung für eine Web Site / Web App. Siehe «CMS», «dynamische Web Sites»*)
- kurze Texte, kurze Ladezeiten
- Geolocation und direktes Anrufen möglich
- Zugriff auf native Gerätefunktionalitäten wie Adressbuch, GPS
- Vorteil wenn es um Interaktionen und Spiele geht
- auch im Offline-Modus verfügbar
- mit Apps kann Geld gemacht werden, sie können an kommerzielle
-nhalte gebunden werden, sie rentieren aber nur wenn sie einen Mehrwert
-ür User und Betreiber schaffen

### Nachteile von Web Apps

*Anm. Abhängigkeit von Betriebssystem = Native App*

- nur auf einem Betriebssystem lauffähig
- langwierige Freigabe- und Prüfungsprozesse
- nur über App-Marktplätze auffindbar

## Olivier Rieser

### Web Site

- defined by its content
- static content – no interaction. displaying content
- what happens when a request hits the server: return = file already formated = static content
- collection of documents accessible via the internet through a web browser
- a web site can be a web app (web site composed of applic.). more often: a web site has multiple web applications
- a website's role is to inform
- primary aim is to provide informations
- a web site is a collection of related web pages including multimedia content, typically identified with a common domain name and published on at least one web server
- to be read-only
- can be presented as a web app as long as users consume it in a similar way they do a native app
- when designing websites, we need to make sure that the information we want the user to consume is easily accessible

### Web App

- defined by its interaction with the user
- depends on interaction and requires programmatic user input and data processing. provides information as user interact
- what happens when a request hits the server: return=response from an application
- software accessible over an internet network or via the internet through a web browser
- a web app's primarly role is to inform using dynamic content
- primary aim is to make the user take a task. are meant to solve a problem of the user.
- a web application or web app is a client–server software application which the client (or user interface) runs in a web browser.
- domain name and published on at least one web server
- to be read-written
- when designing web applications, we need to make sure that the user is able to complete the task he wants to do

### Links

- [stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application](http://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application)
- [en.wikipedia.org/wiki/Web_application](https://en.wikipedia.org/wiki/Web_application)
- [www.visionmobile.com/blog/2013/07/web-sites-vs-web-apps-what-the-experts-think/](http://www.visionmobile.com/blog/2013/07/web-sites-vs-web-apps-what-the-experts-think/)
- [webapphuddle.com/web-application-vs-website-design-a-fundamental-difference/](https://webapphuddle.com/web-application-vs-website-design-a-fundamental-difference/)
