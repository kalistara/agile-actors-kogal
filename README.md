# Agile Actors MultiRepos as MonoRepo

A single project to manage the various Agile Actors micro-services (repos).

## Key technologies:

  * Lerna (sub-projects management and linking)
  * Yarn workspaces (dependencies management)
  * Meta (git control)

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

* Each of the folders under **packages/** is a git repo. You can add it to your favourite git client and handle it the way you would normally do.

   1. agile-actors-actions -> `git@github.com:kogal/next-dot-actions.git`
   2. agile-actors-client  -> `git@github.com:kogal/agile-actor-x.git`
   3. agile-actors-server  -> `git@github.com:kogal/agile-actor.git`

* From the terminal (handles all repos simultaneously):

```
yarn git <command>
```
