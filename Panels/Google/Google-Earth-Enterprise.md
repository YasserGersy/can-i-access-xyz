# Google Earth Enterprise
Google Earth Enterprise (GEE) is Google’s on-premises version of Google Earth that organizations can host on their own servers.

## Type
- On-premises

## Dork
```
title:"GEE Server"
http.favicon.hash:-363070619
```

## Fingerprints
```
Earth Server admin pages
GEE Server</title>
```

## Default-Credentials
```
geapacheuser:geeadmin
```
## Paths
```
/admin/
```

## Success
```
200 OK AND Contain_all(['DashboardPanel', 'Earth Enterprise Server'])
```

## References
- https://www.opengee.org/
  <img width="1351" height="354" alt="image" src="https://github.com/user-attachments/assets/e9f7ca78-4ead-4b39-9c64-76b8a3f168b1" />

