# Docker Container Sammlung

Dieses Repository enthält vorgefertigte Docker Container-Setups für verschiedene Anwendungen. Jeder Container ist in einem eigenen Ordner mit einer individuellen `docker-compose.yml` Konfigurationsdatei strukturiert.

## Inhalt

### Nginx
Der Nginx-Container dient als leistungsstarker und flexibler Webserver und Reverse Proxy. Er kann verwendet werden, um statische Webseiten zu hosten oder Anfragen an andere Dienste weiterzuleiten.

- Enthält eine eigene `docker-compose.yml` zur einfachen Bereitstellung.
- Konfiguration kann flexibel angepasst werden.

### Portainer
Portainer ist eine benutzerfreundliche Verwaltungsoberfläche für Docker-Umgebungen.

- Erlaubt einfache Containerverwaltung über das Webinterface.
- Hilft bei der Überwachung und Steuerung von Docker-Containern und -Netzwerken.

### Watchtower
Watchtower ermöglicht die automatische Aktualisierung laufender Docker-Container, sobald neue Images verfügbar sind.

- Automatisiert das Update-Management.
- Verhilft zu sichereren und immer aktuellen Containern.

### Phiole
Phiole ist ein benutzerdefinierter Container, dessen Zweck hier beschrieben werden kann (bitte anpassen).

- Enthält spezifische Dienste oder Anwendungen.
- Eigene Konfiguration über die enthaltene `docker-compose.yml`.

## Nutzung

1. Navigiere in den gewünschten Container-Ordner.
2. Starte den Container mit: Docker compose up -d


