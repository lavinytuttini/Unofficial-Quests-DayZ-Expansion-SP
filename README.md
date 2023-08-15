# Unofficial-Quests-DayZ-Expansion-SP (CHERNARUS ONLY)
**¡Bienvenidos al Repositorio de Misiones en Español para DayZ!** Aquí encontrarás una colección de emocionantes misiones diseñadas específicamente para el popular mod Expansion Quests, ambientadas en el icónico escenario del mapa Chernarus.

## Anotaciones:

- Todas estas misiones han sido probadas y confirmadas de manera funcional por un grupo de personas que han jugado dentro de un servidor bajo las últimas versiones de DayZ-Expansion v1.8.19 y v1.8.21.
- La convención y mejora de identificación de misiones y objetivos podrán cambiar con el paso del tiempo.
- Según el tiempo del que disponga iré incorporando y creando nuevas misiones.
- Aquí no vas a aprender a configurar DayZ-Expansion-Quests ([Wiki](https://github.com/salutesh/DayZ-Expansion-Scripts/wiki/%5BServer-Hosting%5D-Expansion-Quests)).
- Aquí podrás ver dónde tienes que copiar y pegar todas las misiones, objetivos, objetos de misión, loadouts y npcs que necesitas para incluir todas estas misiones que he modificado y creado completamente en Español.
- Soy consciente de que puede haber errores en todos los aspectos, hago lo que puedo en el tiempo que dispongo. 

## Requerimientos mínimos:

En principio no son necesarios ningún otro mod que pueda influir en la accesibilidad de las misiones, objetivos, objetos de misión, loadouts y npcs. Estas misiones están totalmente limpias y solo se recomienda los mods imprescindibles que solicita Expansion.

**Obligatorio:**

- [CF](https://steamcommunity.com/workshop/filedetails/?id=1559212036)
- [DayZ-Expansion-Core](https://steamcommunity.com/workshop/filedetails/?id=2291785308)
- [Dabs Framework](https://steamcommunity.com/workshop/filedetails/?id=2545327648)
- [DayZ-Expansion-Quests](https://steamcommunity.com/sharedfiles/filedetails/?id=2828486817&searchtext=DayZ-Expansion-Quests)

**Recomendable tener instalados:**

- [DayZ-Expansion-AI](https://steamcommunity.com/sharedfiles/filedetails/?id=2792982069&searchtext=DayZ-Expansion-AI)

_Si no lo deseas, puede ser eliminado borrando las misiones principales 103, 104, 109, 112, 900 y 901, así como eliminando las carpetas de objetivos chernarusplus\profile\ExpansionMod\Quests\Objectives\AICamp, AIPatrol y AIVIP._

- [DayZ-Expansion-Market](https://steamcommunity.com/sharedfiles/filedetails/?id=2572328470&searchtext=DayZ-Expansion-Market)
```
    "Rewards": [
        {
            "ClassName": "ExpansionBanknoteHryvnia",
            "Amount": 50,
            "Attachments": [],
            "DamagePercent": 0,
            "HealthPercent": 0,
            "QuestID": -1
        }
    ],
```
_Si no lo deseas, puede ser modificado por algún otro reward u objeto de otro mod que te interese dentro de cada misión._

## Convención de nombres:

Después de haber estudiado diferentes casos y modelos, sobretodo la de [guiltysyndicate](https://github.com/guiltysyndicate/Unofficial-Quests-For_DayZ-Expansion). He terminado por plantear la siguiente convención de nomenclaturas para identificar fácilmente las misiones y objetivos:

<hr/>

```
1    -  Logros
100  -  Misiones Principales
200  -  Objetivos
300  -  Viajes
400  -  Recolección
500  -  Entrega
600  -  Caza del Tesoro
700  -  AIPatrol
800  -  AICamp
900  -  AIVIP
1000 -  Acción
1100 -  Artesanía
```

_No obstante pueden cambiar esta convención según necesidad. Acordándose siempre de cambiar el ID de cada misión y objetivo ya que son la parte más importante._

<hr/>

He decidido implementar las **Misiones** de esta forma para poder identificarlas de manera más sencilla y rápida.

**Nomenclatura misiones genéricas:**
```
{idQuest}-{typeQuest}-{objetiveQuest}.json
```
**Ej:** _400-Collect-Apples-5.json_ 

**Nomenclatura misiones principales y consecutivas:**
```
{idQuest}-{typeQuest}-{orderQuest}.json
```
**Ej:** _106-MainMission-01.json 107-MainMission-02.json 108-MainMission-03.json_

<hr/>

De otra forma, los **Objetivos** podrán asociarse y verificarse fácilmente de la siguiente manera.

**Nomenclatura objetivos comúnes y/o repetibles:**
```
{idObjetive}-{typeObjetive}-{objetiveObjetive}.json
```
**Ej:** _5-Target-Zeds-Military-10.json_

**Nomenclatura objetivos principales para misiones principales:**
```
{idObjetive}-{typeObjetive}-MainMission-{missionId}.json
```
**Ej:** _3-Collection-MainMission-106.json_

## Cómo instalar estas plantillas:

### 1. Quests

Copiar las Misiones de <code>[chernarusplus/profile/ExpansionMod/Quests/Quests/](https://github.com/lavinytuttini/Unofficial-Quests-DayZ-Expansion-SP/tree/main/chernarusplus/profile/ExpansionMod/Quests/Quests)</code> y pegarlas o transferirlas mediante FTP a tu directorio <code>(profile o config)/ExpansionMod/Quests/Quests/</code>.

### 2. Objetives

Copiar los Objetivos de <code>[chernarusplus/profile/ExpansionMod/Quests/Objectives/](https://github.com/lavinytuttini/Unofficial-Quests-DayZ-Expansion-SP/tree/main/chernarusplus/profile/ExpansionMod/Quests/Objectives)</code> y pegarlas o transferirlas mediante FTP a tu directorio <code>(profile o config)/ExpansionMod/Quests/Objetives/</code>.

### 3. Quest Objects

Copiar los Objetos de Misión de <code>[chernarusplus/mpmissions/dayzOffline.chernarusplus/expansion/objects/](https://github.com/lavinytuttini/Unofficial-Quests-DayZ-Expansion-SP/tree/main/chernarusplus/mpmissions/dayzOffline.chernarusplus/expansion/objects)</code> y pegarlas o transferirlas mediante FTP a tu directorio <code>/mpmissions/dayzOffline.chernarusplus/expansion/objects/</code>.

### 4. NPC's

Copiar los NPC's de <code>[chernarusplus/profile/ExpansionMod/Quests/NPCs/](https://github.com/lavinytuttini/Unofficial-Quests-DayZ-Expansion-SP/tree/main/chernarusplus/profile/ExpansionMod/Quests/NPCs)</code> y pegarlos o transferirlas mediante FTP a tu directorio <code>(profile o config)/ExpansionMod/Quests/NPCs/</code>.

### 5. Loadouts

Copiar las Misiones de <code>[chernarusplus/profile/ExpansionMod/Loadouts/](https://github.com/lavinytuttini/Unofficial-Quests-DayZ-Expansion-SP/tree/main/chernarusplus/profile/ExpansionMod/Loadouts)</code> y pegarlas o transferirlas mediante FTP a tu directorio <code>(profile o config)/ExpansionMod/Loadouts/</code>.

## Está bien que conozcas lo siguiente:

- NO doy soporte.
- NO contesto comentarios.
- NO apruebo cambios ni correcciones.
- Subiré cambios y correcciones cuando YO tenga ganas y tiempo.
- El uso de estos ficheros y lo que hagas con ellos quedan bajo tu responsabilidad.
- Y por último, disfruta lo que te dan gratis y no te quejes.
