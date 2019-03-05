# SmartCity


###### about this project
> SmartCity is a project for ...


## Getting Started

### Clone the project

Clone a copy of the project to your local storage with:

```bash
git clone https://github.com/Rev-Tech/SmartCity.git
```


### Install the dependencies

1. Change the current working directory to the project:
```bash
cd SmartCity
```

2. Install [`learna`](https://github.com/lerna/lerna) (if you haven't):
```bash
sudo npm install -g lerna
```
3. Bootstrap the packages in the current Lerna repo: <?>
```bash
lerna bootstrap
```

4. Install [`yarn`](https://github.com/yarnpkg/yarn) (if you haven't):
```bash
sudo npm install -g yarn
```

5. Install the package dependencies:
```bash
yarn install
```


### start the servers

This system requires [`MongoDB`](https://docs.mongodb.com/manual/installation/) and [`Redis`](https://redis.io/topics/quickstart) in onder to run. Please ensure that your machine already have those installed. If not, consider following the link attached to them for the installation guide. 

There are 2 servers you need to run to start this system. One is the backend server, the other one is the frontend.

* Start the backend server first:
```bash
cd SmartCity/packages/server
yarn start
```

* Then, start the frontend server:
```bash
cd SmartCity/packages/client
yarn dev <?>
```
