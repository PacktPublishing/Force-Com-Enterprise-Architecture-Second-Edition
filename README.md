## $5 Tech Unlocked 2021!
[Buy and download this product for only $5 on PacktPub.com](https://www.packtpub.com/)
-----
*The $5 campaign         runs from __December 15th 2020__ to __January 13th 2021.__*

# Force.com Enterprise Architecture - Second Edition
This is the code repository for [Force.com Enterprise Architecture - Second Edition](https://www.packtpub.com/application-development/forcecom-enterprise-architecture-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781786463685), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will teach you how to architect and support enduring applications for enterprise clients with Salesforce by exploring how to identify architecture needs and design solutions based on industry standard patterns. There are several ways to build solutions on Force.com, and this book will guide you through a logical path and show you the steps and considerations required to build packaged solutions from start to finish.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

### Deploying the source code

Once you have the source code downloaded for your chosen chapter, you should execute the Ant build script to deploy the code into your chosen Salesforce Developer Edition org (as described in Chapter 1, Building, Publishing, and Supporting Your Application).

Open a command line and navigate to the root folder where you downloaded the source code (this should be the folder with the build.xml le in it). To deploy the code, execute the following command, all on one line:

```
# ant deploy
  -Dsf.username=myapp@packaging.andyinthecloud.com
  -Dsf.password=mypasswordmytoken
```
Remember that the password and token are concatenated together.

Keep in mind that each chapter branch builds incrementally from the last and will overlay new les as well as changes into your chosen DE org. So, each branch may overwrite changes you make to existing les as you have been exploring that chapter. If you are concerned about this, it is best to use one of the desktop development tools listed earlier, and prior to running the previous command, download the code from the server for safe keeping. 

The code will look like the following:
```
public class ContestantService{
    public class RaceRetirement{
        public Id contestantId; 
        public String reason;
    }
}
```

In order to follow the practical examples in this book, you will need to install the Salesforce Force.com IDE, Apache Ant v1.9 or later, and Java v1.8 or later, and have access to Salesforce Developer Edition Orgs via developer.salesforce.com. 
The following is the list of software requirements for this book:
* Salesforce Developer Edition Orgs
* Java v1.8 (or later)
* Apache Ant v1.9 (or later)
* GitHub client (optional)
* Salesforce Force.com IDE
* Salesforce Developer Console (optional)

## Related Products
* [Learning Force.com Application Development](https://www.packtpub.com/application-development/learning-forcecom-application-development?utm_source=github&utm_medium=repository&utm_campaign=9781782172796)

* [Mastering Application Development with Force.com](https://www.packtpub.com/application-development/mastering-application-development-forcecom?utm_source=github&utm_medium=repository&utm_campaign=9781782172819)

* [Oracle Business Intelligence Enterprise Edition 12c - Second Edition](https://www.packtpub.com/big-data-and-business-intelligence/oracle-business-intelligence-enterprise-edition-12c-second-editio?utm_source=github&utm_medium=repository&utm_campaign=9781786464712)

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
