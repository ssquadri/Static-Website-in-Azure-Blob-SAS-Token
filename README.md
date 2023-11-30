# Static-Website-in-Azure-Blob-SAS-Token

A small static website will be hosted in Azure blob storage(Container) and then we will access it directly with URL and then generate SAS token and then acess it with SAS token

Here is the Step-By-Step Guide to the project

**Step 1 -Create A Storage Account in Azure**



![1.Create Storage Account in Azure.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/1.Create%20Storage%20Account%20in%20Azure.png)



**Setp 2 -Create container (blob storage) inside Azure Storage Account**



![2.create container inside azure storage account.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/2.create%20container%20inside%20azure%20storage%20account.png) 




**Step 3 -Upload the HTML code file inside the Container**



![3.upload the HTML code file inside the container.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/3.upload%20the%20HTML%20code%20file%20inside%20the%20container.png)



**Step 4 -Once its Uploaded then click on it and then copy its URL (make Sure the container Access tier is anonymous for container and blobs)**


![4.copy url and make sure its public access.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/4.copy%20url%20and%20make%20sure%20its%20public%20access.png)



**Step 5 -Open Incognito in chrome to test the URL**



![5.open Inconito mode and paste url.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/5.open%20Inconito%20mode%20and%20paste%20url.png)



**Step 6- Paste the URL and see the website # Screenshot of Landing page is included in this repository**



![6.see the website.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/6.see%20the%20website.png)


**Step 7-Now change the Access tier to Private NO anonymous Access**



![7.change access to private.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/7.change%20access%20to%20private.png)



**Step 8 -Repeat the same process of opening and psting URL in Incognito , Website is no longer visible**



![8.after changing access to private , nothing is visible.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/8.after%20changing%20access%20to%20private%20%2C%20nothing%20is%20visible.png)


**Step 9-Now go to the HTML file in the container and create SAS token for it (SAS token is limited time & Limited access URL link)**



![9.create SAS token for limited access for limited time.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/9.create%20SAS%20token%20for%20limited%20access%20for%20limited%20time.png)




**Step 10-Copy the SAS token URL and paste in Incognito to see the result, Also note that once the time is over it will no longer be visible to after time expires.**



![10. Paste SAS token URL.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/10.%20Paste%20SAS%20token%20URL.png)





![11.SAS token URL of the HTML file.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/11.SAS%20token%20URL%20of%20the%20HTML%20file.png)




![12.azure logs of activity.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/12.azure%20logs%20of%20activity.png)




![13.once work is done delete the storage account.png](https://github.com/ssquadri/Static-Website-in-Azure-Blob-SAS-Token/blob/1bf251a818efeef90a1df2930aaeba14a5dffe48/13.once%20work%20is%20done%20delete%20the%20storage%20account.png)
