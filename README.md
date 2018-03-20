# agile-actors

Agile Actors MultiRepo

## Build the project
```
yarn build
```

## Run locally

* Start both the client and the server.

```
yarn start
```

* Start the client only:

```
yarn start:client
```

* Start the server only:

```
yarn start:server
```

## Version control (git)

1. Each of the folders under **packages/** is a git repo. You can add it to your favourite git client and handle it the way you would normally do.

 - agile-actors-actions -> `git@github.com:kogal/next-dot-actions.git`
 - agile-actors-client  -> `git@github.com:kogal/agile-actor-x.git`
 - agile-actors-server  -> `git@github.com:kogal/agile-actor.git`

2. From the terminal (handles all repos simultaneously):

```
yarn git <command>
```
