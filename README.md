# PRE DEPLOYMENT
- [ ] When is the most off peak time to upload?
- [ ] SSL certificates enabled on the production server?
- [ ] 301 REDIRECTS list.
- [ ] What is the official site email address, who will be the administrator?
- [ ] What is client's current email management service? Do we need to config the DNS?

**ACCESS DETAILS**
- [ ] FTP / SSH login details to server 
- [ ] DOMAIN REGISTRER - change A RECORDS or NAMESERVERS 

**BACKUPS**
- [ ] BACKUP the current site files and database 

# POST DEPLOYMENT
**Check the uploaded worked and site is error free**
- [ ] CONSOLE LOG for errors 
- [ ] SCREAMING FROG for errors in the response codes section 
- [ ] VIEW SOURCE on all main pages and ensure there is no references to staging or local dev sites 
- [ ] Production only files uploaded. IE: no gruntfiles or node_modules. 
- [ ] FAVICON working
- [ ] 404/ERROR page working

**COMPRESSION**
- [ ] Css and javascript files have been compressed for production 

**SEARCH ENGINES**
- [ ] GOOGLE ANALYTICS working
- [ ] CRAWLABLE by google is working 
- [ ] 301 REDIRECTS inplace.
- [ ] New SITEMAP has been generated and submitted to google (using yoast).
- [ ] All website traffic is directed to either the www or non-www domain (canonical issue)

**SECURITY**
- [ ] Wordfence is installed and sending notifications to the official site administrator 

**WP_ADMIN SETTINGS**
- [ ] Email Address set to the official site administrator 

**EMAILS**
- [ ] SENDING from the website is working. Test to yourself and to the client using the contact form

**ECOMMERCE**
- [ ] TRANSACTIONS are working in a non sandbox enviroment 

**USER ACCESS**
- [ ] USERNAME for the client 

**PLUGINS**
- [ ] LICENSE KEYS owned by the client for all plugins 
