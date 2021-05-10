# containerization-challenge

This repository contains some container related files to containerize an existing app.

Clone repositories:

```bash
git clone https://github.com/treywelsh/containerization-challenge.git \
   && cd containerization-challenge \
   && git clone https://github.com/govpf/devops-challenge.git
```

Run:

```bash
   docker build -t devops-sipf-back -f Dockerfile.back .
   docker build -t devops-sipf-front -f Dockerfile.front .
```
