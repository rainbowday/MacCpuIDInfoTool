# MacCpuIDInfoTool  
### 特定场景应用：机器及授权信息查看工具  
**功能描述**：本MFC项目为读取特定机器码文件和授权信息文件加解密小工具，运用的是openssl开源库。  
**目录结构**：  
　|----**include**：项目所需的openssl开源库头文件  
　|----**lib32**：项目依赖的openssl静态库文件(32位)  
　|----**lib64**：同上(64位)  
　|----**res**：应用程序的图标等资源文件  
　|----**Test**：提供的测试文件  
　|　　　|----GetLicenseInfo：机器码文件  
　|　　　|----LicenceFile：授权信息文件  
　|----***.cpp/ \*.h/ \*.vcxproj**：源文件、头文件、项目文件等  

