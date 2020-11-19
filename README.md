# big-ideas-final
- Team name: Access Denied
- Group members: Ailee Cash (aic25@pitt.edu), Henry Powers (hap60@pitt.edu), Jeffrey Janotka (jlj94@pitt.edu)
- Datasets:
    - City of Pittsburgh Trees (https://data.wprdc.org/dataset/city-trees)
    - Waste Recovery Locations (https://data.wprdc.org/dataset/waste-recovery-locations/resource/51f0c4f3-0ddd-4073-8f39-ad19d7528575)
    - Natural Environment Conditions (https://data.wprdc.org/dataset/pgh/resource/14501cb9-308d-49ce-8bbb-7933ad703fe1)
## Abstract
For this project, we decided to try to determine the most environmentally friendly neighborhood in Pittsburgh. We ended up finding that to be Squirrel Hill South using our metric. The metric is a score ranging from 0-1 for each neighborhood. This score is an average of three other 0-1 scores, one for each dataset. Since every dataset has a different range, we normalized each one to a 0-1 scale by making the maximum value 1 and the minimum value 0 with the rest of the values being in the same relative position to their pre normalized counterpart.
