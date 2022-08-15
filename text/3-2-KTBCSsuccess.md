Multi-Region PostgreSQL Database cluster **${settings.envName}** successfully installed.

Entry point details:    
**Primary**: ${globals.regionName-1} ${globals.extIP-1}   
**Standby 1**: ${globals.regionName-2} ${globals.extIP-2}   
**Standby 2**: ${globals.regionName-3} ${globals.extIP-3}  
**Pgpool-II First node**: ${globals.pgpoolRegionName-1} ${pgpoolGlobals.extIP-1}
**Pgpool-II Second node**: ${globals.pgpoolRegionName-2} ${pgpoolGlobals.extIP-2}   

Database credentials:   
**User**: webadmin    
**Password**: ${globals.password}  
