# notion-scripts
Scripts for working with notion.

## how to
In order to run this script you will need to export a notion integration token
and a notion database ID to the NOTION_INTEGRATION_TOKEN and NOTION_DATABASE_ID
environment variables.

### setup
```
python3 -m virtualenv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
export PATH=$PATH:.
export NOTION_INTEGRATION_TOKEN='<token>'
export NOTION_DATABASE_ID='<database_id>'
```

### execute
```
create-task "Release the Kraken" 2030-02-29
```
