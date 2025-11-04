# K-Chat
A Retro Social Media inspired by the Talkomatic system. This project showcases a unique network system running on only 3 cloud variables (server-side persistent shared variables), User friendly UI, Line based Chatting, Dual Layer Security, and Administration access with security + Passwords. By: Krishaang Kaushik (NOW WITH WORKING SERVERS!!!)
# Guide
### Chat
Press on ***Chat*** Button and enter text you want to share text.
The output you will get will be something like this:

Guest: Example Text.
### Server
Press on ***Server*** Button to change the server.
There are 3 servers as of now.
Servers are non-locational, meaning that you will have same response speeds in all servers.
### Settings
Press on ***Settings*** Button to change settings.
When Admin Password comes up just click enter. (Admin pannel contains features to wipe servers, edit servers, Change encoding type, and Change Admin Password.)
Change user name: Type "y" for yes and "n" for no.
Change Refresh Rate (Speed at which your computer updates the list to showcase the most recent chats) (0.5 by default): Type "y" for yes and "n" for no.
Refresh Servers (Manual Server Update): Type "y" for yes and "n" for no.
# Features
- 3 Separate servers
- 3 + 1 cloud variables (server-side persistent shared variables)
- Up to 30 Messages per server at a time
- Automatic Deletion of oldest messages after 30 messages
- Administration Panel & Administration Commands
- Dual Encoding System for Security
- Works on all browsers
- Username features
- Automatic list refreshing
- Non-local Servers
- International Chating
- 6 Encoding Languages (UTF 16, RAW, BASE64, Uint4Array, EncodedURLComponent, Numeric)
- Automatic security breach ping
- etc...
# How it Works?
### Step 1: Input
After the user enters the text he wants to say, it is taked and put into a list called the server list. Each server has its own list. Now this list is transformed into a single line JSON command.
### Step 2: Input Encoding
The JSON command is then encoded with any 5 of the following encoding languages: UTF 16, RAW, BASE64, Uint4Array, or EncodedURLComponent. This encoded value is then again encrypted into a Numeric format so that it may be put in a cloud variable (server-side persistent shared variables).
### Step 3: Cloud & Internet System
The entire K-Chat network runs on literally 3 + 1 cloud variables (server-side persistent shared variables)! With 30 messages each and 3 servers, that makes the entire K-Chat network able to handel upto 90 Messages at once!!!! And all of this running on 3 variables (With only numeric values). Along with the Previous encoding using any of the 5 languages, it makes it so that even if someone gets their hands on the variable, and is able to decode the numeric code, they will still not be able to decode the final layer. (The +1 is for the Admin Password, so it can be accessed on any device.)
### Step 4: Decoding
When server is refreshed, the user's device pings the network for access to the information stored. The network then reverses the process, going from Numeric -> Encoded -> JSON ->  to List, and then updating it for the user to see. And now the cycle is complete. Letting users chat from anywhere in the world.
### Advanced Security
K-Chat also has some more **Advanced Security** options. When someone trys to type the wrong password in, a message will be sent to the Administrator stating that someone is preforming a breach (Yes I know that there will be many false positives to this approach but what can I do...). When Updating the password if someone enters the wrong previous password the same message will be sent. Along with all of this, the admin Password is encrypted in the same manner with a different encrypting language as that of the main chat. This time the Password is Passed through the encryption languages twice before being encrypted numericaly, (Both times have different encryption languages) making for extra security (3 Layers this time).
# Final Words
So what do you think? Isn't is cool? This project was inspired by the first ever social media which was made in the 1970's called the Talkomatic (Talk + Automatic). This project was made by Krishaang Kaushik Using Turbowarp along with Custom Typescript and HTML.
