## Welcome
Hi, I'm Sean Smith and I'm a data scientist/AI enthusiast. My primary interests are in NLP and Finance. I have experience working on interdisciplinary teams to leverage machine learning and data analytics to help get results from data. Here is some of my work:

### [Formality Transfer](https://github.com/sms1097/formality-transfer)
Formality transfer is a problem where we attempt to render informal sequences as formal rewrites. It's tackled as a supervised Seq2Seq problem and borrows techniches from machine translation. My project focused on finding solutions to the problem that were statistically signficantly better than baseline models. The baseline models I used were RNNs with Bahdanau Attention and Transformers. From there I implemented a number of techniques to augment the data set and was able to show most of the models implemented proved better results. Check out that project for a more formal discussion of my work. 

### [Tree Salviging Strategies for Budworm](https://github.com/sms1097/Carbon-Emissions-Budworm)
This is still a work in progress, but the goal here is to identify when land owners should be given vouchers to not salvage trees. Vouchers would be given to land owners if leaving the trees on the land would prevent carbon emissions compared to salviging the tree. Right now I have a salvage strategy within 0.01% of the optimal salvaging strategy using random forests. I'm working on improving the precision of the classifier and finding interpretable classifiers as well. 

### [Contributions to LaaS](https://gerrit.opnfv.org/gerrit/q/project:laas+owner:ssmith)
This is a list of my commits to the Lab as a Service (LaaS) project for OPNFV. All of this work uses Django, Python, and JavaScript. This work was from my time working at the UNH-InterOperability Lab, where our development team had a contract with the Linux Foundation to maintain the LaaS project.

### [Gym Chatbot](https://github.com/sms1097/Business-Chatbot)
This project trained a chatbot based on FAQs from a local gym to be able to interface with customers. I approached the problem as a topic identification problem and had the network classify intents from customers, then the bot responds with one of the appropriate responses available. I also identified a few ideas I have for expanding that work in the future, however the data for those ideas is not readily available and I'm still hashing out how I could collect it. To duplicate the results a docker image is available with all the pickled models that can be pulled from DockerHub, all details in the project readme. 
