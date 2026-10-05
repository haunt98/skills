# SKILLS

## [ankitpokhrel/jira-cli](https://github.com/ankitpokhrel/jira-cli)

```sh
brew install jira-cli

jira init

rm -rf ~/.agents/skills/jira-cli
cp -rf jira-cli ~/.agents/skills/
```

## [avivsinai/jenkins-cli](https://github.com/avivsinai/jenkins-cli)

```sh
go install github.com/avivsinai/jenkins-cli/cmd/jk@latest

jk auth login https://jenkins.company.example

# Clone the repository
rm -rf ~/.agents/skills/jk
cp -rf ./skills/jk ~/.agents/skills
```

## [pchuri/confluence-cli](https://github.com/pchuri/confluence-cli)

```sh
go install github.com/avivsinai/jenkins-cli/cmd/jk@latest

confluence init --domain confluence.company.example

# Clone the repository
rm -rf ~/.agents/skills/jk
cp -rf ./skills/jk ~/.agents/skills
```
