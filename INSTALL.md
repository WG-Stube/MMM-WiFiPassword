# Installation Gesichtserkennung

## Manuelle Installation

1. In den Modul Ordner wechseln
`cd ~/MagicMirror/modules`

2. Erweiterung herunterladen und installieren
`git clone https://github.com/TeraTech/MMM-WiFiPassword.git``

3. Modul einrichten
 `nano ~/MagicMirror/config/config.js`
 In der Datei ganz am Ende der Liste (nach dem letzten `},` ) einfügen
```js
{
    module: 'MMM-WiFiPassword',
    position: "top_left",
      config: {
        //See 'Configuration options' for more information.
        network: "WLAN_NAME", 
        password: "WLAN_PASSWORT",
      }
  },
```
