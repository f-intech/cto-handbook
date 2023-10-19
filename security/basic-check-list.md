### Domain
##### 1. Firewall rules
Set up a firewall to exclude countries that your service shouldn't be accessible to. If your service is global then update the rules to block countries with the top attack origins. You could use AWS WAF or Cloudflare WAF (5 free rules) to achieve this. 

##### 2. Enable 2FA for internal applications
Set all the 3rd party applications to require 2FA for all the users. For in-house admin portals/dashboards enable domain level 2FA using tools like Cloudflare Access (free for 50 users).

##### 3. Hide the app server IP
Always keep the application server/cluster and databases in the private subnet. If it is a trivial project that needs quick setup, at least make sure that it is not exposed via the DNS lookup. You can use Cloudflare proxy (free) to achieve this.

##### 4. Make sure all (or at least the public) communication is SSL-encrypted
Most application SSL setup encrypts only from the browser to the DNS proxy or application load balancer. This could lead to data being leaked if the 3rd party is compromised. The solution is to encrypt all the data transfers are secured.

