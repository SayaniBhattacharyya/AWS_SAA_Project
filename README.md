# AWS_SAA_Project

Scenario
Your company wants to distribute their content in the form of a website to their global offices. However, due to some legal restrictions, you cannot distribute the content in France and Australia. You need to find a way to prevent these offices from accessing the data.
The content does not change very often; however, some of the files are very large, and you have to find a solution to minimize end user latency.
The last requirement is that the audit department wants to track whoever is accessing the website.
Goals of the project
 Set up a static website using Amazon S3.
o Create a bucket and enable static website hosting.
o Enable logging.
 Set up a CloudFront distribution for the static website with Access Logs enabled.
 Set up Geo Restrictions to prevent users in France and Australia from accessing the data.
 Verify that logging is working.
