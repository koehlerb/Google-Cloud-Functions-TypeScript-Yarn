# Google Cloud Functions TypeScript Yarn

This is a simple Google Cloud Function written in the TypeScript
language and using the Yarn package manager. It can be
deployed using a command similar to the following:

```shell
gcloud functions deploy hello \
    --gen2 \
    --runtime=nodejs18 \
    --region=us-west1 \
    --source=. \
    --entry-point=hello \
    --trigger-http \
    --allow-unauthenticated
```
