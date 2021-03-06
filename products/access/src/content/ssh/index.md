---
title: "SSH"
alwaysopen: false
weight: 5
---

Cloudflare Access can secure connections over Secure Shell (SSH)

Doing so requires configuring your Access-protected server to use Argo Tunnel for SSH connections. Argo Tunnel exposes your origin server directly to Cloudflare, avoiding external internet connections. Using Argo Tunnel ensures that Cloudflare evaluates all requests to your application.

Establishing an SSH connection to an Access-protected server requires installing Cloudflare's `cloudflared` command-line tool on the client machine so that it can connect over Argo Tunnel.

|Guide|Description|
|---|---|
|[SSH Connection](https://developers.cloudflare.com/access/ssh/ssh-guide/)|Guide to connecting a machine to Cloudflare and connecting as an end user over SSH.|
|[Short-lived certificates](https://developers.cloudflare.com/access/ssh/short-live-cert-server/)|Guide to replacing SSH keys with short-lived certificates from Cloudflare.|
|[PuTTY Clients](https://developers.cloudflare.com/access/ssh/putty/)|Guide to using a PuTTY client to connect over SSH through Cloudflare Access.|

A video guide is [also available](https://developers.cloudflare.com/access/videos/configuring-access/).