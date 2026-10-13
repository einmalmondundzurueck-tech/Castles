# Bildprompts für die neuen Bittsteller und Ereignisse

## So gehst du vor

1. Öffne in Gemini einen neuen Chat und lade **das Bauer-Bild als Vorlage** hoch. Gemeint ist das Bild mit dem zerlumpten Bauern vor dem König.
2. Kopiere den **Basis-Prompt** (unten) und hänge den **Abschnitt der gewünschten Figur** darunter.
3. Wenn ein Bild passt, lade es als JPG herunter und benenne es nach dem **Schlüssel**, zum Beispiel `alchemist.jpg`.
4. Schick mir die Bilder. Ich trage sie im Spiel ein und verkleinere sie bei Bedarf.

Tipp: Mach alle Bilder im selben Gemini-Chat und lade die Vorlage immer wieder mit hoch. Dann bleiben König, Saal und Stil am einheitlichsten. Wenn ein Bild stilistisch abweicht, hilft: „Halte dich genauer an den Stil und den Bildaufbau der Vorlage.“

---

## Basis-Prompt (immer zuerst einfügen)

```
Erstelle ein neues Bild im exakt gleichen Stil wie das hochgeladene Vorlagenbild:
detailreiche 16-Bit-Pixelart wie in klassischen DOS-/Amiga-Rollenspielen der frühen 90er,
sichtbare Pixel, begrenzte warme Farbpalette, weiche Dithering-Schatten, Querformat 16:9
(etwa 1100 × 614 Pixel).

Schauplatz und Bildaufbau wie in der Vorlage: mittelalterlicher Thronsaal aus grauem
Quaderstein, Spitzbogenfenster mit hellem Licht im Hintergrund, brennende Wandfackeln,
roter Vorhang rechts. Rechts sitzt derselbe König wie in der Vorlage auf dem steinernen
Thron: goldene Krone, rote Robe mit Hermelinkragen, brauner Bart, nachdenklich das Kinn
auf die Hand gestützt. In der Bildmitte steht ein Wachmann in Kettenhemd mit Hellebarde.
Links im Hintergrund stehen einige Höflinge und Mönche in schlichten Gewändern und schauen zu.

Die neue Figur steht links von der Bildmitte, dem König zugewandt, gut sichtbar im
Vordergrund, etwa so groß wie der Bauer in der Vorlage. Kein Text, keine Schrift,
kein Rahmen, keine Wasserzeichen.

Die neue Figur und die Szene:
```

---

## Bittsteller im Thronsaal

### `fluechtlinge` — Flüchtlinge aus dem Grenzland
```
Eine kleine Gruppe erschöpfter Flüchtlinge: vorn ein Mann mittleren Alters mit
rußverschmiertem Gesicht und zerrissenem Umhang, der flehend die Hände hebt; neben ihm
eine Frau mit Kopftuch, die ein kleines Kind an sich drückt, dahinter ein alter Mann
mit Wanderstab und Bündel über der Schulter. Staubige, angesengte Kleidung — sie sind
vor brennenden Dörfern geflohen. Stimmung: verzweifelt, aber hoffnungsvoll.
```

### `alchemist` — Der Alchemist
```
Ein hagerer Alchemist in langem schwarzem Gewand mit silbernen Sternen- und
Mondsymbolen am Saum, spitzer Bart, stechender Blick, ein Lederbeutel am Gürtel.
In der erhobenen Hand hält er einen glühenden Glaskolben mit goldener Flüssigkeit,
vor ihm auf einem kleinen Tisch ein Tiegel, ein Bleibarren und ein paar Goldmünzen.
Ein leichter grünlicher Rauch steigt auf. Stimmung: verheißungsvoll, etwas zwielichtig.
```

### `turnier` — Der Herold
```
Ein stolzer Herold in einem geteilten Wappenrock (rot und gold) mit einer langen,
geraden Fanfare, an der ein Wappenbanner hängt. Er verbeugt sich leicht und hält in
der anderen Hand eine entrollte Pergamentrolle. Im Hintergrund lehnt neben ihm ein
verzierter Turnierhelm mit Federbusch an einer Turnierlanze. Stimmung: festlich, feierlich.
```

### `wilderer` — Der Förster und der Wilderer
```
Ein kräftiger Förster in grünem Wams und Lederkappe, Jagdhorn am Gürtel, führt einen
gefesselten, mageren Wilderer an einem Strick vor den Thron. Der Wilderer kniet in
abgetragener brauner Kleidung, die Hände vorn zusammengebunden, und blickt flehend
zum König. Vor ihnen liegt ein erlegter Hirsch auf dem Steinboden.
Stimmung: angespannt, bittend.
```

### `wilderer_folge` — Die Wildererbande
```
Ein Bote in staubigem Reisemantel berichtet dem König aufgeregt mit ausgestrecktem Arm.
Durch das Fenster im Hintergrund — oder als Bild im Bild auf einer Pergamentkarte, die er
hochhält — sieht man eine Bande vermummter Wilderer mit Bögen, die mit gestohlenen
Säcken und einem Rehbock in den Wald fliehen. Stimmung: Alarm, Ärger.
```

### `gilde` — Der Gesandte der Kaufmannsgilde
```
Ein wohlgenährter, reich gekleideter Kaufmann in dunkelblauem Samtmantel mit Pelzbesatz
und breitkrempigem Hut, Goldkette mit Gildenabzeichen um den Hals. Er breitet eine
Seekarte von Flandern aus, auf der ein Handelsschiff (Kogge) eingezeichnet ist; neben ihm
eine kleine Truhe mit Tuchballen und einer Waage. Stimmung: geschäftstüchtig, einladend.
```

### `baumeister` — Der berühmte Baumeister
```
Ein älterer, selbstbewusster Baumeister mit grauem Bart, Lederschürze über einem
erdfarbenen Gewand und einer Gelehrtenmütze. Unter dem Arm trägt er gerollte Baupläne,
in der Hand einen großen hölzernen Zirkel, ein Winkelmaß hängt am Gürtel. Vor ihm ist ein
Pergament mit der Zeichnung einer Kathedrale auf einer Staffelei aufgestellt.
Stimmung: stolz, kompetent.
```

### `soeldner` — Der Söldnerhauptmann
```
Ein vernarbter, grimmiger Söldnerhauptmann in zusammengewürfelter Rüstung: Brustpanzer
über einem gesteppten Waffenrock, ein Langschwert über der Schulter, ein Auge mit einer
Augenklappe bedeckt. Er hält dem König mit einem schiefen Grinsen die offene Hand hin.
Hinter ihm warten zwei raue Söldner mit Speeren. Stimmung: gefährlich, käuflich.
```

### `spion` — Der gefangene Spion
```
Zwei Wachen halten einen gefangenen sächsischen Spion an den Armen fest. Der Spion trägt
einen dunklen Kapuzenmantel, die Kapuze ist ihm vom Kopf gerutscht, er presst trotzig
die Lippen zusammen. Auf dem Boden vor ihm liegen beschlagnahmte Zeichnungen der
Burgmauern auf Pergament und ein Stück Kohle. Stimmung: misstrauisch, verschwiegen.
```

### `verraeter` — Der enttarnte Verräter
```
Ein enttarnter Verräter wird von einer Wache gepackt — ein Mann in schlichter
Flüchtlingskleidung, aus dessen aufgerissenem Bündel goldene Münzen und ein kleiner
Kelch aus der Schatzkammer auf den Steinboden fallen. Er blickt erschrocken über die
Schulter. Ein Höfling zeigt anklagend mit dem Finger auf ihn.
Stimmung: Empörung, Schreck.
```

### `silberfund` — Die Steinmetze mit dem Silberfund
```
Zwei staubbedeckte Steinmetze in grauen Arbeitskitteln und Lederschürzen, einer mit
Spitzhacke über der Schulter, der andere hält dem König mit beiden Händen einen
Gesteinsbrocken entgegen, in dem eine glänzende Silberader schimmert. Sie flüstern sich
verschwörerisch zu. Stimmung: aufgeregt, heimlich.
```

---

## Ereignisse (Szenen außerhalb des Thronsaals)

Bei diesen drei Ereignissen tritt niemand vor den König. Ich empfehle eine Szene im Dorf
oder im Burghof, im selben Pixelstil. Ersetze dafür im Basis-Prompt den zweiten Absatz
(Thronsaal, König, Wache) durch den folgenden Text und die Szene darunter.

```
Schauplatz: statt des Thronsaals eine Außenszene im selben Stil und mit derselben
Farbpalette — ein mittelalterliches Dorf bzw. ein Burghof mit Fachwerkhäusern,
Strohdächern und grauer Burgmauer im Hintergrund.
```

### `unwetter` — Der Hagelsturm
```
Ein Hagelsturm über den Feldern vor dem Dorf: dunkle, bleigraue Wolken, weiße
Hagelkörner prasseln herab, das reife Korn liegt platt gedrückt. Ein paar Bauern stehen
verzweifelt am Feldrand, einer hält sich schützend einen Sack über den Kopf.
Im Hintergrund oben auf dem Hügel die Burg. Stimmung: düster, Verlust.
```

### `seuche` — Die Seuche
```
Eine enge Dorfgasse in fahlem, grünlich-grauem Licht. Ein Kranker liegt auf einer
Strohmatte vor seiner Hütte, eine Frau mit Tuch vor dem Mund bringt ihm Wasser.
An einer Tür ist ein Kreidekreuz gemalt, eine Ratte huscht durch die Gasse, ein
Pestarzt mit Schnabelmaske ist in der Ferne zu sehen. Stimmung: bedrückend, still.
```

### `brand` — Feuer im Burghof
```
Nacht im Burghof: aus dem Dach eines hölzernen Wirtschaftsgebäudes schlagen hohe
orange Flammen, Funken und Rauch steigen auf. Knechte und Mägde bilden eine
Eimerkette zum Brunnen, eine Wache ruft mit erhobenem Arm Befehle.
Der Feuerschein spiegelt sich auf dem Pflaster. Stimmung: Hektik, Gefahr.
```

---

## Optional: weitere Bilder für die neuen Spielteile

Diese Stellen zeigen bisher nur ein Symbol. Wenn du magst, kannst du auch dafür Bilder
machen — ich baue sie dann ein.

### `lehnseid` — Ein Fürst leistet den Lehnseid (Thronsaal)
```
Ein Landesherr in Reisemantel mit Wappen kniet vor dem König und legt seine gefalteten
Hände in die Hände des Königs, der sich vom Thron vorbeugt. Ein Schreiber hält eine
gesiegelte Urkunde. Stimmung: feierlich, Treue.
```

### `feldzug` — Der Feldzug zieht aus (Außenszene)
```
Am Burgtor zieht ein Trupp Soldaten mit Speeren, Bogenschützen und dem königlichen
Banner hinaus in hügeliges Land. Im Vordergrund verabschiedet der König die Truppe
von einem Pferd aus. Stimmung: aufbrechend, entschlossen.
```

### `hochkoenig` — Krönung zum Hochkönig (Kathedrale)
```
Im Inneren einer großen gotischen Kathedrale mit bunten Glasfenstern setzt ein Erzbischof
dem König eine prächtigere, größere Krone auf. Links und rechts knien Fürsten und Ritter
mit Bannern. Lichtstrahlen fallen durch die Fenster. Stimmung: Triumph, Höhepunkt.
```

### `winter` — Der lange Winter (Außenszene)
```
Die Burg im tiefen Winter, eingeschneit und von feindlichen Zelten und Lagerfeuern
eingeschlossen. Auf der Mauer stehen frierende Wachen in Umhängen, im Burghof werden die
letzten Vorräte aus dem Lagerhaus verteilt. Stimmung: kalt, angespannt.
```
