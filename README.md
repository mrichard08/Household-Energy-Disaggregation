# DAEN-690-Appliance-Anomaly-Detection

Household energy disaggregation is the process of inferring the electrical power consumption of individual household appliances from the total power measurement of a residential smart meter. Disaggregation algorithms can be used to break down household energy consumption data into appliance level measurements and predict the appliance state and energy consumption. Widespread deployments of residential smart meters have caused energy disaggregation to be a popular research topic and a potential tool for electric utilities to develop demand-side incentives to modify customer energy consumption behavior. This project uses cutting edge deep learning techniques and probabilistic graphical models to develop NILM algorithms that predict individual appliance energy usage using only aggregate smart meter interval load data. The models were trained using the REFIT dataset, which includes approximately two years of aggregate and sub-metered load from 20 households in the UK. In addition to developing an energy disaggregation model, the team implemented an unsupervised anomaly detection algorithm to identify deviations from typical appliance consumption patterns. The combined disaggregation and anomaly detection model could be used by electric utilities to make residential customers more aware of their energy usage and provide notification of potential appliance problems. The models were trained using open source Python libraries such as hmmlearn, Tensorflow, and Keras and they were deployed in the George Mason ARGO Cluster and AWS cloud environment.
