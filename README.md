# Installation
- change direcotry to app1 and run `vendor/bin/sail up -d`. This should start the project initially
- to build the image run `docker build . -t alviahmed/app1`
- push the image to docker registry, first login to docker registry `docker login` and the run `docker push alviahmed/app1:${tag}`

Not including jenkins as I have no prior experience with jenkins and as my environment is wsl on windows there are some issues connecting minikube with jenkins. Although I have included jenkins in `docker-compose.yml`

I also am not including 2 directories for app1 and app2 as it made more sense just creating 2 tags for same application with different outpul