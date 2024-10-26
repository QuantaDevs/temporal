FROM temporalio/web:2.26.2

ENTRYPOINT ["/bin/sh", "-c", "TEMPORAL_GRPC_ENDPOINT=$TEMPORAL_GRPC_HOST:7233 node server.js"]
