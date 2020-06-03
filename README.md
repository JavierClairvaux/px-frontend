# px-frontend

Run the following command to restore dependencies to `vendor/` directory:

    dep ensure --vendor-only

To enable synthetic latency set the environment variable like so:
```
env:
- name: LATENCY
  value: "true"
```

Container based on the frontend container of Google's microservices demo, which can be found [here](https://github.com/GoogleCloudPlatform/microservices-demo/tree/master/src/frontend).
