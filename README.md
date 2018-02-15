# jspm-registry-1070
This repository was created to diagnose https://github.com/jspm/registry/1070

To test, run 

```ps
$ jspm install github:aluanhaddad/jspm-registry-1070
```

Observe that jsdom is not installed, but jquery is.

Then run

```ps
$ npm install aluanhaddad/jspm-registry-1070
```

Observe that jsdom and jquery are both installed.
