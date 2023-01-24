#Static Website Hosting On AWS S3
A simple project on how to host a static website on AWS S3

#TASKS
Clone a the GitHub repo containing the static website files
Navigate to your AWS management console
Under your services, click S3
Click "create an S3 Bucket"
Upon Creation of the S3 bucket ,"Unblock the IP address to allow access"
Then "Create"
After Creating the Bucket, Under your bucket permission, update your bucket policy with this JSON script { "Version": "2012-10-17", "Statement": [ { "Sid": "PublicReadGetObject", "Effect": "Allow", "Principal": "", "Action": [ "s3:GetObject" ], "Resource": [ "arn:aws:s3:::Bucket-Name/" ] } ] }
Update the bucket name with the name of your bucket
Under your objects click "Upload folder"
Upload the website files
After uploading click Index.html
Copy the object URL the paste in a browser
"THE END"
