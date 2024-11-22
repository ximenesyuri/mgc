# Autenticação

1. Ao se autenticar com ferramentas terceiras compatíveis com o block storage da MGC, como `boto3` e `rclone`, deve-se utilizar o `api_key_id` (ao invés do `api_key`) e o `api_secrets`.

# Output

1. Por padrão, os outputs dos comandos do `mgc` (a CLI da MGC) são coloridos em ANSI code. Para parseá-los em `json` ou `yml`, deve-se passar, junto de `--output json/yaml`, a opção `--raw`, a qual retorna o output em plain text, sem coloração. 
