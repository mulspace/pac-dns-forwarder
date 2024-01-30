DNS forwarder with PAC
====

## In order to keep it simply, it can only focus on the belows tasks
- Base on the PAC file, it can set the DNS forwarding destination.
- When the DNS query failed based on PAC, it can fallback to default destination. It can only configure in command line.
- It can only listen on UDP/TCP, not for tls/https and etc.
