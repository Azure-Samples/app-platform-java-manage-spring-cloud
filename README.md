---
page_type: sample
languages:
- java
products:
- azure
extensions:
  services: Appplatform
  platforms: java
---

# Getting Started with Appplatform - Manage Spring Cloud - in Java #


  Azure App Platform sample for managing Spring Cloud.
   - Create a Spring Cloud Service
   - Create 3 app: gateway, auth-service, account-service from sample
   - Open public endpoint for gateway
   - Create a custom domain
   - Add a CNAME to the gateway fully qualified domain name
   - Order a certificate
   - Save the certificate to a key vault
   - Assign certificate to spring cloud
   - Assign custom domain to gateway endpoint
 

## Running this Sample ##

To run this sample:

See [DefaultAzureCredential](https://github.com/Azure/azure-sdk-for-java/tree/main/sdk/identity/azure-identity#defaultazurecredential) and prepare the authentication works best for you. For more details on authentication, please refer to [AUTH.md](https://github.com/Azure/azure-sdk-for-java/blob/main/sdk/resourcemanager/docs/AUTH.md).

    git clone https://github.com/Azure-Samples/app-platform-java-manage-spring-cloud.git

    cd app-platform-java-manage-spring-cloud

    mvn clean compile exec:java

## More information ##

For general documentation as well as quickstarts on how to use Azure Management Libraries for Java, please see [here](https://aka.ms/azsdk/java/mgmt).

Start to develop applications with Java on Azure [here](http://azure.com/java).

If you don't have a Microsoft Azure subscription you can get a FREE trial account [here](http://go.microsoft.com/fwlink/?LinkId=330212).

---

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.