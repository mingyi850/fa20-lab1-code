# IntroLab

Github username: mingyi850
NYU NetID: ml9027
NYU N#: N18796549
Name: Mingyi Lim


As a part of your handin, modify `apps/lab1/README.md` to report the
median number of retries (for 100 trials) when the drop probability is:

* 0.001 (i.e., 0.1%): 1.0
* 0.005 (i.e., 0.5%): 1.0
* 0.01 (i.e, 1%): 1.0
* 0.05 (i.e., 5%): 1.0
* 0.1 (i.e., 10%): 1.0
* 0.2 (i.e., 20%): 1.0
* 0.5 (i.e., 50%): 3.0

Also report any conclusions you can draw from these observations.
*  Even with extreme network conditions, the median number of sends required by a service is still relatively low. 
*  However, retries increase network traffic which cause further delays and retries due to a larger number of messages built up, and thus more timeouts and retries. This might explain the non-linear increase in median pings

# Agreement with Collaboration Policy
I Mingyi Lim have read the course collaboration policy.

# Citations
* https://hexdocs.pm/elixir/introduction.html
* https://hexdocs.pm/elixir/Map.html