# approve.sh
A simple CLI tool to work with ApproveAPI.

```bash
approve.sh: A CLI to work with ApproveAPI. 

where:
 	--help, -h show this help text
 	--key , -k API key found here: https://dashboard.approveapi.com/api_keys
 	--user, -u user(s) to send an approval prompt
 	--title, -t title for prompt
 	--body, -b body for prompt
 
example:
 	./approve.sh --key=1234 --user=bobby@acme.co --body='Allow access to X?'
```
