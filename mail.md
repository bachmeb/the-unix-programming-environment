# unix mail

```
mail
```
> ```
> bash: mail: command not found...
> Packages providing this file are:
> 'mailx'
> 's-nail'

```
mailx
```
> ```
> bash: mailx: command not found...
> Packages providing this file are:
> 'mailx'
> 's-nail'

```
yum search mailx
```
> ```
> Last metadata expiration check: 0:01:07 ago on Sat 11 Sep 2021 09:16:30 AM EDT.
> =============================================== Name & Summary Matched: mailx ================================================
> mailx.x86_64 : Enhanced implementation of the mailx command
> libreport-plugin-mailx.x86_64 : libreport's mailx reporter plugin

```
sudo yum install mailx
```
> ```
> [sudo] password for brian: 
> Last metadata expiration check: 2:58:23 ago on Sat 11 Sep 2021 06:19:35 AM EDT.
> Dependencies resolved.
> ==============================================================================================================================
>  Package                    Architecture                Version                             Repository                   Size
> ==============================================================================================================================
> Installing:
>  mailx                      x86_64                      12.5-37.fc34                        fedora                      262 k
> 
> Transaction Summary
> ==============================================================================================================================
> Install  1 Package
> 
> Total download size: 262 k
> Installed size: 496 k
> Is this ok [y/N]: y
> Downloading Packages:
> mailx-12.5-37.fc34.x86_64.rpm                                                                 251 kB/s | 262 kB     00:01    
> ------------------------------------------------------------------------------------------------------------------------------
> Total                                                                                         166 kB/s | 262 kB     00:01     
> Running transaction check
> Transaction check succeeded.
> Running transaction test
> Transaction test succeeded.
> Running transaction
>   Preparing        :                                                                                                      1/1 
>   Running scriptlet: mailx-12.5-37.fc34.x86_64                                                                            1/1 
>   Installing       : mailx-12.5-37.fc34.x86_64                                                                            1/1 
>   Running scriptlet: mailx-12.5-37.fc34.x86_64                                                                            1/1 
>   Verifying        : mailx-12.5-37.fc34.x86_64                                                                            1/1 
> 
> Installed:
>   mailx-12.5-37.fc34.x86_64                                                                                                   
> 
> Complete!

```
mail
```
> ```
> No mail for brian
