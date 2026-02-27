# Useful Information

## Bucket Policy to Allow Public Access
```json
{
	"Version": "2012-10-17",
	"Statement": [
		{
			"Effect": "Allow",
			"Principal": "*",
			"Action": "s3:GetObject",
			"Resource": "arn:aws:s3:::YOUR_BUCKET_NAME/*"
		}
	]
}
```

## Steps to Change the Bucket Policy
- Navigate to your Console Home and find S3, either from your recently visited or through the 'All Services' tab. 
- Click on the name or icon to enter into your S3 Dashboard.
- Under 'General Purpose Buckets' click on the name of the bucket whose policy you want to change
- Click on the 'Permissions' tab and scroll down to the 'Bucket Policy' section ![Step 4](https://finalprojectfordevops.s3.us-east-1.amazonaws.com/permissions.png)
- Click the 'Edit Policy' button and paste the policy above into the text area, replacing YOUR_BUCKET_NAME with the name of your bucket ![Step 5](https://finalprojectfordevops.s3.us-east-1.amazonaws.com/bucketpolicy.png)
- Scroll down to the bottom of the page, ignore the error, and click the 'Save Changes' Button.

