# DevFest Santiago de Compostela Workshop: Full-stack Performance Testing with Grafana k6

##  0. Before we start

### 0.1. Introduction

### 0.2. Requirements
- Docker
- git
- GitHub account 
- Optional (but recommended): [k6](https://k6.io/docs/get-started/installation/)
  - You can run it inside Docker, but the experience is better if you install it locally. 
    - You get nice colors and dynamic progress bars!
    - Also, it is just a binary, so you can easily remove it afterward if you don't want it.
  - If you plan to use Docker, please, pre-pull the images with:
    - `docker pull grafana/k6`
    - `docker pull grafana/k6:master-with-browser`

###  0.3.  Run the local playground

First of all, clone the repository: 
```bash
git clone https://github.com/dgzlopes/devfest-santiago
```

Then, run the playground with:
```bash
cd devfest-santiago; docker compose up -d
```

To verify everything is working, go to http://localhost:3333 and click the big button. 

If you see a pizza recommendation, that's good!

Also, open http://localhost:3000 and verify that you can see a Grafana instance.
