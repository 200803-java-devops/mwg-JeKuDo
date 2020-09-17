# Testing out some Jenkins-Kubernetes-Docker Synergy!
(It won't let me fix the typo in the About Me since I moved this here from my own Github page :-/)

Do this once to make ./s/dbandr executable:
```
chmod 764 ./s/dbandr
```
To Run and Build the Dockerfile (this will make an image called "i_jkd" and a containor called "c_jkd" and open port 8181 and it will make the other sh scripts executable when run) (Also, it will try to make a job in Jenkins right away, before Jenkins is ready)
```
./s/dbandr
```
Until I implement a script that knows how to wait until Jenkins is ready, please run this after you can see that Jenkins is ready:
```
./s/createJobs
```