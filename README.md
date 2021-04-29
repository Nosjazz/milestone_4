<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Welcome Nosjazz,

[View the live project here.](https://nosjazz.herokuapp.com/)

This website has been created in order to complete the 4th milestone project of the code institute fullstack diploma. This is a blog with a landing page centralizing the features, most recent and a newsletter subscription. A specific blog page giving all articles posted with comments, , a contact us page accessible only when logged in, a login/logout function and a donate function. When logged in as admin, the user can create or edit posts.  HTML, CSS, JS, Python, Django and Jquery were used. Other functionalities such as AllAuth and Crispy form were also used.


## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the project.
        2. As a First Time Visitor, I want to see the most important and recent posts.
        3. As a First Time Visitor, I want to be able to create a user. 
        4. As a First Time Visitor, I want to be able to see comments from other visitors.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find back the information I entered
        2. As a Returning Visitor, I want to be able to support the blog owner.
        3. As a Returning Visitor, I want to be able to contact the blog owner.

-   ### Design
    The Design is taken as a template from [Boostrapious](https://bootstrapious.com/p/bootstrap-carousel) for the following reasons.

    -   #### Colour Scheme
        -   The main colours used are white and turquoise to have a high contrast.
    -   #### Typography
        -   The "Open Sans" font is the main font used throughout the whole website with Sans Serif as the fallback font in case for any reason the font isn't being imported into the site correctly. Open Sans is a simple font that is appealing for this purpose.
        
    -   #### Imagery
        -   The images used were kept minimum to convey a simmple design, keeping one for the banner, one per blog post, as well as one image to present to blog owner in the donation page.

*   ### Wireframes

    -   No wireframes were used as the frontend was taken from a already existing template.

## Features

-   Responsive on all device sizes
<h2 align="center"><img src="/readme_pictures/home_responsive_desktop.PNG">Desktop - home</h2>
<h2 align="center"><img src="/readme_pictures/blog_responsive_desktop.PNG">Desktop - blog</h2>

<h2 align="center"><img src="/readme_pictures/home_responsive_phone.PNG">Mobile - home</h2>
<h2 align="center"><img src="/readme_pictures/blog_responsive_phone.PNG">Mobile - blog</h2>

-   Profile Creation
<h2 align="center"><img src="/readme_pictures/signup.PNG">Sign up</h2>
<h2 align="center"><img src="/readme_pictures/login.PNG">Log in</h2>

-   Nav bar update if logged off, logged in as user or logged in as superuser
<h2 align="center"><img src="/readme_pictures/navbar_no.PNG">Logged off</h2>
<h2 align="center"><img src="/readme_pictures/navbar_normal.PNG">User</h2>
<h2 align="center"><img src="/readme_pictures/navbar_super.PNG">Super user</h2>

-   Create/update articles when logged in as superuser
<h2 align="center"><img src="/readme_pictures/create_article.PNG">Create article - main view</h2>
<h2 align="center"><img src="/readme_pictures/update_delete_article_super.PNG">Update article - blog view</h2>
<h2 align="center"><img src="/readme_pictures/update_article_super.PNG">Update article - main from blog view</h2>

-   Contact us page
<h2 align="center"><img src="/readme_pictures/contactUs.PNG"> Contact us</h2>

-   Donate page
<h2 align="center"><img src="/readme_pictures/donate.PNG"> Donate </h2>

-   Main Search function
<h2 align="center"><img src="/readme_pictures/main_search.PNG"> Main search </h2>

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
-   [JAVASCRIPT](https://en.wikipedia.org/wiki/JavaScript)
-   [Python](https://www.python.org/downloads/)

### Frameworks, Libraries & Programs Used

1. [Bootstrap](https://getbootstrap.com/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Hover.css:](https://ianlunn.github.io/Hover/)
    - Hover.css was used on the Font Awesome icons to add the color and rotation transition while being hovered over.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Poppins' font into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Jquery](https://jquery.com/)
    - Jquery was used to enable interactive development used within Materialize framework.
1. [Django](https://www.djangoproject.com/)
    - Django was used to create templates, recuding the amount of code written in each page.
1. [postgresql](https://www.postgresql.org/)
    - postgresql was used to gather input from users, profile and reviews.
1. [Heroku](https://www.heroku.com/)
    - Heroky was used to enable to live deployment of the project, taking into accounts the dependencies required. 
1. [AWS S3](https://aws.amazon.com/s3/)
    - AWS S3 was used to store static files.
1. [Allauth](https://django-allauth.readthedocs.io/en/latest/)
    - Integrated set of Django applications addressing authentication, registration, account management as well as 3rd party (social) account authentication.
1. [Crispy Forms](https://django-crispy-forms.readthedocs.io/en/latest/)
    - Django-crispy-forms provides you with a |crispy filter and {% crispy %} tag that will let you control the rendering behavior of your Django forms in a very elegant and DRY way. Have full control without writing custom form templates. All this without breaking the standard way of doing things in Django, so it plays nice with any other form application.  

## Testing

### Validators 

The CSS, JavaScript and Python Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) - No error
-   [JShint validator](https://jshint.com/) - No error
-   [PEP8 python validator](http://pep8online.com/checkresult) - No error

### Testing User Stories from User Experience (UX) Section

#### First Time Visitor Goals
1. As a First Time Visitor, I want to easily understand the main purpose of the project.
    Upon entering the website, the visitor have a short about the blog section, explaining the purpose and reason for the blog. Few featured articles and most recent ones follow.

2. As a First Time Visitor, I want to see the most important and recent posts.
    In the homepage, the visitor can see features articles deemed the most important/trendy by the author as well as a section below for the most recent.

3. As a First Time Visitor, I want to be able to create a user. |
    The navbar is tailored to ensure visitor are provided with the right information depending on if there are logged in, ensuring the Signup function is available.

4. As a First Time Visitor, I want to be able to see comments from other visitors and add comments myself.
    The blog post view offer user to add comment only when there are logged in, and request them to sign up if not.

#### Returning Visitor Goals
1. As a Returning Visitor, I want to find back the information I entered
    Every comment added are saved, thanks to Postgres database.

2. As a Returning Visitor, I want to be able to support the blog owner.
    Engaged vistors have to option to Donate through the donate page. However, for marketing purpose, this page is also available for non logged in visitors.

3. As a Returning Visitor, I want to be able to contact the blog owner.
    The contact us page is only available for logged in users, to ensure messages will come from authenticated users who have shown an interest to the blog.

### Further Testing

Please log in with the below credential to be able to test all CRUD functionalities:
login: admin2
password: admin2

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all functions and links were working correctly.
        -   All elements of the navbar are working from all templates: Clicking on the logo, home, blog, login, signup, logout, create article, donate and search function on all said devices and browsers.
        -   The logo redirect to the home page
        -   The signup and login functions work as appropriate and return to the profile page
        -   Adding and Editing for admin users review works as intended
        -   Validating the donation form sent correspondant payment to Stripe
        -   The contact us is sending an email to the desired email address
        -   The articles can be added and deleted only when logged in as super user
        -   The most recent section on the home page is only showing the 3 most recent posts
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

- There is no known bugs

### Further improvements

-   Ensuring a 404 message is tailored
-   Having a message confirming the Contact Us form worked properly
-   Adding a page filtered by category

## Deployment

### GitHub

#### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Nosjazz/todo_list-milestone2)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site in the "GitHub Pages" section.

#### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Nosjazz/todo_list-milestone2)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

#### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/Nosjazz/todo_list-milestone2)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/Nosjazz/todo_list-milestone2
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/Nosjazz/todo_list-milestone2
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

### Heroku 

#### Prerequisites: Install Git and the Heroku CLI
Git installation instructions

Heroku CLI installation instructions

#### Steps

1. Track your codebase in a Git repository

Heroku’s build system uses Git, the popular version control system. Consequently, your codebase needs to be committed to a Git repository in order to be deployed.

Git installation
First-time Git setup
If you are already using another version control system, consult its documentation for help exporting a snapshot to Git.

2. Add a Heroku Git remote

Every Heroku app has its own Heroku-hosted Git repo. You deploy new versions of your app by pushing your code changes to this repo. In order to do that, your local Git repo needs to know the URL of the Heroku-hosted repo.

Complete the step Creating a Heroku remote to add the Heroku-hosted repo as a Git remote.

3. Add a Procfile

Commit a text file to your app’s root directory that is named Procfile without a file extension. This file tells Heroku which command(s) to run to start your app. These commands are probably the same as the ones you use to run your code on your local machine.

Here’s an example Procfile for a simple Node.js app:

web: node app.js
The web process type defined above tells Heroku to start up your web application by running node app.js. The web process type is special, because it’s the only process type that can receive HTTP traffic from the web (i.e., from your app’s users).

You can specify additional process types on separate lines in your Procfile, but process types besides web can’t receive web traffic. Process types can be any alphanumeric string (hyphens and underscores are also allowed).

For example (Rails):

web: bundle exec rails server -p $PORT
worker: bundle exec rake jobs:work
Consult language-specific guides for more information on creating a Procfile for your chosen language and framework.

4. Listen on the correct port

On your local machine, your app’s web server can listen on any open, unreserved port. On Heroku, however, it must listen on a specific port.

This specific port is indicated by the PORT environment variable. When your web server starts up on Heroku, make sure it’s listening on the port number specified by PORT:

app.listen(process.env.PORT);
To avoid having to set the PORT environment variable when running on your local machine, you can replace the line above with the following:

let port = process.env.PORT;
if (port == null || port == "") {
  port = 8000;
}
app.listen(port);
In this case, the server will listen on port 8000 if the PORT environment variable isn’t set.

The examples above are for a simple Node.js app that uses Express. Consult your programming language’s documentation and Heroku’s language-specific guides for details on both reading environment variables and configuring your web server to listen on a particular port.

5. Use a database or object storage instead of writing to your local filesystem

If your app currently writes data to its local filesystem for persistent storage (including to a local SQLite database), on Heroku it must instead write that data to one of the following locations (depending on your use case):

A managed database service (such as Heroku Postgres)
A managed object storage service (such as Amazon S3)
This requirement exists because Heroku dynos (the Linux containers that run your code) have an ephemeral filesystem. Your app’s dynos are automatically replaced at least once daily (this is called dyno cycling), and each time they are, any data your app has written to the local filesystem is lost.

Initially, this “stateless” design pattern for web apps can seem surprising and confusing. Learn more about the methodology behind it.

Provisioning a database
Heroku Postgres is Heroku’s managed SQL database service, and it is the recommended relational database for Heroku apps. Its free hobby-dev plan provides a good starting place for smaller apps, and for testing out the Heroku platform.

Learn how to provision Heroku Postgres, and then also run Postgres on your local machine to ensure parity between your development and production environments.

If you don’t want to use Heroku Postgres, add-ons for other relational databases (including MySQL and MongoDB) are available in the Heroku Elements Marketplace.

Provisioning an object storage service
Learn about using Amazon S3 on Heroku.

Add-ons for managing an S3 bucket are also available in the Heroku Elements Marketplace.

6. Complete language-specific setup

The changes above apply to all Heroku apps, regardless of programming language. In addition to them, language-specific changes might be necessary for your codebase.

### S3 Deployment

#### Step 1: Create an instance profile to access an S3 bucket
In the AWS console, go to the IAM service.

Click the Roles tab in the sidebar.

Click Create role.

Under Select type of trusted entity, select AWS service.

Under Choose the service that will use this role, select EC2.

Select service
Click Next: Permissions, Next: Tags, and Next: Review.

In the Role name field, type a role name.

Click Create role. The list of roles displays.

In the role list, click the role.

Add an inline policy to the role. This policy grants access to the S3 bucket.

In the Permissions tab, click Add Inline policy.

Click the JSON tab.

Copy this policy and set <s3-bucket-name> to the name of your bucket.

Click Review policy.

In the Name field, type a policy name.

Click Create policy.

In the role summary, copy the Instance Profile ARN.

Instance profile ARN
#### Step 2: Create a bucket policy for the target S3 bucket
At a minimum, the S3 policy must include the ListBucket and GetObject actions.

Important

The s3:PutObjectAcl permission is required if you perform Step 7: Update cross-account S3 object ACLs to configure the bucket owner to have access to all of the data in the bucket.

Bucket policy
Paste in a policy. A sample cross-account bucket IAM policy could be the following, replacing <aws-account-id-databricks> with the AWS account ID where the Databricks environment is deployed, <iam-role-for-s3-access> with the role you created in Step 1, and <s3-bucket-name> with the bucket name.

Click Save.

#### Step 3: Note the IAM role used to create the Databricks deployment
This IAM role is the role you used when you set up the Databricks account.

If you are on an E2 account:

As the account owner or an acount admin, log in to the account console.

Go to Workspaces and click your workspace name.

In the Credentials box, note the role name at the end of the Role ARN.

For example, in the Role ARN arn:aws:iam::123456789123:role/finance-prod, finance-prod is the role name.

If you are not on an E2 account:

As the account owner, log in to the account console.

Click the AWS Account tab.

Note the role name at the end of the Role ARN, here testco-role.

IAM role
#### Step 4: Add the S3 IAM role to the EC2 policy
In the AWS console, go to the IAM service.

Click the Roles tab in the sidebar.

Click the role you noted in Step 3.

On the Permissions tab, click the policy.

Click Edit Policy.

Modify the policy to allow Databricks to pass the IAM role you created in Step 1 to the EC2 instances for the Spark clusters. Here is an example of what the new policy should look like. Replace <iam-role-for-s3-access> with the role you created in Step 1:


Click Review policy.

Click Save changes.

## Credits

### Content

-   All content was written by the developer.

### Acknowledgements

-   [Boostrapious](https://bootstrapious.com/p/bootstrap-blog) for the frontend blog template

-   [JustDjango](https://www.youtube.com/watch?v=HWg3zXWwre8) Channel for the Django tutorial

-   [Denis Ivy](https://www.youtube.com/watch?v=oZwyA9lUwRk) Youtube video for the Stripe donation tutorial

-   My Mentor for his continuous helpful feedback.

-   Tutor support at Code Institute for their support - especially Michael. 