# DBpedia vs WikiData RDF-Molecules Test Dataset

## Description
This test dataset contains RDF Molecules information from DBpedia and Wikidata. 20000 people (type : Person)
The dataset contains the following files:

1. **trueGoldStandard.nt** : This file contains the sameAs link between DBpedia and Wikidata molecules. It represents the gold standart to be compared at the end of the integration process.
2. **goldStandard_dbp_cleaned.nt.zip**: This file contains the DBpedia molecules information. sameAs link to the WikiData molecule were removed.
3. **goldStandard_wd_upd_cleaned.nt.zip**: This file contains the Wikidata molecules information. sameAs link to the DBpedia molecule were removed.
4. **adSem.tar.gz**: This file contains additional semantic information for the molecules. Equivalent properties of molecules, owl:sameAs of objects of molecules.
