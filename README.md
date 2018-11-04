# ivansible.lin_ipv6_cloudflare

This installs a small linux bash script that detects ipv6 on a network
inteface and updates a cloudflare dns record.


## Requirements

None


## Variables

Available variables are listed below, along with default values.

    ipv6_cloudflare_email: user@example.com
    ipv6_cloudflare_token: supersecret
    ipv6_cloudflare_interface: eth0
    ipv6_cloudflare_hostname: ipv6.example.com
    ipv6_cloudflare_zone_id: 123
    ipv6_cloudflare_record_id: 456


## Tags

- `lin_ipv6_cloudflare_all`
- `lin_ipv6_cloudflare_install`
- `lin_ipv6_cloudflare_configure`


## Dependencies

None


## Example Playbook

    - hosts: vagrant-boxes
      roles:
         - role: lin_ipv6_cloudflare
           variable1: 1
           variable2: 2


## License

MIT

## Author Information

Created in 2018 by [IvanSible](https://github.com/ivansible)
