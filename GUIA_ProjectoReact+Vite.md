# CRIAR  PROJETO NO REACT USANDO VITE 
 - Verificar se temos node.js instalado, no terminal digitar:
```
node -v
```
 - Installar node.js no caso de não ter: nodejs.org, download e instalar
 - Depois de instalar, rodar o mesmo comando, e algo deste genero tem de aparecer:
[image](https://github.com/user-attachments/assets/eff5addf-87df-4565-98e5-08ad04b46579)

 - Agora no VScode, instalar a extenção "prettier"
 Para a activar: Prefeências -> Settings -> (Procurar "Format on save"), verificar a caixa correspondente.

Criar a app, usando VITE:

```
npn create vite@latest
```
Ou para criar a app usando uma versão espesifica do vite:
```
npn create vite@4.1.0
```
Autorizar instalação dos packages
```
y
```
Nomear o Projeto;
Escolher a framwork -> React;
Escolher a linguagem -> TypeScript;

-> PROJECTO CRIADO <-

Agora, navegar até a pasta do projeto.
```
cd D:\Git\gestvid
```
Instalar as dependências. (Estando dentro da pasta!)
```
npm install
```
ou
```
npm i
```
Abrir o projeto no VScode
```
code .
```
Abir o terminal no VScode (Terminal -> New Terminal)
Iniciar o servidor web (No terminal do VScode)
```
npm run dev
```
É possivél que surjam alguns erros no projeto, nos ficheiros
- tsconfig.app.jason
- tsconfig.node.jason

Se isso acontecer, simplesmente comentem as linhas que dão erro.
```
//
```
E pronto, se chegaram até aqui terão uma app demo a rodar no endereço localhost:5173 

