# AkkuTakt — Datenschutzerklärung / Privacy Policy

**Stand / Last updated: 29. September / September 2026**
Diese Richtlinie gilt für AkkuTakt (ehemals Ampere Battery Lab), Android (`com.ampere.batterylab`) und iOS (`com.ampere.batterylab`). Sie ist in Deutsch, Englisch, Spanisch, Französisch, Italienisch, brasilianischem Portugiesisch und Niederländisch verfügbar.

## Deutsch

### Verantwortlicher und Datenschutzkontakt

Verantwortlicher für die Verarbeitung personenbezogener Daten im Zusammenhang mit AkkuTakt ist Julian Dominic Altmann, handelnd unter der Geschäftsbezeichnung Altmann Digital Studio. Altmann Digital Studio ist die Geschäftsbezeichnung des nicht eingetragenen Einzelunternehmens von Julian Dominic Altmann. Anschrift: Amselweg 5, 14513 Teltow, Deutschland. Für Datenschutzanfragen: [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). Das [Impressum](https://ai-on-mac.com/impressum/) enthält die Anbieterangaben.

### Geltungsbereich und lokale Daten

AkkuTakt benötigt kein Benutzerkonto, zeigt keine Werbung und betreibt keinen eigenen Anwendungsserver. Akku-Messwerte wie Zeitstempel, Akkustand, Ladezustand, Strom, Temperatur, Spannung, Bildschirmstatus, Sitzungen und Gesundheitsmessungen werden lokal auf dem Gerät verarbeitet und gespeichert.

Wenn du den optionalen Android-Nutzungszugriff erlaubst, kann AkkuTakt Paketnamen von Vordergrund-Apps lokal speichern, um den Akkuverbrauch pro App zu schätzen. Die App-Namen werden nicht an Firebase gesendet. Die Funktion bleibt ohne diesen Zugriff eingeschränkt.

### Optionale Nutzungsanalyse

Die Google-Analytics-for-Firebase-Erfassung ist standardmäßig ausgeschaltet und startet erst nach deiner ausdrücklichen Zustimmung. Wir verwenden diese Zählungen, um zu erkennen, wie AkkuTakt genutzt wird, und Verbesserungen an Bedienbarkeit und Zuverlässigkeit gezielt zu priorisieren. AkkuTakt zählt dann, welche App-Bereiche geöffnet und welche ausgewählten Steuerelemente angetippt werden. Außerdem zählt die Analyse, wann ausgewählte Einstellungs- und Detailansichten angezeigt und das Startbildschirm-Widget oder die Kachel in den Schnelleinstellungen angetippt werden. Pro App-Bereich erfasst sie außerdem in vier groben Stufen, ob du ein Viertel, die Hälfte, drei Viertel oder das Ende der scrollbaren Inhalte erreichst; genaue Scrollpositionen werden nicht übermittelt. In der Standard- und Großschriftansicht zählen ausgewählte Dashboard-Karten sowie Zusammenfassungs- und Aktionsbereiche erst als angesehen, wenn mindestens die Hälfte des Bereichs eine Sekunde lang sichtbar bleibt. Erfasst wird nur eine feste Bereichskategorie, niemals die angezeigten Akkuwerte. Dazu gehören Navigation, ausgewählte Einstellungen, Verlaufsfilter und -exporte, Alarmsteuerungen, Aktionen zur Kapazitätsmessung, App-Verbrauchsansichten sowie Aktualisierungsaktionen. Interaktionsereignisse enthalten nur feste Kategorien für Bereich, Element und Aktion; keine eingegebenen Texte, Schwellen- oder Ladezielwerte, Akku-Messwerte, Zeitstempel des Verlaufs oder Vordergrund-App-Namen. Funktionsereignisse zählen ausgewählte Funktionsaufrufe und aktivierte Alarme. Bei einem Export erfasst die Nutzungsanalyse außerdem nur den festen Exporttyp und ob das Speichern erfolgreich war, abgebrochen wurde oder fehlschlug; Dateiname, Speicherort und Inhalt werden nie übermittelt. Firebase verarbeitet außerdem App-Starts, Sitzungen, eine pseudonyme App-Instanzkennung sowie technische Angaben wie App-Version, Android-Version und Gerätemodell. Soweit Google Play sie bereitstellt, kann auch die Installations- oder Update-Quelle übermittelt werden.

Bei der Erfassung durch Google Analytics verwendet Google die IP-Adresse, um ungefähre Standortinformationen abzuleiten. Google verwirft die IP-Adresse, bevor sie protokolliert oder gespeichert wird. Werbe-ID-Erfassung und personalisierte Werbung sind ausgeschaltet. Akku-Messwerte, Vordergrund-App-Namen, Kontodaten und genaue Standortdaten werden nicht als Analytics-Ereignisse gesendet. Firebase verschlüsselt Analytics-Daten während der Übertragung mit TLS.

Im verknüpften Firebase-Analytics-Projekt sind Ereignis- und Nutzerdaten derzeit auf zwei Monate Aufbewahrung eingestellt. Die Option, die Aufbewahrungsfrist für Nutzerdaten bei neuer Aktivität zurückzusetzen, ist ausgeschaltet. Zusammengefasste Berichte können länger bestehen bleiben. Du kannst deine Zustimmung in der App widerrufen; dadurch stoppt AkkuTakt künftige Erfassung und setzt die Analytics-App-Instanzkennung zurück. Bereits an Google übermittelte Daten werden dadurch nicht gelöscht. AkkuTakt bietet keine gesonderte Fernlöschanfrage für diese Daten an.

### Verbindungen, Updates, Sicherungen und Exporte

Die Android-Direct-Ausgabe kontaktiert GitHub regelmäßig, um öffentliche Update-Metadaten abzurufen. GitHub kann dabei die IP-Adresse und technische Anfragedaten gemäß seiner [Datenschutzerklärung](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) verarbeiten. Eine APK wird erst heruntergeladen, nachdem du ein Update auswählst. Die Google-Play-Ausgabe erhält Updates über Google Play; iOS-Updates kommen über den Apple App Store.

Android-Cloud-Backups und Android-Geräteübertragungen schließen AkkuTakt-Akkuverlauf, Sitzungen, Einstellungen und Telemetrie aus. Sicherungen älterer Android-Versionen können beim Anbieter verbleiben. iOS-Gerätesicherungen können lokale App-Daten enthalten; Apple und deine Geräteeinstellungen steuern das. Eine manuelle Sicherung erstellst du ausdrücklich in der App und wählst das Ziel selbst. Die exportierte Datei ist möglicherweise nicht verschlüsselt.

CSV, Forschungs-JSON und Diagnoseberichte werden nur auf deine Anforderung erstellt. CSV und Forschungs-JSON können Zeitstempel, Akku- und Sitzungs-Telemetrie sowie Paketnamen von Vordergrund-Apps enthalten, wenn der Android-Nutzungszugriff aktiv ist. Das Forschungs-JSON enthält zusätzlich App- und Geräte-Buildangaben sowie einen Fingerabdruck des Release-Zertifikats. Es enthält kein Benutzerkonto, keinen genauen Standort, keine Seriennummer und keine Werbe-ID. Die Dateien werden nicht automatisch an AkkuTakt übertragen; du wählst den Speicherort oder eine weitere App aus.

### iOS

Die iOS-App verwendet Apples `UIDevice`-Schnittstelle für Akkustand und Ladezustand. Sie speichert die Messpunkte lokal in der App und behält höchstens die jüngsten 720 Einträge. iOS stellt Drittanbieter-Apps keine verlässlichen Strom-, Designkapazitäts- oder Verschleißwerte bereit; AkkuTakt erfindet oder überträgt solche Werte nicht. Die iOS-App enthält keine Firebase-Analytics-Erfassung.

### Deine Datenschutzrechte

Soweit das anwendbare Datenschutzrecht diese Rechte vorsieht, kannst du Auskunft, Berichtigung, Löschung, Einschränkung oder Übertragbarkeit deiner personenbezogenen Daten verlangen und einer Verarbeitung widersprechen. Eine Einwilligung kannst du jederzeit mit Wirkung für die Zukunft widerrufen; die Verarbeitung vor dem Widerruf bleibt davon unberührt. Du kannst dich außerdem bei einer zuständigen Datenschutzaufsichtsbehörde beschweren. Für Anfragen nutze den unten genannten Datenschutzkontakt.

### Kontakt und Drittanbieter

Für Datenschutzanfragen nutze bitte den Kontakt im jeweiligen App-Store-Eintrag. Weitere Informationen zur Datenverarbeitung durch Google findest du in der [Google-Datenschutzerklärung](https://policies.google.com/privacy) und bei [Firebase Datenschutz und Sicherheit](https://firebase.google.com/support/privacy). Für GitHub gelten die oben verlinkten Datenschutzbestimmungen.

## English

### Controller and privacy contact

The controller for personal data processing in connection with AkkuTakt is Julian Dominic Altmann, trading as Altmann Digital Studio. Altmann Digital Studio is the business name of Julian Dominic Altmann's unregistered sole proprietorship. Address: Amselweg 5, 14513 Teltow, Germany. For privacy requests, contact [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). The [German legal notice](https://ai-on-mac.com/impressum/) provides the operator details.

### Scope and data stored locally

AkkuTakt (formerly Ampere Battery Lab) requires no user account, displays no ads and operates no application server. Battery readings such as timestamps, level, charging state, current, temperature, voltage, screen state, sessions and health measurements are processed and stored on your device.

If you grant optional Android app-usage access, AkkuTakt may store foreground app package names locally to estimate battery use by app. App names are not sent to Firebase. The feature is limited if you decline access.

### Optional usage analytics

Google Analytics for Firebase collection is off by default and starts only after your explicit consent. We use these counts to understand how AkkuTakt is used and to prioritize usability and reliability improvements. AkkuTakt then counts which app sections are opened and which selected controls are tapped. It also counts when selected settings and detail screens are displayed and when the home-screen widget or Quick Settings tile is tapped. For each app section, it also records in four broad steps whether you reach one quarter, half, three quarters or the end of the scrollable content; exact scroll positions are not sent. In standard and large-text layouts, selected dashboard cards or summary and action areas count as viewed only after at least half of the area stays visible for one second. Analytics records only a fixed area category, never the battery readings shown. Categories include navigation, selected settings, history filters and exports, alarm controls, capacity-measurement actions, app-usage screens, and update actions. Interaction events contain only fixed categories for section, control and action; they do not include entered text, alarm thresholds or charge-target values, battery readings, history timestamps, or foreground app names. Feature events count selected feature launches and enabled alarms. For each export, analytics also records only the fixed export type and whether saving completed, was cancelled or failed; it never receives the file name, destination or contents. Firebase also processes app starts, sessions, a pseudonymous app-instance ID and technical details such as app version, Android version and device model. When Google Play provides it, the app’s install or update source may also be received.

During Google Analytics collection, Google uses the IP address to infer approximate location, then discards it before it is logged or stored. Advertising ID collection and personalized advertising are disabled. Battery readings, foreground app names, account data and precise location are not sent as Analytics events. Firebase encrypts Analytics data in transit using TLS.

In the linked Firebase Analytics project, retention is currently set to two months for event-level and user-level data. The setting that would reset the user-level retention period when new activity arrives is off. Aggregated reports may remain longer. You can withdraw consent in the app; AkkuTakt then stops future collection and resets the Analytics app-instance ID. This does not delete data already sent to Google. AkkuTakt does not provide a separate remote deletion request for that data.

### Connections, updates, backups and exports

The Android Direct edition periodically contacts GitHub to fetch public update metadata. GitHub may process your IP address and technical request details under its [Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). An APK is downloaded only after you choose an update. The Google Play edition receives updates through Google Play; iOS updates come through the Apple App Store.

Android cloud backups and Android device transfers exclude AkkuTakt's battery history, sessions, settings and telemetry. Backups created by older Android versions may remain with the provider. iOS device backups may include local app data; Apple and your device settings control that. You can create a manual backup in the app and choose its destination. The exported file may not be encrypted.

CSV, research JSON and diagnostic reports are created only when you request them. CSV and research JSON may contain timestamps, battery and session telemetry, and foreground app package names when Android app-usage access is enabled. Research JSON also includes app and device build details and a release-certificate fingerprint. It contains no user account, precise location, serial number or advertising ID. The files are not automatically sent to AkkuTakt; you choose their destination or another app.

### iOS

The iOS app uses Apple’s `UIDevice` interface for battery level and charging state. It stores readings locally in the app and keeps at most the latest 720 samples. iOS does not provide third-party apps with reliable current, design-capacity or wear measurements; AkkuTakt does not invent or transmit those values. The iOS app does not include Firebase Analytics collection.

### Your privacy rights

Where applicable data protection law provides these rights, you may request access to, correction or deletion of your personal data, restriction of processing or data portability, and object to processing. You can withdraw consent at any time for the future; this does not affect processing carried out before withdrawal. You may also lodge a complaint with a competent data protection authority. For requests, use the privacy contact listed below.

### Contact and third parties

For privacy questions, use the contact shown in the relevant app-store listing. For Google’s data practices, see the [Google Privacy Policy](https://policies.google.com/privacy) and [Firebase Privacy and Security](https://firebase.google.com/support/privacy). GitHub’s privacy statement is linked above.

## Español

### Responsable y contacto de privacidad

El responsable del tratamiento de los datos personales relacionados con AkkuTakt es Julian Dominic Altmann, que opera bajo el nombre comercial Altmann Digital Studio. Altmann Digital Studio es el nombre comercial de la empresa individual no inscrita de Julian Dominic Altmann. Dirección: Amselweg 5, 14513 Teltow, Alemania. Para consultas de privacidad, escribe a [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). El [aviso legal en alemán](https://ai-on-mac.com/impressum/) contiene los datos del operador.

### Alcance y datos almacenados localmente

AkkuTakt (antes Ampere Battery Lab) no requiere una cuenta de usuario, no muestra anuncios y no opera un servidor propio. Las lecturas de batería, como marcas de tiempo, nivel, estado de carga, corriente, temperatura, voltaje, estado de pantalla, sesiones y mediciones de salud, se procesan y almacenan en el dispositivo.

Si autorizas el acceso opcional al uso de aplicaciones en Android, AkkuTakt puede guardar localmente los nombres de paquete de las apps en primer plano para estimar el consumo por app. Los nombres no se envían a Firebase. La función queda limitada si no concedes este acceso.

### Análisis de uso opcional

La recopilación de Google Analytics for Firebase está desactivada de forma predeterminada y solo empieza tras tu consentimiento explícito. Usamos estos recuentos para comprender cómo se utiliza AkkuTakt y priorizar mejoras de usabilidad y fiabilidad. AkkuTakt cuenta entonces qué secciones de la app se abren y qué controles seleccionados se tocan. También cuenta las vistas de determinadas pantallas de ajustes y detalles, y cuándo se toca el widget de la pantalla de inicio o el mosaico de Ajustes rápidos. Por sección, registra en cuatro niveles generales si llegas a un cuarto, la mitad, tres cuartos o el final del contenido desplazable; no envía posiciones exactas. En los diseños estándar y de texto grande, las tarjetas seleccionadas del panel o las áreas de resumen y acciones solo se cuentan como vistas cuando al menos la mitad del área permanece visible durante un segundo. El análisis solo registra una categoría fija del área, nunca las lecturas de batería mostradas. Las categorías incluyen navegación, ajustes seleccionados, filtros y exportaciones del historial, controles de alertas, acciones de medición de capacidad, vistas del consumo por app y acciones de actualización. Los eventos de interacción solo contienen categorías fijas de sección, control y acción; no incluyen texto introducido, umbrales ni valores del límite de carga, lecturas de batería, marcas de tiempo del historial ni nombres de apps en primer plano. Los eventos de funciones cuentan determinados inicios de funciones y alertas activadas. Para cada exportación, las estadísticas también registran solo el tipo fijo y si el guardado se completó, se canceló o falló; nunca reciben el nombre, el destino ni el contenido del archivo. Firebase también procesa inicios de la app, sesiones, un ID seudónimo de instancia y datos técnicos como la versión de la app, Android y el modelo del dispositivo. Si Google Play los proporciona, también puede recibirse el origen de instalación o actualización.

Durante la recopilación de Google Analytics, Google usa la dirección IP para deducir una ubicación aproximada y la descarta antes de registrarla o almacenarla. La recopilación del ID de publicidad y la publicidad personalizada están desactivadas. Las lecturas de batería, los nombres de apps en primer plano, los datos de cuenta y la ubicación precisa no se envían como eventos de Analytics. Firebase cifra los datos de Analytics durante la transferencia mediante TLS.

En el proyecto de Firebase Analytics vinculado, los datos de eventos y de usuario tienen actualmente un periodo de conservación de dos meses. La opción de reiniciar el periodo de conservación de los datos de usuario cuando hay nueva actividad está desactivada. Los informes agregados pueden conservarse durante más tiempo. Puedes retirar el consentimiento en la app; AkkuTakt detiene la recopilación futura y restablece el ID de instancia de Analytics. Esto no elimina los datos ya enviados a Google. AkkuTakt no ofrece una solicitud independiente para eliminarlos a distancia.

### Conexiones, actualizaciones, copias de seguridad y exportaciones

La edición Android Direct se conecta periódicamente a GitHub para obtener metadatos públicos de actualizaciones. GitHub puede procesar tu dirección IP y datos técnicos de la solicitud conforme a su [declaración de privacidad](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). El APK solo se descarga cuando eliges una actualización. La edición de Google Play recibe actualizaciones mediante Google Play; las de iOS llegan a través de Apple App Store.

Las copias en la nube y las transferencias de dispositivo de Android excluyen el historial de batería, las sesiones, los ajustes y la telemetría de AkkuTakt. Las copias creadas por versiones anteriores de Android pueden seguir en el proveedor. Las copias de seguridad de iOS pueden incluir datos locales de la app; Apple y los ajustes del dispositivo controlan ese proceso. Puedes crear una copia manual desde la app y elegir el destino. Es posible que el archivo exportado no esté cifrado.

Los archivos CSV, JSON de investigación e informes de diagnóstico solo se crean cuando los solicitas. El CSV y el JSON pueden contener marcas de tiempo, telemetría de batería y sesiones, y nombres de paquete de apps en primer plano si está autorizado el acceso al uso de aplicaciones en Android. El JSON de investigación también incluye datos de compilación de la app y del dispositivo, y la huella del certificado de publicación. No incluye cuenta, ubicación precisa, número de serie ni ID de publicidad. Los archivos no se envían automáticamente a AkkuTakt; tú eliges el destino o la app receptora.

### iOS

La app de iOS usa la interfaz `UIDevice` de Apple para el nivel y el estado de carga. Guarda las lecturas localmente en la app y conserva como máximo las 720 más recientes. iOS no proporciona a las apps de terceros mediciones fiables de corriente, capacidad de diseño o desgaste; AkkuTakt no inventa ni transmite esos valores. La app de iOS no incluye recopilación de Firebase Analytics.

### Tus derechos de privacidad

Cuando la legislación de protección de datos aplicable reconozca estos derechos, puedes solicitar acceso a tus datos personales, su rectificación o supresión, la limitación del tratamiento o su portabilidad, y oponerte al tratamiento. Puedes retirar tu consentimiento en cualquier momento para el futuro; esto no afecta al tratamiento realizado antes de retirarlo. También puedes presentar una reclamación ante una autoridad de protección de datos competente. Para tus solicitudes, utiliza el contacto de privacidad indicado abajo.

### Contacto y terceros

Para consultas de privacidad, utiliza el contacto que aparece en la ficha de la app correspondiente. Consulta la [Política de privacidad de Google](https://policies.google.com/privacy) y [Privacidad y seguridad de Firebase](https://firebase.google.com/support/privacy) para conocer las prácticas de Google. La declaración de privacidad de GitHub está enlazada arriba.

## Français

### Responsable du traitement et contact relatif à la confidentialité

Le responsable du traitement des données personnelles liées à AkkuTakt est Julian Dominic Altmann, exerçant sous le nom commercial Altmann Digital Studio. Altmann Digital Studio est le nom commercial de l’entreprise individuelle non immatriculée de Julian Dominic Altmann. Adresse : Amselweg 5, 14513 Teltow, Allemagne. Pour toute demande relative à la confidentialité, écrivez à [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). Les [mentions légales allemandes](https://ai-on-mac.com/impressum/) indiquent les coordonnées de l’exploitant.

### Portée et données stockées localement

AkkuTakt (anciennement Ampere Battery Lab) ne nécessite aucun compte utilisateur, n’affiche aucune publicité et n’exploite aucun serveur applicatif. Les mesures de batterie — horodatage, niveau, état de charge, courant, température, tension, état de l’écran, sessions et mesures de santé — sont traitées et stockées sur l’appareil.

Si vous autorisez l’accès facultatif aux données d’utilisation d’Android, AkkuTakt peut enregistrer localement les noms de package des applications au premier plan afin d’estimer la consommation par application. Ces noms ne sont pas envoyés à Firebase. La fonctionnalité est limitée si vous refusez cet accès.

### Statistiques d’utilisation facultatives

La collecte Google Analytics for Firebase est désactivée par défaut et ne commence qu’après votre consentement explicite. Nous utilisons ces comptages pour comprendre l’usage d’AkkuTakt et prioriser les améliorations d’ergonomie et de fiabilité. AkkuTakt compte alors les sections de l’application ouvertes et les commandes sélectionnées touchées. La collecte compte aussi l’affichage de certains écrans de réglages et de détails, ainsi que les appuis sur le widget d’accueil ou la tuile Paramètres rapides. Pour chaque section, elle indique en quatre paliers si vous atteignez un quart, la moitié, les trois quarts ou la fin du contenu défilant ; la position exacte n’est pas transmise. Dans les mises en page standard et grand texte, les cartes sélectionnées du tableau de bord ou les zones de résumé et d’actions ne sont comptées comme vues qu’après être restées visibles au moins à moitié pendant une seconde. L’analyse enregistre uniquement une catégorie fixe de zone, jamais les mesures de batterie affichées. Les catégories comprennent la navigation, certains réglages, les filtres et exports de l’historique, les commandes d’alerte, les actions de mesure de capacité, les vues de consommation par application et les actions de mise à jour. Les événements d’interaction ne contiennent que des catégories fixes pour la section, la commande et l’action ; ils n’incluent ni texte saisi, ni seuils ou valeurs de limite de charge, ni mesures de batterie, horodatages de l’historique ou noms d’applications au premier plan. Les événements de fonctionnalité comptent certains lancements de fonctions et les alertes activées. Pour chaque export, l’analyse enregistre aussi uniquement le type prédéfini et si l’enregistrement a abouti, a été annulé ou a échoué ; elle ne reçoit jamais le nom, la destination ni le contenu du fichier. Firebase traite aussi les démarrages de l’application, les sessions, un identifiant pseudonyme d’instance ainsi que des données techniques comme la version de l’application, d’Android et le modèle de l’appareil. Si Google Play les fournit, la source d’installation ou de mise à jour peut également être reçue.

Lors de la collecte par Google Analytics, Google utilise l’adresse IP pour déduire une localisation approximative, puis l’écarte avant son enregistrement ou son stockage. La collecte de l’identifiant publicitaire et la publicité personnalisée sont désactivées. Les mesures de batterie, noms d’applications au premier plan, données de compte et localisations précises ne sont pas envoyés comme événements Analytics. Firebase chiffre les données Analytics en transit à l’aide de TLS.

Dans le projet Firebase Analytics associé, la durée de conservation est actuellement réglée sur deux mois pour les données au niveau événementiel et utilisateur. L’option qui réinitialiserait la durée de conservation des données utilisateur lors d’une nouvelle activité est désactivée. Les rapports agrégés peuvent être conservés plus longtemps. Vous pouvez retirer votre consentement dans l’application ; AkkuTakt arrête alors toute collecte future et réinitialise l’identifiant d’instance Analytics. Cela ne supprime pas les données déjà envoyées à Google. AkkuTakt ne propose pas de demande séparée de suppression à distance de ces données.

### Connexions, mises à jour, sauvegardes et exportations

L’édition Android Direct contacte périodiquement GitHub pour récupérer les métadonnées publiques de mise à jour. GitHub peut traiter votre adresse IP et les données techniques de la requête selon sa [déclaration de confidentialité](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Un APK n’est téléchargé qu’après votre choix de mise à jour. L’édition Google Play reçoit ses mises à jour via Google Play ; celles d’iOS proviennent de l’Apple App Store.

Les sauvegardes cloud et les transferts d’appareil Android excluent l’historique de batterie, les sessions, les paramètres et la télémétrie d’AkkuTakt. Les sauvegardes créées par d’anciennes versions d’Android peuvent rester chez le fournisseur. Les sauvegardes iOS peuvent inclure les données locales de l’app ; Apple et les réglages de l’appareil gèrent ce processus. Vous pouvez créer une sauvegarde manuelle dans l’app et en choisir la destination. Le fichier exporté peut ne pas être chiffré.

Les fichiers CSV, JSON de recherche et rapports de diagnostic ne sont créés que sur votre demande. Le CSV et le JSON peuvent contenir des horodatages, des données de télémétrie de batterie et de session, ainsi que les noms de package d’applications au premier plan lorsque l’accès aux données d’utilisation d’Android est autorisé. Le JSON de recherche contient aussi des informations de version de l’application et de l’appareil et l’empreinte du certificat de publication. Il ne contient ni compte, ni localisation précise, ni numéro de série, ni identifiant publicitaire. Les fichiers ne sont pas envoyés automatiquement à AkkuTakt ; vous choisissez leur destination ou l’application qui les reçoit.

### iOS

L’application iOS utilise l’interface `UIDevice` d’Apple pour le niveau de batterie et l’état de charge. Elle stocke les mesures localement et conserve au maximum les 720 plus récentes. iOS ne fournit pas aux applications tierces de mesures fiables du courant, de la capacité nominale ou de l’usure ; AkkuTakt n’invente ni ne transmet ces valeurs. L’application iOS n’intègre pas la collecte Firebase Analytics.

### Vos droits en matière de protection des données

Lorsque la législation applicable prévoit ces droits, vous pouvez demander l’accès à vos données personnelles, leur rectification ou leur effacement, la limitation du traitement ou leur portabilité, et vous opposer au traitement. Vous pouvez retirer votre consentement à tout moment pour l’avenir ; cela n’affecte pas le traitement effectué avant ce retrait. Vous pouvez également introduire une réclamation auprès d’une autorité de contrôle compétente en matière de protection des données. Pour vos demandes, utilisez le contact indiqué ci-dessous.

### Contact et tiers

Pour toute question relative à la confidentialité, utilisez le contact indiqué dans la fiche de l’application concernée. Consultez la [Politique de confidentialité de Google](https://policies.google.com/privacy) et [Confidentialité et sécurité Firebase](https://firebase.google.com/support/privacy). La déclaration de confidentialité de GitHub est liée ci-dessus.

## Italiano

### Titolare del trattamento e contatto privacy

Il titolare del trattamento dei dati personali relativi ad AkkuTakt è Julian Dominic Altmann, che opera con il nome commerciale Altmann Digital Studio. Altmann Digital Studio è il nome commerciale dell’impresa individuale non iscritta di Julian Dominic Altmann. Indirizzo: Amselweg 5, 14513 Teltow, Germania. Per richieste relative alla privacy, scrivi a [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). Le [informazioni legali in tedesco](https://ai-on-mac.com/impressum/) riportano i dati del gestore.

### Ambito e dati archiviati localmente

AkkuTakt (in precedenza Ampere Battery Lab) non richiede un account utente, non mostra pubblicità e non gestisce un proprio server applicativo. Le letture della batteria — data e ora, livello, stato di carica, corrente, temperatura, tensione, stato dello schermo, sessioni e misurazioni dello stato della batteria — vengono elaborate e archiviate sul dispositivo.

Se autorizzi l’accesso facoltativo ai dati di utilizzo di Android, AkkuTakt può salvare localmente i nomi dei pacchetti delle app in primo piano per stimare il consumo per app. Questi nomi non vengono inviati a Firebase. La funzione è limitata se non concedi l’accesso.

### Analisi facoltativa dell’utilizzo

La raccolta di Google Analytics for Firebase è disattivata per impostazione predefinita e inizia solo dopo il tuo consenso esplicito. Usiamo questi conteggi per capire come viene utilizzato AkkuTakt e dare priorità ai miglioramenti di usabilità e affidabilità. AkkuTakt conteggia quindi le sezioni dell’app aperte e i controlli selezionati toccati. Conteggia inoltre la visualizzazione di alcune schermate di impostazioni e dettagli e i tocchi sul widget della schermata Home o sul riquadro Impostazioni rapide. Per ogni sezione registra in quattro livelli se raggiungi un quarto, la metà, tre quarti o la fine dei contenuti scorrevoli; la posizione esatta non viene inviata. Nei layout standard e a caratteri grandi, le schede selezionate del pannello o le aree di riepilogo e azioni vengono conteggiate come visualizzate solo dopo che almeno metà dell’area è rimasta visibile per un secondo. L’analisi registra solo una categoria fissa dell’area, mai i dati della batteria mostrati. Le categorie includono navigazione, alcune impostazioni, filtri ed esportazioni della cronologia, controlli degli avvisi, azioni di misurazione della capacità, schermate del consumo per app e azioni di aggiornamento. Gli eventi di interazione contengono solo categorie fisse per sezione, controllo e azione; non includono testo inserito, soglie o valori del limite di carica, letture della batteria, timestamp della cronologia o nomi delle app in primo piano. Gli eventi delle funzioni conteggiano l’avvio di funzioni selezionate e gli avvisi attivati. Per ogni esportazione, le statistiche registrano anche solo il tipo predefinito e se il salvataggio è riuscito, è stato annullato o non è riuscito; non ricevono mai nome, destinazione o contenuto del file. Firebase elabora anche avvii dell’app, sessioni, un identificatore pseudonimo dell’istanza e dati tecnici come versioni dell’app e di Android e modello del dispositivo. Se disponibili tramite Google Play, può ricevere anche la fonte di installazione o aggiornamento.

Durante la raccolta di Google Analytics, Google usa l’indirizzo IP per ricavare una posizione approssimativa e lo elimina prima che venga registrato o conservato. La raccolta dell’ID pubblicità e la pubblicità personalizzata sono disattivate. Le letture della batteria, i nomi delle app in primo piano, i dati dell’account e la posizione precisa non vengono inviati come eventi Analytics. Firebase cifra i dati Analytics durante il trasferimento con TLS.

Nel progetto Firebase Analytics collegato, la conservazione dei dati a livello di evento e utente è attualmente impostata su due mesi. L’opzione che reimposterebbe la conservazione dei dati utente in caso di nuova attività è disattivata. I report aggregati possono essere conservati più a lungo. Puoi revocare il consenso nell’app; AkkuTakt interrompe la raccolta futura e reimposta l’ID dell’istanza Analytics. Questo non elimina i dati già inviati a Google. AkkuTakt non offre una richiesta separata per eliminarli da remoto.

### Connessioni, aggiornamenti, backup ed esportazioni

L’edizione Android Direct contatta periodicamente GitHub per recuperare i metadati pubblici degli aggiornamenti. GitHub può elaborare il tuo indirizzo IP e i dati tecnici della richiesta secondo la propria [informativa sulla privacy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). L’APK viene scaricato solo dopo che scegli un aggiornamento. L’edizione Google Play riceve gli aggiornamenti tramite Google Play; quelli iOS tramite Apple App Store.

I backup cloud e i trasferimenti tra dispositivi Android escludono la cronologia della batteria, le sessioni, le impostazioni e la telemetria di AkkuTakt. I backup creati da versioni precedenti di Android potrebbero restare presso il provider. I backup iOS possono includere i dati locali dell’app; Apple e le impostazioni del dispositivo gestiscono questo processo. Puoi creare un backup manuale nell’app e sceglierne la destinazione. Il file esportato potrebbe non essere crittografato.

I file CSV, JSON di ricerca e i rapporti diagnostici vengono creati solo su tua richiesta. CSV e JSON possono contenere timestamp, telemetria della batteria e delle sessioni e nomi dei pacchetti delle app in primo piano se è consentito l’accesso ai dati di utilizzo di Android. Il JSON di ricerca include anche dettagli di build dell’app e del dispositivo e l’impronta del certificato di rilascio. Non contiene account, posizione precisa, numero di serie o ID pubblicità. I file non vengono inviati automaticamente ad AkkuTakt; scegli tu la destinazione o l’app ricevente.

### iOS

L’app iOS usa l’interfaccia `UIDevice` di Apple per livello della batteria e stato di carica. Archivia le letture localmente nell’app e conserva al massimo le 720 più recenti. iOS non fornisce alle app di terze parti misurazioni affidabili di corrente, capacità di progetto o usura; AkkuTakt non inventa né trasmette questi valori. L’app iOS non include la raccolta di Firebase Analytics.

### I tuoi diritti in materia di protezione dei dati

Quando la normativa applicabile prevede questi diritti, puoi chiedere l’accesso ai tuoi dati personali, la rettifica o la cancellazione, la limitazione del trattamento o la portabilità e opporti al trattamento. Puoi revocare il consenso in qualsiasi momento con effetto per il futuro; ciò non pregiudica il trattamento svolto prima della revoca. Puoi anche presentare un reclamo a un’autorità di controllo competente per la protezione dei dati. Per le richieste, usa il contatto indicato qui sotto.

### Contatti e terze parti

Per domande sulla privacy, usa il contatto indicato nella scheda dello store pertinente. Per le pratiche di Google consulta l’[Informativa sulla privacy di Google](https://policies.google.com/privacy) e [Privacy e sicurezza Firebase](https://firebase.google.com/support/privacy). L’informativa di GitHub è collegata sopra.

## Português (Brasil)

### Controlador e contato de privacidade

O controlador do tratamento de dados pessoais relacionados ao AkkuTakt é Julian Dominic Altmann, que atua sob o nome comercial Altmann Digital Studio. Altmann Digital Studio é o nome comercial da empresa individual não registrada de Julian Dominic Altmann. Endereço: Amselweg 5, 14513 Teltow, Alemanha. Para solicitações sobre privacidade, escreva para [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). O [aviso legal em alemão](https://ai-on-mac.com/impressum/) informa os dados do responsável pelo site.

### Escopo e dados armazenados localmente

O AkkuTakt (antigo Ampere Battery Lab) não exige conta de usuário, não exibe anúncios e não opera um servidor próprio. Leituras da bateria — data e hora, nível, estado da carga, corrente, temperatura, tensão, estado da tela, sessões e medições de saúde — são processadas e armazenadas no dispositivo.

Se você permitir o acesso opcional ao uso de apps no Android, o AkkuTakt poderá salvar localmente os nomes de pacote dos apps em primeiro plano para estimar o consumo por app. Esses nomes não são enviados ao Firebase. O recurso fica limitado se você não conceder o acesso.

### Análise de uso opcional

A coleta do Google Analytics for Firebase fica desativada por padrão e só começa após seu consentimento explícito. Usamos essas contagens para entender como o AkkuTakt é usado e priorizar melhorias de usabilidade e confiabilidade. O AkkuTakt conta então quais seções do app são abertas e quais controles selecionados são tocados. Também conta a exibição de algumas telas de configurações e detalhes e os toques no widget da tela inicial ou no bloco de Configurações rápidas. Em cada seção, registra em quatro etapas amplas se você chega a um quarto, metade, três quartos ou ao fim do conteúdo rolável; a posição exata não é enviada. Nos layouts padrão e de texto grande, os cartões selecionados do painel ou as áreas de resumo e ações só são contados como visualizados depois que pelo menos metade da área permanece visível por um segundo. A análise registra apenas uma categoria fixa da área, nunca as medições de bateria exibidas. As categorias incluem navegação, configurações selecionadas, filtros e exportações do histórico, controles de alertas, ações de medição da capacidade, telas de consumo por app e ações de atualização. Os eventos de interação contêm apenas categorias fixas de seção, controle e ação; não incluem texto digitado, limites ou valores do objetivo de carga, leituras da bateria, horários do histórico nem nomes de apps em primeiro plano. Eventos de recursos contam determinadas inicializações de recursos e alertas ativados. Em cada exportação, a análise também registra apenas o tipo fixo e se o salvamento foi concluído, cancelado ou falhou; nunca recebe o nome, o destino ou o conteúdo do arquivo. O Firebase também processa inicializações do app, sessões, um identificador pseudônimo da instância e dados técnicos como versões do app e do Android e modelo do dispositivo. Quando fornecida pelo Google Play, a origem da instalação ou atualização também pode ser recebida.

Durante a coleta do Google Analytics, o Google usa o endereço IP para inferir uma localização aproximada e o descarta antes do registro ou armazenamento. A coleta do ID de publicidade e a publicidade personalizada estão desativadas. Leituras da bateria, nomes de apps em primeiro plano, dados da conta e localização precisa não são enviados como eventos do Analytics. O Firebase criptografa os dados do Analytics em trânsito usando TLS.

No projeto vinculado do Firebase Analytics, a retenção de dados em nível de evento e de usuário está atualmente definida para dois meses. A opção que redefiniria o período de retenção dos dados de usuário quando há nova atividade está desativada. Relatórios agregados podem ser mantidos por mais tempo. Você pode retirar o consentimento no app; o AkkuTakt interrompe a coleta futura e redefine o ID da instância do Analytics. Isso não exclui dados já enviados ao Google. O AkkuTakt não oferece uma solicitação separada para excluí-los remotamente.

### Conexões, atualizações, backups e exportações

A edição Android Direct contata periodicamente o GitHub para buscar metadados públicos de atualização. O GitHub pode processar seu endereço IP e dados técnicos da solicitação conforme a [política de privacidade](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). O APK só é baixado depois que você escolhe uma atualização. A edição do Google Play recebe atualizações pelo Google Play; as do iOS vêm pela Apple App Store.

Os backups na nuvem e as transferências entre dispositivos do Android excluem o histórico da bateria, as sessões, as configurações e a telemetria do AkkuTakt. Backups criados por versões anteriores do Android podem continuar no provedor. Backups do iOS podem incluir dados locais do app; a Apple e os ajustes do dispositivo controlam esse processo. Você pode criar um backup manual no app e escolher o destino. O arquivo exportado pode não ser criptografado.

Arquivos CSV, JSON de pesquisa e relatórios de diagnóstico só são criados quando você solicita. CSV e JSON podem conter registros de data e hora, telemetria da bateria e das sessões e nomes de pacote dos apps em primeiro plano quando o acesso ao uso de apps no Android está ativado. O JSON de pesquisa também inclui detalhes de build do app e do dispositivo e a impressão digital do certificado de lançamento. Não inclui conta, localização precisa, número de série nem ID de publicidade. Os arquivos não são enviados automaticamente ao AkkuTakt; você escolhe o destino ou o app que os receberá.

### iOS

O app iOS usa a interface `UIDevice` da Apple para nível da bateria e estado da carga. Armazena as leituras localmente no app e mantém no máximo as 720 mais recentes. O iOS não fornece a apps de terceiros medições confiáveis de corrente, capacidade de projeto ou desgaste; o AkkuTakt não inventa nem transmite esses valores. O app iOS não inclui coleta do Firebase Analytics.

### Seus direitos de privacidade

Quando a legislação de proteção de dados aplicável reconhecer esses direitos, você poderá solicitar acesso aos seus dados pessoais, correção ou exclusão, limitação do tratamento ou portabilidade, e se opor ao tratamento. Você pode retirar seu consentimento a qualquer momento para o futuro; isso não afeta o tratamento realizado antes da retirada. Você também pode apresentar uma reclamação à autoridade de proteção de dados competente. Para solicitações, use o contato de privacidade informado abaixo.

### Contato e terceiros

Para dúvidas sobre privacidade, use o contato indicado na listagem da loja correspondente. Consulte a [Política de Privacidade do Google](https://policies.google.com/privacy) e [Privacidade e segurança do Firebase](https://firebase.google.com/support/privacy) para saber mais sobre as práticas do Google. A declaração de privacidade do GitHub está vinculada acima.

## Nederlands

### Verwerkingsverantwoordelijke en privacycontact

De verwerkingsverantwoordelijke voor persoonsgegevens in verband met AkkuTakt is Julian Dominic Altmann, handelend onder de handelsnaam Altmann Digital Studio. Altmann Digital Studio is de handelsnaam van de niet-ingeschreven eenmanszaak van Julian Dominic Altmann. Adres: Amselweg 5, 14513 Teltow, Duitsland. Voor privacyverzoeken kun je mailen naar [macmini-ai.lifter912@silomails.com](mailto:macmini-ai.lifter912@silomails.com). De [Duitse juridische kennisgeving](https://ai-on-mac.com/impressum/) bevat de gegevens van de exploitant.

### Reikwijdte en lokaal opgeslagen gegevens

AkkuTakt (voorheen Ampere Battery Lab) vereist geen gebruikersaccount, toont geen advertenties en beheert geen eigen applicatieserver. Batterijmetingen — tijdstippen, niveau, laadstatus, stroom, temperatuur, spanning, schermstatus, sessies en gezondheidsmetingen — worden op je apparaat verwerkt en opgeslagen.

Als je optioneel toegang tot appgebruik op Android verleent, kan AkkuTakt lokaal pakketnamen van apps op de voorgrond opslaan om het verbruik per app te schatten. Deze namen worden niet naar Firebase gestuurd. Zonder deze toegang is de functie beperkt.

### Optionele gebruiksanalyse

Google Analytics for Firebase staat standaard uit en begint pas na je uitdrukkelijke toestemming. We gebruiken deze tellingen om te begrijpen hoe AkkuTakt wordt gebruikt en verbeteringen in gebruiksgemak en betrouwbaarheid te prioriteren. AkkuTakt telt dan welke apponderdelen worden geopend en welke geselecteerde bedieningselementen worden aangetikt. Ook telt de analyse wanneer geselecteerde instellingen- en detailpagina’s worden weergegeven en wanneer op de startschermwidget of de tegel Snelle instellingen wordt getikt. Per appgedeelte registreert de analyse in vier grove stappen of je een kwart, de helft, driekwart of het einde van de scrollbare inhoud bereikt; exacte scrollposities worden niet verstuurd. In de standaard- en grote-tekstweergave tellen geselecteerde dashboardkaarten of samenvattings- en actiegebieden pas als bekeken nadat minstens de helft van het gebied één seconde zichtbaar is geweest. De analyse registreert alleen een vaste gebiedscategorie, nooit de weergegeven batterijmetingen. De categorieën omvatten navigatie, geselecteerde instellingen, geschiedenisfilters en -exports, alarmbediening, acties voor capaciteitsmetingen, schermen met verbruik per app en updateacties. Interactiegebeurtenissen bevatten alleen vaste categorieën voor onderdeel, bedieningselement en actie; geen ingevoerde tekst, alarmdrempels of laadlimietwaarden, batterijmetingen, tijdstippen uit de geschiedenis of namen van apps op de voorgrond. Functiegebeurtenissen tellen geselecteerde functieopeningen en ingeschakelde alarmen. Per export registreert de analyse ook alleen het vaste type en of opslaan is gelukt, geannuleerd of mislukt; de bestandsnaam, bestemming en inhoud worden nooit ontvangen. Firebase verwerkt ook appstarts, sessies, een pseudonieme app-instantie-ID en technische gegevens zoals appversie, Android-versie en apparaatmodel. Als Google Play deze informatie levert, kan ook de installatie- of updatebron worden ontvangen.

Tijdens de verzameling door Google Analytics gebruikt Google het IP-adres om een globale locatie af te leiden. Google verwijdert het IP-adres voordat het wordt vastgelegd of opgeslagen. Het verzamelen van de advertentie-ID en gepersonaliseerde advertenties zijn uitgeschakeld. Batterijmetingen, namen van apps op de voorgrond, accountgegevens en precieze locatie worden niet als Analytics-gebeurtenissen verzonden. Firebase versleutelt Analytics-gegevens tijdens de overdracht met TLS.

In het gekoppelde Firebase Analytics-project is de bewaartermijn voor gegevens op gebeurtenis- en gebruikersniveau momenteel ingesteld op twee maanden. De optie om de bewaartermijn van gebruikersgegevens bij nieuwe activiteit opnieuw te laten ingaan, staat uit. Geaggregeerde rapporten kunnen langer bewaard blijven. Je kunt toestemming in de app intrekken; AkkuTakt stopt dan toekomstige verzameling en stelt de Analytics-app-instantie-ID opnieuw in. Eerder naar Google verzonden gegevens worden hierdoor niet verwijderd. AkkuTakt biedt geen apart verzoek om die gegevens op afstand te verwijderen.

### Verbindingen, updates, back-ups en exports

De Android Direct-editie maakt periodiek verbinding met GitHub om openbare updategegevens op te halen. GitHub kan je IP-adres en technische verzoekgegevens verwerken volgens het [privacybeleid](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Een APK wordt pas gedownload nadat je een update kiest. De Google Play-editie ontvangt updates via Google Play; iOS-updates komen via de Apple App Store.

Android-cloudback-ups en apparaatoverdrachten sluiten de batterijgeschiedenis, sessies, instellingen en telemetrie van AkkuTakt uit. Back-ups die met oudere Android-versies zijn gemaakt, kunnen bij de provider blijven staan. iOS-back-ups kunnen lokale appgegevens bevatten; Apple en je apparaatinstellingen beheren dat. Je kunt in de app zelf een back-up maken en de bestemming kiezen. Het geëxporteerde bestand is mogelijk niet versleuteld.

CSV-, onderzoeks-JSON- en diagnoserapporten worden alleen gemaakt wanneer je ze aanvraagt. CSV en onderzoeks-JSON kunnen tijdstempels, batterij- en sessietelemetrie en pakketnamen van apps op de voorgrond bevatten wanneer toegang tot appgebruik op Android is ingeschakeld. De onderzoeks-JSON bevat ook buildgegevens van de app en het apparaat en de vingerafdruk van het releasecertificaat. Er staan geen account, precieze locatie, serienummer of advertentie-ID in. De bestanden worden niet automatisch naar AkkuTakt gestuurd; jij kiest de bestemming of de ontvangende app.

### iOS

De iOS-app gebruikt Apples `UIDevice`-interface voor batterijniveau en laadstatus. De metingen worden lokaal in de app opgeslagen; maximaal de 720 meest recente blijven bewaard. iOS biedt apps van derden geen betrouwbare metingen van stroom, ontwerpcapaciteit of slijtage; AkkuTakt verzint of verzendt zulke waarden niet. De iOS-app bevat geen Firebase Analytics-verzameling.

### Je privacyrechten

Voor zover de toepasselijke privacywetgeving deze rechten geeft, kun je verzoeken om inzage in, correctie of verwijdering van je persoonsgegevens, beperking van de verwerking of overdraagbaarheid, en bezwaar maken tegen verwerking. Je kunt je toestemming op elk moment voor de toekomst intrekken; dit verandert niets aan de verwerking vóór die intrekking. Je kunt ook een klacht indienen bij een bevoegde privacytoezichthouder. Gebruik voor verzoeken het privacycontact hieronder.

### Contact en derden

Gebruik voor privacyvragen het contact in de betreffende app-storevermelding. Zie het [Google-privacybeleid](https://policies.google.com/privacy) en [Firebase Privacy en Beveiliging](https://firebase.google.com/support/privacy) voor de gegevenspraktijken van Google. De privacyverklaring van GitHub staat hierboven gelinkt.
