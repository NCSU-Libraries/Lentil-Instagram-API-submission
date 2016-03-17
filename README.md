# Lentil Instagram API Submission Process
## General Information
Recent changes to the Instagram API have caused every new client that is created to be placed in a sandbox mode, that can only access a small number of accounts. In order for your app to have full access to the Instagram API you will need to submit the application for review. These are the steps that I took to submit a new Instagram API client for approval to be removed from the sandbox.

This repository contains three example files:

- [Lentil-API-Use-Case.md](https://github.com/NCSU-Libraries/Lentil-Instagram-API-submission/blob/master/Lentil-API-Use-Case.md)
- [example-privacy-policy.md](https://github.com/NCSU-Libraries/Lentil-Instagram-API-submission/blob/master/example-privacy-policy.md)
- [application-description.md](https://github.com/NCSU-Libraries/Lentil-Instagram-API-submission/blob/master/application-description.md)


You can modify those files to meet your needs prior to submitting your application for approval. The most important of the three files is the API Use Case file, as it outlines how the Lentil app meets the 'Valid Use Cases' as outlined by Instagram, and also addresses which API endpoints Lentil requires permissions for from Instagram. 

# Submission Process 
## 1) Create New Lentil App (optional)
*This step is necessary if you are creating a brand new app, that you have not yet registered an Instagram API client for. All new clients that are being registered are limited to 'sandbox' mode until they are approved by Instagram through the submission process. If you have a pre-existing app with an associated Instagram API client you can skip to step 2.*

  **A)** Set up new [Lentil App](https://github.com/ncsu-libraries/lentil) and publish it to Heroku (or your own dev site as long as it is publicly accessible). This allows the API reviewers to see a 'live' version of the app (e.g. http://lentil-api-test.herokuapp.com/) This part is obviously not necessary if you have an existing app that is already up an running. As part of this process you will register a new Instagram client that will be placed in 'sandbox' mode. This means that the only account the app will pull from will be your own (or the accounts of up to 10 people you invite to your sandbox).

  **B)** By default your new Instagram client has one sandbox user, and that is you. If you are using a development account that has not posted any images to Instagram, Lentil will not be able to harvest. If you need to you can invite another account (e.g. your personal account) to the sandbox for testing. When selecting a tag to harvest make sure that one or more photos have been recently posted by one or more of the accounts in the sandbox using the tag you are using for testing.

## 2) Prepare API Submission
Once you have tested your new app, or are ready to submit a pre-existing application for review, you will need to create a few things for the submission. The actual submission process is rather short, only one quick form that is accessed from the permissions tab of the client you are requesting permissions for. You reach the permissions tab by clicking on 'edit' and then 'permissions'on the client you are wishing to submit an approval request for. However, an permissions approval request requires the following items to be present before you are able to submit:

  1) **Client Description** - a short description of your application that is found on the 'Details' tab of the edit client page.

    Example Description:  
    *The purpose of the My #NCSULibrary app is to aggregate Instagram images that showcase the wonderful spaces and services provided by NCSU Libraries. We do this by encouraging our campus community, and the public at large, to add the #NCSULibrary hashtag to their photos. This allows us to centrally collect and add these photos to our University archives.*

  2) **Privacy Policy URL** - the approval process requires that you have a posted privacy policy that can be accessed by the reviewers. (e.g. http://lentil-api-test.herokuapp.com/about). This repository also includes a copy of the privacy policy that I used (example-privacy-policy.md).

  3) **API Use Case** - A detailed use case that outlines the permissions you will need, and how your application fits into one of their three valid use cases. It is important the the use case description clearly states both the exact permissions you are requesting (Lentil requires both the **basic** and **public_content** permissions in order to harvest images) as well as which of the three valid use cases your application fits into. This repository contains an example API Use Case Statement (Lentil-API-Use-Case.md) that addresses both the valid use case for the application as well as outlining the API endpoint requirements that will you will need permission to use in order for Lentil to harvest images. 

  4) **Screencast** - Each submission requires that you post a link to a screencast of the application being used. The application process does not make it clear whether or not the screencast has to be narrated or not, I chose to narrate mine. You can find my example screencast at **https://www.youtube.com/watch?v=ABDGm5DeDIw**.
