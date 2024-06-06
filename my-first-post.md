# đây là bài viết test ở github
## Managing keys

Generate new key
```bash
nibid keys add wallet
```
Recover key
```bash
nibid keys add wallet --recover
```
List all key
```bash
nibid keys list
```
Delete key
```bash
nibid keys delete wallet
```
Export key
```bash
nibid keys export wallet
```
Import key
```bash
nibid keys import wallet wallet.backup
```
Query wallet balances
```bash
nibid q bank balances $(nibid keys show wallet -a)
```
## Managing validators 

end
