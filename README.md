# Cloudformation

### [website.yaml](https://github.com/Aishabs/Cloudformation/blob/acf697fdcc488e838ec924fed73b0cb2b51f4dbe/website.yml) 
cloudformation stack thats create a custom VPC, two ec2 servers, two security groups, bootstrap apache2 server with default page 
and it will be publicly accessible.

</br>

---

### [ec2-instance.yaml](https://github.com/Aishabs/Cloudformation/blob/acf697fdcc488e838ec924fed73b0cb2b51f4dbe/ec2-instance.yaml) 
cloudformation stack with default IP 0.0.0.0 allow only standard IP format, allow only t2.nano, t2.micro, t2.small, t2.medium instances, public port 80 access but port 22 access only from your own IP, one instance of amazon linux Latest AMI of amazon linux taken as 
parameter and output AZ, DNS, public IP
</br>

---
###### This project was part of Saudi Digital Acadmy's ( SDA ) DevOps  BootCamp 2022 
