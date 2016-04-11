# osTicket-v1.9.12-Nginx-configuration
# Documenting Nginx configurations for osTicket which officially supports Apache and IIS

I also edited: function get_path_info() as mension https://github.com/tomashastings/osTicket-1.7/blob/develop/include/class.osticket.php and updated host 

Solved 
* Blank popups and dialogs
* Image upload errors on both backend and frontend

Tested on
* Nginx 1.4.6
* PHP 5.6.20


osTicket is a platform-independent web-based application, meaning it is compatible with all operating systems. To install and run osTicket (as of version 1.7) the following components are required;
- Web Server: Apache or IIS
- PHP Version: 5.3+
- MySQL Database: 5.0+


http://osticket.com/download
