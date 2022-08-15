Multi-Region PostgreSQL Database cluster **${settings.envName}** successfully installed.

Entry point details:    
**Primary**: ${globals.regionName-1} ${globals.extIP-1}   
**Standby**: ${globals.regionName-2} ${globals.extIP-2}  
**Pgpool-II First node**: ${globals.pgpoolRegionName-1} ${pgpoolGlobals.extIP-1}
**Pgpool-II Second node**: ${globals.pgpoolRegionName-2} ${pgpoolGlobals.extIP-2}   
**Pgpool-II Third node**: ${globals.pgpoolRegionName-3} ${pgpoolGlobals.extIP-3} 

Database credentials:   
**User**: webadmin    
**Password**: ${globals.password}  
