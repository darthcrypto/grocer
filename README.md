# grocer

### User Experience
```bash
1) gf gets on Google Sheets  makes the spreadsheet of food she wants
2) gf gets on Slack, says "/grocer"
3) slack reaches out to AWS, runs Lambda Function(python)
4) list is in Google Tasks
```

### Needs:
```bash
1) python code to transfer data from Sheets to Tasks
2) Slack bot
3) AWS stuff???
```


### Dev environment setup:
```bash
#in project directory:
virtualenv --python python3 envgrocer
source envgrocer/bin/activate
deactivate
```

### Dependency management:
```bash
#pin depedencies in current project:
pip freeze > requirements.txt

#download dependencies when working in different environment:
pip install -r requirements.txt
```