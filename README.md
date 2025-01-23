Cara menerapkan:

1. Buat file `cloudwatch-cleanup.yaml` dengan konten di atas
2. Deploy menggunakan AWS CLI:
```
aws cloudformation create-stack --stack-name cloudwatch-cleanup --template-body file:///Users/rnrifai/Documents/GitHub/Jobseeker/crontjob_cloudwatch/cloudwatch-cleanup.yaml --capabilities CAPABILITY_IAM
