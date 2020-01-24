# Create your Pipeline project in Jenkins

1. In main page click `create new jobs` under _Welcome to Jenkins!_ or click New Item at the top left.

2. In the Enter an item name field, specify the name for your new Pipeline project (e.g. _node-jenkins-test (template)_). Scroll down and click _Pipeline_, then click OK at the end of the page.

> **( Optional )** On the next page, specify a brief description for your Pipeline in the Description field (e.g. An entry-level Pipeline demonstrating how to use Jenkins to build a simple Node.js and React application with npm.)

3. Click the Pipeline tab at the top of the page to scroll down to the Pipeline section.

     From the Definition field, choose the _Pipeline script from SCM_ option. This option instructs Jenkins to obtain your Pipeline from Source Control Management (SCM), which will be your locally cloned Git repository.
     
     From the SCM field, choose _Git_.

    In the Repository URL field, specify the url to repository `https://github.com/jmruiza/node-jenkins-test.git`.

    Click _Save_ to save your new Pipeline project. You’re now ready to begin [creating your Jenkinsfile](create-jenkinsfile.md), which you’ll be checking into your locally cloned Git repository.

