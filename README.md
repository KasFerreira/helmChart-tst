# Repositório centralizado de Helm charts 

### Como criar o seu primeiro chart

Execute o seguinte comando dentro da sua estrutura de charts:

```
helm create <nome do seu chart>
```

Adicione um ícone ao seu chart:
- No arquivo Chart.yaml
  - entrada: icon
  - exemplo:
    - icon: https://logodownload.org/wp-content/uploads/2018/03/nginx-logo-1.png

Envio ao seu repositório git:

```
# adicione 
git add .

# commit
git commit -m "msg"

# push
git push 
```