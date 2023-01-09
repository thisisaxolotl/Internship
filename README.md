# Continuous Integration (CI)
In a non-CI production pipeline, there exists a _merge day_, when codes from different sectors are merged together to integrate into the application. This is known to be tedious and time-consuming, since thousands of changes from multiple developers have been committed since last time.

**Continuous Integration (CI)** is deployed to circumvent this resource-intensive situation. The idea behind this practice is intergrating code changes from many developers automatically into a shared branch multiple times a day. The changes are tested against each other for errors, which are fixed on the spot should any are spotted. This helps solving conflicts early on, and saves businesses countless hours of debugging time. 

# Continuous Delivery (CD) 
**Continuous Delivery (CD)** acts as the next step to CI. This practice automates everything from merging codes (from CI) to delivering primed builds for an application. It validates, tests and releases codes spontaneously in the same vein as the CI process. The goal of this practice is providing developers the ability to deploy an app easily at any given time.

# Tools for CI and CD
The list below describes some of the tools used to support the CI/CD pipeline, and what advantages they have:
- **Jenkins**: One of the most well-known. It is open-source and customizable, also supports many OS like MacOS, Windows and Linux.
- **Travis CI**: It supports many programming languages, and is quick to deployed with pre-installed services.
- **CircleCI**: It only runs on MacOS and Linux, but has great customizations and integrates with GitHub services.
- **BuildBot**: It is open-source, and can automatically test the tree after every code changes to pinpoint problematic components.

# Sources:
- RedHat: https://www.redhat.com/en/topics/devops/what-is-ci-cd#continuous-deployment
- Katalon: https://katalon.com/resources-center/blog/ci-cd-tools
