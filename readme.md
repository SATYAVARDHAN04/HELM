```bash
helm install nginx .
```

```bash
helm list
```

```bash
helm upgrade nginx .
```

```bash
helm status nginx
```

```bash
helm history nginx
```
```bash
helm upgrade nginx --description "upgrading to stabe nginx version" .
```

```bash
helm rollback nginx # goes to previous version
```

```bash
helm rollback nginx 1 
```