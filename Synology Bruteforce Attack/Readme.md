# Synology Bruteforce Attack
During the last 2 weeks, starting on 10/19/2022, Zettasecure has seen a sharp increase in Bruteforce attacks against Synology NAS systems of its own customers, as well as various deployed Honeypots by Zettasecure. These were initially focused on specific usernames like "admin", "syno", "synology", or "administrator" and then changed last week into a more general direction to standard names like "eden", "peter", "joyce", etc.. There is obviously an attempt to get a successful login. We tested what the attackers did with it and could see that after a successful compromise, all data is stripped off and then appears in an encrypted split folder. All other files were completely removed. After that, Bitcoins are demanded for the password. This is a variation of a ransomware attack.

Inside this folder you will find all IPs that have been seen attacking our customers.

