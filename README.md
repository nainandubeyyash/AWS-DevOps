# AWS-DevOps
Tasks &amp; practical I have done till date on AWS &amp; DevOps

## 1)Virtual Machine Configuration: 

##### Virtual machine: A compute resource that uses software instead of a physical computer to run programs and deploy apps
#### Steps includes:
(i)Download latest version of Virtual machine in your system from : https://www.virtualbox.org/

(ii)Download any latest Linux server for example for Ubuntu: https://ubuntu.com/download/server

(iii)Create VM, provide a name, select machine folder, chose type & version of OS:
![image](https://user-images.githubusercontent.com/108335056/213415587-e83cc9f1-678b-4453-9cdb-582fc5affcc9.png)

(iv)Provide memory size,then create a Virtual Hard Disk, choose Hard Diak file type as VDI:
![image](https://user-images.githubusercontent.com/108335056/213416011-b70a2d65-4670-44cf-94fb-0f327e6efb05.png)
![image](https://user-images.githubusercontent.com/108335056/213416073-e308163c-e3e7-41f0-a4b2-5347e27b0f1e.png)
![image](https://user-images.githubusercontent.com/108335056/213416410-59abe96b-8218-4d89-8506-7558bbeec957.png)

(v)Start the created VM & do the storage configuration:
![image](https://user-images.githubusercontent.com/108335056/213416656-a6fc6bcf-512f-4269-b0fe-a2f8b8cbd35c.png)
Then setup user profile:
![image](https://user-images.githubusercontent.com/108335056/213416830-658f143e-692d-40f9-8935-2b2fa76fe260.png)
We can also create as many users as we want in our VM through useradd _username_ & can delete the user by command userdel _username_

This is how we can configure our first VM.
