# Harper Basic Data Example

A very simple example of using the Harper `dataLoader` plugin along with corresponding GraphQL schema for the table.

Intended to be used for demos along side more complex Harper application examples such as the [Harper Next.js Example](https://github.com/harperdb/nextjs-example)

To deploy this example to a Harper instance, you can use the [Harper CLI](https://docs.harperdb.io/docs/deployments/harper-cli#operations-api-through-the-cli).

```bash
harperdb deploy \
	target="<operations api url>" \
	username="<username>" \
	password='<password>' \
	project=basic-data-example \
	package=HarperDB/basic-data-example \
	replicated=true \
	restart=true
```