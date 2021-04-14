## This will serve as a way to "dechifrer" a dockerfile

    * The docker file starts with "FROM" and represents the oS image.
      * FROM ubuntu:18.04  
      *  Example: nvcr.io/nvidia/deepstream:5.0-20.07-triton
    
    * All the commands you would write is under "RUN"
    * ENV is used to define path
    * Otherwise everything is with RUN

## Ref: 
   * https://github.com/pbridger/pytorch-video-pipeline/blob/master/docker/Dockerfile
