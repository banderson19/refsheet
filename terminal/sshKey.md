
/* cd ~/"folder" */ change directly to specific folder 
bradfords-air:uofu-virt-bo-fsf-pt-01-2021-u-b band8$ cd ~/.ssh
bradfords-air:.ssh band8$ ls
id_rsa		id_rsa.pub	known_hosts
/* pbcopy < "file" */ copies "file" to clipboard
bradfords-air:.ssh band8$ pbcopy < id_rsa.pub

/* copy id_rsa.pub to ssh section in gitlab */
bradfords-air:UofU band8$ cd uofu-virt-bo-fsf-pt-01-2021-u-b/

/* git pull pulls down changes made to a repository */
bradfords-air:uofu-virt-bo-fsf-pt-01-2021-u-b band8$ git pull
hint: Pulling without specifying how to reconcile divergent branches is
hint: discouraged. You can squelch this message by running one of the following
hint: commands sometime before your next pull:
hint: 
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint: 
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
Enter passphrase for key '/Users/bradfordanderson/.ssh/id_rsa': 
/* passphrase = ranger99 */
remote: Enumerating objects: 157, done.
remote: Counting objects: 100% (157/157), done.

***************************

ssh-add KEY