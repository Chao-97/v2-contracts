- create MultiSig for performing actual upgrade
- Contract needs to be EIP1967-compatible
- ```prepare_upgrade.js``` script needed to specify the Proxy Address
- Network files: commit to [source control](https://docs.openzeppelin.com/upgrades-plugins/1.x/network-files) the files for all networks except the development ones.
The development version can be ignored:
```
// .gitignore
# OpenZeppelin
.openzeppelin/unknown-*.json
```
-