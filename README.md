#jekyll

Container including jekyll, git, vim and their dependencies

##RUN
```
docker run -dti --name jekyll francois:jekyll:latest /bin/bash
```

##BUILD
Build as usual
```
git clone https://github.com/francois-docker/jekyll.git
cd jekyll
docker build -t fancois/jekyll .
```

