
1. In your own words, explain the difference between continuous integration, continuous delivery, and continuous deployment.
Answer: 
Continuous Integration: This refers to the syncing of a snippet of code implementation of a developer in to the main system continuously. 
Continuous Delivery: This is the stage of deploying every update to users for services after having gone through testing and automation. 
Continuous Deployment: Continuous deployment is a further automated step of continuous delivery. The change passing through the automated tests is deployed to production automatically. 

2. How does DevOps team model (e.g., site reliability engineer) differ than a a NoOps team model (e.g. Netflix team)? What differences in architecture allow for a NoOps model?
Answer: In a DevOps team model, the deployment team is responsible for the operation. However, in NoOps model the managemnt of infrastrctre is reduced or completely eliminated. Instead, developers are able to deploy and scale their application without time spent intalling and configuring servers, databases, and other resources. The architectural difference in NoOps model can be achieved through Platform-as-a-service architecture. The developers choose from the technologies available by the PaaS and then enable their application to be automatically configure upon deployment. The instances deployed can be manually or automatically scaled depending on the future traffic. 


3. Explain the principle of Every Feature is an Expertiment
Answer: In continuous deployment, developers need to deploy a feature continuously. It may ore may not work every time. Some features may be eliminated due to incompatibility. Since the features aren't full proof, it is more of an expiremnt. Only then it goes through test and automation. The feautre is tested with records being taken along with data analytics for it to be released.

4. Explain the principle of Be Fast to Deploy, Slow(er) to Release.
Answer: Deployment phase should be faster because new features should always be added. It can be tested and evaluated over time. The results from the test can be kept in recored by the developer and hidden from users. When successful and stabilized, it can be released to the users for use. More time should be invested in deployment so that any glitch is not faced by the user. 


