## 📄 Description des colonnes du dataset accidents de la route

| Colonne | Type | Description |
|--------|------|-------------|
| `ID` | string | Identifiant unique de l’accident |
| `Source` | string | Source de la donnée (ex. capteur, service public) |
| `Severity` | integer | Gravité de l’accident (1 à 4, 4 étant le plus grave) |
| `Start_Time` | timestamp | Date et heure de début de l’accident |
| `End_Time` | timestamp | Date et heure de fin estimée de l’impact |
| `Start_Lat` | double | Latitude du lieu de l’accident |
| `Start_Lng` | double | Longitude du lieu de l’accident |
| `End_Lat` | double | Latitude de fin (peut être manquante ou identique à start) |
| `End_Lng` | double | Longitude de fin |
| `Distance(mi)` | double | Distance impactée estimée en miles |
| `Description` | string | Description textuelle de l’accident |
| `Street` | string | Nom de la rue concernée |
| `City` | string | Ville de l’accident |
| `County` | string | Comté de l’accident |
| `State` | string | État américain (code à 2 lettres) |
| `Zipcode` | string | Code postal |
| `Country` | string | Pays (principalement US) |
| `Timezone` | string | Fuseau horaire local |
| `Airport_Code` | string | Code de l’aéroport le plus proche |
| `Weather_Timestamp` | timestamp | Date/heure de la mesure météo associée |
| `Temperature(F)` | double | Température en degrés Fahrenheit |
| `Wind_Chill(F)` | double | Température ressentie (facteur vent) |
| `Humidity(%)` | double | Taux d’humidité (%) |
| `Pressure(in)` | double | Pression atmosphérique en pouces de mercure |
| `Visibility(mi)` | double | Visibilité en miles |
| `Wind_Direction` | string | Direction du vent (ex. N, NW, SSW…) |
| `Wind_Speed(mph)` | double | Vitesse du vent en mph |
| `Precipitation(in)` | double | Quantité de précipitations en pouces |
| `Weather_Condition` | string | Condition météo générale (ex. Rain, Fog, Clear…) |
| `Amenity` | boolean | Proximité d’un équipement ou installation |
| `Bump` | boolean | Présence d’un dos-d’âne |
| `Crossing` | boolean | Proximité d’un passage piéton ou intersection |
| `Give_Way` | boolean | Panneau de priorité (Give Way) présent |
| `Junction` | boolean | Proximité d’un carrefour |
| `No_Exit` | boolean | Route sans issue proche |
| `Railway` | boolean | Voies ferrées proches |
| `Roundabout` | boolean | Proximité d’un rond-point |
| `Station` | boolean | Station de transport proche |
| `Stop` | boolean | Présence d’un panneau stop |
| `Traffic_Calming` | boolean | Aménagement de ralentissement (ex. chicane) |
| `Traffic_Signal` | boolean | Présence d’un feu de circulation |
| `Turning_Loop` | boolean | Présence d’un point de retournement |
| `Sunrise_Sunset` | string | Moment de la journée (Day/Night) |
| `Civil_Twilight` | string | Crépuscule civil (Day/Night) |
| `Nautical_Twilight` | string | Crépuscule nautique (Day/Night) |
| `Astronomical_Twilight` | string | Crépuscule astronomique (Day/Night) |