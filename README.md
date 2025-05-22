# Manuscript
This is a README file of article "Is telomere length set already at conception? Insights from an assortative breeding experiment in a songbird".

Author information


Introductory information
Data file: ERC1_egg_chick_436st.xlsx & mid-parent_mid-off reg_r.xlsx

R-script: ERC1_egg_chick_r.rmd

Description of the data and file structure

Main data file contains measurements that collected during breeding experiment time (etc clutch size and body mass of nestlings) and relative telomere length (t/s-ratio) that measured with qPCR method after breeding experiment.

Lab_id
Lab ID is unique to every individual (either embryo or nestling) that has sampled.

Type
There are two type of samples in the dataset. Embryo, that collected after 6 days incubation from an incubator. And nestling, that hatched and raised by parents zebra finch in the nest.

Ring_no
The ring number is unique to every nestling that has been ringed at 10-days-old when blood sample was collected. Only for nestlings.

Cage
The cage number of each pair of zebra finch pair

Mother and Father 
The ring number of parents zebra finches for each offspring

TLGroup
The selected telomere length group based on parent zebra finches’ early telomere length (long or short).

AgeGroup
The age group of parent zebra finches, young or old.

Sex
The sex of offspring, nestling sex can be determined based on morphology when 45-days-old. Sex of embryo were determined with molecular sexing method.

ts
the relative telomere length, or t/s-ratio. Measured by qPCR method. 

Round
The t/s-ratio of each offspring was measured twice. First round of qPCR happened in May 2021 and round two happened on May 2022.

clutch_egg and clutch_hatch & hatch_rate
Clutch_egg, the number of eggs that laid by each nest (zebra finch breeding pair), and clutch_hatch is how many of the eggs that laid in one nest is hatched. Hatch_rate is the proportion of successful hatching for each nest, calculated by clutch_hatch divided by clutch_egg.

sampling_age
The age of the nestling when its blood sample was collected. Only for nestlings. 

mass_d10
The body mass of the nestling when blood samples were collected. 

dead_chick_between_d0_d10, motarlity_d0_d10 & survived_chick
Dead_chick_between_d0_d10, is the number of chicks that dead from hatch to 10-days-old. Survived_chick is the number of chicks survived from hatch to 10-days-old. Mortality_do_d10 is the proportion of dead chick for each nest, calculated by dead_chick_between_d0_d10 divided by clutch_hatch.

egg_dev, dev_rate & infertility
Egg_dev, is the number of developed embryo checked 5/6days after incubation starts by either artificial incubator or parents. Dev_rate is the proportion of developed embryos per clutch. Infertility is the proportion of un-developed embryos per clutch

Code/Software
The rmd file contains the R (v4.3.1) code to perform all analysis described in the manuscript, also codes to make the particular figures based on the extracted data.




