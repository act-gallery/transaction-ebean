# ACT Framework Demo Applications

## KNOWN ISSUE

* At the moment act-ebean does not work on Java9+

## Usage:

To start in dev mode:

```bash
cd /path/to/a/app
mvn clean compile act:run
```

To start in prod mode:

```bash
cd /path/to/a/app
mvn clean package
cd target/dist
tar xzf *.tgz
./run
```
