# GenesisEsports <img height="25px" src="img/logo.PNG">
<p align="center">
  <img width="60%" src="img/logo.PNG">
</p>
<h1>Overview </h1>
<h3>Description</h3>
Competitive Esports is a form of sports competition that includes videogames. It involves professional players from all around the globe that compete against one another for trophies and prize pools. This creates a problem with non-professional players who love the competition but are not skillful enough to play at a professional level. This problem has gotten a lot of attention recently due to Esports growing rapidly and the amount of casual players growing with it as well, all of these casual players don’t have a setting to play in and the Esports Tournament Website is an example of a solution to this growing problem. 

The Esports Tournament Website, is an online web application that will help users online connect with friends, make teams, and compete in a high-level setting. The user will be able to create their own profile and either make a team or join one.  On the admin side of the webpage, admins will be able to create leagues for these players so the teams can join and compete to win prizes and gain popularity among the ranks.
<h3>Technologies Used</h3>
<p align="center">
  <img width="60%" src="img/tech.PNG">
</p>
<h3>Click below for more information about technologies used!</h3>
<details>
  <summary>Click to Expand</summary>
  <b>React JS</b>
  <blockquote>
    React will let developers make large scale web applications that can render data, without the need to manually reload the   page. This is an event driven architecture which is different from MVC and will let the data display dependent on the event that is fired on the page. React is simple, fast and scalable and allows the use of reusable UI components.
  </blockquote>
  <b>Spring Boot</b>
  <blockquote>
    Spring is one of the most popular Java-Based frameworks to build enterprise applications, different from other frameworks that focus on only a single area of development Spring Framework will allow a user a veriety of features such as: REST, XML/Annotation/Java based configuration, bean injetion and many more. I used Spring Boot to build my REST service which was simple and clear to use. 
  </blockquote>
  <b>AWS Amplify</b>
  <blockquote>
    AWS Amplify is designed to be a package of tools and services that will make it easy for a developer to deply their application. It includes code libraries, ready-to-use components and a built in CLI. The friendly UI and self explanitory CLI makes it a friendly tool for developers to use this AWS Service. Some of the features that I liked about this cloud were the Data Storage, Analytics, Notifications, Authentication and last but not least the cost is fair and amazing for developers to deploy their personal projects.
  </blockquote>
  <b>Heroku</b>
  <blockquote>
    Heroku is a Platform as a Service (PaaS), a cloud that handles the deployment, managment and scalibility of most moderin apps. The platform is easy to use and offers the simplest deployment UI, but it also has its own CLI as well. It is fully managed on its own givint the developers the freedome to work on their own application.
  </blockquote>
  <b>Node.JS</b>
  <blockquote>
    Node.JS was a technology that was used primarily for the node package manager, which was used in the react application. This event driven architecture fit in perfectly with the application that was developed and was able to assist for a simple and good design.
  </blockquote>
  <b>Visual Studio Code</b>
  <blockquote>
    Visual Studio Code is a easy to use and intuitive code editor that is wildly popular among developers. In this application it was used in order to develop the React application. It provided alot of extensions that were helpful throughout development.
  </blockquote>
  <b>MongoDB</b>
  <blockquote>
    Unlike other database technologies, MongoDb is a document based database that is built on the scale-out architecture. It provides horizontal scalibility which will allow high volume of data and trafic. This application with the event driven architecture has alot of calls that are made to the database, and this NoSQL database was proven to be efficient and most useful.
  </blockquote>
  <b>GitHub</b>
  <blockquote>
    GitHub is an open source code reopsitory that uses the git technology for revision controls and runs in command line interface. It is the most popular source control software in the world and that is due to the simplicity and professinal look that the website has. It is simple to use both as a developer and as a user who is just viewing code. GitHub was used in order to simply store the applications code online and connect the clouds to the repository in order to deploy.
  </blockquote>
 </details>
 <h1>High-level Functional and Non-functional Requirements</h1>
  <h3>High-Level Requirements</h3>
  The GenesisEsports application supports alot of high-level functional requirments throughout the application. The Website is build with a Spring Boot application as a REST Service with full CRUD functionality for User, Teams, Leagues and Matches. Once a User is logged in they have the ability to Login or Register, once in the application the user then will have the choice to join a team or create a team and depending where they are in the application they will be prompted that some settings are limited so they will be asked to join a team. On the admin side the admin can create a league and will allow the team leaders to join a league. Once a league has teams in it the admin will be able to lock it, enabeling the application to create matches based on how many teams there are in the league.
  <h3>Non-functional Requirements</h3>
  The GenesisEsports application has simple Non-Functional reqirements such as page responsiness and availibility. The client side react application has pages built with MaterialUI therefore making the pages responsive. The application is deployed on Heroku and AWS Amplify, making it availible to the client at all times and easily recoverable.
<h1>GenesisEsport on the Cloud</h1>
<h3>AWS Amplify</h3>
GenesisEsports client side application is hosted on the AWS Service, Amplify. This cloud was easy to use and had a simple deployment UI. This allowed me to focus more on the development of the appliction, the cloud service did not cause any issues and supports fault tolerance in case the application breaks within the code. 
<h3>Heroku</h3>
Heroku was used for a heavy application which was built with Spring Boot, the business side of the application was used as a REST Service and Heroku supports this functionality. 
<h1>Technologies Learned</h1>
<h3>React and Node.JS</h3>
In my experience the most tough and stressful language to learn has been react. The event driven architecture that is used in this language was coutnerintuitive to my usual MVC Architecture Design mindset. Though tough and stressful, I chose this technology to learn because it is one of the most popular languages in the industry, and now that I have built a full stack application by using it, I can understand why people like it. The limiltess functionality that it provides is very powerful and while structured properly can be lightweight and efficient. 
<h3>MongoDB</h3>
MongoDB was the easiest database system that I have learned. I chose it because it was considered a lightweight database with performance on scalibility and high volume data trafficking. 
<h3>Spring Boot</h3>
This technology was not new to me, I have had experience with spring and wanted to use the more popular version of it since it is one my my preferred frameworks for website development.
<h1>General Technical Approach</h1>
The Genesis Esports application consists of the React App, Spring App and the MongoDB Database which is stored in Atlas MongoDB Cloud.The React application will be deployed on AWS Amplify and the Spring Boot application is stored in Heroku Cloud both will be in separate clouds and will communicate with each other through a REST API by using Axios commands. React will be considered the front end, it will display and render pages to create a flow for the website and all the data handling will happen in the Spring App. The Spring App is considered the business layer, which will contain all the services for the application and will communicate with the database to complete the requests sent by the front end. Lastly, MongoDB will store all the data, making it the database of the application and it will be on the cloud as well, MongoDB will allow the developers to access its unique repository operations so that no SQL commands need to be programmed. 
<h1>Key Technical Design Decisions</h1>
The technologies used for this project have changed throughout the planning phase and some of the design decisions for compatibility reasons, but currently what has been chosen is final. For the front end React JS will be used to implement the front end of the application, this front end JavaScript language will provide a clean and approachable design for the application as well as the powerful capabilities that it has makes it easier to implement with frameworks such as spring. React will be combined with Material UI to make the front end responsive as well as to have a cleaner design. In the backend for the business service, Spring Framework is going to be used, it is a relatively new framework still and it was mostly chosen due to experience with it as well as it being compatible with React and MongoDB, which were high priority technologies that were planned to implement. For the Data Layer, MongoDB is the database that is going to be used and the reason for using it is due to the NoSQL implementation that it has, as a developer wanting to learn technologies like this is important to keep up with the industry as well as it has the repository operations which will make it more efficient to use. 

To deploy the application, Heroku supports these Spring Boot and was chosen due to experience as well as it has easy to implement configurations regarding the MongoDB Database, AWS Amplify supports React very well for deployment. The database will be hosted on its unique cloud (DBaaS), which is Atlas MongoDB and will be accessed through a tool that is called MongoDB Compass. 

