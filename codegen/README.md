# json-rpc-codegen

### Install node modules

```
npm install
```

### Build
```
npx tsc
```

### Run
```
node dist/cli.js
```

# Command line options
```
Usage: json-rpc-codegen [options] <schema>

json-rpc interface code generator

Arguments:
  schema                 openapi.yml schema

Options:
  -V, --version          output the version number
  -c, --client <string>  Generate TypeScript client interface (default: "./rpc-interface.ts")
  -s, --server <string>  Generate C++ server interface (default: "./RpcInterface.h")
  -h, --help             display help for command
  ```