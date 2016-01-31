Last login: Sun Jan 31 08:53:57 on console
You have mail.
nishanths-MacBook-Pro:~ nishanth$ cd msd_project
nishanths-MacBook-Pro:msd_project nishanth$ ls
command_files	iofiles
nishanths-MacBook-Pro:msd_project nishanth$ cd command_files
nishanths-MacBook-Pro:command_files nishanth$ ls
commandfifo
nishanths-MacBook-Pro:command_files nishanth$ vim command fifo
2 files to edit
nishanths-MacBook-Pro:command_files nishanth$ ls
command		commandfifo
nishanths-MacBook-Pro:command_files nishanth$ vim commandfifo











 32 
 33       if(request=number_of_memory_requests -1)
 34         {     
 35         cout<<"Buffer full no more requests are accepted";
 36         }
 37       else
 38         {
 39         cin>>row_address;
 40         cin>>column_address;
 41         Bank.request.row_address;         //initiate bank n instance
 42         rowaddress_maping(row_address);
 43         Bank.request.column_address;///function call
 44         columnaddress_mapping(column_address);
 45 
 46                 cout<<"Please enter Memory Requests";
 47                 cin>>Activate;                       //for request 1
 48                 //add wait states
 49                 cin>>Activate;                       //for request 2
 50                 //add wait states
 51                 cin>>Read;                           //for request 1
 52                 //add wait states
 53                 cin>>Read;                           //for request 2                    
-- INSERT --
