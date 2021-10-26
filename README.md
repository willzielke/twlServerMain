# TWL Server (.NET, NodeJs, Azure Blob Storage, Azure VM)

  Project: **Together We Learn**

  Made In: Porter Gaud CS Dept.
  
  Website Homepage (Blob Storage): https://twlazure.z13.web.core.windows.net/
  
  Website Homepage (NodeJS upload service): http://52.170.35.138:80  

**Description:**

   Uses .NET (Windows side) to upload and download .txt documents to Azure Blob Storage. (Setup account for the POC, and for the project) Currently working on Node.js implementation to upload from the TWL Azure Static website. Essently teachers can upload unity scenes or links for their lessons. POC is currently working on a localhost server. Need to deploy to Azure. Also need to add code to handle the delivery of the assets for the VR headsets. (Unity3d) Need oculus testing.

**Prerequisites:**

        Install .NET SDK (5.0.402 TESTED)
        Install Node.JS

**Instructions (.NET implementation):**
        
INSERT in cmd:
        
        dotnet new console -n TWLSERVER (Creates project)

        cd TWLSERVER (goes to project folder)

        mkdir data (creates the subdir "data" in the project folder)

        dotnet add package Azure.Storage.Blobs (Adds the package responsible for Blob storage uploading/downloading)

Copy "Program.cs" to the created Directory

INSERT in cmd:

        dotnet build (builds app)

        dotnet run (runs app)
        
**Instructions (NodeJs implementation):**
        
        Pending (Assets attached are not exhustive)
        
        
**Helpful Links:**
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website
        https://docs.microsoft.com/en-us/azure/storage/blobs/quickstart-blobs-javascript-browser
