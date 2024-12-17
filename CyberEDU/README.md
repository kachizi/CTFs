# CTF-Writeups
Documenting challenges and solutions from various Capture The Flag competitions.

## Challenges
# 1.robots
1. After selecting and opening an appropriate question, click [Unlock Challenge].
2. Click [Start Task] on the left side of the screen and wait for a while.
3. After waiting a minute or two, the address will appear in yellow letters on the screen.
   ![image](https://github.com/user-attachments/assets/22f8f0fa-f7b9-460f-abd0-54424f01804b)
4. You can visit the site in question by copying this address, pasting it into your browser's address bar and pressing Enter.

Then we analyze and attack the site to look for flags.
Now, let's look for the flag hidden on the site. The flag is a string in the form of CTF{・・・}.

5 .When I accessed the site, there was only one line of text.
![image](https://github.com/user-attachments/assets/fff0264a-9b10-48ba-aeb5-52f8e6606101)

6. Judging from the title of this problem, it seems like there might be a clue in robots.txt, so I'll open /robots.txt in my browser.
   ![image](https://github.com/user-attachments/assets/23804d77-188d-43e7-b51c-09523415779f)

7. When I opened /g00d_old_mus1c.php in robots.txt in a browser, the flag was displayed.
   ![image](https://github.com/user-attachments/assets/408bfada-491f-4a1d-b26d-7a9bf2d62629)







