# dhat
This repositry consists the docker-compose files for different platforms to run D-HAT tool.

## It can be downloaded by:

```git clone https://github.com/cisco-dhat/dhat/```

## Enter the folder you cloned:

```cd dhat```

## Examine the contents:

```ls```

We support Windows, MAC and Linux platforms, as seen above

Based on the platform, you can navigate to the corresponding folder and  run docker-comoose up 

## For Linux based distributions, 

```
cd linux
docker-compose up
```


## For Windows, 

```
cd windows
docker-compose up
```


## For MAC, 

```
cd mac
docker-compose up
```


Note: To run in the detached mode, you can add the -d flag, as shown below:
```docker-compose  up -d```


## To bring the server down,

```docker-compose down```

## To restart the server,

```docker-compose restart```
