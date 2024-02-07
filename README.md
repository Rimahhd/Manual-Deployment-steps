GitHub
If you are a developer, then you must know about Git for source code management. Developers use GitHub when it comes to interaction with multiple team members and open source contributors for developing coding solutions.

The best thing about Git is that it allows developers to create custom workflows manually, or by integrating third party PHP deployment tools.

Cloudways allows you to deploy code of your application from your Git repositories. Your Git repository must support Git over SSH for this to work. For Git deployment, you must follow simple steps given below.

Signup & Launch Server
First of all, signup at Cloudways and launch your server and application. Next, move to the Application tab by selecting any app from application page .
Generating SSH Keys
Here, you must download SSH keys by moving to Deployment via Git tab,

We will use these keys to allow access from your Cloudways server to your git repository. Now click on the Generate SSH Keys button to generate the keys.
Now, click on Download SSH Keys to download SSH Public Key that we will use in the next step.

Upload SSH Key To GitHub Repository
On Github, navigate to the repository and find the code which you want to deploy. If you are using another Git service, you will have to find the equivalent way of deploying them. Go to Settings -> Deploy keys and click on the Add Deploy Key button to add the SSH key. You can also give a name to this key in the title field and copy the key to the box. Click on the Add Key button to save the SSH key.

Copy the SSH Address Of Repository
Copy the repository address as shown in the image below. Make sure to copy the SSH address as other formats (like HTTPS) are not supported.

Deploy Code from Your Repository
Go back to Cloudways console. Paste the SSH address you got in Step 4 into the Git Remote Address ” field.
Select the branch of your repository you want to deploy from. In this example, we are using the master ” branch.
Type the deployment path (i.e. the folder in your server where the code will be deployed). Make sure to end it with a backslash (/) . If you will leave this field empty, the code will be deployed to public_html/ .
Click on the Start Deployment button to deploy your code to the selected path.

Repository Successfully Cloned
You will get a notification once the deployment process finishes.

You have further options to delete the repository from the server (no files will be deleted, see FAQ below). Pull the latest changes or change the branch you deploy from.
