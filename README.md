# aws-storage-services.
i created an s3bucket , configured it, created an object, made it public then deleted them. 
i uploaded html files on a new created bucket. but couldnt acess the website because it wasnt secure even though i made them public. the html file was for meentee Ada Chukwu
i had to install aws cli , created an IAM user and connected it with my git bash by inputing the acess key, secret key and region. i had to grant admisitration acess at aws IAM in order to compute.
aws s3 mb s3://bucket-name/  =to make bucket
aws s3 ls to list 
aws configure    = to configure
aws s3 cp file.txt s3://your-bucket-name/   = to upload file
aws s3 rm file.txt s3://your-bucket-name or file-name/  = top remove bucket or object.
e.t.c
