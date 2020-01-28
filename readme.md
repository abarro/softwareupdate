*pra rodar e buildar local:*
`bundle exec jekyll serve`
#isso já vai procurar pelas mudanças de css e html. Só dar um refresh no browser pra ver.

Edite o arquivo assents/main.scss para editar o css.

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
*Talvez tenha que estar em gh-pages a branch*
*Convenção pra nomear arquivo de post*
`YEAR-MONTH-DAY-title.MARKUP`