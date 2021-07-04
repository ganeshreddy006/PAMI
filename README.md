# PAMI stands for PAttern MIning

This software is provided under GNU GENERAL PUBLIC LICENSE Version 3, 29 June 2007. For more information on license visit: https://www.gnu.org/licenses/quick-guide-gplv3.html

PAMI constitutes of several pattern mining algorithms to discovers interesting patterns in transactional/temporal/spatiotemporal databases.

# Required python packages 
    Please install the following python packages before installing/utilizing PAMI package: 
    1. psutil : To calculate memory requirements of an algorithm, and 
    2. pandas : The patterns generated by our algorithms can be read into a pandas data frame. 
    
    COMMAND: pip install psutil pandas
    
    As a part of future work, we intend to extend PAMI to accept pandas data frame as an input to a pattern mining algorithm.
   
    
# Details 
Total available algorithms: 37

1. Frequent pattern mining: 
     
   | Basic | Closed | Maximal |
   |-------|--------|---------|
   |Apriori|Closed|maxFP-growth|
   |FP-growth|    |   |
   |ECLAT| | |
   |ECLAT-bitSet| | |

2. Frequent pattern mining using other measures:
    
    |Basic|
    |-----|
    |RSFP|
        
3. Correlated pattern mining: 

    |Basic|
    |-----|
    |CP-growth|
    |CP-growth++|
    
4. Frequent spatial pattern mining: 

    |Basic|
    |-----|
    |spatialECLAT|
    |FSP-growth ?|
    
5. Correlated spatial pattern mining: 

    |Basic|
    |-----|
    |SCP-growth|
    
5. Fuzzy correlated pattern mining:

    |Basic|
    |-----|
    |CFFI|
    
6. Fuzzy frequent spatial pattern mining:

    |Basic|
    |-----|
    |FFSI|
    
7. Fuzzy periodic frequent pattern mining:

    |Basic|
    |-----|
    |FPFP-Miner|
    
8. High utility frequent spatial pattern mining:

    |Basic|
    |-----|
    |HDSHUIM|
 
9. High utility pattern mining:

    |Basic|
    |-----|
    |EFIM|
    |UPGrowth|
    
10. Partial periodic frequent pattern:

    |Basic|
    |-----|
    |GPF-growth|
    |PPF-DFS|
    
12. Periodic frequent pattern mining: 

    |Basic| Closed | Maximal |
    |-----|--------|---------|
    |PFP-growth|CPFP|maxPF-growth|
    |PFP-growth++| | |
    |PS-growth| | |
    |PFP-ECLAT| | |
    
13. Partial periodic pattern mining:

    |Basic|Maximal|
    |-----|-------|
    |3P-growth|max3P-growth|
    |3PECLAT| |
    

14. Uncertain correlated pattern mining: 
    
    |Basic|
    |-----|
    |CFFI|
    
15. Uncertain frequent pattern mining:
    
    |Basic|
    |-----|
    |PUF|
    |TubeP|
    |TubeS|
    
16. Uncertain periodic frequent pattern mining:
     
     |Basic|
     |-----|
     |PTubeP|
     |PTubeS|
     |UPFP-growth|
     
17. To be continued. 


