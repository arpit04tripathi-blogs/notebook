# jekyll-template

This repo is a template to create more repos for jekyll based repo.
- This is based on jekyll-theme [minima](https://github.com/jekyll/minima#contents-at-a-glance)
- Official documentation for jekyll is [here](https://jekyllrb.com/)

**table of contents**
- [jekyll-template](#jekyll-template)
- [Getting started](#getting-started)
- [Troubleshooting](#troubleshooting)
  - [Port already used](#port-already-used)


# Getting started
1. Create new repo using this template `Use this template` -> `Create a new repository`.
2. `git clone` your repo to your laptop.
3. Open in Editor, ex. Visual Studio Code
4. you should have these installed - `docker` and `chrome browser`
5. Run the command in terminal - `sh scripts/jekyll-new.sh`
6. This creates basic folder structure.
7. Replace all instances of text `jekyll-template` with your repo name (example - `my_repo_name`), this will change below files
   1. `docker-compose.yml` - change `container_name: jekyll-template` to `container_name: my_repo_name`
   2. `localhost.sh` - `http://localhost:9999/jekyll-template/` to `http://localhost:9999/my_repo_name/`
8.  `_config.yml`
    1.  update `baseurl` as `/my_repo_name`
    2.  uncomment `exclude:` and add below yml section to ignore files for creating _site
9.  Delete files 
   - `scripts/jekyll-new.sh`
   - `setup.md`
   - `docker/docker-compose-new.sh` and `docker/docker-compose-new.yml`

```yml
# ignore files for creating _site
exclude:
  - scripts/
  - docker/
  - README.md
```

# Troubleshooting

## Port already used
```bash
# find process_id using the port
netstat -vanp tcp | grep 9999
# kill the process based on process_id
kill -9 <PROCESS_ID>
```
