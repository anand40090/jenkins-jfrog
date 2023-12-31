# jenkins-jfrog
Build the code and store the antifactory on Jfrog artifactory 

### References -
1. [Jenkins Artifactory Integration Example Tutorial: Uploading artifact](https://www.youtube.com/watch?v=4PX3LCVjAEA)
1. [jfrog artifactory tutorial, jfrog installation, jfrog integration with jenkins](https://www.youtube.com/watch?v=v0OiZejQLts)
1. [Integrate Artifactory with Jenkins | How to integrate Artifactory and Jenkins ](https://www.youtube.com/watch?v=k3_byI8Eql4&t=70s)
1. [How to Configure Artifactory in Jenkins - ****Very IMP****](https://www.youtube.com/watch?v=fj_TD9pufFM)
1. [Jenkins Pipeline Example](https://jfrog.com/blog/ci-cd-side-by-side-jenkins-and-jfrog-pipelines/)
1. [IMP Blog](https://medium.com/@nanditasahu031/jenkins-pipeline-jfrog-artifactory-and-jenkins-integration-4fed3fc8d556)
1. [Jfrog Release](https://releases.jfrog.io/artifactory/bintray-artifactory/org/artifactory/oss/jfrog-artifactory-oss/)

```
Jfrog Tutorials = 
https://www.youtube.com/watch?v=4PX3LCVjAEA
https://www.youtube.com/watch?v=v0OiZejQLts
https://www.youtube.com/watch?v=k3_byI8Eql4&t=70s
https://www.youtube.com/watch?v=fj_TD9pufFM
```

### Steps - 
***1. Install Jfrog Artifactory plugins in jenkins -*** 
   
   ![image](https://github.com/anand40090/jenkins-jfrog/assets/32446706/7fd164c0-d68e-461f-a520-3e7af718661d)

***2. Login to Jfrog Artifactory - Create Token -***
   
   ![image](https://github.com/anand40090/jenkins-jfrog/assets/32446706/967a00c8-5787-4a6f-bf74-7cb0da5aa9a8)
   ![image](https://github.com/anand40090/jenkins-jfrog/assets/32446706/df9ae722-088e-43a2-8f2c-b6cd02208542)

***3. Configure the Jfrog Credentials in jenkins -***
   ![image](https://github.com/anand40090/jenkins-jfrog/assets/32446706/99a562ea-3efb-48bf-a149-4c2b690a7652)

***4. Install JF Cli in Jenkins system -***
- Get the appropriate installation and follow the steps mentioned on website
```
https://jfrog.com/getcli/
```
***5. Configure Jfrog in jenkins configuration -***

![image](https://github.com/anand40090/jenkins-jfrog/assets/32446706/e04ae0ae-36ee-4d6e-be97-ac3c806ccd5c)

***6. Build the Jenkins Pipeline to push Artifacts on Jfrog -***



