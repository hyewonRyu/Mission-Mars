

# Project Name : Finding Lutjanus johnii - NT Fisheries, Northern Territory, Australia 
## Participants : Steve Van Bodegraven, Azadeh Khojandi, Tempest van Schaik, Borys Rybak, Marieke Kortsmit, Graham Elliott, Megan Mallin, Youngwook Kim, Hyewon Ryu, Micheleen Harris, Jean-Sebastien Dupuy

__Challenge Statement__
 * __desired state__
explore footage of Golden Snapper and the Giant Clam to proactively identify techniques to build out during a development spike scheduled for June.
the ultimate goal is a human-in-the-loop pipeline for online learning with BRUV footage to determine max(n) of individual species in each fishery, and the knowledge transfer to progress the state-of-the-art we provide. As models are developed for each fishery and model zoo begins to emerge further accelerating transfer learning to further fisheris.
To aid research into sustainability individual stocks need to be quantified in individual fisheries based on the guidance of researchers.

 * __current state__
CSE have a development spike with fisheries research scientists from NT Fisheries and graduate students from Charles Darwin University scheduled for June with their baited remote underwater video footage.
From recent papers, two techniques have provided acceptable results for detecting and classifying fish in video; a deep convolution neural network and a set of robust statistical techniques. The state-of-the-art has since progressed and with minimal image pre-processing YOLOv3, Detectron and TensorFlow Object Detection API are each able to detect fish and classify incorrectly. Further initial exploratory data analysis indicates we can begin to classify fish correctly by applying transfer learning.

A data preparation development spike was completed to conduct initial exploratory data analysis and prepare compute and data for a variety of framework. The initial exploratory data analysis has been documented in Azure Notebooks, being used to knowledge transfer to NT Fisheries, and including scoring using YOLOv3, Detectron and TensorFlow Object Detection API and applying robust statistical techniques from papers.

 * __consequences__
 * __proposed solution__
we have to decide which network is good for this project. And after that, we could write a solution. 

 * __expected benefits__
For Microsoft Australia, the Northern Territory and Queensland Account Team have been successful enabling Azure for the Northern Territory Government, their first account and subscriptions, to provide the services for this engagement. Proving provenance through this engagement is leading to further opportunities to explore AI applied to primary industries in the Northern Territory.

For Commercial Software Engineering, we have the opportunity to develop a pipeline/service which provides out-of-the-box scoring of images and footage using a combination of Region Proposal Networks, base networks / models and framework, to expedite initial exploratory data analysis, drawing from domain specific model zoos. We then better equip ourselves to help develop domain specific computer vision models globally. We¡¯re also encouraging the collation of the equivalent of ImageNet for BRUV, a perspective the can be used for further domains.

__Target Deliverables(we will update it until next Tuesday)__
 * architecture
 * components
 * features/enhancements
 * collateral
   * Azure Template in GitHub to deploy CV Model Scoring pipeline with options for base models and domain specific models/zoo
 * feedback

__Key Questions/Expected Learnings__
 * What's the right Region Proposal Network
 * What's the right base network
 * What's the right base model/dataset
 * What's the right framework
 * What's the right tooling

__Leverage Plan__
 * Applied Computer Vision knowledge transfer to project team members
 * Knowledge transfer to NT Fisheries and Charles Darwin University
 * Knowledge transfer to Cloud Solution Architects for QLD, NSW, VIC, TAS, SA and WA Fisheries
 * Azure Template in GitHub to deploy CV Model Scoring pipeline with options for base models and domain specific models/zoo
 * Upkeep of the Azure Template to account for new RPNs, base networks and domain specific models
 * Conversation with fisheries globally


[Azure Notebooks](https://notebooks.azure.com/Codegraven/libraries/FindingLutjanusjohnii/html/README.md)
[VSTS](https://ntfisheriescse.visualstudio.com/Finding%20Lutjanus%20johnii/_backlogs/TaskBoard/Data%20Preparation)
