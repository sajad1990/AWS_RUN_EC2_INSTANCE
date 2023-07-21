# AWS_lunch_EC2_INSTANCE & connect
we will lunch a ec2 instance and step by step connect to it throw ssh

1:Open the EC2 dashboard on the AWS Management Console.

2:Click on the "Launch instance" button to start the instance creation wizard.

![1](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/73dfe936-e160-425d-83ca-bac4eaf235ba)

3: in the next step choose a name for your instance

![2](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/c4bf896f-7fcd-4fc9-a24f-b747e1bc84ee)

4:Select an Amazon Machine Image (AMI) that suits your requirements 

![Screenshot 2023-07-20 184534](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/1fd06218-c202-420f-8419-8dfd6b92acba)

5:choose an instance type and also give a name to your key and create a key pair (we will need key pair to be able to connect to our ec2 instance )

![3](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/f0da99f1-2196-4650-b49d-b6a49204fd77)

6: create security group 

![4](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/a31a788c-dd03-42c8-b4c4-4336f8cbd3c3)

7: lunch your instance 

![5](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/046c3c1a-a230-44f3-8fdb-7b80970ed954)


8: congrats you just lunched your ec2 instance now for connecting to your ec2 instance we have to follow these steps ( connecting to ec2 instance using ssh in windows )

![6](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/ac415de0-1ccd-484d-b670-654786d955cb)



9: now we want to connect to our ec2 instance with shh for that i am going to use PuTTY 
(for download this app you just need to search it in google)
now open your PuTTY : 

![Screenshot 2023-07-20 190253](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/4519c1cb-f791-47a8-b72b-b286a0180133)

10: after that you need to go to your ec2 dashboard and check the select box beside your instance as you see in the picture and then copy that address 


![7](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/6ecda63b-d3ec-4878-9132-4992323fd944)

11: now paste it in PuTTY as you see in the picture and then add (ec2-user@) in the beginning of your public ip address as picture follows 

![10](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/bd188628-fca0-440d-a67b-aa068519a1be)


12 : in your left hand side find SSH ==> Auth ==> credentional ==> navigate to your key that you created before 

![8](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/7d865e54-734a-43f0-b442-11e19401dbcd)

13 ; now you are connected to your ec2 instance ,you can use ping command to test it as picture follow 
![11](https://github.com/sajad1990/AWS_RUN_EC2_INSTANCE/assets/93401276/27bd603b-dcb6-4a9b-b3c3-4d9f81e4e16c)
