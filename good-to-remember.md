### EAP

* By default, cache-type of your security-domain is "default" which uses a ConcurrentHashMap implementation which never expire cached entries. However, when the HTTP session is invalidated, the cache entry is removed in EAP6 (not removed in EAP7).
