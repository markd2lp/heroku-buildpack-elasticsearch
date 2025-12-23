# Heroku Buildpack for Elasticsearch 7.10.2

A custom Heroku buildpack that installs Elasticsearch 7.10.2 for Heroku CI.

## Usage

Add to your `app.json`:

```json
{
  "buildpacks": [
    {
      "url": "https://github.com/markd2lp/heroku-buildpack-elasticsearch"
    }
  ]
}
