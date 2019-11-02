# Mike Yatsenko, and here is my kottans-backend

## Task 1. Git Basics —  done
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Git_Intro/git.png)
## Task 2. Unix Shell —  done
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Unix_Shell/1.png)
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Unix_Shell/2.png)
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Unix_Shell/3.png)
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Unix_Shell/4.png)
Speaking about Point 2 (http://linuxcommand.org), it’s quite difficult to read everything, but for me it was very convenient to use the format of tables with expressions, directories and wildcards and their explanations during reading.
## Task 3. Git Collaboration —  done
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Git_Collaboration/git.png)
<strong> And what about my feelings...</strong> 
Working with GitHub and Git was new experience for me. Since I worked on my projects almost by myself. Incredibly convenient thing, and most importantly, I felt the optimization of even small details of this tool . The course is interesting , I like the moment that you need to work with the repository by yourself.
Some things were shocking, <i> for example </i>: ![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Git_Collaboration/4.png)
But in any case, it is <b>very</b> interesting.
So I will continue, thanks!
## Task 4. Python Basic-1 —  done
[My profile on HackerRank](https://www.hackerrank.com/yatsbb)
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Python_basic1/1.png)
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Python_basic1/2.png)
## Task 5. Memory Management — done
Questions:
1. Stack Overflow and after it segmentation fault wiil be recieved.
2. Will be created an anonymous memory mapping.
3. Text memory segment is read only and stores data as a string literals. Data memory is read and write and saving the contents for static variables initialized in source code.

```
556528b6a000-556528b86000 r-xp 00000000 103:01 2621474                   /bin/dash
556528d85000-556528d87000 r--p 0001b000 103:01 2621474                   /bin/dash
556528d87000-556528d88000 rw-p 0001d000 103:01 2621474                   /bin/dash
556528d88000-556528d8a000 rw-p 00000000 00:00 0
556529c01000-556529c22000 rw-p 00000000 00:00 0                          [heap]
7f77d1ded000-7f77d1fd4000 r-xp 00000000 103:01 3674829                   /lib/x86_64-linux-gnu/libc-2.27.so
7f77d1fd4000-7f77d21d4000 ---p 001e7000 103:01 3674829                   /lib/x86_64-linux-gnu/libc-2.27.so
7f77d21d4000-7f77d21d8000 r--p 001e7000 103:01 3674829                   /lib/x86_64-linux-gnu/libc-2.27.so
7f77d21d8000-7f77d21da000 rw-p 001eb000 103:01 3674829                   /lib/x86_64-linux-gnu/libc-2.27.so
7f77d21da000-7f77d21de000 rw-p 00000000 00:00 0
7f77d21de000-7f77d2205000 r-xp 00000000 103:01 3674801                   /lib/x86_64-linux-gnu/ld-2.27.so
7f77d23e6000-7f77d23e8000 rw-p 00000000 00:00 0
7f77d2405000-7f77d2406000 r--p 00027000 103:01 3674801                   /lib/x86_64-linux-gnu/ld-2.27.so
7f77d2406000-7f77d2407000 rw-p 00028000 103:01 3674801                   /lib/x86_64-linux-gnu/ld-2.27.so
7f77d2407000-7f77d2408000 rw-p 00000000 00:00 0
7ffe39224000-7ffe39246000 rw-p 00000000 00:00 0                          [stack]
7ffe393ea000-7ffe393ed000 r--p 00000000 00:00 0                          [vvar]
7ffe393ed000-7ffe393ee000 r-xp 00000000 00:00 0                          [vdso]
ffffffffff600000-ffffffffff601000 r-xp 00000000 00:00 0                  [vsyscall]
```
 `Heap - 556529c01000-556529c22000`, `Stack - 7ffe39224000-7ffe39246000`, `MMS - 556528d88000-556528d8a000`.
 
**Regarding the topic**: The first article was very difficult for me. I used additional articles and videos to understand how the memory management tool works. The task was quite simple.

## Task 6. TCP.UDP.Network — done
![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Task_Networks/4.png)

<b>Internet101</b>: Very nice course in terms of presentation and animation, it was nice to watch, especially at the weekend.

<b>howdns.works</b>: Perhaps the most interesting material that I saw on this topic.

![Image alt](https://github.com/MikeYatsenko/kottans-backend/blob/master/Task_Networks/5.png)

<b>Networking for Web Developers</b>: I worked very little with Linux, so this course, in general, was difficult, but useful.

TCP sniffer: [here](https://github.com/MikeYatsenko/kottans-backend/blob/master/Task_Networks/sniffer.py)

## Task 7. HTTP & HTTPS — done
- curl https://api.github.com/users/MikeYatsenko
- curl-i https://api.github.com/users/MikeYatsenko
- curl --user "MikeYatsenko:BLABLABLA" https://api.github.com/gists/starred
- curl --user "MikeYatsenko:*********" https://api.github.com/gists/starred
- curl --user "MikeYatsenko" https://api.github.com/gists/starred
- curl -i https://api.github.com/orgs/kottans/repos
- curl -H 'Authorization:*********' https://api.github.com/repos/MikeYatsenko/kottans-backend/issues -d '{"title": "Test Issue"}' 

Questions:

<b>1.</b> _Name at least three possible negative consequences of not using HTTPS._

HTTPS is a protocol that involves the use of a certificate, which creates a secure encrypted connection between the web server and the web browser.

1) Data is not encrypted, and it can be intercepted by third parties to gather data being passed between the two systems.
2) You can lose data integrity. SSL and TLS provide data integrity by calculating a message digest.
3) Encrypting a communication is good but it is not enough, you need to be confident about  that you are talking to the  right person or the right server. So you need to use identification provided by certificate.

<b>2.</b> _Explain the main idea behind public key cryptography in few sentences._

TLS is a hybrid cryptographic system. This means that it uses several cryptographic approaches, which we will consider further:

1) Asymmetric encryption (a public-key cryptosystem) for generating a shared secret key and authentication (that is, verifying that you are the one who claims to be).
2) Symmetric encryption using a secret key for further encryption of requests and responses.

The public key is used to encrypt the message text in characters, while the private key is used to decrypt and retrieve the source text. Since the message has been encrypted using the public key, it can only be decrypted with the corresponding private key. None of the keys can perform both functions. The public key is published in the public domain without risking exposing the system to threats, but the private key should not reach anyone who does not have the right to decrypt data.

<b>3.</b>  _An application for pet clinic._

-POST, add new pet, response will be status 201.
-GET, search pet by name, response will be status 200.
-PUT, change name of an existing pet, response will be status 200.
-PUT, add new info about pet's health, response will be status 200.
-PUT, assign a pet to a particular doctor, response will be status 200.
-PUT, register an appointment for a pet, response will be status 200.
