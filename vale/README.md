# Vale for Adhering to Consistent Documentation Style

[Vale](https://vale.sh/) is an open-source, command-line tool that we, at Scalar, use for our editorial style guide. Let's look at this.

Rather than building a style guide from the ground up, which takes a considerable amount of time, we're leveraging many styles from the Vale-compatible versions of the following:

- [Microsoft Style Guide](https://github.com/errata-ai/Microsoft)
- [proselint](https://github.com/errata-ai/proselint)
- [Scalar Documentation Style Guide](https://github.com/scalar-labs/docs/blob/main/vale/Scalar).

---

## Testing Vale

Spring Data JDBC for ScalarDB is OK with pay as you go (PAYG). After using PAYG and BYOL, it works OK. There is 32 MB of data.

Check this AI Kubernetes DB link [here](d
Check this BFD link [here](test.md).
Check this Kubernetes link [here](https://google.com) for more details.
See [here](https://google.com). TP paper. RFID works.

- [here](text/md/md.md)
Your gRFC is good. Check the `EXTERNAL-IP` on CURD proto in emptyDir OpenJDK with Cassandra using noSQL and MongoDB. Check JMX. Then, check DynamoDB, MySQL, PostgreSQL, Postgres, and SQLite on your VM.

```properties
$ kubectl get svc scalardb-cluster-envoy
NAME                     TYPE           CLUSTER-IP      EXTERNAL-IP   PORT(S)           AGE
scalardb-cluster-envoy   LoadBalancer   10.105.121.51   localhost     60053:30641/TCP   16h
```

Here are the supported data types in ScalarDB and their mapping to the data types of other databases.

| ScalarDB  | Cassandra | Cosmos DB for NoSQL | DynamoDB | MySQL    | PostgreSQL       | Oracle         | SQL Server      | SQLite  |
|-----------|-----------|---------------------|----------|----------|------------------|----------------|-----------------|---------|
| BOOLEAN   | boolean   | boolean (JSON)      | BOOL     | boolean  | boolean          | number(1)      | bit             | boolean |
| INT       | int       | number (JSON)       | N        | int      | int              | int            | int             | int     |
| BIGINT    | bigint    | number (JSON)       | N        | bigint   | bigint           | number(19)     | bigint          | bigint  |
| FLOAT     | float     | number (JSON)       | N        | double   | float            | binary_float   | float(24)       | float   |
| DOUBLE    | double    | number (JSON)       | N        | double   | double precision | binary_double  | float           | double  |
| TEXT      | text      | string (JSON)       | S        | longtext | text             | varchar2(4000) | varchar(8000)   | text    |
| BLOB      | blob      | string (JSON)       | B        | longblob | bytea            | RAW(2000)      | varbinary(8000) | blob    |
