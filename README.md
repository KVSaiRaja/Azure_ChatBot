# Chatbot Support for Website Using Azure AI services 
*azure-chatbot*
| &nbsp; | &nbsp; |
| --- | ----------- |
| **Objective** | - To create a functioning **chatbot** using **Azure Bot Service** and **Language Service** <br>- To build and deploy web app to Azure from a code repository using **Static Web Apps** Service |
| **Approach** | - Completed all the steps involved in chatbot development i.e., train, build, test, deploy, monitor on Azure platform <br>- Followed the walkthrough for frontend development to create a website using **JavaScript, HTML, CSS** |
| **Impact** | - Successfully trained the chatbot by user defined intents and test the chatbot on Azure Congnitive Service platform</br>- Developed the website and connected it with remote data using **Azure Bot Service** of Microsoft Azure |

**Project Title:**  Chatter - Chatbot for Aditya University

**Industry Name:** Azure

**Problem Statement/Opportunity:** Aditya University desires to construct a clever and skillfully designed internet site because the on-line enquiring and service portal has been developing at an super convenient in state-of-the-art world. To construct an entire internet site they've selected Azure Cloud Platform. Build a internet site which have terrific functions like banner textual content slider, desirable hover effects, easy scrolling navigation, gallery mild container effect, and plenty extra to serve their customers. It must also include an AI chatbos to not only automate customer support, but they also help optimise improve experiences of the visitor of the website and improve customer care.

**Project Description:** We created a University website using HTML, CSS, bootstrap framework, and JavaScript to have a more interactive experience with our university. The website can be used to answer basic student query questions, provide course information, or direct students to the right place on the website. This internet site is a 100% responsive cross-browser template, well matched on all devices, and displayed on all display sizes. We used Microsoft Azure with Github to install the University site and completed this project. This project is to create a website that provides high-quality information on a variety of topics. The GLA University website will feature a wide range of categories and topics, as well as a search engine to allow users to find specific topics. The website will be designed to be user-friendly, with a modern and easy-to-navigate interface. Additionally, the website will incorporate social media sharing capabilities, allowing users to share the content they find on the website. The website will also feature an interactive forum, where users can exchange ideas and ask questions. The website will be regularly updated with new content, and users will be able to receive notifications when new content is added. Chatter - the chatbot will automate repeated customer support enquiries. Chatter provides 24/7 real-time support for all visitors, regardless of language barrier and geographic location. It gives visitors of the website an accessible channel to find answers to their questions.

**Primary Azure Technology:** Azure Bot Service, Language Service, Static Web Apps

---

## Steps to deploy chatbot using Azure bot service and Language Service:

**Step 1:** Go to azure portal login page and looks like this **Home page of the Azure portal** then click on **Create Resource**
![Screenshot (98)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/ec8a710d-ca2e-4f57-a17c-5f8fd511b631)
**Step 2:** Here click on **Ai + Machine Learning** and then create the **Language Resource** for language support 
![Screenshot (99)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/a5bcb53e-cd68-4e9b-8628-0b179ba16c71)
**Step 3:** The page looks like this here we are using the Azure AI search click on **Custom Question Answering** for basic QnA service
![Screenshot (100)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/b8124065-f330-48ca-bc96-a7d19d4b3058)

**Step 4:** In this page fill the basic details like resource name, proper region, proper unique name for language, the pricing tier and finally click on **Review + Create**
![Screenshot (7)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/91a9f834-9dbc-407f-919e-e67b0ed6e906)
![Screenshot (8)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/71e3d2ae-56e3-40b8-97ce-07fb72cb89dc)

**Step 5:** After creating language resource the page looks like this then click on Language type resource (**Chat-botpro**)
![Screenshot (9)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/f66e9e02-ddf5-4359-a0a7-bcf0c0e70051)
**Step 6:** After opening the Chat-botpro overview in the down side click on **Language Studio** it will redirect to the language studio web service provided by azure platform
![Screenshot (11)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/003c34b0-79a7-41ff-ba92-8434bff03ad1)

**Step 7:** Here we have to login with our **Azure account** and then select the language resource for creating the project
![Screenshot (12)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/2b2c6b6a-a727-465d-bd83-cad56ee1f6d4)
**Step 8:** Click on **Create new** and again click on **Custom Question Answering** then select **I want to select the language when I create a project in this resource** after that select the language for the project
![Screenshot (13)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/c78531b4-be70-4628-8748-27c67494053a)
![Screenshot (14)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/a45777ec-716d-4939-814f-32f813fbc213)
![Screenshot (15)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/31a45f27-fc6d-42b4-8462-701a7ee476cf)
**Step 9:** Here create a unque name for the project and write the answer for wrong data as **No answer found,Contact the administrator** as for your understanding purpose and after that click on **Add source** to add data like URL's, Files and Chitchat
![Screenshot (16)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/1a7b78bb-799b-4ce5-ba1c-4263aaa70ed6)
![Screenshot (17)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/cdd18bb3-7875-4c0b-b2c8-effe73ac05be)
The data looks like this 
![Screenshot (101)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/9373f2ec-b6bf-4e27-927b-cb67219bc699)
**Step 10:** Click **Deploy** and then click **Create Bot**. Further, you can create the bot using azure bot service
![Screenshot (18)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/aad835b4-6655-48e0-bfb1-0fbf2cf514a1)

**Step 11:** After that the page looks like this the fill the all required details like unique name and pricing tier and click **Next**
![Screenshot (19)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/0e73c7d9-eb7c-41a7-9b3c-90450131b24b)
**Step 12:** In this page we have to enter the **Keys and endpoint** from Language resource in **Azure Bot service** and click **Next**
![Screenshot (10)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/93702939-5ba8-42ca-b9ef-7210f4c78d15)
![Screenshot (20)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/4420974e-fd9d-4684-90f8-3450afa365f8)
**Step 13:** Click **Create** to create the bot service after that click on **Go to resource**
![Screenshot (21)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/dc758cc6-f0b4-4b67-83ae-e6a3047ac8a7)
![Screenshot (22)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/3cf16854-2421-48ae-9d4f-e8dfecad2733)

**Step 13:** After that the page looks like this then click on **Azure Bot** type name as **Chat-botpro-bot** to open the bot overview page
![Screenshot (23)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/5a549225-2b6a-4e00-99b5-911c4e762cbd)

**Step 14:** After that the page looks like this the overview of **Azure Bot service**
![Screenshot (24)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/0610e0e5-d5f4-42c0-a074-851185761187)

**Step 15:** Here we can see the **Channels** like Web Chat, Microsoft Teams, Telegram, skype, etc.
![gfhg](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/3c04638f-43ef-438d-92b0-324083610bd2)

**Step 13:** Click **Test in Web Chat** to test the chatbot
![Screenshot (25)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/f7a1cf37-c005-499b-b405-9762b5384a97)

**Step 14:** Click on **Web chat** there we can see the **Secret keys and embedded code** where these are used in the website development
![Screenshot (26)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/56fd9279-5c58-4a83-a2e9-4107d511ef16)

**Step 15:** Click on **Static Web Apps** to create the website url for our chatbot
![Screenshot (104)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/2cfde885-fcc1-407f-b83e-106f6c459ebd)
**Step 16:** Here we have to link our Git hub account to Azure Static Web App services to use the website codes
![Screenshot (27)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/74a2d562-3b5a-4c52-b357-78622659b3be)
![Screenshot (28)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/fb3cd1b4-7ce5-46a0-a71b-bada7326cb41)

**Step 17:** Here fill all required details and select **GitHub** as the deployment source and then select the account
![Screenshot (29)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/4ad64d3a-5603-4d11-a874-9e700dd028f6)


**Step 18:** Here we have to select the organization name, repository name and branch name where we are uploaded our chatbot website code and then click **Review + create**
![Screenshot (30)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/718f10c7-5978-4f3f-b6f7-6078693733bb)

**Step 19:** Click **create** and check details of our github account repository and then click **Go to resource**
![Screenshot (31)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/a0be853f-5e08-44bf-8e09-761a791a3d10)
![Screenshot (32)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/fe184b96-5527-4481-9929-6833616117d6)

**Step 20:** After that finally we can see the website **URL** and **Status** to open our working deployed website. Copy the URL. This URL is the URL of our website that is hosted using Azure Static Web Apps sevice
![Screenshot (33)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/a2a65e36-9eb9-48e3-90ee-85f623f5bdba)

**Step 21:** In github repository, click on **Action**. GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.
![Screenshot (103)](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/49be7ecc-f0b7-4336-aa05-c038f07d19b5)

**Step 22:** And finally here is the output of our project 
![https](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/452c29f2-0e6c-4e0e-a971-16ae7bb567fd)
![Untitled design](https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/bba898cd-610f-48cb-9b6a-70f24ec903a5)


### Demo Video of Project


https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/f091aa59-1244-46cc-9af2-7be4c96c5b39

https://github.com/KVSaiRaja/Azure_ChatBot/assets/84494920/6dbe3aab-7cb5-4dd3-bc88-3e825248523b


