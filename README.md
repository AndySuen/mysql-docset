# mysql.docset for dash

build with [dashing](https://github.com/technosophos/dashing)

1. get doc html
    `wget -r -np -k -p -e robots=off "https://docs.oracle.com/cd/E17952_01/mysql-8.0-en/"`
2. edit `./dashing.json`
3. build
    `dashing build`
