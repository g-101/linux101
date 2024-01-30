# Linha de Comando

## Shell

Uma vez que um usuário digita um comando, o terminal aceita o que o usuário digitou e o passa para o shell.

**O que é um terminal?**

É um programa que abre uma janela e permite que você interaja com o shell. Há vários emuladores de terminal diferentes: **gnome-terminal, konsole, xterm, entre outros**.

**O que é Shell?**

O shell é o interpretador de linha de comando que traduz os comandos inseridos por um usuário em ações a serem executadas pelo sistema operacional.

O ambiente Linux possui muitos shells diferentes, porém o shell mais usado nas distribuições Linux é chamado de Bash.

Quando o aplicativo de terminal é executado e um shell é exibido, ele mostra uma parte importante da interface: O prompt.

O prompt além de servir para indicar que os comandos podem ser executados, também transmite informações úteis ao usuário.

Abaixo uma estrutura de prompt comum:

```bash
debian@localhost:~$
```

O prompt exibido contém as seguintes informações:

-   debian: é o nome do usuario atual.
-   localhost: nome da maquina do usuario.
-   ~ (til): diretorio atual.
-   $ (simbolo do dolar): símbolo padrão do prompt para usuários comuns, que não são root.
