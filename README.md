# YSI prediction
This notebook predicts fuel [Yield Sooting Index(YSI)](http://pfefferlehallerlabs.yale.edu/ysi-database). The fearures are molecular descriptors calculated by [Dragon](http://www.talete.mi.it/products/dragon_description.htm). A 
machine learning pipeline is constructed with regularized linear models. This 
simple model achieves comparable performance with fully connected neural networks adopted by the [original paper](http://pubs.acs.org/doi/abs/10.1021/acs.energyfuels.7b00616).
See [here](https://dataverse.harvard.edu/file.xhtml;jsessionid=5f253efa287a5d3bb89541a3dc76?fileId=3048974&version=RELEASED&version=.0) for a primer for YSI.
The data are taken from [here](https://github.com/pstjohn/ysi_qsar_energy_fuels).
