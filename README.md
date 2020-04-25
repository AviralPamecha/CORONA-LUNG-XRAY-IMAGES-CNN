# CORONA-LUNG-XRAY-IMAGES-CNN
                                      A CNN Model to Classify Lung Images of Patients as Normal or Infected
                                  
Possible reasons for stale accuracy on 20 epochs

Highly imbalance target variables
COVID-19 target value = positive rows have count as 58
Normal target value = negative rows have count as 1342
100 * (1342 / 1400) ~ 95.86 %
Even if model classifies all the images as "Normal" label, it would achieve 95.86 % accuracy                                  
