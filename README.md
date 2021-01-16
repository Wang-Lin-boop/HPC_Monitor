# HPC_Monitor
Automatic monitoring of HPC information and Send warning information by E-mail.

Modes Currently Supported:      

      1.pestat
      2.top

Dependence
----

You must confirm that SendEmail can be used on HPC.

Or install it now.

            wget http://caspian.dotconf.net/menu/Software/SendEmail/sendEmail-v1.56.tar.gz
            tar zxvf sendEmail-v1.56.tar.gz 
            cd sendEmail-v1.56
            echo "export PATH=${PWD}:\$PATH" >> ~/.bashrc

Usage
----

          Usage: HPC_Monitor [OPTION] <parameter>    

          Example: HPC_Monitor -s Monitor@shanghaitech.edu.cn -r User@shanghaitech.edu.cn -x ******   
               -s sender_E-mail
               -r recipients_E-mail 
               -x passwd_of_sender_E-mail

******
Thank you for your using, If you found any problem, Please contact wanglin3@shanghaitech.edu.cn.
