# Week-7-Codepath
(XSS) 
Version 4.1
1. create a new post 
2. enter the title, and any comments
3. hack with XSS script
4. Post it!!!
5. Get the alert message :)

![image](https://user-images.githubusercontent.com/31251224/31975680-e07c55dc-b900-11e7-8fc1-6cbb051b1cf1.png)



-- source code link: https://www.veracode.com/security/xss




(SQLI)
Version < 12.0.8
This vulnerability is caused by the lack of sanitization in user provided data.
first open up sql from terminal
![image](https://user-images.githubusercontent.com/31251224/31974764-571de22e-b8fb-11e7-8398-8521d7c3a166.png)

then look up the table for a list of users
![image](https://user-images.githubusercontent.com/31251224/31974860-b76f1ad0-b8fb-11e7-88f6-bf05146a3f85.png)

finally look up columns that contains informations about email id, id, etc
![image](https://user-images.githubusercontent.com/31251224/31974894-f4253e8c-b8fb-11e7-8323-57d0fe69ee23.png)

Then join the informations from above to find the actual emails of the users.


wphttp://localhost/wordpress/index.php/2017/10/19/wp/






(CSRF)
Version 0.1b
An attack that forces an user to go through an unwanted action in a web application which
they are authorized in.
First you need to execute the csrf file and obtain the prompt.
And then you search for the information you are looking for and change them into 
what you desire.
![image](https://user-images.githubusercontent.com/31251224/31972688-cf5169b6-b8ef-11e7-849d-3fbbe229ef7c.png)
https://techtites.com/how-to-prevent-csrf-vulnerability-in-wordpress-plugins-and-themes/



(USER ENUMERATION)
This is to bypass by getting users information.
first you need to open up terminal and pull up wpscan and pull up help to see the controls
![image](https://user-images.githubusercontent.com/31251224/31975497-9e92f69a-b8ff-11e7-92d4-aa01744c59d7.png)

As it says on the example for enumeration, you input the website and insert --enumerate u to get the list of
usernames.
![image](https://user-images.githubusercontent.com/31251224/31975541-e4e693ea-b8ff-11e7-90d9-e37ce2218a5e.png)

Then brute force password by using any of the names from the table.

(PRIVILEGE ESCALATION)
First download the injection python
Then pull up the python code like so:
![image](https://user-images.githubusercontent.com/31251224/31986365-341ded9c-b936-11e7-9055-d1a3fed05edb.png)

Now you use nano code to input what you want to say on the web:
![image](https://user-images.githubusercontent.com/31251224/31986560-f6ad72ba-b936-11e7-9529-f027a353c169.png)


Then, along with the first code above, insert the web link you want to use. after the the web link input the content number and the content you wanted to input:
![image](https://user-images.githubusercontent.com/31251224/31986450-8cada0ec-b936-11e7-86f1-31c4fa365a76.png)

Now refresh the page and the content should appear as your nano code.






