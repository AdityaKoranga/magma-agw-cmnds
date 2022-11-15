# magma-agw-cmnds

1. for hardware-id and challenging key
```bash
show_gateway_info.py
```
for magma service
```bash
sudo service magma@* stop
sudo service magma@magmad start
sudo service magma@* status
```
> you can also check the status of single service using `sudo service magma@<service-name> status`. Instead of `*` use `service name`.

for checking logs
```bash
sudo journalctl -fu magma@<service-name>
```
