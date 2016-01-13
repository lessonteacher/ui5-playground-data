# ui5-playground-data #

Contains rethinkdb docker data volume for messing around with.

Usage, clone the repo to wherever

```
cd /path/to/dir
git clone <this-repo>
```

Run RethinkDB via docker, use this folder as the mount and it must be the full path

```
docker run --name rethinkdb -v /path/to/dir/ui5-playground-data -p 28000:8080 -p 28015 -p 29015 -d rethinkdb
```

Once running you can see the console at 'localhost:28000' in a browser
