# Network-Information-Security<a name="TOP"></a>
Network and Information Security - Spring 2023

Course Code: 0852X22303

## Table of Contents
1. [Syllabus](#syllabus)
2. [Calendar](#calendar)
3. [Readings](#readings)
4. [Labs and Assignments](#labs-and-assignments)
5. [Final Project](#final-project)
6. [Resources](#resources)

## Syllabus

This course makes use of any programming language and computing environment of your choice.

### Course Meeting Times
Lectures: A session / week, 3 credit hours

### Prerequisites
* Data Communications & Networks
* Algorithms
* Web Technology

### Description
Network Information Security studies the design and implementation of securing digital information, systems, and distributed computations against adversarial attacks. Lectures cover threat models, attacks that compromise security, and techniques for achieving security, based on recent research topics/papers. Topics include operating system (OS) security, capabilities, information flow control, language security, network protocols, hardware security, and security in web applications and modern cryptography. Assignments include labs that may involve implementing and compromising a secure web server and web application, and a group final project. The course is primarily intended for master students who want to learn about how to build secure systems and applications in detail. Ph.D. students are also welcome.

### Lectures
Each lecture will cover a paper in systems security or chapter(s) from resources book. Read the paper or chapter before lecture, and submit by 10PM the night before:

1. An answer to the homework reading question.
2. Your own question about the paper/from book chapter (will try to answer in lecture).

We’ll discuss the paper/chapters in class. Please interrupt, ask questions, and point out mistakes.

### Quizzes
There will be two quizzes during our regular lecture time slot. No “final exam” during final week; second quiz near end-of-term.

### Assignments
There are 5 labs and a final project in this course. Labs will look like real-world systems, in some respects: There are many interacting parts written in different languages. We’ll look at Python, Java, Javascript, etc…

There will be a final project at the end of the course (groups of 2-3 people), and presentations during the last week of class. Think of projects you’d like to work on as you’re reading papers and chapters. Either attack or defense-oriented projects are possible, Hacking the a Cipher, application authentecaion. It is ok to combine this project with other class projects or your own research.

### Grading System
|ACTIVITIES	                      | PERCENTAGES|
|:---                             |:---        |
|2 Quizzes	                       | 20%        |
|Lab Exercises                    |	35%        |
|Final Project and Presentation   |	25%        |
|Homework and Class Participation |	20%        | 

Lab exercises will be graded on the correctness based on both the lab assignment and whether they fulfill the specifications imposed by the grading / checking scripts. Grading will be done with a staff-version of the Makefile and grading scripts, so you should pass all the tests without any modifications to those files.

### Collaboration
You may not collaborate on quizzes. You are welcome to discuss the labs with other students, but you should complete all assignments on your own, and you should carefully acknowledge all contributions of ideas by others, whether from classmates or from sources you have read. Final projects will be in groups, where you should collaborate.

### Warning About Security Work / Research of ZJNU (and in General)
You may learn how to attack systems so that you know how to defend them. Just because something is technically possible, doesn’t mean it’s legal.


## Calendar

## Readings

## Labs and Assignments

## Final Project

## Resources
This section contains external resources related to the materials we will use in this class.

### Computer Network Security
* Joseph Migga Kizza. Guide to Computer Network Security, 4th edition. Springer, 2017. ISBN 978-3-319-55605-5. [Resource](https://github.com/Madjeisah/Network-Information-Security/blob/master/2017_Book_GuideToComputerNetworkSecurity.pdf)

### Cryptography
* William Stallings. Cryptography and Network Securuty: Principle and Practice, 5th edition. Pearson, 2010. ISBN-10: 0136097049. [Resource](https://github.com/Madjeisah/Network-Information-Security/blob/master/Cryptography_and_Network_Security-Prins_and_Pract._5th_ed.pdf)
* Schneier, Bruce. Applied Cryptography: Protocols, Algorithms, and Source Code in C. John Wiley & Sons, 1996. ISBN: 9780471117094. [Resource]
* Menezes, van Oorschot, and Vanstone. Handbook of Applied Cryptography. CRC Press. 1996. ISBN: 9780849385230. [Resource]
* Buchmann, Johannes. Introduction to Cryptography. Springer, 2004. ISBN: 9780387211565. [Resource]

* Cryptographic libraries:
  * [GPGME](https://www.gnupg.org/related_software/gpgme/) by GnuPG.
  * [OpenSSL](https://www.openssl.org/).
  * [NaCl: Networking and Cryptography library](http://nacl.cr.yp.to/) by Tanja Lange and Daniel J. Bernstein.

### Control Hijacking Attacks
* [Smashing The Stack For Fun And Profit](http://phrack.org/issues/49/14.html#article), Aleph One.
* [Bypassing non-executable-stack during exploitation using return-to-libc (PDF)](http://css.csail.mit.edu/6.858/2014/readings/return-to-libc.pdf) by c0ntex.
* [Basic Integer Overflows](http://phrack.org/issues/60/10.html#article), blexim.
* [Intel Memory Protection Extensions](https://www.intel.com/content/www/us/en/developer/overview.html#gs.ob34l9).
* [Intel 80386 Programmer’s Reference Manual](http://css.csail.mit.edu/6.858/2014/readings/i386/toc.htm), 1987. Alternatively, in [PDF format](http://css.csail.mit.edu/6.858/2014/readings/i386.pdf). Much shorter than the full current Intel architecture manuals below, but often sufficient.
* [Intel Architecture Software Developer Manuals](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html).

### Web Security
* [Browser Security Handbook](https://code.google.com/archive/p/browsersec/wikis/Main.wiki), Michael Zalewski, Google.
* [Browser attack vectors](https://code.google.com/archive/p/google-caja/wikis/AttackVectors.wiki).
* [Google Caja](https://code.google.com/archive/p/google-caja/) (capabilities for Javascript).
* [Google Native Client](https://bugs.chromium.org/p/nativeclient/issues/list) allows web applications to safely run x86 code in browsers.
* [Myspace.com - Intricate Script Injection Vulnerability](https://bugtraq.securityfocus.com/archive), Justin Lavoie, 2006.
* [The Security Architecture of the Chromium Browser (PDF)](http://seclab.stanford.edu/websec/chromium/chromium-security-architecture.pdf) by Adam Barth, Collin Jackson, Charles Reis, and the Google Chrome Team.
* [Why Phishing Works (PDF)](https://people.eecs.berkeley.edu/~tygar/papers/Phishing/why_phishing_works.pdf) by Rachna Dhamija, J. D. Tygar, and Marti Hearst.

### OS Security
* [Secure Programming for Linux and Unix HOWTO](https://dwheeler.com/secure-programs/), David Wheeler.
* [Setuid demystified (PDF)](https://people.eecs.berkeley.edu/~daw/papers/setuid-usenix02.pdf) by Hao Chen, David Wagner, and Drew Dean.
* [Some thoughts on security after ten years of qmail 1.0 (PDF)](http://cr.yp.to/qmail/qmailsec-20071101.pdf) by Daniel J. Bernstein.
* [Wedge: Splitting Applications into Reduced-Privilege Compartments (PDF)](http://css.csail.mit.edu/6.858/2014/readings/wedge.pdf) by Andrea Bittau, Petr Marchenko, Mark Handley, and Brad Karp.
* [KeyKOS source code](http://css.csail.mit.edu/6.858/2014/readings/keykos/).

### Exploiting Hardware Bugs
* [Bug Attacks (PDF) on RSA](https://link.springer.com/chapter/10.1007/978-3-540-85174-5_13), by Eli Biham, Yaniv Carmeli, and Adi Shamir.
* [Using Memory Errors to Attack a Virtual Machine (PDF)](https://www.cs.princeton.edu/~appel/papers/memerr.pdf) by Sudhakar Govindavajhala and Andrew Appel.

### Mobile Devices
* [iOS security (PDF)](http://css.csail.mit.edu/6.858/2014/readings/ios-security-may12.pdf)












[Go To TOP](#TOP) 

