
Proccess Related Commands:

#ps -ef                                               To check running process
#ps -ef | grep sshd                                   To check sshd process running or not
#top  / #htop                                         To monitor the all process
#ps -eo pid,user,%cpu,%mem,cmd --sort=-%cpu | head    To check process cosuming high cpu


Systemd Related commands

#systemctl status/enable/start/restart/reload/stop <service name>   To perform different action service
#systemctl is-enable sshd                                           To check sshd is enabled after booting
#systemctl is-active sshd                                           To check sshd is running or not
#journalctl -u sshd -f                                              To check sshd latest logs
#journcalctl -u sshd -n 50                                          To check latest sshd 50 logs
