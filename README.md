
* High Level Approach
My approach for this project was to first implement all of the commands and parsing through the command line arguments. Then I implemented each of the commands and the client calls. Then I figured out which ones needed to access a data channel, all in a seperate method called client. I also made sure to test each param to see which one contained the ftp address. Based on the command called the the parameters, that was the client command I sent, which handled all of the server communication. 

* Difficulties/ Challenges
I had issues with handling some responses, as orignally, i had read responses in every single command, however, I quickly realized that by doing that it was forever putting my program on hold. I also had a few issues regarding seperating which parameter had the FTP address and username and login. I remedied this by checking for which was the FTP and then assigning a variable a number to refer to which param had it. ... I FORGOT A SPACE BETWEEN ONE OF MY COMMANDS FOR UPLOAD AND THEN IT JUST DIDN"T WORK FOR 2 HOURS HAHAHAHHAHAHAHAH I AM NOT LOSING MY MIND AT ALL HAHAHHAHAHAHAHAHAHAH. fun.


* Testing
I basically ran the program, originally I had error handling, however, it was making my screen a little too cluttered, so I cleaned it out after I passed the point in the program where it was not failing anymore. I also utilized ls to ensure I was able to connect to the server and get a response. 