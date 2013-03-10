# JAGD - Just Another Google Dorker

Jagd ist zwar ein weiterer Google Dorker, zeichnet sich aber durch eine aktive
Entwicklung und vielen brauchbaren Features aus.


### Verbesserte Resultate

Dies zeichnet sich bereits in den Ergebnissen ab. Viele Dorker haben entweder
wenige Resultate oder viele False-Positives. Dies kann viel Zeit rauben. Aus
diesem Grund werden zuerst die Parameter auf deren Verhalten geprüft. Erst wenn
diese dynamisch sind, werden sie auf Lücken getestet. Beim Test wird dann nur
der hinzugekommene Text überprüft. So können Blogeinträge über SQL-Injections
oder Ähnliches keine False-Positives mehr verursachen. Zusätzlich sind die Fünde
in verschiedene Gruppen eingeteilt, die eindeutige Lücken von eventuellen Lücken
trennt.


### Viele Injection-Techniken

Zusätzlich zu der Get-Injection werden weitere Injection-Techniken wie die Subdomain-
Injection, Useragent-Injection und Referer-Injection verwendet. Das erhöht die
Treffer und deckt viele unbenutzte Lücken auf.


### Hohe Leistung

Dank asynchronen Scans wird die Zeit sinnvoll genutzt und während des Suchens
einer neuen Seite die alte Seite auf Lücken überprüft. Auch wird durch Multi-
Threading die reibungslose Arbeit mit der GUI und die gleichzeitige Nutzung
vom Dorker und AutoPWNer ermöglicht.


### AutoPWNer

Um die verbesserten Resulate gemütlich auszunutzen, wurde der AutoPWNer
implementiert. Dieser ermöglicht ein automatisiertes Dumping oder Back-
dooring durch SqlMap.


### Intuitive GUI

![Dorker](http://www1.xup.in/exec/ximg.php?fid=57425029)
![AutoPWN](http://www1.xup.in/exec/ximg.php?fid=86547005)
![Settings](http://www0.xup.in/exec/ximg.php?fid=12577735)



#### Features:
- Asynchronous google dorking
- Language search
- Error-based SQLI-Check
- Subdomain SQLI-Check
- Useragent SQLI-Check
- Referer SQLI-Check
- Dump by SqlMap
- Backdoor by SqlMap
- Intuitive GUI




#### ToDo:
- Proxy-Support
- LFI-Scanner
- RFI-Scanner
- Boolean-based SQLI-Check
- New String filtering
- Safe-mode off