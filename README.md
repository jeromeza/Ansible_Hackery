# Ansible_Hackery
Playground for Ansible Hackery. 
  
**Requires the following shell environment variables to be set:**.   
export CF_EMAIL=your@email_here.com  
export CF_APIKEY=your_cf_api_key_here  
export CF_ACCOUNTID=your_cf_accountid_here  
export CF_DOMAIN=your_cf_domain_here  
export CF_WORKERNAME=your_cf_worker_name_here  
export CF_ROUTE=your.domain.com/*  
  
**The following playbooks perform the following tasks:
get_zoneid.yml - Extract Zone ID From A Cloudflare Domain  
  
add_worker.yml - Upload A Specific Cloudflare Worker script  
del_worker.yml - Delete A Specific Cloudflare Worker script  
get_worker.yml - List All Cloudflare Workers  
  
get_route_id.yml - List All Cloudflare Routes For A Domain   
add_route.yml - Add A New Cloudflare Route  
del_route.yml - Delete A Specific Cloudflare Route  
update_route.yml - Update An Existing Route  
  


