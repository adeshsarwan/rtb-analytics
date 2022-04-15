# rtb-analytics
This Project has the ES Index mappings and Saved Objects Export from Kibana

Below work is required to migrate to new server using the configs and exports

1. Create New Roles for Advertiser/Publisher which has read access to only Advertiser/Publisher indices on elasticsearch and dashboard read access on Kibana
2. Enabled Document based access to roles and have many users for that roles
3. Create separate space for Advertisers/Publishers and control their access
4. Export and import dashboards, index and visuals
5. Set default route for spaces
6. Add the respective space to role
