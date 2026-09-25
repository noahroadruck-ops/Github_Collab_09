# WORKFLOW_ANALYSIS.md
   
# What triggers this workflow to run? (Look at the on: section)
    -The workflow runs when changes are made and then pushed to main.

# What are the four main steps this workflow performs? (List each step name)
    -checkout code
    -validate html
    -check links
    -upload artifact

# What does the "Checkout code" step do and why is it necessary?
    -Checkout code step checks a specific version of the repository code. It lets the workflow see the repository file so it can test them.

# What is the purpose of the environment configuration?
    -The environment configuration provides the settings and any permissions so the workflow can work correctly.

# How does this automated deployment improve reliability compared to manual deployment?
    -Automated deployment makes the process more reliable as it automates the tests so it cant catch any issues before deployment. Manual deployment can have mistakes involved due to inconsistency. 

# What would happen if you pushed code to a different branch (not main)?
    -Then the deployment workflow would not be triggered, and no changes would deployed.