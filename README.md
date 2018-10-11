# Microsoft.SqlServer.IntegrationServices.Build
Project based on https://archive.codeplex.com/?p=sqlsrvintegrationsrv​​

This version can compile the Microsoft.SqlServer.IntegrationServices.Build.dll for SQL Server 2016 and Visual Studio 2017 Professional

You must change the directory of DLL if you change SQL Server version or Visual Studio (version or edition)

Once this DLL is generated, you have to install it in the folder : 
C:\Program Files (x86)\Microsoft Visual Studio\2017\Professional\Common7\IDE\PrivateAssemblies​. 
We must take all the DLLs that are in the Release folder after compilation.
