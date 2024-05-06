
## Summary (Summarize the bug encountered concisely)

    Incorrect naming of the section: instead of Create black project it should be Create blank project

## Steps to reproduce     

   1. Login to the GitLab
   2. Go to HomePage
   3. Click on "Projects" in left sidebar
   4. Click on "New project"
   5. First block has wrong name "Create black project" instead of "Create blank project

## What is the current bug behavior?

     First block has wrong name "Create black project"

## What is the expected correct behavior?

    First block should have name "Create blank project"
     
## Relevant logs and/or screenshots

      Screenshot of bug:
      "Image" > "Bug_Project_create_blank.png"

## Possible fixes

    Current html code
    <h3 class="gl-font-size-h2 gl-reset-color">Create black project</h3>

    Posible fix
    <h3 class="gl-font-size-h2 gl-reset-color">Create blank project</h3>

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-change 
    /cc @project-manager 
    /assign @qa-tester

## Priority
    Major - It is text misstake, which may cause missundersanding, and also Create black project is not an appropriate name
      
