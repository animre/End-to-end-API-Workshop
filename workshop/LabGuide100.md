Lab 100 - Designing the serviceTickets API with Apiary
================
## Introduction

It's often hard to see how an API will be used until you have the chance to code against it. That's why we are using Apirary in this workshop which allow you to design and modify your API in a real time manner. You can learn more information of Apirary and sign up for a free developer account at http://apiary.io.

## Objectives
- Create an Apiary account and login
- Create the API Design

Get Started with Apiary and create an API Design
=======================

### **Step 1**: Create an Apiary account and login

1. To design our API using Apiary we will first need to create an account. Navigate to [Apiary](http://apiary.io), in the top right of the page select "Sign Up". Follow the steps to create your account.

  **NOTE:** If you already have an apiary account, you may advance to the next task.

  ![](images/100/apiaryCreate.png)

2. Once your account is created, you may login and proceed to the Step 2.
  ![](images/100/apiaryLogin.png)


### **Step 2**: Create the API Design

  ![](images/100/image001.png)

  1. Create a personal (not team) API called serviceTickets in the API Blueprint format. Private API is not checked when you select Personal API. It only shows if you select Team API

  ![](images/100/image003.png)

  2. Your API will be pre-populated from a sample template which you can begin modifying to meet the requirements of a serviceTicket

    -   Update the collection from "questions" to "serviceTickets"
    -   Update the description to a meaningful explanation of service tickets
    -   Update the name of the GET method from “List All Questions” to “List All Tickets”

    > You will see that on the left side, you have the API Blueprint and on
    > the right side, you have an easy to read documentation of your API.
    > You can try changing some things like the values in your JSON payload
    > or the descriptions around the text and you will notice the
    > documentation will update live as you work.

  ![](images/100/image005.png)

  
  4. After you saved the changes from the top right corner, you can test the API blueprint by selecting one of the resources in your documentation. 

  ![](images/100/image009.jpg)

  5. Clicking on the resource, will bring up the test example. Here, make sure you have selected the **Mock Server** and you can choose any language for an example **Raw**. Notice the example includes the URL and method. Additionally, there is a code-sample of how you would call the service in the language of your choice. 

  ![](images/100/image011.png)

  6. Once you click on the **Try** button, a section for the required parameters will appear.

  ![](images/100/image013.png)

  7. Click on Call Resource and scroll down to see Sample Response

  ![](images/100/image015.png)

  8. You can switch back to the example to see other languages.

  ![](images/100/image017.png)

  9. Call the Mock Service URL with your REST client

  ![](images/100/image019.png)


Summary
=======================

Now, with your design in place, your application developer could begin working on the front-end, while your service developer's work on the back-end implementation and you can work on the API implementation, all in parallel.
