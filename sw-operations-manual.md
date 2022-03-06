SearchWing Helgoland Betriebshandbuch
===

# Übersicht
Für die Flüge nach Helgoland brauchen wir eine Genehmigung vom Luftfahrtbundesamt und dazu ist ein Betriebshandbuch erforderlich. 

Siehe: [gitlab issue 19](https://gitlab.com/searchwing/operational/MissionsPlanung/-/issues/19)

Die Gliederung erfolgt nach Annex A zum AMC1 zu Artikel 11 von EU2019/947. 

Siehe:  [Easy Access Rules for Unmanned Aircraft Systems (Regulation (EU) 2019/947 and Regulation (EU) 2019/945)](https://www.easa.europa.eu/document-library/easy-access-rules/easy-access-rules-unmanned-aircraft-systems-regulation-eu)

Bitte hier NUR TEXT, damit das Dokument nach odf exportiert werden kann. Mit Bildern geht das nicht... **Gliederungsnummern behalten!!!**

# A.1 Guidance for the collection and presentation of operationally relevant information

## A.1.1 Reserved
## A.1.2 Organisation overview

(a) The SearchWing group at Hochschule Augsburg develops a drone to search people in distress at sea. Students from HS Augsburg, students from other universities and members which are not part of a university work together in this group. Most of the work is done as voluntary work. The drone supports civil search and rescue organizations like Resqship e.V., Sea-Watch e.V. or Sea-Eye e.V.

In Augsburg are about 6 members doing the mechanical, electrical and flight firmware design of the drone and the ground station. The Berlin team is responsible for the image capture and analysis. There are members in Hamburg, Heidelberg and Zürich who mainly support the image analysis software team in Berlin.

Contact:

Prof. Dr.-Ing. Friedrich Beckmann
Hochschule Augsburg / Fakultät Elektrotechnik
An der Hochschule 1
86161 Augsburg
Email: friedrich.beckmann@hs-augsburg.de
Phone: +4917648576782

Website: https://searchwing.org

**UAS Operator Team**
Friedrich Beckmann
Gregor Walter
Philipp Borgers

**Remote Pilot Team**
Friedrich Beckmann
Gregor Walter
Philipp Borgers

**Safety Manager**
Friedrich Beckmann

(b) The responsibilites of the UAS operator are the ones defined in UAS.SPEC.050 except paragraph (k) and (l). In addition we have

1. an Operations Manual (OM - this document) including procedures to communicate with the authorities responsible for the management of the airspace
2. ???

### A.1.2.1 Safety
(a) We use an [issue tracking system](https://gitlab.com/searchwing) on gitlab to monitor and follow technical and organisational issues including safety issues. For all flights we do a [flight analysis](https://www.hs-augsburg.de/~beckmanf/dokuwiki/doku.php?id=searchwing#flugberichte) where we also discuss safety critical issues. Some risks which we identified and where we defined countermeasures were for example

- Propeller might hit your hand during hand launch => Provide and use cut protection gloves
- Working on Firmware setup might start the motor => Always remove propeller
- Switching to manual mode results in loss of control => Change remote switch configuration

New team members are introduced to the safety measures when doing the relevant work or more formalized by check lists.

(b) No additional safety related information

### A.1.2.2 Design and Production

(a) We design and build the drone within the SearchWing group.

Augsburg:
- mechanical and electrical design, production and test of the drone
- design, production and test of the ground station hardware and firmware for communication
- Flight tests

Berlin:
- Image capture and analysis on the drone
- Groundstation image analysis software
- Build drones
- Flight tests

(b) n.a. - we design and build the drone
(c) n.a. - we design and build the drone

### A.1.2.3 Training of staff involved in operations
The helgoland test flights are done by the SearchWing Team. We are all involved in the production of the drone. The UAS Operator Team will do an introduction to the special situation on Helgoland for the team members who were not involved in planning for Helgoland.

### A.1.2.4 Maintenance
(a) The general maintenance philosophy is to have procedures in place to reduce the risk of failure during flight for the safety relevant parts. We have time based maintenance for the motor together with a condition based replacement of parts, e.g. for the propeller. In addition we have procedures to reduce the risk of failure.

(b) The maintenance procedures are:

1. Replace the propeller if visual inspection shows any damage or fractures.
2. Rinse the drone with fresh water after each contact with seawater, especially before storage
3. Replace the battery if the battery voltage was below 12,4 V
4. Replace the motor after XXXh of flight

(c ) We do not have a special maintenance organization

### A.1.2.5 Crew

(a) The responsibilities of the crew members are:

(1) The remote pilot has the responsibilities according to UAS.SPEC.060. In addition the remote pilot informs and aligns the flight plan with the ship crew.

(2) The support team

1. A launch helper launches the drone by hand. The launch is done with the remote pilot operating the remote control which arms the drone and starts the motor. The launch helper and remote pilot are in close distance such that they can communicate directly. A launch procedure is shown in this video: https://vimeo.com/631180395#t=110s
2. The recovery helper retrieves the drone out of the water after landing. The drone lands in the water nearby the ship. An example recovery with a sailing yacht is shown in this video: https://youtu.be/BJjEGadHUUY?t=85
3. Ship crew: The ship crew is responsible for positioning the ship for launch and retrieval of the drone. The ship crew can stop the drone operation if the drone operation is not compatible with a safe ship operation.

(b) We do not do multi-crew operations

(c ) We do not have different types of UAS

(d) If a pilot or other team members do not feel fit, capable and able to conduct the planned operations, then we do not fly, i.e. any team member can stop the operations. The UAS operator team will stop any operations if members of the team are obviously not ready to do safe flight operations.

### A.1.2.6 UAS Configuration Management
Our drone is an experimental drone. Before the drone is ready for flights on the sea we do component tests, e.g. for water resistance and then we fly in visual line of sight on the ground.

### A.1.2.7 Other positions and other information

No other positions and no other information

## A.1.3 Operations

### A.1.3.1 Type of Operations

The flights are done during a student Exkursion to Helgoland between 10.8.2022 and 18.8.2022. We only fly during daylight between sunrise and sundown.

We fly search patterns over the sea near Helgoland in the "Extended BVLOS UAV Area" from Fraunhofer Institut für Fertigungstechnik und Angewandte Materialforschung (IFAM). Our drone has two cameras on board which operate at target ground resolution at an altitude of 550m above ground. The camera system covers a width of 2km on the ground. Therefore the flight trajectories will be 2km apart. We can cover an area of about $140 km^2$ on the ground during one flight.

The drone is operated from the Aade ship which is provided from the Alfred Wegener Institut (AWI). The ship will be in the flight area during the complete flight time. The ground station is also on the Aade. The drone is launched from the ship with a hand launch in automatic mode. The search pattern flightplan is stored in the flight computer and follows the flightplan automatically.

### A.1.3.2 Normal operation strategy

### A.1.3.3 Standard operating procedures

#### A.1.3.3.1 Normal operating procedures

#### A.1.3.3.2 Contingency and emergency procedures

#### A.1.3.3.3 Occurence reporting procedures

### A.1.3.4 Operational limits

### A.1.3.5 Emergency Response Plan

## A.1.4 Remote Crew Training

# A.2 Guidance for the collection and presentation of technical relevant information


















