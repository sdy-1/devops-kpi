Mykola Dikarev, IS-02

# Node.js Hello World app in docker

### Command used to build, push and run docker image:
  - ```docker build -t boringq/devops-lab```
  - ```docker login```
  - ```docker push boringq/devops-lab```
  - ```docker run docker run -d -p 80:3000 -m 128m --cpus="1" --name node_server boringq/devops-lab:latest```
