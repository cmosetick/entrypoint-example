entrypoint-example
==================

Hello World training example, demonstrating Docker `ENTRYPOINT` and `CMD`.

basic usage:  
`docker pull cmosetick/entrypoint-example`
`docker run --rm cmosetick/entrypoint-example`

optional building on your own system:  
```
git clone https://github.com/cmosetick/entrypoint-example.git
docker build --no-cache -t cmosetick/entrypoint-example .
```

Training Lessons:  
* What are some methods that you can make a container spawned from this image (Dockerfile) display the actual `uptime` of the system.

* Describe two methods to run `debug-mode.sh` and what happens when you run it?
