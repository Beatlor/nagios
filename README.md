nagios
======

Check command: 

`define command {  
        command_name  setSvcStatusByHostStatus  
        command_line  /usr/lib/nagios/plugins/setservicebyhost -h $HOSTNAME$ -s $HOSTSTATEID$ -u $HOSTATTEMPT$ -a $MAXHOSTATTEMPTS$ -m o  
        register 1  
}`  
