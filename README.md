<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
</head>
<body>
  <h1>Working Links for the Project:</h1>
  <ul>
    <li>Web Application hosted on Azure: <a href="http://172.191.80.84/azure/index.php"> Ethnic_jewellery </a></li>
    <li>Github Repository: <a href="https://github.com/02vandup11/Azureproject">Azure_Project_Repository </a></li>
    <li>Project Documentation With Project Videos: <a href="https://drive.google.com/drive/folders/1QYfl4MXiELvct8XdxBHmDFbHIdRq7oL7?usp=drive_link">Drive_Link</a></li>
    <li>Short video: <a href="https://drive.google.com/file/d/1PY8rf1ET0PnV9oib_l4CeidmPo5eMgOd/view?usp=drive_link">Short_VIDEO_LINK</a></li>
    <li>Full detailed video: <a href="https://drive.google.com/file/d/16IsMfVojNo19QESLVvWTlCcTMOaMkPdF/view?usp=drive_link">Detailed_VIDEO_LINK</a></li>
    <li>Documentation: <a href="https://drive.google.com/file/d/1vZPU6xKs59phGIsBm339peQhnVS8wvx4/view?usp=drive_link">Documentation_pdf</a></li>
  </ul>
  <hr>

  <h1>Project Summary:</h1>
  <p>
    The project is an e-commerce platform designed as an online jewellery store, enabling users to browse, search, buy, pay, and update their profiles seamlessly. Leveraging various Azure and AI services, it provides a reliable, efficient, and user-friendly experience. Key features include an intuitive interface, comprehensive Azure integration with virtual machines for hosting, monitoring services for system performance, backup and restore services to protect data, file share services for collaboration, and log analytics for insights. AI services, such as an AI ChatBot, enhance customer support. The notification system ensures users receive emails and SMS alerts for operations and critical actions. Regular backups and quick restoration options ensure data safety, while continuous monitoring maintains system health. This integration of technology enhances operational efficiency, boosts customer satisfaction, and supports business growth.
  </p>
  <hr>

  <h1>Overview:</h1>
  <p>
    Our e-commerce platform seamlessly integrates various Azure components to deliver a reliable, efficient, and user-friendly experience. Azure VMs host our platform, providing scalable computing power to handle user traffic and workload fluctuations effectively. Azure monitoring services track system performance and user interactions in real-time, logging and monitoring operations for performance and security. These events trigger alerts via email or SMS to keep stakeholders informed. Azure's backup and restore services ensure the safety of our data with regular backups and quick restoration options. Azure file shares facilitate seamless collaboration among team members, while Azure Log Analytics offers valuable insights into system behaviour and user activity. An AI-powered chatbot enhances customer support, reducing the workload on human agents and improving overall efficiency and customer satisfaction. This integration ensures operational excellence, data security, and enhanced user engagement, with a monitoring and notification system providing timely alerts for critical actions, enabling proactive response and ensuring a smooth user experience.
  </p>
  <hr>

  <h1>Azure Services Used:</h1>
  <h2>1. Virtual Machine (VM) and Deployment in VM</h2>
  <h3>Virtual Machine (VM):</h3>
  <ul>
    <li><strong>Definition:</strong> A VM is an emulation of a computer system. It runs an operating system and applications just like a physical computer.</li>
    <li><strong>Role:</strong> In your project, VMs are used to host your AI services and other applications, providing a scalable and flexible environment.</li>
  </ul>
  <h3>Deployment in VM:</h3>
  <ul>
    <li><strong>Definition:</strong> This involves installing and configuring software applications and services on a VM.</li>
    <li><strong>Role:</strong> Ensures that your AI service chatbot and other applications are up and running within the VM environment.</li>
  </ul>

  <h2>2. AI Service Chatbot</h2>
  <ul>
    <li><strong>Definition:</strong> An AI chatbot is a software application that uses artificial intelligence to conduct conversations with users through text or voice.</li>
    <li><strong>Role:</strong> Provides automated customer support, information retrieval, and user interaction in your project.</li>
  </ul>

  <h2>3. Monitoring and Alert</h2>
  <ul>
    <li><strong>Definition:</strong> Monitoring involves tracking the performance and health of your applications and infrastructure. Alerts are notifications triggered by specific conditions or thresholds.</li>
    <li><strong>Role:</strong> Ensures the reliability and performance of your AI services by notifying you of issues that require attention.</li>
  </ul>

  <h2>4. Log Analytics Workspace</h2>
  <ul>
    <li><strong>Definition:</strong> A Log Analytics Workspace is a centralized repository for collecting, analyzing, and querying log data from various sources.</li>
    <li><strong>Role:</strong> Helps in monitoring, troubleshooting, and gaining insights into the performance and health of your AI services and infrastructure.</li>
  </ul>

  <h2>5. File Share</h2>
  <ul>
    <li><strong>Definition:</strong> A file share is a network shared folder that can be accessed by multiple users and systems.</li>
    <li><strong>Role:</strong> Provides a common storage space for files that need to be accessed or shared across your AI services and VMs.</li>
  </ul>

  <h2>6. Backup and Restore through Service Vaults of VM</h2>
  <h3>Backup:</h3>
  <ul>
    <li><strong>Definition:</strong> The process of creating copies of data to protect against data loss.</li>
    <li><strong>Role:</strong> Ensures data protection and disaster recovery for your VMs and their applications.</li>
  </ul>
  <h3>Restore:</h3>
  <ul>
    <li><strong>Definition:</strong> The process of retrieving data from backups.</li>
    <li><strong>Role:</strong> Allows recovery of data in case of accidental deletion, corruption, or other data loss scenarios.</li>
  </ul>
  <h3>Service Vaults:</h3>
  <ul>
    <li><strong>Definition:</strong> Specialized storage locations used for securely storing backup data.</li>
    <li><strong>Role:</strong> Provides a secure and reliable repository for backup data of your VMs.</li>
  </ul>

  <h2>7. Storage Account Container</h2>
  <ul>
    <li><strong>Definition:</strong> A container within a storage account is a grouping of blobs (binary large objects), which can store unstructured data like text or binary data.</li>
    <li><strong>Role:</strong> Organizes and manages the storage of data used by your AI services.</li>
  </ul>

  <h2>8. Storage Account with Soft Delete, Change the Date of Soft Delete, and Versioning</h2>
  <h3>Storage Account:</h3>
  <ul>
    <li><strong>Definition:</strong> A storage account provides a unique namespace in Azure for your data objects.</li>
    <li><strong>Role:</strong> Houses all your Azure Storage data objects, including blobs, file shares, queues, and tables.</li>
  </ul>
  <h3>Soft Delete:</h3>
  <ul>
    <li><strong>Definition:</strong> A feature that temporarily retains deleted data, allowing recovery within a specified retention period.</li>
    <li><strong>Role:</strong> Protects against accidental deletions by allowing you to restore deleted data.</li>
  </ul>
  <h3>Change the Date of Soft Delete:</h3>
  <ul>
    <li><strong>Definition:</strong> Adjusting the retention period for soft deleted data.</li>
    <li><strong>Role:</strong> Gives you flexibility in managing how long deleted data is retained.</li>
  </ul>
  <h3>Versioning:</h3>
  <ul>
    <li><strong>Definition:</strong> A feature that maintains previous versions of data objects, enabling recovery of earlier versions.</li>
    <li><strong>Role:</strong> Allows you to revert to previous states of your data in case of accidental changes or corruption.</li>
  </ul>
  <hr>

  <h1>Web Technologies Used:</h1>
  <ul>
    <li>HTML</li>
    <li>PHP</li>
    <li>JS</li>
    <li>TAILWIND CSS</li>
  </ul>
  <hr>

  <h1>Resource Visualizer:</h1>
  
  ![RES](https://github.com/02vandup11/Azureproject/assets/138954560/444048a6-3171-43d5-9e53-9a4f33c25626)
<hr>

  <h1>Azure Resources Overview:</h1>
  <h2>1. Virtual Machine and Deployment</h2>
  <hr>
  
   ![image](https://github.com/02vandup11/Azureproject/assets/138954560/0f0d1481-a8a7-4b7d-bbff-034b8fa2201c)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/bcee7a1d-caec-445f-afc8-286cbeb1212b)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/a61197b0-fd35-4787-85ce-d3c0f9c23e7b)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/3a006afa-106f-4d95-8398-0914c08e6263)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/de607b6c-610b-4ac4-9ae6-fe336e0c1716)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/2f2813fd-d0c7-45ea-b62b-bc7d692b72a3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6dcaec8b-4e30-4cde-84a3-26d0124b4b03)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6dc22f8a-3988-4a04-ad39-cbfc75894879)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0e34c5f9-ed63-4a08-8115-2eae78edcfaf)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/b0228a17-92a1-41a5-a010-b91aafc3b8cf)
<hr>

 <h2>2. AI Service Chatbot</h2>
 <hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/c2cfda09-64d3-482e-8042-97c150905600)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/20216bc6-74d0-488d-9db2-d49a4396abc6)
  ![image](https://github.com/02vandup11/Azureproject/assets/138954560/34a93533-fc62-418a-a30d-6712bf26843a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/67d4f25b-8686-4105-8424-9bc53a5a1deb)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6fec991b-4d69-4df5-9169-14c74d8eff96)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/7657b039-b86a-4964-9ffd-b95255d97be3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/fa58463d-e39e-42e0-8b17-3cdef27d1fac)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/69b2628d-ec4b-49b5-8efa-b15032e15a55)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/9eb7bffa-3132-45e0-9c1d-35c2c37b71ab)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0bfc6664-bc82-4d2d-bb2d-958a0f674b43)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/f54eb293-c8d7-462e-90f4-9bcdbf03f095)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/d2b3c899-061b-40a9-9d91-0468e2c8a4f7)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/71bd666c-c134-4ced-8e2f-7c66a025489f)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e0c36392-f3f8-4218-b015-12f88d62c0cd)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/dedd3fc6-4c6c-4dda-ab88-b7dce0e917a6)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/deee60d1-0669-4900-b8e5-c5c9c2e674ed)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ddc6b826-fa16-4d68-95ac-6584929dc05a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/364ba538-9865-4b09-8086-f2467c0756c3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/91f8546c-fc7d-4897-82d7-d8fdc7459d6d)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/616dc4d1-dabd-4d58-b34f-502212dbc406)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e1929322-dd0c-486a-8ebc-4c8b8bc6baaa)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/5b20c8f6-1ee5-4e4b-ac1f-795437196c53)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/207af198-8071-43a7-88e1-620e95dfef85)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/0d7589cb-7354-4fd1-9a87-8f6d9895f398)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ce366d2e-6b5a-4569-aa66-ed614c71236a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/e845398f-c81a-48fb-9aa8-163f80bacaf4)
<hr>

   <h2>3)	Monitoring and Alert</h2>
<hr>
      
![image](https://github.com/02vandup11/Azureproject/assets/138954560/3e9266a4-b799-48dc-825d-0c32bd8f0e9a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/fe2606e3-7305-46e6-a021-177572d7d8ba)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/03c1543a-fa9d-4c54-abc4-14832d5b06fa)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/8c3d5700-6ff0-4ddd-8af4-66d0da8b6730)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/73e39929-20d2-42c4-b003-0db3e9964b95)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/be7eed2d-6d32-40e4-8e1e-273a0ff0a1ea)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/ff7247c6-5c2d-4fab-ae0d-4a3bfbf0cf17)
<hr>

  <h2> 4)	Log Analytics Workspace</h2>
<hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/9efd296a-180f-4404-8efe-dc110c2e5be8)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6d2e8561-84b2-41ad-b4f0-8a02a8e11b7b)
<hr>

  <h2> 5)	File Share </h2>
<hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/6a0dc95d-b884-4aaf-8f5c-07b54ff139be)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/d1a01f5c-933d-44ad-a269-a9e25af0b84a)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/5964ac79-10c4-4679-9613-621a46398eaa)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/156acb67-3b9d-40e8-ba94-e57ab5fa6dec)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/8cfa371b-b9ef-497f-9f48-e84ee411efe0)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/63bce8bd-92d4-4a33-a2d6-079ca12956a4)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/5c29f344-57d1-432d-9251-fd5ba9994750)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/d8cd3549-95b1-4ed0-bb82-0d768517dcf2)
<hr>

  <h2> 6)	Backup and Restore through Service Vaults of VM </h2>
<hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/c2784cae-dddd-4e30-a3af-cadb7aff97ca)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/6b085622-d880-45ce-8033-92ea210077bc)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/db9a8ee9-b282-4862-9aef-80ba3b2df694)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/9184f2af-ad19-49ae-8673-fd67d375efad)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/a09020ba-02f9-4153-9f07-cfce45dbcc2e)

  <h2> 7)	Storage Account Container </h2>
<hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/16e5d565-8fc6-44d5-afd6-c4917982f956)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/4631571c-d224-46d7-af08-4440d784c7eb)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/778cd9cd-0282-4a19-9401-3d8a6cf85db9)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/affc39ed-e8b1-49ad-9620-d3146ce855b3)
<hr>
 <h2> 8)	Storage Account with Soft Delete, Change the Date of Soft Delete, and Versioning </h2>
<hr>

![image](https://github.com/02vandup11/Azureproject/assets/138954560/90b8b28b-cfe9-4635-8946-bd2e5e1e4683)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/9edcc5ef-611a-4abd-8a3a-4794467a35b3)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/85e79a8d-a4b8-4832-a28b-5894dbf58b50)
![image](https://github.com/02vandup11/Azureproject/assets/138954560/707d1617-ea85-4dc7-a683-c8fda77b03fa)

•	For Screenshots and proper project information how it is create please refer the drive file attached.
<hr>
<h2> WebSite Preview: </h2>
<hr>

![Screenshot (47)](https://github.com/02vandup11/Azureproject/assets/138954560/4b430ee5-604f-446c-a0e4-e1b846fd5c3b)
![Screenshot (48)](https://github.com/02vandup11/Azureproject/assets/138954560/ab4eeab9-2f85-4798-b603-111afaa92445)
![Screenshot (49)](https://github.com/02vandup11/Azureproject/assets/138954560/a8f95d64-4ec8-4317-8573-0f2f5e3a5732)
![Screenshot (50)](https://github.com/02vandup11/Azureproject/assets/138954560/0ea0c0f4-80bd-48f9-829b-f18fa44d913d)
![Screenshot (51)](https://github.com/02vandup11/Azureproject/assets/138954560/59336f8d-a8d9-462a-94f5-2ec9d682c7e9)
![Screenshot (52)](https://github.com/02vandup11/Azureproject/assets/138954560/fb42c036-3b3f-4016-b2ad-6e444a72499b)
![Screenshot (53)](https://github.com/02vandup11/Azureproject/assets/138954560/1ab6da90-fde7-4d5a-ae3c-920470cf667e)
![Screenshot (54)](https://github.com/02vandup11/Azureproject/assets/138954560/f314cf4c-ca1e-4b8e-a4b2-356aaad9b79e)
![Screenshot (55)](https://github.com/02vandup11/Azureproject/assets/138954560/fe3b90a2-5abf-40dc-aa4e-974da033c9df)
![Screenshot (56)](https://github.com/02vandup11/Azureproject/assets/138954560/575fcd17-4459-4c6d-b6f9-5cd3dbd6f928)
![Screenshot (57)](https://github.com/02vandup11/Azureproject/assets/138954560/bf3e09f3-4320-495f-816f-3049856c9ae5)
![Screenshot (58)](https://github.com/02vandup11/Azureproject/assets/138954560/ec545deb-64bc-448c-8fac-d27237929268)
![Screenshot (59)](https://github.com/02vandup11/Azureproject/assets/138954560/26d8bdd4-cbc5-4a69-accd-cf211951dff3)
![Screenshot (60)](https://github.com/02vandup11/Azureproject/assets/138954560/e25215a2-f820-4929-a26a-e3fba1904d3c)
![Screenshot (61)](https://github.com/02vandup11/Azureproject/assets/138954560/d3f61ff4-7d39-42b7-ab25-59b4351415f4)
![Screenshot (62)](https://github.com/02vandup11/Azureproject/assets/138954560/c31712a3-5a75-4371-95e0-c983b82e4ee2)
![Screenshot (63)](https://github.com/02vandup11/Azureproject/assets/138954560/bc59c39b-b5d0-4f03-aaab-0e9ed90e3b7e)
![Screenshot (64)](https://github.com/02vandup11/Azureproject/assets/138954560/b9c3155d-2ba0-4f0d-8cfc-fd04cda8e6f8)
![Screenshot (65)](https://github.com/02vandup11/Azureproject/assets/138954560/ac91eb82-6065-4d7a-9c7e-277d72f41a30)
![Screenshot (66)](https://github.com/02vandup11/Azureproject/assets/138954560/f5e24891-a7a0-4ea5-86bb-87e0fe27c40f)
![Screenshot (67)](https://github.com/02vandup11/Azureproject/assets/138954560/a720cd91-e3c4-4519-84ec-8b1c81b3500a)
<hr>

<strong> THANK YOU !!!! </strong>
</body>
</html>











