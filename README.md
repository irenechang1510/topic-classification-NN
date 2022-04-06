# Topic classification Neural Network
 
*Check out my Towardsdatascience [article](https://towardsdatascience.com/covid-19-policies-multi-classification-with-neural-network-d85cbc0f90c0) on this project!*
 
This is an ongoing project I'm working on for Coronanet.org, a NPO working on collecting data on covid policies around the globe, cleaning and publishing them to an open source repo that academia, journalists and government can use to do analysis. We have a team of research assistants (RAs) who extract the data from various sources and 'code' them into the big database through filling out a survey. The raw dataset format has multiple columns for every detailed information of the policy.

The current task of the team is to build a machine learning/deep learning model that predicts the type for a policy (Social Distancing, Business Regulation, Curfew, etc) based on its text description. The ultimate goal is to have the system help the RAs in the group reduce the misclassification rate when coding the policy, hence alleviating the task of the data validation/data cleaning team. From then, we can publish the cleaner version of data more quickly and efficiently.

The task involves 2 main stages: building a model, and building an interactive UI (for internal use) on which RAs can use to predict the type of any new policy (used for confirmation), and data cleaning team can use to validate the results of the model on unseen data, correcting the misclassifications that the model makes on these new policies, from which the corrected labels will be fed back into the model as a new data point.

In building the ML model, we tried different algorithms and discuss the results together. The model still has a lot of rooms for improvement, but here is a snapshot into the model we are building, in which I used the data already published on the website of the organization, instead of that from the internal database, as well as adjusting the codes anywhere appropriate. 
