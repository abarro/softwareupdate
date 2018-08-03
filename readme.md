*pra rodar e buildar local:*
`bundle exec jekyll serve`

*outros comandos*
```jekyll build
# => The current folder will be generated into ./_site

jekyll build --destination <destination>
# => The current folder will be generated into <destination>

jekyll build --source <source> --destination <destination>
# => The <source> folder will be generated into <destination>

jekyll build --watch
# => The current folder will be generated into ./_site,
#    watched for changes, and regenerated automatically.
```

*Pra postar: git push origin master*
*Convenção pra nomear arquivo de post*
`YEAR-MONTH-DAY-title.MARKUP`