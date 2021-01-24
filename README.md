# TUMuchIdeas
Technical Project Description of the TUM techchallenge to target the shortage of plastic consumables for COVID-19 PCR tests.

## About us

## Brief Introduction and our Solution Approach

The coronavirus pandemic is an ongoing pandemic caused by the COVID-19 disease (for more information to the pandemic we refer to [wikipedia](https://en.wikipedia.org/wiki/COVID-19_pandemic)).
In order to control this pandemic by disrupting infection chains, PCR tests have been one of the most essential tools so far.
Extensive PCR testing by many countries has lead to shortages and price increases for testing equipment.
Since first world countries have a higher market power and more money to spend compared to third world countries, this development has hit third world countries overproportional more than first world countries.
In particular, third world countries are struggling to get  access to plastic consumables for PCR tests on the world market. These are swabs, tubes, pipette tips, and spin columns.

To dampen the effects of supply shortages of such consumables, we have developed a mobile production table which is capable of producing these consumables within the testing laboratories. Our production plant is optimized to be simply deployable to laboratories in third world countries, to be operable by a low amount of labor, and only requires a minimum amount of training to be operated.


## Materials and Methods

Our production consists of three steps: printing, post processing, and packaging.

![production process](figures/production_process.png)

### Printing

To print the plastic consumables, first the CAD files are needed. These are found
here (TODO).
The CAD model of the consumables have to perfectly fit to the laboratory equipment.
Since every laboratory uses slightly different equipment, eventually some of the models
have to be adapted.
If the model is finished, it has to be sliced and converted to a STEP file for the 3D printer.
Afterwards, the printing can be started.

For the printing we use the .... resin.

### Post Processing

Post processing consists of two parts: Rinsing of excess material and UV curing.
For rinsing the excess resin we put the printed model into an isopropanol bath.

TODO: Wie lange muss das Teil drinnen bleiben?

For UV curing we build a custom designed UV chamber. It consists of a trash can out of metal,
where we put a cord with 2 UV lamps through the lid. Both UV lamps are 405 nm lamps.
The model than put on a glass plate which is then put into the UV chamber.

TODO: Wie lange dauert der Prozess?

### Packaging

Since our production happens within the laboratory, for consumables which are used within
a small amount of time, packaging is not required. However, this requires a good logistics
by the operators of the laboratory.
For equipment which should be stored, or should be delivered to other places (which is necessary for the swabs),
the consumables can be packaged into sterilized pouches.


## Results

In the following pictures of some of our printed consumables are shown.

![pipette](figures/printed_prototypes/pipette.jpg)

![spin_column](figures/printed_prototypes/spin_column.jpg)

![swab](figures/printed_prototypes/swab.jpg)

![tube](figures/printed_prototypes/tube.jpg)

In the following table, the printing times and costs of the consumables is shown.

|Resin            |Name                             |Density     |FIELD4    |Price per Liter|FIELD6          |FIELD7           |FIELD8      |
|-----------------|---------------------------------|------------|----------|---------------|----------------|-----------------|------------|
|                 |Surgical Guide Resin             |            |          |220            |                |                 |            |
|                 |Phrozen Beige Flex               |            |          |84.5           |                |                 |            |
|                 |                                 |            |          |               |                |                 |            |
|**Micropipette Tips**|**Name**                     |**Volume [m^3]**|**Volume [L]**|**Length [mm]**    |**Price/Part [EUR]**|**Time / Part [min]**|**Parts/Print** |
|                 |L30                              |1.08E-07    |0.00      |30             |0.091598        |141.7            |312         |
|                 |L50                              |2.99E-07    |0.00      |50             |0.2522325       |234              |112         |
|                 |L85                              |6.68E-07    |0.01      |85             |0.564122        |390              |72          |
|                 |                                 |            |0.00      |               |                |                 |            |
|**Swabs**            |**Name**                         |**Volume [m^3]**|**Volume [L]**|**Length [mm]**    |**Price/Part [EUR]**|**Time / Part [min]**|**Parts/Print** |
|                 |Honeybee Swab (Hexagonal Pattern)|1.41E-06    |0.01      |               |3.1042          |702              |209         |
|                 |Double Helix Swab                |1.48E-06    |0.01      |               |3.2472          |702              |209         |
|                 |Circular Pattern Swab            |1.42E-06    |0.01      |               |3.1152          |702              |209         |
|                 |                                 |            |          |               |                |                 |            |
|                 |Packaging tube swabs             |            |0.00      |               |0               |                 |            |
|                 |                                 |            |          |               |                |                 |            |
|**Spin Column**      |**Name**                         |**Volume [m^3]**|**Volume [L]**|**Length [mm]**    |**Price/Part [EUR]**|**Time / Part [min]**|**Parts/Print** |
|                 |Inner Tube                       |1.09E-06    |0.01      |               |0.91767         |161.2            |8           |
|                 |Outer Tube                       |1.88E-06    |0.02      |               |1.5886          |196.3            |28          |
|                 |                                 |            |          |               |                |                 |            |
|**Tubes**            |**Name**                         |**Volume [m^3]**|**Volume [L]**|**Length [mm]**    |**Price/Part [EUR]**|**Time / Part [min]**|**Parts/Print** |
|                 |Cylindrical Tube 1.5ml           |1.43E-05    |0.14      |               |12.0940118      |192.4            |12          |
|                 |                                 |            |          |               |                |                 |            |
|                 |Tube 1.5ml                       |1.35E-06    |0.01      |               |1.14413         |202.8            |12          |


From the print times and parts/print of the table, it can be seen that one printer is not able to produce the desired amount of
plastic consumables for one laboratory. However, this is not the goal of our project. Instead, we want to bypass short outages of
some plastic consumables. We expect that such outages are foreseeable and the production of these items can already start in advance.

TODO: Ausrechnen für welche plastic consumables wieviele am Tag produziert werden können.

## Discussion and Outlook
