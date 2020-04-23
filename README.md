
#### Maven Build
Traditionally the PingIdentity SDK provides an Ant build script for their adapter development. This project is just a template to get started with.

#### Build Instructions

Copy `pf-protocolengine.jar` from `<pf_install>/server/default/lib` to the lib folder in this repo.

```
mvn clean install
```

#### Metadata for PF
The jar would be packaged with `PF-INF/<adapater>` file which contains the class name of the adapter
