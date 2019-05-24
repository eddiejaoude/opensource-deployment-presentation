# opensource-and-cloud-deployment

Open Source powers most of the internet, through  the existence of linux, python, angular and bootstrap to name a few.  

With some Open Source projects having in excess of 70,000 contributors, it is necessary for there to be methods and standards in order for these projects to succeed. 

We will be looking at how we can best manage and deploy the great tools we have at our disposal in order to achieve better collaboration, less technical conflicts and ultimately a more inclusive project.

This talk will also look at one of the biggest drivers in Open Source: it’s Community, and how best to be part of this Community both from a contributor and maintainer perspective. 

![Screenshot](https://user-images.githubusercontent.com/624760/58321740-e6ea3600-7e16-11e9-9a7a-d175bf2624a9.png)

## Notes

* Open source
    * What is it
    * Its not just about code
    * Why contribute to open source
    * Contributor tips
    * What are the benefits to a project maintainer
    * Maintainer tips
* Cloud
    * Setup pipeline and deploy hello world first
    * Feature branching (gitflow)
    * Commit strategy + Changelog generation
    * Merging strategies
    * Automation - automated testing (cypress), extra tools like static code analysis / mutation testing
    * CI (run all automation)
    * CD (each feature/epic branch gets it own environment, protect main branches (GitHub code owner file), delete feature/epic environments after PR is closed)
    * Serverless / Firebase much easier (cost model is very effective), AWS / GCP more infrastructure as code is required
