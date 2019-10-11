# notarize-app
Linear notarize and staple for build tools.

1. Run `altool --notarize-app`
2. Run `altool --notarization-info` periodically and `sleep` until notarization is complete
3. Run `stapler staple`


## Usage
```sh
notarize-app <asc-provider> <username> <password> <primary-bundle-id> <file>
```
e.g.
```sh
notarize-app AB0CDEF2GF 'user@example.net' '@keychain:notarize-app' 'net.example.app' *.pkg
```
