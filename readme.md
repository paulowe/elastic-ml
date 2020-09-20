# Elastic-ML

> Integrate machine learning into your application with a variety of our APIs

This project "saasifies" an example serverless REST API built on AWS. It uses a standard [OpenAPI](https://swagger.io/specification/) spec to describe the API's endpoints.

Saasify (a different service) acts as a proxy in front of this external API to handle auth, billing, rate limiting, etc. This allows the backend API to focus solely on the product's unique value proposition.


_Note that an OpenAPI spec is no longer required to use Saasify_. Including an OpenAPI spec allows Saasify to auto-generate API docs for your product. It also allows Saasify to perform additional validation as it proxies HTTP calls to your backend API.

See our [quick start](https://docs.saasify.sh/#/quick-start) for a walkthrough of how to get started and our [OpenAPI guide](https://docs.saasify.sh/#/openapi) for more information on generating your own OpenAPI spec.

## License

MIT © [paulowe](https://github.com/paulowe)
