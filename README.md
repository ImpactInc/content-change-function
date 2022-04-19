
# Content Change Google Cloud Function

A Golang cloud function that compares website Content



## Authors

- [@ewaldvanrooyen](https://github.com/Ewald-Van-Rooyen-Impact)


## Documentation

[Documentation](https://impact.atlassian.net/wiki/spaces/CIND/pages/3159195659/Google+Cloud+Function)


## Deployment

To deploy this project run

```bash
  gcloud functions deploy ContentChangeFunction \
--runtime go116 --trigger-http
```


## Resources

- [Google Cloud Function Go Tutorial](https://cloud.google.com/blog/products/application-development/cloud-functions-go-1-11-is-now-a-supported-language)
- [Local Development](https://github.com/GoogleCloudPlatform/functions-framework-go#quickstart-hello-world-on-your-local-machine)

