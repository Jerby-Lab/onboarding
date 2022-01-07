# Onboarding Computational Cookbook
_This repo contains information and documentation to help newcomers to the Jerby Lab with computational setup._

## Slack

If you are not already on slack, please ask by searching **JerbyLab** and requesting to join here: https://stanford.enterprise.slack.com/

## Stanford Virtual Private Network 

The Stanford VPN is useful to install for a variety of reasons! But the most important one for the lab will be such that you can access the computing clusters for research in Stanford Medicine.

Instructions for setting up VPN: https://uit.stanford.edu/service/vpn

## Computing Resources

Stanford Research Computing Center is the hub of all computing resources for the School of Medicine. https://srcc.stanford.edu/. The two servers that are most relevant:

- **SCG** - Genomics Cluster (most commonly used in Dept of Genetics)
- **Sherlock** - Higher performance computing with GPU accelerators, approved for patient health information (PHI)

### SCG
Please use SCG as this cluster should allow you to do almost everything you need to do. If you need more intensive GPU power or are working with PHI, reach out to Livnat. 

Please add the following computing cluster Slack resources. There are folks on call on Slack if you ever run into any issues. Remember, there is no such thing as a dumb question:

| channel name      | description                                                                                                                 |
| ----------------- |:---------------------------------------------------------------------------------------------------------------------------:|
| #scg-users        | A space for people to ask general questions about SCG usage, applications, problems, ...                                    |
| #scg-announce     | Place where SCG related announcements are made. Outages, maintenance, configuration changes, seminars, related services, …  |
| #scg-office-hours | SCG office hours happen every two weeks, in this Slack channel. Hours are announced in advance at #scg-announce             |

To gain access to SCG, please email scg-action@lists.stanford.edu, cc-ing Livnat to ask for access and they will process it on the back end. Once you are approved, you can sign into SCG via the Terminal by the following command: 

        ssh SUNetID@scg.stanford.edu 

## Storage - Oak 

Once you gain access to SCG or Sherlock, you should have access to Oak storage. Oak is file system where we store all of our data. More information here: https://uit.stanford.edu/service/oak-storage. 

You can access oak in Terminal via the directory `/oak/stanford/groups/ljerby/`

To mount Oak on Mac, use the Finder (command-K) and the following URL: smb://oak-smb-ljerby.stanford.edu/groups/ljerby
*IMPORTANT:* Please use SUNetID@stanford.edu as login (and not only your SUNet ID)
If you are not on the Stanford wifi, then you'll need to connect first via VPN. Use the terminal to run code on Sherlock/SCG clusters – those have access to the lab Oak project directories to retrieve input data and save output files.

## More Questions? 

The Jerby Lab has a `#computing` channel on Slack for all your remaining computing questions.



