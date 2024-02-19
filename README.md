# Aqui neste repostorio ensinarei a criar um banco de dados postgres via termial do linux 

# Abra o terminal e vamos criar o database.
```
sudo -u postgres createdb nome-do-banco
```
# Para entrar você pode usar este comando abaixo.
```
sudo -u postgres psql nome-do-banco
```
# Comandos para visualização
- \dt mostra tabelas
- \l mostra o databases criados
- \c nome-do-banco , é utilizado para entrar em outro banco de dados

# Apagar database 
```
sudo -u postgres psql postgres 
```
# Veja o nome do banco que deseja remover com o comando
```
\l
```
## remova o banco com o comando
```
DROP DATABASE nome-do-banco;
```
