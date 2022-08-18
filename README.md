Connect to docker

```
docker exec -it postgresql /bin/bash
```

Connect to postgresql with postgres

```
psql -U postgres
```

Find database

```
\l
```

Find tables from scheme (hello-prisma-postgresql)

```
\dt "hello-prisma-postgresql".*
```

Select table with schema name ("hello-prisma-postgresql"."User")

```
select * from "hello-prisma-postgresql"."User";
```
