# System Information Report Script  

## 📌 Project Title  
**System Information Report Script**  

## 🎯 Objective  
Automate the collection of system and network information for troubleshooting.  

## 🛠️ Tools & Environment  
- **Operating System:** Windows  
- **Script Type:** Batch Script (`.bat`)  

## 📜 Script Example  
```bat
@echo off
echo Collecting system information...

systeminfo > %USERPROFILE%\Desktop\SystemReport.txt
ipconfig /all >> %USERPROFILE%\Desktop\SystemReport.txt

echo Report saved on Desktop as SystemReport.txt
pause
```

## 🚀 Steps to Run  
1. Open **Notepad** and paste the script.  
2. Save the file with a `.bat` extension (e.g., `SystemReport.bat`).  
3. Right-click the `.bat` file and select **Run as Administrator**.  
4. Observe the script executing in the Command Prompt.  
5. Verify that `SystemReport.txt` is created on the Desktop.  
6. Open the file to confirm system and network details are included.  

## ✅ Results  
- A system report (`SystemReport.txt`) is generated on the desktop containing system and network details.  

## ⚠️ Issues & Fixes  
- **Issue:** Script did not run properly when double-clicked due to administrative privileges required.  
- **Fix:** Run the `.bat` file as Administrator.  

## 🔮 Future Improvements  
- Automatically include date and time in the filename (e.g., `SystemReport_2025-09-05.txt`).  
- Add additional checks (disk usage, memory status, etc.).  
- Redirect errors to a separate log file for troubleshooting.  

## 📚 Key Learning  
Learned how to use batch scripting to automate IT support tasks.  
