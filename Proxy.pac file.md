Proxy.pac file  
  
function FindProxyForURL(url, host) {  
    var ip = dnsResolve(host);  
      
    if (ip == "108.196.192.90") {  
        return "DIRECT";  
    }  
      
    return "PROXY geo.iproyal.com:12312";  
}  
