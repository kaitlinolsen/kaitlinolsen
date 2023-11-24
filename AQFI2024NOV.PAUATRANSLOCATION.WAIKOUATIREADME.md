## Translocation of Pāua from Waikouati River Mouth to Butterfly Bay AQFI301 2023 November Trip

By: Kaitlin Olsen, Alexandra Faulkner, Lily Harvey, and Maddison Hafoka 

There are three versions of Pāua translocation this is the version from Waikouati River Mouth, while the other two versions are from Warrington Point (Okahau) and Puketeraki. 

This initiative involved the transfer of 120 Blackfoot pāua (Haliotis iris) from Waikouati River Mouth to Huriawa Pā (Peninsula) Butterfly Bay located in the Karitane Taiāpure part of Otago, New Zealand. Before the translocation, a population density survey was conducted to assess the existing population, measuring lengths and counts along a 30-meter transect line using a random number generator to decide the placement of a quadrat along the transect line, 10 quadrat (1m^2) samples were taken. Pāua scheduled for translocation the next day were also documented with the same variables and categorized for different release methods.

Release Methods:
Two release methods were employed hard release (HR) and soft release (SR). Hard release involved placing pāua, translocated within a dive catch bag, directly onto rocks at the new site. Soft release utilized pōhā made from Southern Bull kelp, with pāua placed at the translocation site along with the pōhā. The day after the initial translocation, a count of pāua was recorded to evaluate the viability of the new site.

## ./data/input/
- 'population_density_survey.csv': formally 'populationdensitysurvey.xlsx' Quadrat number, meterage surveyed, pāua count in quadrat, and length of all pāua found. A short description of the habitat is also included. data has been summarised with corresponding ID's to create graph outputs

| Code         | Meaning                           |
|--------------|-----------------------------------|
| QN | Quadrat location on transect  (*meters*) |
| Average Length  | *millimeters*              |
| Sand Coverage   | *percent*          |

- 'population_density_of_translocated.csv': formally 'populationdensityoftranslocatedpaua.xlsx' length measurements *millimetres* of pāua selected for translocation, release type and associated release number

| Code         | Meaning                           |
|--------------|-----------------------------------|
| HHP1 | Hard Release Huriawa Pa bag 1 |
| HHP2 | Hard Release Huriawa Pa bag 2             |
| HHP3 | Hard Release Huriawa Pa bag 3          |
|PHP1  | Pōhā Release Huriawa Pa bag 1|
|PHP2| Pōhā Release Huriawa Pa bag 2|
|PHP3|Pōhā Release Huriawa Pa bag 3|

- 'paua_within_2m_radius.csv': formally 'pauafoundwithin2mradiusofrelease.xlsx' number of pāua found within 2 meter radius of the release location

| Code         | Meaning                           |
|--------------|-----------------------------------|
| N/A | pōhā bag unable to be found, no data collected  |
