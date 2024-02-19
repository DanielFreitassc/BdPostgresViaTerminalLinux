# Aqui neste repostorio ensinarei a criar um banco de dados postgres via termial do linux 

# Abra o terminal e vamos criar o database.
```
sudo -u postgres createdb nome-do-banco
```
![create](https://github.com/DanielFreitassc/BdPostgresViaTerminalLinux/assets/129224303/52156395-abda-41d5-be4d-a1a85d11188f)


# Para entrar você pode usar este comando abaixo.
```
sudo -u postgres psql nome-do-banco
```
![psql](https://github.com/DanielFreitassc/BdPostgresViaTerminalLinux/assets/129224303/7ab159a7-1d20-4eab-a687-e597a7eb9a65)

# Comandos para visualização
- \dt mostra tabelas
  
  ![tabela](https://github.com/DanielFreitassc/BdPostgresViaTerminalLinux/assets/129224303/ed158a2d-b0f2-4384-9a6b-8fbf10661fdb)

- \l mostra o databases criados
  
![databases](https://github.com/DanielFreitassc/BdPostgresViaTerminalLinux/assets/129224303/841b5d1a-e4c9-4667-a269-4e517a1deedf)

- \c nome-do-banco , é utilizado para entrar em outro banco de dados
  
![troca de database](https://github.com/DanielFreitassc/BdPostgresViaTerminalLinux/assets/129224303/7dddea68-f9b8-4464-a65e-cd001a2b4fa4)


- \q sai da visualização 
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
DROP DATABASE "nome-do-banco";
```
.obs aspas em alguns casos devem ser utilizadas
