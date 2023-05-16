[![release-rapidapi](https://github.com/Siebjee/alfred-workflows/actions/workflows/rapidapi.yaml/badge.svg)](https://github.com/Siebjee/alfred-workflows/actions/workflows/rapidapi.yaml)
[![release-github](https://github.com/Siebjee/alfred-workflows/actions/workflows/github.yaml/badge.svg)](https://github.com/Siebjee/alfred-workflows/actions/workflows/github.yaml)
[![release-networklookup](https://github.com/Siebjee/alfred-workflows/actions/workflows/networklookup.yaml/badge.svg)](https://github.com/Siebjee/alfred-workflows/actions/workflows/networklookup.yaml)
[![release-nmap](https://github.com/Siebjee/alfred-workflows/actions/workflows/nmap.yaml/badge.svg)](https://github.com/Siebjee/alfred-workflows/actions/workflows/nmap.yaml)
[![release-slack](https://github.com/Siebjee/alfred-workflows/actions/workflows/slack.yaml/badge.svg)](https://github.com/Siebjee/alfred-workflows/actions/workflows/slack.yaml)


# Port workflow
Use keyword `port` and a port number to lookup the default serice of that port.
![port](./screenshots/port.png)

# Slack workflow
Use keyword `slack` and it shows you your recent chats.
![slack](./screenshots/slack.png)

# NMAP workflow
Use keyword: `nmap` and a target `10.10.10.10` to start a simple portscan.
![nmap_scan](./screenshots/nmap_scan.png)

# GitHub workflow
Use keyword `gh clear` to clear the known repositories.
![gh_clear](./screenshots/gh_clear.png)

Use keyword `gh` and a repository name to quickly open this repository in your browser.
![gh_search](./screenshots/gh_search_1.png)

Modifiers:
- `command` - Copy ssh clone URL
- `option` - Copy HTTPS clone URL
- `control` - Open pull request dashboard

Use keyword `gh update` to update the known repositories using the github API and your access token.
![gh_update](./screenshots/gh_update.png)


# RapidAPI workflow
Configure:
- keyword, default `paw`
- location, example: `/path/to my/projects/dir`

Use keyword `paw` to open the application. Or search for your RapidAPI project.
![rapidapi](./screenshots/rapidapi.png)
