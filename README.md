# svxrdb

Das ist ein sehr einfaches Dashboard für den Service svxreflektor(Server Seite).

Den Ordner in das root Verzeichniss vom Webservice z.B. /var/www/html oder /var/www/html/httpdocs verschieben.

In der Datei logparse.php unter 
file_get_contents("svxlinkreflector.log");
die Logdatei angeben.

Der Zeitstempel in der svxreflector.conf sollte so eingestellt sein.
[GLOBAL]
TIMESTAMP_FORMAT="%d.%m.%Y %H:%M:%S"

Dies ist eine Beta und wird noch erweitert, bitte auf Dateirechte der Logdatei achten.
