---
title: Active Scan
url: https://www.zaproxy.org/docs/desktop/start/features/ascan/
date: '0001-01-01'
author: ''
feed_url: https://www.zaproxy.org/index.xml
---
Active Scan Active scanning attempts to find potential vulnerabilities by using
known attacks against the selected targets. Active scanning is an attack on those targets. You should NOT use it on web applications that you do not own. In order to facilitate identifying ZAP traffic and Web Application Firewall exceptions, ZAP is accompanied
by a script “AddZapHeader.js” which can be used to add a specific header to all traffic that passes through
or originates from ZAP. eg: X-ZAP-Initiator: 3
