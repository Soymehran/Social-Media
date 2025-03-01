### **SQL Queries for Social Network Management**  

#### **1. Remove `date_joined` Column from `users` Table**  
Since security is not a concern, remove the `date_joined` column permanently so that new users do not have a join date.  

#### **2. Update Email for `user3`**  
Change the email of the user with the username `user3` to `new3@example.com`.  

#### **3. Add `@` to All Usernames**  
Modify the `username` column in the `users` table by adding `@` at the beginning of each username.  

#### **4. Insert a New User**  
Insert a new user with the following details:  
- `username`: `@user4`  
- `password`: `password4`  
- `email`: `user4@example.com`  

#### **5. Retrieve All Information for `@user4`**  
Fetch all details of the user with the username `@user4`.  

#### **6. Censor the Word "hate" in Comments**  
Replace every occurrence of the word "hate" in the `content` column of the `comment` table with `****`.
