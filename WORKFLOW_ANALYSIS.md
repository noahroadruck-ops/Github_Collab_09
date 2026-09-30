# WORKFLOW_ANALYSIS.md
   
# What triggers this workflow to run? (Look at the on: section)
    -The workflow runs when changes are pushed to the main branch.

# What are the four main steps this workflow performs? (List each step name)
    -Checkout code
    -Validate html
    -Check links
    -Upload artifact

# What does the "Checkout code" step do and why is it necessary?
    -The checkout code step gets the repository code so the workflow can access it. It lets the workflow see the repository file so it can test them to validate the code.

# What is the purpose of the environment configuration?
    -The environment configuration provides the settings and permissions so that the workflow can work correctly and deploy the code.

# How does this automated deployment improve reliability compared to manual deployment?
    -Automated deployment makes the process more reliable as it automates the tests so it can catch any issues before deployment. Manual deployment can have mistakes involved because each step needs done manually each time. 

# What would happen if you pushed code to a different branch (not main)?
    -Then the deployment workflow would not be triggered because it is set to run when changes are pushed to main. The changes would remain on the branch until merged into the main branch.