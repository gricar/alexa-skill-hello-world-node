# alexa-skill-hello-world-node

- **Step 1:** Clone the [sample skill](https://github.com/alexa/skill-sample-nodejs-hello-world) and install the `node_modules` dependency
    
    ```bash
    # Clonar o repo
    git clone https://github.com/alexa/skill-sample-nodejs-hello-world.git
    
    # Instalar node_modules
    cd lambda/custom/
    npm i
    ```
    
- **Step 2**: Set up the test framework from npm
    
    ```bash
    # project root folder
    cd ../../
    mkdir test
    cd test/
    npm install alexa-skill-test-framework --save-dev
    npm install mocha --global
    ```
    
- **Step 3**: Run a sample test case
    - Copy the Hello World sample test file: helloworld-tests.js from GitHub and put it under the “test” folder.
    
    ```bash
    mocha helloworld-tests.js
    ```
