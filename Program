// Will Z 2021
//Project: TWL

using Azure.Storage.Blobs;
using Azure.Storage.Blobs.Models;
using System;
using System.IO;
using System.Threading.Tasks;

namespace TWLSERVER
{
    class Program
    {
        static async Task Main()
        {
            System.Net.WebClient wc = new System.Net.WebClient();
            string webData = wc.DownloadString("https://twlupload.blob.core.windows.net/images/OpenCore_Install_Resources.txt"); //Get key
            Console.WriteLine(webData);
        }

    }
}
