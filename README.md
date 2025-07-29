# Home Lab: Sophos XG NGFW – Deny All + White List Firewall

## Project goals:
- Create policy "deny all:
- Implement "white list" (for chosen website and services)
- Add SSL Inspection
- Learn network managment

## Technologies:
-**Proxmox VE** - Hypervisor
-**Sophos XG** - Virtual NGFW - home edytion
-**Windows 10 VM** - test client
-**AdGuard Home** - DNS implementation

## Main function and configuration
- 'Deny All' - as default policy
- 'Allow DNS', 'Allow HTTPS' - for chosen services
- Web Filtering - white list URL
- SSL Inspection and instalation sophos certificate
- Exclusion for aplicationn like Goodle Chrome (dl.google.com for download and update Google Chrome) 
