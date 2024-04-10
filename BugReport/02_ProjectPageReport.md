
## Summary (Summarize the bug encountered concisely)

Typo in the creation of new Blank Project ([Link to New Project](https://gitlab.com/projects/new)). Insted of 'black' should be 'blank'.

![Image info](../Image/Bug_Project_create_blank.png)

## Steps to reproduce     

   - Log In to a GitLab Account
   - Go to [Create New Project Page](https://gitlab.com/projects/new)
   - We can see the typo in the upper-left option title

## What is the current bug behavior?

The upper-left option title shows 'Create black project'

## What is the expected correct behavior?

The upper-left option title should show 'Create blank project'
     
## Relevant logs and/or screenshots

Page with the bug

![Image info](../Image/Bug_Project_create_blank.png)

Page without the bug 

![Image info](../Image/Bug_Screenshot_Solved.png)

## Possible fixes

Change the typo in the line of code 
```html
<h3 class="gl-font-size-h2 gl-reset-color">Create black project</h3>
```
to 
```html
<h3 class="gl-font-size-h2 gl-reset-color">Create blank project</h3>
```

## Whom do you report/ Assign To/ Tags

    /label ~bug ~reproduced ~needs-investigation 
    /cc @project-manager 
    /assign @qa-tester

## Priority

      Trivial
