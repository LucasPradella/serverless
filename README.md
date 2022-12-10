# Estudos aplicações serverless

# Explorando serverless framework 

## 💻 Principais comandos

Ubuntu:

instalar serverless :
```
npm install -g serverless
```

criar projeto utilizando template sls:
```
serverless create --template aws-nodejs --path cadastro-paciente
```

rodar localmente :
```
serverless invoke -f listaPacientes
```

rodar localmente informando parametros de entrada :
```
serverless invoke -f listaPacientes -d '{"vai":"corinthians"}'
```

deploy na aws
```
serverless deploy
```


## 🤝 Referencias
https://www.alura.com.br/

https://www.serverless.com/