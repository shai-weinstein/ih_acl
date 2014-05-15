#Module for limiting access to admin pages per IP
#add to settings.php variables:

$conf['ih_acl_paths'] = array("/^admin/i","/^user/i","/^node\/+.*\/+edit/i", "/^node\/+add/i");
#regex list for path limit

$conf['ih_acl_ips'] = array('127.0.0.1', '194.90.1.5');
#list of allowed IPs
