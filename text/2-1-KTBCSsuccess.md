Multi-Region PostgreSQL Database cluster **${settings.envName}** successfully installed.

Entry point details:    
**Primary**: ${globals.regionName-1} ${globals.extIP-1}   
**Standby**: ${globals.regionName-2} ${globals.extIP-2}    
**Pgpool-II First node**: ${globals.pgpoolRegionName-1} ${pgpoolGlobals.extIP-1}    

Database credentials:   
**User**: webadmin    
**Password**: ${globals.password}  