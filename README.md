# Simple Docker Image to Measure Code Complexity Number (CCN)

To measure CCN, just run:

```shell
cd /path/to/your/project
docker run -v $PWD:/lizard --rm diverse/lizard
```

For example, if you want to list Swift methods whose CCN is equal or greater than 10:

```shell
docker run -v $PWD:/lizard --rm diverse/lizard -l swift -C 10
```

License: [MIT](https://github.com/diverse-inc/docker-lizard/blob/master/LICENSE)
