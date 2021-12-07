# Crypto Marketplace

There will be two projects:
 - contracts, like a backend
 - marketplace, the front end

They will be conected with git submodules

# Tecnologies

The initial tecnology stack will be:
 - NextJS
 - Web3JS
 - Solidity

After that, can be made some reseash about polygon and thegraph protocol.

# Development Flow

The project use git submodule. To start the project first clone into the machine, then:

```sh
$ git submodule init 
& git submodule update
```

Then go to the project that you need to modify for futher instructions.

If you already in the project, make sure to be up to date with the remote using the following command:
```sh
git pull "$@" &&
  git submodule sync --recursive &&
  git submodule update --init --recursive
```

# References

The first reference will be this article and code:
 - https://dev.to/dabit3/building-scalable-full-stack-apps-on-ethereum-with-polygon-2cfb
 - https://github.com/dabit3/polygon-ethereum-nextjs-marketplace/

# License 

Licensed under the [MIT License](LICENSE).

<br>

___

Made with :black_heart: by Vinícius