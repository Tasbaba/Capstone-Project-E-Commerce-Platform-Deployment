## Capstone Project: E-Commerce Platform Deployment with Git, Linux, and AWS

### Project Introduction
I am assigned to develop an e-commerce website for a new online marketplace, and the should be "MarketPeak". The platform should feature product listings, a shopping cart, and user authentication. I am to utilize git for my version control, develop the platform in a linux environment, and then, deploy it onAWS EC2 instance.

### 1. Implement Version Control with Git
#### 1.1 Initialize Git Repository
I started the project by creating a directory and named it "MarketPeak_Ecommerce", and I initialize a Git repository inside the directory to help manage the version control via the use of Git.

I lunch the git, and navigate to the directory where I intend to create the project directory, and I used the "mkdir" command to create the directory inside the directory, as shown below.

    - `mkdir MarketPeak_Ecommerce`

I have to use the change directory "cd" command to enter the directory and also use the "git init" command to initialize the Git repository to manage my version control as show below.

    - `cd MarketPeak_Ecommerce`

    - `git init`

### Print Screen of MarketPeak_Ecommerce directory created, and Git initialization

![mkdir, git init](./images/create_marketpeak_Ecommerce.jpg)

#### 1.2 Obtaining and Preparing the E-Commerce Website Template
In this project I will be using a pre-existing e-commerce website template downloaded from specific template instead of developing an E-commerce website from the scrach to allow me focus on the deployment and operational aspects.

- I downloaded the E-commerce template and extracted the template into the MarketPeak_Ecommerce directory via the use of the command below,

- `cp Desktop/Desktop/2129_crispy_kitchen Desktop/Desktop/AYUBA/Darey.IO-Training/git-project/MarketPeak_Ecommerce/`

#### Print Sceen of the Copied Ecommerce template into the MarketPeak_Ecommerce Directory
![copy_ecommerce](./images/copying_the_ecomerce_templtate_into_the_MarketPeak_Ecommerce.jpg)

NOTE: Since I do not have strong development skills, I have concluded to use the Ecommerce template the same way I downloaded it.

#### 1.3 Stage and Commit the Template to Git

i.  I added the website files to the Git repository using the "git aad ." command to stage the files as shown below.
    
    - `git add .`

ii. I setup the Git global configuration with my username and email using the global commands as shown below,

##### Git config --global usr.name "YourUsername" 

I used the (Git config --global user.name "YourUsername") command to set my Git username as shown below.

    - `git config --global user.name "tasbaba"

I then used the (Git config --global user.email "YourEmail") command to set my emaill address associated with my Git commit globally as shown below.

    - `git config --global user.email "tasayuba@yahoo.com"`

#### git commit -m

In other to commit my created files, I use the "git commit -m" command to commit the files to my git repository with a message describing the changes made as shown below.

    - `git commit -m "Initial commit with basic e-commerce site structure"`

#### Print screen showing the used commands i.e git add ., git config --global, and git commit -m

![stage&commit](./images/stage&commit.jpg)

#### 1.4 Push the code to Github Repository

After I have initialized my git repository and I have added and commited the e-commerce website template. the next step will be for me to push my file and codes to the remote repository on my Github as this step is important for the version control and collaboration.

- In other to push the files and code to my remote github respository, I will have to do the following.

#### Create a remote Repository in Github

    i.  I will log into my GitHub account and create a new repository, and name it "MarketPeak_Ecommerce" and the repository should be left empty without a README, gitignone, or licence.

    - See print screen below for the new MarketPeak_Ecommerce created repository

- Click on the + to create new repository

    ![create_rep](./images/github1.jpg)

- Give the new repository a name, and click on the create repository green button as show below.

    ![creating_github](./images/github2.jpg)

#### Link my Local Repository to Github

From my terminal, in my project directory, I will add the remote repository URL of my created repository to my local repository configuration via the use of the below command.

` git remote add origin https://github.com/Tasbaba/MarketPeak_Ecommerce.git`

- Print Screen hit remote add origin

![gitremote](./images/gitremte.jpg)

#### Push my Code and Files

In other to push the my local repository content to my Github repository, I will have to use the below "git push -u" command.

    `git push -u origin master`

- Print screen for git push command

![gitpush](./images/gitpush.jpg)


















