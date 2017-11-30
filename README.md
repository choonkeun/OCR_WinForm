# OCR_WinForm
OCR using Tesseract 3.04 version

#--- How to Use

===============================================
Dot net 4.5.2, Visual Studion 2013 C#
===============================================

1. Prepare tessdata
    C:\Tesseract-OCR\tessdata

2. Prepare all DLLs (x64: C:\Windows\System32\ and x86: C:\Windows\SysWOW64\)
    VCRuntime140.dll
    api-ms-win-crt-heap-11-1-0.dll      
    api-ms-win-crt-math-l1-1-0.dll      
    api-ms-win-crt-string-l1-1-0.dll    
    api-ms-win-crt-studio-l1-1-0.dll    
    api-ms-win-crt-utility-l1-1-0.dll   
    api-ms-win-crt-runtime-l1-1-0.dll   
    api-ms-win-crt-convert-l1-1-0.dll   
    api-ms-win-crt-time-l1-1-0.dll      
    api-ms-win-crt-environment-l1-1-0.dll
    api-ms-win-crt-filesystem-l1-1-0.dll

3. Install "vc_redist.x64.exe"

4. Under bin\debug\x64 and debug\x32
    "liblept172.dll" for platform x64
    "libtesseract304.dll"
