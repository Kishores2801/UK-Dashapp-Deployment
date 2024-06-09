gcloud builds submit --tag gcr.io/key-sign-425907-v3/project-uk-railways  --project=key-sign-425907-v3

gcloud run deploy --image gcr.io/key-sign-425907-v3/project-uk-railways --platform managed  --project=key-sign-425907-v3 --allow-unauthenticated