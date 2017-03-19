# trash-gmail-msg
A simple Tool to trash gmail messages based on "From" email Id

1. Set up and download config from here https://developers.google.com/gmail/api/quickstart/go
2. Rename and move configuration into currentdir/client_secret.json
3. go build
4. FROM=abc@abc.com ./trash-gmail-msg
5. Provide authorization when prompted and copy paste the code
5. Open you gmail and view messages under trash and delete

# *** Ensure that you authorize as per https://developers.google.com/gmail/api/v1/reference/users/messages/trash (All access) 
