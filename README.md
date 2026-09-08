# LS25_Real_Physik_Reifenverschleiss


erweitert den Farming Simulator 25 um ein eigenständiges und deutlich detaillierteres Verschleißsystem für Reifen und Bandlaufwrke und Kettenfahrwerke.

Reifen und Raupenfahrwerke Kettenfahrwerke nutzen sich abhängig von der tatsächlich zurückgelegten Strecke, der Belastung durch Schlupf und diverse anderer Faktoren ab. Es spielt jetzt eine Rolle wie dein Fahrwrhalten ist, auf welchen Boden du unterwegs bist, welche Wettereinflüsse es gibt, welches Gewicht du bewegst und wie die dynamische Lastverteilung auf deine Räder oder Fahrwerke wirkt. Der Verschleiß wird individuell für jedes Fahrzeug und jedes Rad/Fahrwerk erfasst und gespeichert und ist damit unabhängig vom normalen GIANTS-Fahrzeugverschleiß. Das gilt für alle in deinem Hofbesitz befindlichen Fahrzeuge. Gekauft, gemietet, geleast. Ki Traffic Fahrzeuge, oder von anderen Höfen, oder Maschinen und Geräte die für eine Mission "gemietet" wurden werden nicht erfasst.

Ziel der Mod ist ein realischtische optische Verschleißabnutzung der Räder, Band und Kettenfahrwerke sichtbar darzustellen, jeweils aktuell zum tatsächlchen Verschleiß. Unterstützt werden klassische Radfahrzeuge ebenso wie Maschinen mit Gummi- und Kettenlaufwerken. Auch Anhänger und Anbaugeräte mit eigenen Rädern werden berücksichtigt und erfasst. Für Band und Kettenwahrwerke werden entsprechend ihrem tatsächlichen Aufbau auch Laufrollen in den Verschleiß mit einberechnet und seperat über ein Kombisymbol angezeigt. Getestet wurden die meisten Ingame Fahrzeuge als auch viele Mods. eine 100% kompatibilität gibt es nicht, aber weit über 90% auf jedenfall. Verzeintelt kann noch nciht alles erfasst werden, Zweiräder, Drikes, Sondermaschinen (mods)können eventuell inkompatible sein. Es wird aber weiter an der Kombatibilät gearbeitet. Für spezielle Mods benötige ich aber die Mod selber mit ihren i3d dateien und UV Masken, i3d Mapping/Shapes, sowie die Fahrzeug xmls. Nur dann kann ich schauen ob es dafür eine Machbarkeit gibt.

Mit zunehmender Abnutzung verändert sich nicht nur die optische Darstellung. Stark verschlissene Reifen verlieren zunehmend an Traktion und beeinflussen dadurch das Fahrverhalten. Es gibt jetzt eine Tragheitsverschiebung/verzögerung die dein Fahrzeug rutschen lassen. Beim Anfahren, beim Bremsen, beim Einlenken. Reifen und Fahrwerke und laufrollen können über die Werkstatt erneuert werden; die Kosten berücksichtigen unter anderem Fahrzeugtyp, Anzahl und Größe der Reifen bzw. Laufwerkskomponenten und es gibt einen kleinen Faktor abhängig des gewähltem Kilometer-Referenzwertes.

Die gewünschte Referenz-Lebensdauer kann in den Einstellungen angepasst werden. Zur Auswahl stehen 350, 500 und 750 km für kleinere bzw. klassische 2×2-Maps sowie 1000, 1500 und 2000 km für größere 4×4-Maps und entsprechend längere Einsatzzeiten. Wichtig zu wissen ist, das 1000km nicht bedeuten der Reifen/Fahrwerk hält mindestens 1000km, der Referenzwert ist die Berechnungsgrundlage für die Verschleißabnutzung. Der Reifen wird daher eher weniger halten, kann aber auch länger halten. Das liegt jetzt am Fahrverhalten und Arbeitstätigkeit und Belastung.

Weiterhin unterstützt die Mod die Verschließberechnung über Ki gesteuerte Fahrzeug, also Courseplay, Autodrive und Giants KI. Damit dies sauber funktioniert wurde von mir eine elektronische Wegfahrsperre entwickelt die speziell dazu das Fahrzeug bis nach der Startphase und Initialisierung aller Systeme, blickiert und von außen keinen Eingriff zulässt. Dies ist notwendig da CP und AD die eigens von Giants vorgesehen Startphase umgehen. Daher könnte es sonst zu unsauberen Zuständen kommen, und zu ungewollten Problemen. Stell dir einfach eine Parkbremse 2.0 vor, sobald das Fahrzeug startbereit ist, schaltet sich die EWFS ab und alles ist wie immer.

Es gibt zu dem 3 Malis in der Mod. Erstens einen Traktionsverlust der Reifen und Fahrwerke je nach deren Abnutzungszustand. Es wird aber so sein, das man das Fahrzeug noch zur Werkstatt fahren kann, mit entsprechenden Handicap und ggf. ohne Anhänger. Als weiters gibt es ein Tempomalus im KI Mode. Der KI-Tempomat wird bis auf 20kmh gedrosselt, je nach Abnutzung, damit eine Fahrzeug/Routensteuerung noch möglich ist. Bei normalen Geschwindigkeiten ist AD mit rutschenden Reifen und Traktionsverlust nicht mehr in der Lage das auszugleichen. Wenn du das Fahrzeug manuel fährst gibt es keine Beschränkung, aber entsprechnde Handicaps.
Als drittes gibt eines einen Malus auf die maximale Geschwindigkeit bei Bandfahrwerken und Kettenfahrwerken. Je nach Abnutzung der inneren Laufrollen gibt es bis zu 50% Maximalgeschwindigkeitmalus. Wenn die Laufrollen erneuert wurden, verschwindet auch der Malus wieder.

In Verbindung mit FS25 Lights & Symbol HUD können die aktuellen Verschleißzustände direkt im HUD dargestellt werden. Rad-, Fahrwerks- und Anhängerzustände werden dabei getrennt visualisiert. Auch die entsprechenden Laufrollen werden als Kombisymbole angezeigt. Es wird daher empfohlen die Lights and Symbol HUD mit zu installieren. Wem es nicht gefällt, kann sie in den Settings auch komplett ausblenden.



keine Abnutzung des Reifen
<p align="center">
  <img src="Reifenverschleiss0.png" alt="Mod Icon">
</p> 
Voll abgenutzter Reifen
<p align="center">
  <img src="Reifenverschleiss1.png" alt="Mod Icon">
</p>
nicht abgenutztes Kettenfahrwerk
<p align="center">
  <img src="Reifenverschleiss3.png" alt="Mod Icon">
</p>
Voll abgenutztes Kettenfahrwerk
<p align="center">
  <img src="Reifenverschleiss2.png" alt="Mod Icon">
</p>
nicht abgenutztes Bandfahrwerk
<p align="center">
  <img src="Reifenverschleiss5.png" alt="Mod Icon">
</p>
Voll abgenutztes Bandfahrwerk
<p align="center">
  <img src="Reifenverschleiss4.png" alt="Mod Icon">
</p>

<p align="center">
  <img src="HUD4.png" alt="Mod Icon">
</p> 

Release-Version: 1.2.0
Autor: duestereLegende



