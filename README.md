## Philosophy -- A note to my future Engineers/Data Scientists of My Company
   * Waiting for this come: Github Codespaces
     * Until Then: Use replit.com to test a github Machine Learning code.
        * If you need more space, buy the hacker membership of 5 bucks/month
        * TODO: Find a way to fast-inference test pretrained models. (Use paperspace cloud to test the repos: Build docker             and always for fast testing)

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
      * 1) Build docker as mentionned here:
           * Typical: sudo docker build <docker.file> without sudo you get docker-daemon error
           * If you are on a local computer: add current user to new user group as follows:
             *  https://askubuntu.com/questions/477551/how-can-i-use-docker-without-sudo
      * 2) If you are on a virtual machine: I use Paperspace (6h continuous runtime).        
      * 3) Make <docker> file for every git --> docker build docker --> create a repository on docker --> push docker image              to docker hub 
           *  
  
## How to?:
   * https://hub.docker.com/r/thingio/deepstream-l4t (pulled and built successfully)
        TODO: push to docker hub registry --> pull into paperspace cloud service.
   * 2) Connect the myhub/container to Gradient on paperspace --> perform testing, NN Training and Inference


## Ref
   * https://docs.paperspace.com/gradient/notebooks/create-a-notebook/notebook-containers/building-a-custom-container
