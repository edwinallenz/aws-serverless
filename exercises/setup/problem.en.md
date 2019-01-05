What is Serverles Framework?

Lambdas in any cloud platfom can be tricky to configure, the framework replaces that complex configuration with a single configuration file.
Another great point is the templates that it have in many programming languages, with a shell command it can generate boilerplates for C#, Java, Python and of course NodeJS.
It uses a tipical dev workflow using the terminal and editor instead to log into the cloud provider console.

## AWS
To follow the workshop you must have a AWS account and have your account secrets in place.

If you don't have an acccount you can follow this link to do your setop `https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/`

---

If you haven't made a new folder for this workshop, do so now.
Install the packages `aws-cli` and `serverless` as global packages.
From your terminal use the command `serverless config credentials --provider aws` to add your secret and key to the framework. Rememer to configure using your serverless profile.

Run the verify & menu commands for all lessons.

To follow this workshop create let's create a folder where we can organize all our files.
To check if the setup was done  correct run this command:

`$ javascripting verify introduction.js`

