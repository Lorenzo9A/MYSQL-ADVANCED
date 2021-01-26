# Antwoorden Eindopdracht

1. Copy paste je gemaakte SQL query hieronder
   SELECT races.name AS "Race", circuits.name AS "circuit" FROM races LEFT JOIN circuits ON races.circuitId = circuits.circuitId WHERE races.year = "2018"
2. Copy paste je gemaakte SQL query hieronder
   
3. Copy paste je gemaakte SQL query hieronder
    SELECT drivers.forename, drivers.surname, pitstops.duration FROM pitstops LEFT JOIN drivers ON pitstops.driverId = drivers.driverId WHERE pitstops.duration < "25"
4. Copy paste je gemaakte SQL query hieronder
   SELECT constructors.name, races.name AS "races" FROM races LEFT JOIN constructors ON races.circuitId = constructors.constructorId WHERE constructors.name = "McLaren" AND races.year = "2018"
5. Copy paste je gemaakte SQL query hieronder
   
