        To get saved WIFI passwords  and names using python code
       
ALGORITHM:
1. Import the subprocess module 
2. Get the metadata of the wlan(wifi) with the help of check_output method 
3. Decode the metadata and split the meta data according to the line 
4. From the decoded metadata get the names of the saved wlan networks 
5. Now for each name again get the metadata of wlan according to the name 
6. Start try and catch block and inside the try block, decode and split this metadata and get the password of the given wifi name 
7. Print the password and the wifi name and print blank if there is no password 
8. In except block if process error occurred print encoding error occurred
