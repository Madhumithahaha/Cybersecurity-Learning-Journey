# Access Control - July 21, 2026

## Topics learnt:
1. Security by obscurity - Using a unpredictable URL is not an effective security functionality. 
    I found the 'obscure URL'
   
    <img width="700" height="370" alt="image" src="https://github.com/user-attachments/assets/d821bbca-9c19-457d-9fab-e9614e14b12e" />

2. Parameter-based access control methods- By changing the value of a hidden field, cookie, preset query string parameter, we can override access control

    <img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/370087f1-5501-406d-9f74-f299515766b4" />       <img width="700" height="350" alt="image" src="https://github.com/user-attachments/assets/350770bb-a41f-401a-bc28-0431e2cb0457" />

3. X-Original-URL: It is a non-standard HTTP header used to over-write the original URL(when front end restricts access based on URL)
4. Method based access control: By changing request method, I was able to perform originally unauthorised actions(upgrading wiener to admin) as administrator.
   
     <img width="1857" height="916" alt="image" src="https://github.com/user-attachments/assets/6bda3b47-4bff-46ec-b532-742e58a235d1" />
     
5. IDOR: By simply changing user-parameters in the URL, I was able to access sensitive data(API key) of another user.
6. 

