********************Project is Related to Data Engineering using  Apache Spark and S3 **************
*Here,i extract data from data world and downloaded data which is Popular game IPL.
*Data source:https://data.world/mkhuzaima/ipl-data-till-2017
* uploaded all data into Amazon S3 where you can easily create a bucket and upload all those csv data over there.
* Give public access for your s3 bucket where you can eaily extract data.
   steps:
 1. Go to AWS S3 Console
 2. Open ipl-data-nyima
 3. Click Permissions → Bucket Policy
 4. Ensure it allows read access:
     {
  "Version": "2012-10-17",
  "Statement": [
  {
      "Effect": "Allow",
      "Principal": "*",
      "Action": "s3:GetObject",
      "Resource": "arn:aws:s3:::ipl-data-nyima/*"
    }
  ]
}

* Use data bricks platform to write all your  code for into pyspark
  which is cloud based platform built around apache spark that offers a unified analytics workspace to hande large scale data engineering and data science projects.
* In DataBrick create compute and use notebooks to write your code.

Technoogy & Tools
1.Pyspark
2.SQl
3.Python
4.Matplotlib
5.Seaborn


  ************* Thank you **************

  
