Friend Finder - Node and Express Servers

Overview
In this activity, you'll build a compatibility-based "FriendFinder" application -- basically a dating app. This full-stack site will take in results from your users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.

<img width="1215" alt="Screen Shot 2020-01-11 at 1 12 55 PM" src="https://user-images.githubusercontent.com/42060484/72210794-a9a1e980-3475-11ea-8e0d-3220d89559ad.png">

**Description**

Your survey should have 10 questions of your choosing. Each answer should be on a scale of 1 to 5 based on how much the user agrees or disagrees with a question.

<img width="1269" alt="Screen Shot 2020-01-11 at 1 27 01 PM" src="https://user-images.githubusercontent.com/42060484/72210835-161ce880-3476-11ea-9c68-bc7ab95e06b3.png">


The matching is done by computing the difference between each survey response and accumulating these differences. Which ever member on the database has the smallest difference will be presented as the closest match.

<img width="601" alt="Screen Shot 2020-01-11 at 1 17 05 PM" src="https://user-images.githubusercontent.com/42060484/72210795-aa3a8000-3475-11ea-83d4-93de112d1ed5.png">



node.js Dependencies:

express
body-parser
path


Backend modules:

server.js - starts server
apiRoutes.js - specifies routes for API services
htmlRoutes.js - specifies routes for HTML services