# Security CTF

The Pixels Camp Security CTF is an event for those that are passionate about Security in general, more specifically in Web Security, Cryptography and Forensics. If you want to challenge your knowledge in Security by breaking standard cryptographic algorithms or breaking applications in general and learn a lot on the way, then get ready to rumble.

In order to participate in the Pixels Camp Security CTF, you first need to qualify for it.

## Qualifiers

[Qualifiers][2] consist of a set of six challenges on the topics mentioned above. We will post the first challenge on the Pixels Camp site and you can start from there. You need to solve the first challenge to get access to the second one and so on and so forth. At the end of each challenge you’ll receive a flag. In order to qualify you need to be amongst the first ten contestants to submit the six correct flags, or be invited by one of those ten. The contest will have a maximum of ten teams with a maximum of four elements on each team. The first ten persons to submit the six correct flags will be the leaders of the teams and will invite three other elements to form a team. Everyone that qualifies is automatically accepted to Pixels Camp. For those who were invited and weren’t yet accepted to Pixels Camp, they’re subject for approval.

The first person to submit the six flags will win a prize (to be given at the end of Pixels Camp).

We believe that the qualifiers provide good preparation for the Pixels Camp Security CTF. If you, or your team, are not able to complete this challenge, then you will most likely fail at the CTF, since both share the same topics.

Rules: Web scanners, Brute-force tools/scripts, DoS attacks and any type of cheating is lame and will result in immediate disqualification.

### How to play

You submit your answers via git commits so if you haven't already,

[CREATE YOUR REPO HERE][1].

You should get a GitHub email notifying you the repo was created. The repo will be git@github.com:pixelscamp-ctf/<username>.git

The flow is:

* clone the challenge repo:
* git clone git@github.com:pixelscamp-ctf/<username>.git
* checkout the challenge branch:
* git checkout answer
* edit answer.txt and write the flags there
* commit: git commit -am '<insert nice message for us>'
* push the changes: git push
* wait for the answers to be checked
* if they're correct checks will pass
* if not try harder
* Start the first challenge here

## Security CTF

![Screenshot](https://github.com/PixelsCamp/docs/blob/master/img/ctf.png?raw=true)

### How it works

The games starts off with one open question (lead question). The first team that answers the lead question is able to open another question (the next lead question). The lead question consists of only one question and it’s the last opened question. An open question is either the lead question or an old lead question. All teams can answer the lead question and all previously opened questions.

For each question, the first team to answer the question receives 100% of the points for that question, the second team receives 95% and the remaining teams receive 90% of the points. If two teams answer the same question at the same exact time, it’s possible that the two teams receive the same amount of points (they both deserve it).

Teams will not be penalized for submitting an incorrect answer, so basically every team has an unlimited number of tries to answer a question. Attempting to brute force an answer is not permitted and will result in disqualification. Also, the game board site is throttling requests and you will be blocked from the site.

Only team members can participate in the contest. You cannot get help from anyone but your team colleagues.

### Colors on the Game Board

* **Green**: you already answered this question
* **Blue**: open question: you can answer this question
* **Yellow**: lead question: the guy that’s kicking your ass is on this question
* **Black**: closed question: you (and everyone else) isn’t fast enough to get to this yet

### Abuse

You are not allowed to perform any type of brute force on the servers or run any sort of scanners against the servers. It is possible that you need brute forcing to solve a challenge, so we will let you know when brute forcing is allowed (in the challenge description).

Any type of abuse will be announced on the game board, so other teams will know that you are trying to cheat.

### Other things you should know

When a team answers a lead question correctly, the team has 120 seconds to open another question (the next lead question). If the team fails to open another question within the specified time, a random one will be opened from the set of questions that generate the lowest questions.

If no progress is achieved within 20 mins, a new random question will be opened. Staff may also open a new random question if the game progress is stalled.

The timer on the game board runs in your browser (client-side). The official time of the game is the server time. Answers that exceed the 3:00:00 after the start of the game are not accepted. Even though the timer on the game board is synced with the server every 10 seconds, if the load of your computer is high, it’s possible that the timer may become delayed by a few seconds.

[1]: https://pixels-camp-security-ctf.herokuapp.com/register
[2]: http://quals.ctf.pixels.camp/
