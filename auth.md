---
permalink: auth
title: Authentication
---

# Authentication
Melony uses next auth so you will need the session cookie. When making a request set the `Cookie` header to `__Secure-next-auth.session-token=your-next-auth-token`. Do not share this with anyone as it gives access to your entire Melony account.
