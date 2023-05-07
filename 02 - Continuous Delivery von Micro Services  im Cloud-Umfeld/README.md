# Continuous Delivery von Micro Services im Cloud-Umfeld

Foliensatz [part-2.pdf](https://github.com/phd4hsma/HSMA/blob/main/02%20-%20Continuous%20Delivery%20von%20Micro%20Services%20%20im%20Cloud-Umfeld/part-2.pdf)

## Live-Beispiel (zum Mitmachen)
Notwendige Resourcen
- GitHub Konto wäre hilfreich
- Neues Repository anlegen (z.B. CD-JAVA)
- Eine simple Java-Datei [NachKaufabschluss.java](https://github.com/phd4hsma/HSMA/blob/main/02%20-%20Continuous%20Delivery%20von%20Micro%20Services%20%20im%20Cloud-Umfeld/NachKaufabschluss.java) im Verzeichnis "java/" erzeugen
- Zum Reiter (Tab) "Actions" wechseln und einen neuen Workflow "set up a workflow yourself" erstellen
- Folgende Datei kann als GitHub Actions File [java.yml](https://github.com/phd4hsma/HSMA/blob/main/02%20-%20Continuous%20Delivery%20von%20Micro%20Services%20%20im%20Cloud-Umfeld/java.yml) verwendet werden.
- Hinweis: Das Deployment wird nicht funktionieren, da am Ende die JAR-Datei auf meinem Server hochgeladen werden soll. Dazu fehlt aber der Servername (SERVER_NAME), Benutzer (SERVER_USERNAME) und Kennwort (SERVER_PASSWORD). Diese in den "Settings - Secrets und Variables - Actions - New Repository secret" anlegen.

## Quellen (Internet)
- [What is Continuous Delivery?](https://continuousdelivery.com/)
- [What is Continuous Delivery?](https://learn.microsoft.com/en-us/devops/deliver/what-is-continuousdelivery)
- [What is Continuous Delivery?](https://www.ibm.com/topics/continuous-delivery)
- [Continuous Delivery](https://de.wikipedia.org/wiki/Continuous_Delivery)
- [GitHub Actions Documentation](https://docs.github.com/en/actions)
- [Cartoons zu Continuous Delivery](https://continuousdelivery.com/2014/02/visualizations-of-continuous-delivery/)

## Zum Weiterlesen
- [Dave Farley: Continuous Delivery Pipelines: How To Build Better Software Faster](https://www.amazon.de/Continuous-Delivery-Pipelines-Better-Software/dp/B096TTQHYM)
- [Eberhard Wolff: Continuous Delivery: Der pragmatische Einstieg](https://www.amazon.de/Continuous-Delivery-pragmatische-Eberhard-Wolff/dp/3864903718)
- [Jez Humble, David Farley: Continuous Delivery: Reliable Software Releases Through Build, Test, and Deployment Automation](https://www.amazon.de/Continuous-Delivery-Deployment-Automation-Addison-Wesley/dp/0321601912)
