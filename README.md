# Prisma + MongoDB local replicaSet

This project is an example of a development environment using Prisma with MongoDB local replicaSet.

The MongoDB database connector uses transactions to support nested writes. Transactions requires a replica set deployment. You can use this project to create your replica set locally or you can use a free tier of [Mongo Atlas](https://www.mongodb.com/cloud/atlas).

## Summary

- [Prisma + MongoDB local replicaSet](#prisma--mongodb-local-replicaset)
  - [Summary](#summary)
  - [Dependencies](#dependencies)
  - [Running](#running)

## Dependencies

- [Docker](https://www.docker.com/)
- [Make](https://www.gnu.org/software/make)
- [MongoDB](https://www.mongodb.com/)
- [Prisma](https://www.prisma.io/)

## Running

To start the containers:

```bash
make start
```

To stop the containers without removing them:

```bash
make stop
```

If you want to remove the containers:

```bash
make destroy
```

---

[Reginaldo Morais](mailto:reginaldo.cmorais@gmail.com)
