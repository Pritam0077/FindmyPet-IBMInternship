# FindmyPet
Deploying Static Website on Amazon S3 By: Cloud Computing-Team 06,ByteCoders

website link-

### What is Static Website? 

- Static Websites are series of HTML pages each that represents separate webpages for the website and the information remains same for all the users. 
- This kind of Websites are generally made with HTML and CSS.  

Technologies we are going to use for the deployment of static website 

- HTML (Hypertext Markup Language) 
  - HTML is a markup language that is going to describe the structure of the website. It is the skeletal framework of the website 
- CSS (Cascading style sheets) 
  - CSS is a sheet style language that is used to describe the style and appearance of webpage.  
- Bootstrap  

o  Bootstrap is a free, open-source front-end development framework for the creation of websites and web apps. It is used for developing responsive application for the devices with different screen sizes 

### Structure of HTML file (DOM tree) 

![](Aspose.Words.b5431fc5-a9f4-451d-98a1-07e5f8be43c0.001.png)

### Internal Working of Website 

![](Aspose.Words.b5431fc5-a9f4-451d-98a1-07e5f8be43c0.002.png)

### How the website is reaching to us? 

![](Aspose.Words.b5431fc5-a9f4-451d-98a1-07e5f8be43c0.003.png)

### What are AWS S3 and Why Host our Static Website on AWS S3? 

- Amazon Simple Storage Service (Amazon S3) is an object storage service that offers industry- leading scalability, data availability, security, and performance. 
- For a variety of use scenarios, websites, mobile applications, backup and restore, archives, business applications, IoT devices, and big data analytics, we can store and safeguard any quantity of data using Amazon S3. 
- S3 only Hosts static Websites so there are no servers used in this case which helps in significant cut of costs in hosting websites and we do not need to incur any cost 
- It will be always available until and unless we delete the bucket. 

### How S3 Works? 

- Amazon S3 is an object storage service that stores data as objects within buckets, 

an **object** is a file and any metadata that describes the file. A **bucket** is a container for storing objects 

- To first store our Objects in S3 we need to create a bucket in S3 and specify the bucket name which must be globally unique and we need to specify the region. 
- Each object in the bucket has only one **key**, which is the unique identifier for the object within the bucket. 
- Buckets and Objects are private by default and to make it public we have to explicitly grant permissions by using bucket policy. 
- We can use versioning in S3 to keep multiple copies of the websites in the same bucket and we can create backup and retrieve the old copies anytime we want. 

S3 Structure 

![](Aspose.Words.b5431fc5-a9f4-451d-98a1-07e5f8be43c0.004.jpeg)

Our Webpage is going to be deployed in the following format 

![](Aspose.Words.b5431fc5-a9f4-451d-98a1-07e5f8be43c0.005.jpeg)
