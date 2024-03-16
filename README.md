# LipNet: End-to-End Sentence-level Lipreading
Tensorflow implementation of the method described in the paper `LipNet: End-to-End Sentence-level Lipreading` by Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (https://arxiv.org/abs/1611.01599).

I have made a few changes to the method used in the paper -

- Instead of using all 32 speakers in the GRID Dataset, I have used only 1 so as to save training time and computational resources.
- The paper uses dlib for extracting the lip region.I have done it statically myself so as to keep it straight forward

# Model 

![163DC9D2-78EE-46A9-A135-30451741397C](https://github.com/MayankPalan2004/LipNet/assets/144169682/a40d1dd7-13b6-4646-971b-684baf66e7e9)

# Results

##  Sentence spoken
![03CCAA0E-B144-44CB-A54C-B544017D5BC9](https://github.com/MayankPalan2004/LipNet/assets/144169682/b6829a85-38ff-40b3-89e2-607c4d212ca2)
![A679C56E-0CE4-4B78-820B-7484677111CA](https://github.com/MayankPalan2004/LipNet/assets/144169682/24a4ebad-c5aa-4d7e-81b9-c832a3f39976)

## Predictions
![F2A63F44-3DD4-46E6-B1B0-FA45AA536481](https://github.com/MayankPalan2004/LipNet/assets/144169682/383c0d8f-e8e6-4214-ac4a-f645af39925a)
![0C4D2B74-7078-4873-9EEA-816D03761849](https://github.com/MayankPalan2004/LipNet/assets/144169682/b2311aaf-0047-4f7f-bd1f-923c11420520)

