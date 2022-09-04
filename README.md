# Austin Animal Center Shelter Intakes and Outcomes

## About Dataset

### Context
The [Austin Animal Center](https://www.austintexas.gov/austin-animal-center) is the largest no-kill animal shelter in the United States that provides care and shelter to over 18,000 animals each year. As part of the AAC's efforts to help and care for animals in need, the organization makes available its accumulated data and statistics as part of the city of Austin's Open Data Initiative.

### Content
The data contains intakes and outcomes of animals entering the Austin Animal Center from the beginning of October 2013 to the present day. The datasets are also freely available on the Socrata Open Data Access API and are updated daily.

The following are links to the datasets hosted on Socrata's Open Data:

- [Austin Animal Center Intakes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm)
- [Austin Animal Center Outcomes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238)

The data contained in this dataset is the outcomes and intakes data as noted above, as well as a combined dataset. The merging of the outcomes and intakes data was done on a unique key that is a combination of the given Animal ID and the intake number. Several of the animals in the dataset have been taken into the shelter multiple times, which creates duplicate Animal IDs that causes problems when merging the two datasets.

Copied from the description of the Shelter Outcomes dataset, here are some definitions of the outcome types:

- Adoption
    - the animal was adopted to a home
- Barn Adoption
    - the animal was adopted to live in a barn
- Offsite Missing
    - the animal went missing for unknown reasons at an offsite partner location
- In-Foster Missing
    - the animal is missing after being placed in a foster home
- In-Kennel Missing
    - the animal is missing after being transferred to a kennel facility
- Possible Theft
    - Although not confirmed, the animal went missing as a result of theft from the facility
- Barn Transfer
    - The animal was transferred to a facility for adoption into a barn environment
- SNR
    - SNR refers to the city of Austin's Shelter-Neuter-Release program. I believe the outcome is representative of the animal being released.
    
### Acknowledgements

The data presented here is only possible through the hard work and dedication of the Austin Animal Center in saving and caring for animal lives.
