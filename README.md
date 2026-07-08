# yoho-vpn-manifest

Public, Ed25519-signed bootstrap manifest for the Yoho VPN app's multi-endpoint failover.
The app verifies `sig` against an embedded public key before trusting `payload.endpoints`, so
this mirror is a dumb static host — tampering fails verification. Served via GitHub raw + jsDelivr.
