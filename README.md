# mysql.docset for dash

build with [dashing](https://github.com/technosophos/dashing)

## Introduction

Dash app offers an official MySQL docset, but its chapters are merged together, which makes it inconvenient to browse. Therefore, I created this project that stores the chapters separately.

## Get Started

1. get doc html
   - `wget -r -np -k -p -e robots=off "https://docs.oracle.com/cd/E17952_01/mysql-8.0-en/"`
2. edit `./dashing.json`
3. build
   - `dashing build`
