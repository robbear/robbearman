# robbearman
robbearman.com

Follow instructions at https://blog.atj.me/2018/04/cloud9-with-a-chance-of-hugo/
to set up Hugo.

Also see https://gohugo.io/hosting-and-deployment/hosting-on-netlify/
regarding theme and git submodules.

Create a post:
```
hugo -s src new post/My Post.md 
```

Run locally in C9 with:
```
hugo serve -D --bind=0.0.0.0 -p 8080 -b https://robbearman-robbear.c9users.io/ --appendPort=false --disableFastRender -s src
```