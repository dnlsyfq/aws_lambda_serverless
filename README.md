

Setup
```
npm install -g serverless

serverless config credentials --provider aws --key XXX --secret YYY --profile serverless-admin


accesskey :AKIAQ******
secretaccesskey : +shbuR*****
```

### Simple Hello world
```
1. serverless or sls
2. sls create --template aws-python --path <projet-name>
3. Modify serverless.yml
4. Modify handler.py
5. sls deploy -v
```
* see result from terminal
```
6. sls invoke -f hello -l

```
* updating function only from terminal 
```
7. modify handler.py
8. sls deploy function -f hello
9. sls invoke -f hello -l
```
* fetching function logs from terminal
```
1. sls logs -f hello -t
```
* removing function
```
1. sls remove
```