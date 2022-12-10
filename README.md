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
serverless invoke -f listarPacientes
```

rodar localmente informando parametros de entrada :
```
serverless invoke -f listarPacientes -d '{"vai":"corinthians"}'
```

deploy na aws, de toda aplicação
```
serverless deploy
```

deploy na aws, passando apenas uma função
```
serverless deploy -f obterPacientes
```

verificar logs tem tempo real(CloudWatch)
```
serverless logs -f obterPacientes --tail
```

verificar informações 
```
serverless info
```

iniciar npm
```
npm init -y
```

adicionando plugin, para emular projeto localmente
```
npm install serverless-offline --save-dev
```

iniciar projeto localmente
```
sls offline
```


## Plugins utilizados
https://www.serverless.com/plugins/serverless-offline

## 🤝 Referencias
https://www.alura.com.br/

https://www.serverless.com/


