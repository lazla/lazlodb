&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Logo](http://www.auplod.com/u/plaudob1d7a.png)

### Lazlo is a portable, compact & serverless NoSql database built using Node JS & MessagePack

## Installation
* Full Database
```sh
npm install -g lazlodb
```
* Lightweight Node JS Library
```sh
npm install lazlo-node
```

## Storage
* Data is stored in **.laz** files in MessagePack encoded form. As MessagePack is smaller than JSON, it takes less space & hence the files are compact.
* Each **.laz** file represents a **document** (or a table in sql).
* All documents exist in a database, which is essentially a folder being tracked by lazlo.

## Features
* Databases do not require an isolated environment. They can exist anywhere, even in your cloud folder (this will sync your database to the cloud).
* Very easy to use.
* Multiple commands for the same operation (Eg. **newdoc** & **create doc** both will create a new document).
* Interactive cli
* Extensive use of terminal styling (Eg. Success messages are displayed in green & errors are displayed in red)
* Command auto-completion available (Eg. Type create & press tab. You will get recommendations for all commands starting with create).
* Powerful inbuilt logger which logs all the transactions.
* Special features (Eg. Display all records in a document for a given creation date).

## Major third party libraries used :
* vorpal js
* msgpack-lite
* chalk
* simple-node-logger
* edit-json-file

#### For usage info refer the [docs](https://github.com/zaygozi/lazlodb/wiki)
