# batch-scripting
Batch Scripting for windows
1. ```Basic Comment for Batch Script```
   - @echo on/off -> on will return the path, off will not return the path
   - Title <Basic Tile> -> This will show the CMD prompt title
   - echo <Description>
   - pause -> this will stop the execution
   - start <file(exe) || URL> -> start the execution
     
2. ```Open URL in the Chrome and msedge```
   
   ```
   @echo off
   Title Ashok BATCH
   echo Open url in the chrome and msedge
   pause
   start chrome.exe google.com get2data.com
   start msedge.exe google.com get2data.com
   ```
   
4. ```Open Website in the chrome incognito window```
   
   ```
   @echo off
   Title Ashok BAT
   echo Open url in the chrome and msedge
   pause
   echo Open then url in chrome incognito window
   start chrome.exe -incognito google.com
   ```
5. ```Open Website in the edge inprivate window```
    ```
   @echo off
   Title Ashok BATCH
   echo Open url in the chrome and msedge
   pause
   echo open msedge browser
   start msedge.exe -inprivate google.com
   ```
6. ```Open Application``` 
       ```
      @echo off
      Title Ashok BATCH
      echo Open Application
      pause      
      start notepad.exe
      ```
7. ```Open the file using the file path```
    ```
   @echo off
   Title Ashok BATCH   
   echo Open file using the path
    pause
   start /d "%windir%\system32" mspaint.exe
   ```
8. ```Move file form one folder to another folder```
    ```
   @echo off
   Title Ashok BATCH
   echo Move the file from one folder to another folder
   pause
   move "C:\Users\Ashok\Downloads\gkauditors_finance.sql" "C:\Users\Ashok\Downloads\Test"
   ```
9. ```Move all file form one folder to another folder```
    ```
   @echo off
   Title Ashok BATCH
   echo Move the all file from one folder to another folder
   pause
   move "C:\Users\Ashok\Downloads\*.sql" "C:\Users\Ashok\Downloads\Test"
   ```


