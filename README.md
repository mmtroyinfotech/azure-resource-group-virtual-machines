<p align="center">

</p>

<h1>Microsoft Azure Resource Groups and Virtual Machines</h1>
In this tutorial, we will create Microsoft Azure Resource Group and Virtual Machines. <br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure Resource Groups
- Azure Virtual Machines

<h2>Operating Systems Used </h2>

- Windows 10 Pro, verison 22H2

<h2>Create a Resource Group:</h2>

- Sign into azure portal and type Resource Groups in the search bar. Click on "Resource groups".
  
<p>  
<img src="https://imgur.com/SXhn5to.png"/>
</p>

- Click on "Create" or "+ Add."

<p> 
<img src="https://imgur.com/alN5XYF.png"/>
</p>

- Enter a name for your resource group.
- Select a region where you want to store the resource group's metadata.
- Click "Review + create" and then "Create" to finalize the creation.
<p> 
<img src="https://imgur.com/lcAZ9f4.png"/>
</p>
<br />
<h2>Create a Virtual Machine (VM):</h2>

- Type Virtual Machines in the search, click on "Virtual machines".
<p>
<img src="https://imgur.com/uMadCp2.png"/>
</p>

- Select "Create" and then "Azure Virtual Machine".
<p>
<img src="https://imgur.com/StsRCX1.png"/>
<img src="https://imgur.com/LEa3Zhe.png"/>
</p>

- Click Resource Group and select the resource group you created prior.
- Name your Virtual Machine
- select the same region as the resource group. 
<p>
<img src="https://imgur.com/4W7gvKa.png"/>
</p>

- Image refer to Operatiing System. Click and choose desired OS.
- Next pick your size. Recommended 2 or more vcpus. But I think free subscriptions only have 1.
<p>
<img src="https://imgur.com/hoziqTj.png"/>
</p>

- Create Username and Password
- Be sure RDP (3389) is selected for inbound ports
<p>
<img src="https://imgur.com/xQwiq8e.png"/>
</p>

- Check Licensing Box
- Click Next: Disks
<p>
<img src="https://imgur.com/PQAbasA.png"/>
</p>

- Skip Disk Setup
- Click Next: Networking 
<p>
<img src="https://imgur.com/YtXwZWd.png"/>
</p>
<br />

<h2>Configure Networking:</h2>

- Here's where you setup Vnet(Virtual Network) and Subnet.
- Best for operating multiple virtual machines to communicate on the same network.
<p>
<img src="https://imgur.com/8e9httz.png"/>
</p>

Select the virtual network (VNet) and subnet where the VM will reside.

Configure public IP and inbound port rules as needed.
- Review and Create:
- Review the VM settings and click "Create" to deploy the VM.
3. Manage and Monitor
