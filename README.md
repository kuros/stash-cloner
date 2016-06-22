# stash-cloner
Utility to clone multiple repositories for stash project

# Setting Config file
modify config.json to provide base info:

1. user: username 
2. host: name of the host to connect
3. filter-name: filter the project by name/ "null" if you want to load all projects
4. https: true/false (is stash on https)
5. ssh: true/false (do you want to clone using ssh)
6. cwd: "specify the current working directory, keep it falsy if not required"


# Steps to run

```
npm install (one time effort)
node index.js
```

