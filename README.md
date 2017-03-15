# manofscience.co.uk

Personal website and proto-folio of Henry Hadlow

## Installing the build tools

```
rbenv install
bundle install
```

## Running the build tools

```
jekyll build
```

## Deploying

You’ll need a copy of `s3_website.yml`. This contains security credentials, so it’s not supplied in this repo.

Then you can just type:

```
s3_website push
```
