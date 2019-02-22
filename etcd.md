---
layout: 2017/sheet
og_type: article
type: article
category: Markup
excerpt_separator: "<!--more-->"
prism_languages:
- "\\"
title: ETCD
---

Getting started
---------------
{: .-two-column}

### List Members

```bash
export ETCDCTL_API=3
export ETCD_CA=/opt/rke/etc/kubernetes/ssl/kube-ca.pem
export ETCD_CERT=/opt/rke/etc/kubernetes/ssl/kube-etcd-
export ETCD_CERT_KEY=/opt/rke/etc/kubernetes/ssl/kube-etcd-
etcdctl --cacert=${ETCD_CA} --cert=${ETCD_CERT} --key=${ETCD_CERT_KEY}
```