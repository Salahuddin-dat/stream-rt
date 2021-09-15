# Streamlit first test
## Lets strart 

gcloud builds submit --tag gcr.io/stream-mask/Stream  --project=stream-mask
gcloud run deploy --image gcr.io/stream-mask/Stream --platform managed  --project=stream-mask --allow-unauthenticated
