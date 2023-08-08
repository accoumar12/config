# My config files

## Command to commit a new config file 
curl -L -X PUT -H "Authorization: token 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" -H "Content-Type: application/json" -d '{
    "message": "Add .bash_aliases file",
    "content": "'"$(base64 -w 0 .bash_aliases)"'"
}' "https://api.github.com/repos/accoumar12/config/contents/dotfiles/.bash_aliases"

https://docs.github.com/en/rest/repos/contents?apiVersion=2022-11-28
