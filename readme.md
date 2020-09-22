# Serverless ML APIs

> Integrate machine learning into your application with a variety of our APIs

<a href="https://paulowe_elastic-ml_b304288f.saasify.sh" target="_blank"><img src="images/serverlessml.png" align="center" width="500" alt="Serverless ML APIs"></a>
<br />
Try out the <a href="http://paulowe-destination-site.s3-website.us-east-2.amazonaws.com" target="_blank"><strong>Demo here</strong></a>.


This project "saasifies" an example serverless REST API built on AWS. It uses a standard [OpenAPI](https://swagger.io/specification/) spec to describe the API's endpoints.

Saasify (a different service) acts as a proxy in front of this external API to handle auth, billing, rate limiting, etc. This allows the backend API to focus solely on the product's unique value proposition.


_Note that an OpenAPI spec is no longer required to use Saasify_. Including an OpenAPI spec allows Saasify to auto-generate API docs for your product. It also allows Saasify to perform additional validation as it proxies HTTP calls to your backend API.

See our [quick start](https://docs.saasify.sh/#/quick-start) for a walkthrough of how to get started and our [OpenAPI guide](https://docs.saasify.sh/#/openapi) for more information on generating your own OpenAPI spec.

## License

MIT © [paulowe](https://github.com/paulowe)
