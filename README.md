LAB B1 - DEVICE BOOT AND INITIAL CONFIGS

1. configured root login using system root authentication
2. configured system host-names for both vSRX devices
3. configured a login message for both devices
4. configured an admin user with a super-user class
5. Enabled SSH and NETCONF
   - ssh allows both devices to accept ssh connections from client for remote access management
  
6. configured security zones trust for both devices ge-0/0/0 interfaces to accept host-inbound-traffic pings
   - Allows ping to vSRX devices
  
8. Assigned IPv4 address for both devices on the g-0/0/0 interfaces
   - Allows both devices to communicate with each other and ping one another
