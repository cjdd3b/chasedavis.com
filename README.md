chasedavis.com
--------------

Code and Grunt workflow for personal website.

Setup
=====

```
git clone git@github.com:cjdd3b/chasedavis.com.git && cd chasedavis.com
npm install
bower install
grunt serve
```

Deploying
=========

First build with `grunt build` and then deploy with `grunt s3`. Be sure to export `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` environment variables with appropriate values or else S3 publishing will not work.