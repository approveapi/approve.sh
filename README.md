# approve.sh
A simple CLI tool to work with ApproveAPI.

## How does it work?

Use `approve.sh` to request an approval from someone for any workflow in real-time.

- If the user **approves**, you can trigger the workflow by attaching it to `&&`. 
- If the user **rejects**, the script will fail with an exit code `1` and your workflow will not get triggered.

For example:

```bash

./approve.sh --key="sk_test_123" --user="bobby@acme.co" --body='Allow X?' && allow_x

```

## Options

```bash
approve.sh: A CLI to work with ApproveAPI. 

where:
 	--key ,  -k 	API key found here: https://dashboard.approveapi.com/api_keys
 	--user,  -u 	user(s) to send an approval prompt
 	--title, -t 	title for prompt
 	--body,  -b 	body for prompt
```

