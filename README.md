#Documentation On Static Website Hosting WITH AWS S3
#STEP 1
Clone the github repository containing the website files either using your CLI or by running the command "git clone 'the link of the repo'"
#STEP 2
Navigate to your management console and under services, click S3 then create your bucket. Make sure to uncheck the box "Block all Public IP address" in order to all access, then create the bucket. After creating the bucket, navigate to permissions and click edit bucket policy with a JSON or YAML script in order to make the bucket publicly acessible through the internet.
#STEP 3
Upload the cloned repository to your recently created bucket then click on "index.html" and copy the object URL then paste it into a browser .



#The End
