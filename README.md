#Managing Azure AD identities

In this task your Prerequisites should be: Azure Portal, Azure AD Premium license P2

Task 1: create and configure Azure AD users 

Task 2: create ad groups, assign dynamic membership

Task 3: manage azure ad guest users


Task 1: create and configure Azure AD users

        -Sign in to Azure portal
       - Search for Azure Active Directory 
       - Below manage section - click on user settings- Add user
       - Create new user **setup password** **usage location** **job title **department**
       - click on the created user
       - click on assign roles-choose user admin for the created user
       - Once account is created- click on reset password in the user portal
       - in a private tab - open portal.azure.com with **new user** 
       - copy temp password from the global admin portal- copy and paste temp password - then change password
       - Create another user and repeat steps/ for practice

Task 2: Create Azure AD groups with assigned and dynamic membership

      - In Active directory-overview tab- select licenses
      - In manage section - click on all products
      - click on try/buy to active AAD Premium license 2
      - Refresh browser and choose AAD Premium p2 and you will have created users
      - In active directory- select **create new group**
      - security group name=**IT Admin** Group Description **Contoso cloud admin**
      - membership type **dynamic user** **add dynamic query**
      - On the Configure Rules tab of the Dynamic membership rules blade, create a new rule with the following settings:

        Setting <**Value**>
        Property <**jobTitle**>
        Operator <**Equals**>
        Value	<**job designation**>

      - Repeat above steps for 2nd user
      - Repeat above steps but this time create members with rule (assigned group) instead of dynamic membership rule
      - check if the users are under the respective dynamic group

Task 3: 

Create a new user with the following settings (leave others with their defaults):

Setting	<Value>
User name	<**John raymonds**>
Name	<**John Raymonds**>
Let me create the password	<**enabled**>
Initial password	<**Provide a secure password**>
Job title	<**System Administrator**>
Department	<**IT**>

Coming back to *Users-All users** blade, click the newly created user 

Click on **Invite external users**

On the **new user account profile, click on groups

Click on **add membership and add guest user account


Task 4:

***Please do not forget to clear up your resources to save cost of unused enviornment***
