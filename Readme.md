<p align="center">
  <img src="https://raw.githubusercontent.com/zaygozi/lazlodb/master/lazlo-logo-max.png">
</p>

### Lazlo is a portable, compact & serverless NoSql database built using Node JS & MessagePack

## Installation
* Full Database
```sh
npm install -g lazlodb
```
#### Note : You may need to give write permissions to node_modules using sudo chmod if there is a write access error
* Execute Cli
```sh
lazlo
```
* Lightweight Node JS Library (Official Repository : [lazlo-node](https://github.com/zaygozi/lazlo-node))
```sh
npm install lazlo-node
```

## Storage
* Data is stored in **.laz** files in MessagePack encoded form. As MessagePack is smaller than JSON, it takes less space & hence the files are compact.
* Each **.laz** file represents a **document** (or a table in sql).
* All documents exist in a database, which is essentially a folder being tracked by lazlo.

## Features
* Databases do not require an isolated environment. They can exist anywhere, even in your code repository or cloud folder.
* Very easy to use.
* Multiple commands for the same operation (Eg. **newdoc** & **create doc** both will create a new document).
* Inbuilt caching system caches recently queried documents leading to faster responses.
* Extensive use of terminal styling (Eg. Success messages are displayed in green & errors are displayed in red).
* Command auto-completion available (Eg. Type create & press tab. You will get recommendations for all commands starting with create).
* Powerful inbuilt logger which logs all the transactions.

## Major third party libraries used :
* vorpal js
* msgpack-lite
* chalk
* simple-node-logger
* edit-json-file

## For usage info refer the [docs](https://github.com/zaygozi/lazlodb/wiki)
