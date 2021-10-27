# TWL Server (.NET, NodeJs, Azure Blob Storage, Azure VM)

  Project: **Together We Learn**

  Made In: Porter Gaud CS Dept.
  
  Website Homepage (Blob Storage): - https://togetherwelearn.z13.web.core.windows.net/
  
  Website Homepage (WEB APP + Blob Storage): https://twluploadserver.azurewebsites.net/

**Description:**

   Uses .NET (Windows side) to upload and download .txt documents to Azure Blob Storage. (Setup account for the POC, and for the project) A file upload service to Azure is currently operational. (C#)

**Prerequisites:**

        Install .NET SDK (5.0.402 TESTED)

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
        
**Instructions (Web App implementation):**
        
        https://www.c-sharpcorner.com/article/upload-and-download-file-to-azure-blob-storage-using-c-sharp/
        
        
**Helpful Links:**
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-blob-static-website
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-upload-process-images?tabs=dotnet%2Cazure-powershell
