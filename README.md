# Contingent Causal Event Pairs
This page was migrated from https://nlds.soe.ucsc.edu/contingent. Please see zip file above for download. Please contact me to download the IMDSB film scenes (26MB).

**If you use this data in your research, please refer to and cite**: Hu, Zhichao, Elahe Rahimtoroghi, Larissa Munishkina, Reid Swanson, and Marilyn A. Walker. "[Unsupervised Induction of Contingent Event Pairs from Film Scenes](https://www.researchgate.net/profile/Marilyn_Walker2/publication/256695472_Unsupervised_Induction_of_Contingent_Event_Pairs_from_Film_Scenes/links/00b7d5239f6966d083000000.pdf)." In Conference on Empirical Methods in Natural Language Processing (EMNLP), Seattle, Washington, USA, 2013.

## Overview

Contingency is the name of a PDTB relation that holds between two events that is a generalization of two subrelations: causality and condition. Both causality and condition relations hold between events that are likely to happen together in a certain context. Sometimes these relations are marked by discourse cues, such as because or if-then. Often in raw text it is unclear which of causality or condition holds, in which case the contingency relation can be used.

## Data
This paper tests 4 different methods to estimate the likelihood of contingent relation between events in a corpus of film scenes for the Action Genre and the Romance Genre. We evaluate the top 100 contingent event pairs from each method against random event pairs using Mechanical Turk. The corpus contains the MT ratings for each pair. 

## Related Papers
The film corpus used to build this corpus is based on the following papers.

* Marilyn A. Walker, Ricky Grant, Grace Lin, Jennifer Sawyer, Noah Wardrip-Fruin and Michael Buell. [Perceived or Not Perceived: Film Character Models for Expressive NLG](http://users.soe.ucsc.edu/~maw/papers/icids-v12.pdf). In Interactive Storytelling: Fourth Joint Conference on Interactive Digital Storytelling (ICIDS), Vancouver, Canada, 2011.
* Marilyn A. Walker, Grace I. Lin, Jennifer E. Sawyer. "[An Annotated Corpus of Film Dialogue for Learning and Characterizing Character Style](http://www.lrec-conf.org/proceedings/lrec2012/pdf/1114_Paper.pdf)." In Language Resources and Evaluation (LREC), Istanbul, Turkey, 2012.
