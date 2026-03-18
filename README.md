# Container-UID-GID
Manual UID/GID overrides for non-Polarix containers

# User Mapping

| Container                                               | UID:GID          | Notes                                         |
|---------------------------------------------------------|------------------|-----------------------------------------------|
| docker.io/miniflux/miniflux:latest-distroless           | 300000:300000    |                                               |
| quay.io/redlib/redlib:latest                            | 300001:300001    |  Use the same mapping for alt containers      |
| dhi.io/uptime-kuma:2                                    | 300002:300002    |                                               |
| docker.io/coturn/coturn:alpine                          | 300003:300003    |                                               |
| docker.io/xgaia/signaturepdf                            | 300004:300004    |                                               |
| ghcr.io/jitsi-contrib/hardened-images/web               | 300005:300005    |                                               |
| ghcr.io/jitsi-contrib/hardened-images/prosody           | 300006:300006    |                                               |
| ghcr.io/jitsi-contrib/jitsi-oidc-adapter:latest         | 300007:300007    |                                               |
| gnuxie/draupnir:latest                                  | 300008:300008    |                                               |
| oci.element.io/element-admin:latest                     | 300009:300009    |                                               |
| ghcr.io/etkecc/synapse-admin:latest                     | 300010:300010    |                                               |
| ghcr.io/element-hq/lk-jwt-service:latest                | 300011:300011    |                                               |
| docker.io/livekit/livekit-server:latest                 | 300012:300012    |                                               |
| kweg/omnipoly:latest                                    | 300013:300013    |                                               |
| docker.io/kweg/omnipoly:latest                          | 300014:300014    |                                               |
| ghcr.io/stirling-tools/stirling-pdf:latest-ultra-lite   | 300015:300015    |                                               |
| ghcr.io/goauthentik/ldap                                | 300016:300016    |                                               |
| ghcr.io/goauthentik/rac                                 | 300017:300017    |                                               |
| ghcr.io/jitsi-contrib/hardened-images/jicofo            | 300018:300018    |                                               |
| ghcr.io/jitsi-contrib/hardened-images/jvb               | 300019:300019    |                                               |
