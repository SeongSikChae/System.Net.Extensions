# System.Net namespace Extensions

## System.Net.IPAddress Extensions

* IPAddress GetNetwork(IPAddress netmask)
* bool ValidNetwork(IPAddress netmask)
* bool ValidHost(string cidr)
* bool ValidHost(IPAddress network, IPAddress netmask)
* int ToCidr()
* IPAddress GetBroadcast(IPAddress netmask)
* IPAddress GetFirstAddress(IPAddress netmask)
* IPAddress GetLastAddress(IPAddress netmask)
* uint GetAddressCount()
* Dictionary<string, HashSet<IPAddress>> GetLocalHostAddresses(AddressFamily addressFamily)

## System.Net.SubnetCalculator

* SubnetInfo Calculate(IPAddress host, string cidr)
* SubnetInfo Calculate(IPAddress host, IPAddress netmask)

## System namespace Extensions

### Int32 Extensions

* IPAddress ToSubnetMask()
* uint GetAddressCount()