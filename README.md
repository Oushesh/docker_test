## Philosophy -- A note to my future Engineers/Data Scientists of My Company
   * Waiting for this come: Github Codespaces
     * Until Then: Use replit.com to test a github Machine Learning code.
        * If you need more space, buy the hacker membership of 5 bucks/month
        * TODO: Find a way to fast-inference test pretrained models. (Colab does not work so much)
     
    
   * Once the code works and you run without errors, fast-configure Docker-File
     * Write the dockerfile and test the run locally. Pull Docker and test.
     * Set up Github docker action 

   * Machine Learning Part: 
     * Self made data--annotation Tool, inference automation, etc-.. soon
    
## Problems with Docker on VM and Cloud services.
   * https://phoenixnap.com/kb/how-to-create-sudo-user-on-ubuntu
   * https://phoenixnap.com/kb/su-command-linux-examples
   * https://docs.docker.com/engine/security/rootless/
    
    * Docker run
      * Typical: sudo docker build <docker.file> without sudo you get docker-daemon error
        * If you are on a local computer: add current user to new user group as follows:
          *  https://askubuntu.com/questions/477551/how-can-i-use-docker-without-sudo
        * If you are on a virtual machine: example the one I use: Paperspace then lets see
          * TO Write the fix here  


## Current Training and Inference Cycle:
   * 1) Make <docker> file for every git --> docker build docker --> push docker image to docker hub 
   * 2) Connect the myhub/container to Gradient on paperspace --> perform testing, NN Training and Inference
