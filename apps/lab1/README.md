# IntroLab

Github username: mingyi850
NYU NetID: ml9027
NYU N#: N18796549
Name: Mingyi Lim


As a part of your handin, modify `apps/lab1/README.md` to report the
median number of retries (for 100 trials) when the drop probability is:

* 0.001 (i.e., 0.1%): 4.0
* 0.005 (i.e., 0.5%): 4.0
* 0.01 (i.e, 1%): 4.0
* 0.05 (i.e., 5%): 5.0
* 0.1 (i.e., 10%): 5.0
* 0.2 (i.e., 20%): 6.0
* 0.5 (i.e., 50%): 7.5

Also report any conclusions you can draw from these observations.
*  With a 0.001 drop rate and no delay, we should expect about 2 out of 1000 messages to be dropped, and a median of 1.0 sends per message. However, we observe a much higher retry rate. Based on the observations, the average delay of 10ms causes up to 3 retries given a timeout of 100ms, possibly due to the server not being able to respond in time.
* As the drop rate increases, we do see a small increase in retries, 

# Agreement with Collaboration Policy
I Mingyi Lim have read the course collaboration policy.

# Citations
