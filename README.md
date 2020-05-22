# A singularity container running Coq+Mathcomp+VSCodeServer

If this is the first time you use vscoq extension which you can get [here](https://marketplace.visualstudio.com/items?itemName=maximedenes.vscoq), manually install it as follows:
```
singularity run okuisatoshi-singularity-coq-mathcomp-code-server-master-latest.simg  --install-extension maximedenes.vscoq-0.3.1.vsix
```

Typical Usage:

First, invoke code server:
```
PASSWORD=foo1234 singularity run okuisatoshi-singularity-coq-mathcomp-code-server-master-latest.simg 
```
Then visit `http://localhost:8080`.




