### 0.1.12
- Port range (xxx:yyy) support

### 0.1.11
- Multiport services are now solving conflicts on their own
### 0.1.10
- Multiple fixes

### 0.1.9
- NIDS ( scan detection ) is on and running

### 0.1.8
- Add IPtables rule mutliport support (use {PORTS} template)
- Logging is moved out of befw core
- Consul KV errors doesn't affect ipset content anymore

### 0.1.7
- debug log is now hidden in production
- new config options & timeouts
### 0.1.6
- befw watcher optimisations
- befw-sync refactoring
### 0.1.5
- go mod 2.0
- befw now has timeouts for consul connections
### 0.1.4
- befw now uses stale to get updates faster
- new paths: $ipset$ for ipsets and $service$ for services

### 0.1.3
- befw now checks if its rules is consistent
- befw now can recover firewall access if consul is dead with a hard-coded ( TOTO: configured ) networks

### 0.1.2
- fix 0.0.0.0/0 centos7 ipset bug
- befw-sync now wipes old records
- documentation fixes
- befw-sync timeouts & races fixed

### 0.1.1
- Uses short hostnames instead of FQDN
- Additional sleep(s) if errors repeat
- Fix ipset refresh
- Fix static ipset aliases

### 0.1.0
- a huge documentation update
- befw-firewalld now supports configuration file
- All hard-coded settings gone to the past
### 0.0.9
- Multiple ports support for services via tags
- Performance optimisation
### 0.0.8
- befw-sync added
- logging improvements
- ipset name length quickfix
### 0.0.7
- befw-cli - new functions
### 0.0.6
- befw-cli program added
- now befw-firewalld watches for kv & services changes
### 0.0.5
- befw-firewalld now supports data collection via NFLOG:402
### 0.0.4
- befw-firewalld now watches for configuration changes
### 0.0.3
- Empty ( collect all/block all ) ipset support
### 0.0.2
- Alias (befw/$alias$/*) support
### 0.0.1
- Initial version
