
On mac you will need to run the following command in your terminal

open -n -a "Google Chrome" --args --user-data-dir=/tmp/temp_chrome_user_data_dir http://localhost:3000/ --disable-web-security

On windows run the following from within the directory of chrome

chrome.exe --disable-site-isolation-trials --disable-web-security --user-data-dir="D:\temp"
