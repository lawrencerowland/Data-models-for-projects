# Data models for projects




# Requirements

1. Data model

- managing multiple client instances (IT4IT does this very well for IT portfolios, so you can scale to 1000’s of projects. e.g. see [P13](https://architecture-center.com/images/IT4IT%20Framework%20Overview.pdf). [Full text](https://www.opengroup.org/IT4IT/download)

- most Data models will work well applied in a classic relationship database model solution (Project Online +Azure etc) but others will go the knowledge-graph route. This more readily enables theautomation of workflows and the provision of cognitive services (e.g.robo-advisers). [this](https://www.yworks.com/yed-live/?file=https://gist.githubusercontent.com/lawrencerowland/e2687f8fe5ff09186c721ecd325df026/raw/2019_08_P3_example-LR) is a simple example. To open and close the rectangles, click on it’s plus sign. You can then get a tidy view by clicking on the layout button (top left) and hitting Apply without changing the pre-set options.

- make the most of the APQC model which links project tasks to KPIs [here](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=3&cad=rja&uact=8&ved=2ahUKEwirzu2yqv3jAhWLa8AKHU-pBb4QFjACegQIABAC&url=https%3A%2F%2Fwww.apqc.org%2Fsites%2Fdefault%2Ffiles%2Fosb%2F292%2520-%2520Information%2520Technology%252020181212.xlsx&usg=AOvVaw16vjoewXYRlDR8dhYF1ShU)
2. Usability and visualisation- for maintaining a single data set edited by all users, exploit the progress made by other fields on the identical problem, notably enterprise architecture and system engineering (e.g. EAS Ltd and Archimate for EA. MBSE and digital twin approaches (e.g.Capella) for Systems)- Allowing stakeholders to see only those elements that they already understand and use.You as portfolio manager can see them all and keep them stitched together. See the portfolio data model repo for two perspectives for two executives with different views (Pam has one view of how strategy and operations are delivered by the programmes and Phyllis has another and only you need to see the big picture. Many more options here).
3. Machine Learning- Getting out a common list of features per portfolio and per project, as you are doing, will enable datasets to start developing ASAP. This will allow unsupervised machine learningafter a few months, clustering and identifying patterns within and across organisations.
- Additionally, identifying whether a project or a portfolio objective has been successful or not will allow supervised machine learning in future, where you can identify commonfeatures of successful projects. This can be with numeric data or via natural language processing.- Link with initiatives such as [EngineB](www.EngineB.com) to scale sharing of secure portfolio data across companies.
4. Flexibility, configuration management and updating learning within the core data model
- Apply only those elements of the model needed at a particular company by using a branch and forking approach e.g.GitHub.You can adopt successful forks into the core model.- Of course, many companies will want to allow a deliberate strategy approach to co-evolve with an emergent strategy approach, where the projects and operations influence the strategy as much as the other direction (Mintzberg all the way back in 1985 has some great pictures to be able to imagine these different approaches [here](http://my2.ewb.ca/site_media/static/library/files/1177/of-strategies-deliberate-and-emergent.pdf). There are then all the subsequent agile variants. Kopmann et al, 2017 confirm using 182 firm portfolios that deliberate+emergent is best)
 
