<details>
<summary>
<strong> Read this guide in English </strong>
</summary>
    <ul>
        <li><a href="./CONTRIBUTING.md"> English </a></li>
    </ul>

</details>

# Requisitos para contribuir

- Conhecimentos básicos de programação são obrigatórios.
- A capacidade de usar Git e GitHub.
- Algum conhecimento de Java, Python, HTML/CSS/JavaScript é preferível para uma vantagem inicial.
- Habilidades de UI/UX Design são apreciáveis, mas não obrigatórias.
- Alguma ideia sobre SQL, JSP, XML, PHP ou vontade de aprender.

# Diretrizes gerais de codificação

Se você quiser adicionar um recurso ou corrigir um bug, teremos o maior prazer em aceitar o PR! Pedimos apenas algumas coisas:

- Certifique-se de que seu código não contém erros do analisador, por exemplo:
  - O código é compatível com o modo forte.
  - O código está livre de erros de lint.
- Formate seu código com `ms-python.python` para Python, `redhat.java` ou `./eclipse-java-google-style.xml` para Java e `esbenp.prettier-vscode` para HTML/CSS/JavaScript .
- Escrever documentação útil.
- Se você gostaria de fazer uma mudança maior/fundamental na base de código, envie um exemplo leve de PR/problema.

# 💥 Como Contribuir

- Dê uma olhada nas issues existentes [Issues](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/issues) ou [crie uma nova issue](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/issues/new/choose)!
- [Fork the Repo](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/fork). Em seguida, crie uma branch para qualquer problema no qual esteja trabalhando. Finalmente, comita o seu trabalho.
- Crie um **[Pull Request](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/compare)** (_PR_), que será prontamente analisado e receberá sugestões de melhorias pela comunidade.
- Adicione screenshots ou capturas de tela ao seu Pull Request para nos ajudar a entender os efeitos das mudanças propostas em seu PR.

## ⭐ COMO FAZER UM PULL REQUEST:

**1.** Comece fazendo um fork do repositório [**ISUTC-LEIT-LECC**](https://github.com/edilsonmatola/ISUTC-LEIT-LECC). Clique no <a href="https://github.com/edilsonmatola/ISUTC-LEIT-LECC/fork"><img src="https://i.imgur.com/G4z1kEe.png" height="21 " width="21"></a> no canto superior direito.

**2.** Clone seu fork do novo repositório:

```bash
git clone https://github.com/<your-github-username>/ISUTC-LEIT-LECC
```

**3.** Navegue até o novo diretório do projecto:

```bash
cd ISUTC-LEIT-LECC/
```

**4.** Configure o comando upstream:

```bash
git remote add upstream https://github.com/edilsonmatola/ISUTC-LEIT-LECC.git
```

**5.** Mude de main para **development**.

```terminal
git check-out development
```

**6.** Crie uma branch de recursos a partir da branch **development**!

```bash
git checkout -b YourBranchName
```

**7.** Sincronize seu fork ou seu repositório local com o repositório de origem:

- Em seu fork de repositório, clique em "Fetch upstream"
- Clique em "Fetch and merge"

### Como alternativa, a maneira Git CLI para sincronizar o fork do repositório com o repositório de origem:

```bash
git fetch upstream
```

```bash
git merge upstream/development
```

### [Github Docs](https://docs.github.com/en/github/collaborating-with-pull-requests/addressing-merge-conflicts/reresolution-a-merge-conflict-on-github) para sincronização

**8.** Faça suas alterações no código-fonte.

⚠️ **Actualize** o seu **Java SDK e JRE/Pyhton Version**, se aplicável.

**9.** Organize suas alterações e comita:

⚠️ **Certifique-se** de não executar os comandos `git add .` ou `git add *`. Em vez disso, organize suas alterações para cada arquivo/pasta

```bash
git add <nome do arquivo>
```

```bash
git commit -m "<your_commit_message>"
```

**10.** Envie seus commits locais para o repositório remoto:

```bash
git push origem YourBranchName
```

**10.** Crie um [Pull Request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)!

⚠️ **Certifique-se** de enviar o Pull Request para a branch **development**.

## Lista de verificação de contribuição

Ao abrir um problema ou pull request, use este modelo em seu comentário:

- [ ] Eu li as diretrizes de contribuição em [CONTRIBUTING.md](CONTRIBUTING.md)
- [ ] Eu verifiquei outros problemas/PRs para ter certeza de que não é uma duplicata
- [ ] Eu concordo que minha contribuição está sujeita à [Licença MIT](LICENSE.md) deste projeto

**11.** **Parabéns!** Você fez sua primeira contribuição para [**ISUTC-LEIT-LECC**](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/graphs/contributors)! 🙌🏼

# Guia de estilo para mensagens de commit do Git :memo:

**Como você pode agregar mais valor aos seus registros de contribuição:**

- Use o tempo presente. (Exemplo: "Adicionar recurso" em vez de "Recurso adicionado")
- Use o modo imperativo. (Exemplo: "Mover item para...", em vez de "Movimentei item para...")
- Limite a primeira linha (também chamada de Linha de Assunto) a _50 caracteres ou menos_.
- Capitalizar a linha de assunto.
- Separe o assunto do corpo com uma linha em branco.
- Não termine a linha de assunto com um ponto.
- Enrole o corpo em _72 caracteres_.
- Use o corpo para explicar o _what_, _why_, _vs_ e _how_.
- Referência [Issues](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/issues) e [Pull Requests](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/pulls) liberalmente após a primeira linha.

## 💥 Issues

Para discutir as alterações, você pode [abrir uma issue](https://github.com/edilsonmatola/ISUTC-LEIT-LECC/issues/new/choose) sobre o que você gostaria de contribuir. Melhorias são sempre encorajadas e apreciadas.

## Tudo de bom! 🥇

Sente-se e relaxe, você deu sua contribuição!

Para obter ajuda para começar a usar Java, Python, HTML/CSS/JavaScript, PHP e JSP, consulte a documentação on-line, que oferece tutoriais, exemplos, orientação sobre desenvolvimento e uma referência completa da API.
