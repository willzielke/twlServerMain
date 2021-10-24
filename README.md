# TWL-Server-.NET-Azure-

  Designer/Developer: Will Zielke

  Project: **Together We Learn**

  Made for: Porter Gaud CS Dept.
  
  Website Homepage: https://twlazure.z13.web.core.windows.net/

**Description:**

   Uses .NET (Windows side) to upload and download .txt documents to Azure Blob Storage. (Setup account for the POC, and for the project) Currently working on Unity scene uploads as well (for showcase). 

**Prerequisites:**

        Install .NET SDK (5.0.402 TESTED)

**Instructions:**
        
INSERT in cmd:
        
        dotnet new console -n TWLSERVER (Creates project)

        cd TWLSERVER (goes to project folder)

        mkdir data (creates the subdir "data" in the project folder)

        dotnet add package Azure.Storage.Blobs (Adds the package responsible for Blob storage uploading/downloading)

Copy "Program.cs" to the created Directory

INSERT in cmd:

        dotnet build (builds app)

        dotnet run (runs app)
        
**Helpful Links:**
        https://docs.microsoft.com/en-us/azure/storage/blobs/storage-quickstart-blobs-dotnet
