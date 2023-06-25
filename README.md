# 📚 Getting Started with GitLab CI/CD

This repository demonstrates a simple CI/CD pipeline using GitLab. The pipeline consists of three stages: build, test, and deploy, which are executed automatically upon pushing changes to the repository.

## 🚀 Pipeline Overview

The pipeline follows the following sequence of stages:

1. **Build:** In this stage, the application is built using the specified build commands. This stage is responsible for compiling the source code, resolving dependencies, and generating any required artifacts.

2. **Test:** The application undergoes testing in this stage. Unit tests, integration tests, or any other relevant tests are executed to ensure the application's correctness and stability.

3. **Deploy:** Once the application passes the testing stage, it is deployed to the desired environment, such as a server or a cloud platform. The deployment commands are executed in this stage.

## ⚙️ Configuration

The pipeline is configured using the **.gitlab-ci.yml** file located at the root of the repository. This file defines the stages and jobs that make up the pipeline. You can customize this file based on your specific requirements.

The provided example **.gitlab-ci.yml** file includes the following jobs:

 - **build_job:** Executes the build commands to compile the application and generate artifacts.

 - **test_job:** Runs tests to verify the functionality and integrity of the application.

 - **deploy_job:** Deploys the application to the target environment.

Feel free to modify and expand upon these jobs to suit your project needs. You can add additional stages, jobs, and scripts to accommodate your build, test, and deployment processes.

## ✅ Conclusion

This repository demonstrates a basic CI/CD pipeline using GitLab. By customising the **.gitlab-ci.yml** file, you can configure the pipeline to build, test, and deploy your applications seamlessly. GitLab provides extensive features to enhance your CI/CD process, such as environment variables, caching, artifacts, and more.

For more information on GitLab CI/CD, refer to the [official documentation](https://docs.gitlab.com/ee/ci/).

Feel free to explore and expand upon this pipeline to suit the needs of your specific project. Happy coding! 🎉

## 📄 License

MIT / BSD

## 🇬🇧🇭🇰 Author Information

* Author: Jody WAN
* Linkedin: https://www.linkedin.com/in/jodywan/
* Website: https://www.jodywan.com