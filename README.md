# Cloud Configuration Properties

Spring Cloud Config

## Test Config Server

`http://localhost:<port-number>/<application-name>/<profile>`

// 20230709214355
// http://localhost:8888/test-application-client/default

{
  "name": "test-application-client",
  "profiles": [
    "default"
  ],
  "label": null,
  "version": "23b4895d1140c9d53983a14688825bf4ce163a05",
  "state": null,
  "propertySources": [
    {
      "name": "https://github.com/zahidhasanpapon/spring-cloud-config-props.git/test-application-client.yml",
      "source": {
        "greeting": "Hello, World!"
      }
    }
  ]
}
