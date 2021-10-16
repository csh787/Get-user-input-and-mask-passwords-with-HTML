# batch-file-will-create-a-web-page
batch file will create a web page, then use Visual Basic Scripting and the Windows Scripting Host to launch Internet Explorer to show that page.
:: This batch file will create a web page, then use 
:: Visual Basic Scripting and the Windows Scripting Host 
:: to launch Internet Explorer to show that page.
:: Values entered in the web page will be read via
:: scripting, then will be saved as %TEMP%\USERIN.BAT
:: After the USERIN.BAT is CALLed from the main batch 
:: (and assuming there is enough room in the environment)
:: environmental variables USERNAME and PASSWORD will be set.
:: It is your responsibility to delete the USERIN.BAT
:: after you CALL it. Because this batch file needs to
:: find itself, you must be sure to call it from your 
:: main batch file with a full path and file name.
:: Written and tested under Win95. NT/2000/XP users will
:: have to do some modifications before it will work.
:: For example, %0 changes to %f0
:: Public Domain. Use freely. No guarantees! It may not work!
:: http://www.ericphelps.com
