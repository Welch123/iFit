# Introduction
This is the replication package for our work submitted to ICSE 2023.

``Note that we only provide the data set used in our work. Tools used to perform the work will be available after our paper's acceptance.``

# CSN<sub>WD</sub>
This directory contains the CSN<sub>WD</sub> that we built for all the subject systems used in our experiments. There are three versions of CSN<sub>WD</sub>s according to different weighting mechanisms (i.e., OWM, EWM and DWM).

``We made the class names in these files anonymous, which will be recovered after the acceptance of our work.``

# goldset
This directory contains the <i>true key classes</i> in each subject system. We collected this data set from the literature.

# Results
This directory contains the results obtained in the experiments. We use these results to answer the research questions, RQ1 and RQ2. We can use the data in RQ1 to answer RQ3.

``Because there is greater redundancy in reporting <i>Precision</i>, <i>Recall</i>, and <i>F<sub>1</sub></i> at the same times. Due to space limitation, we do not put the <i>precision</i> and <i>F<sub>1</sub></i> results in our manuscript. The file Results/RQ1/reasons.pdf provides a detailed description of the reason why we only reported the <i>Recall</i> results in our manuscript.``

## Results/RQ1/Recall|Precision|F<sub>1</sub>
These three directories contain the <i>recall</i>, <i>precision</i>, and <i>F<sub>1</sub></i> results of iFit and eight baseline approaches when we examine k% (k<15) of the top-ranked classes.

## Results/RQ2/Recall|Precision|F<sub>1</sub>
These three directories contain the <i>recall</i>, <i>precision</i>, and <i>F<sub>1</sub></i> results of iFit and eight baseline approaches when we examine the top-30 ranked classes.
