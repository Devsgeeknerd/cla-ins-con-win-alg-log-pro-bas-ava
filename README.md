<!-- TITLE -->
# Instalação e Configuração no Windows

***Conteúdo da Aula:***

1. Baixar os *softwares* que estão disponíveis junto aos materiais para *download* desta aula.

2. Instalar e configurar o ***Java***.

    2.1. Abra o terminal e execute o comando abaixo para checar se já existe alguma versão do *Java* instalada:

    ```powershell
    java --version
    ```

    ou

    ```powershell
    java -version
    ```

    2.2. Se for apresentada alguma versão, verifique se é uma versão 11 ou maior.

    2.3. Se for igual ou maior a 11, tudo certo.

    2.4. Pode pular esta etapa.

    2.5. Se for uma versão menor, primeiro desinstale e então instale e configure esta nova versão.

    2.6. Após a instalação, vamos criar uma variável de ambiente chamada **JAVA_HOME** apontando pata o diretório de instalação do *Java*.

    2.7. Feche qualquer tela ou terminal aberto, reabra o terminal e teste novamente o comando para checar a versão:

    ```powershell
    java --version
    ```

    ou

    ```powershell
    java -version
    ```

    2.8. Vamos criar um projeto em ***Java*** para testarmos o ambiente.

3. Instalar e configurar o compilador ***C/C++.***

    3.1. Abra o terminal e execute o comando abaixo para checar se já existe alguma versão do compilador *C/C++* instalada:

    ```powershell
    gcc --version
    ```

    3.2. Se for apresentada alguma versão, pode pular esta etapa.

    3.3. Instale o compilador.

    3.4. Verifique se o comando de checagem de versão e reconhecido no terminal:

    ```powershell
    gcc --version
    ```

    3.5. Se for reconhecido pode ir para o próxima etapa, caso contrario continue abaixo.

    3.6. Adicione os binários do compilador no **path** do sistema.

    3.7. Feche qualquer tela ou terminal aberto, reabra o terminal e teste novamente o comando para checar a versão:

    ```powershell
    gcc --version
    ```

4. Instalar e configurar o ***Python***.

    4.1. Abra o terminal e execute o comando abaixo para checar se já existe alguma versão do *Python* instalada:

    ```powershell
    python --version
    ```

    4.2. Instale o *Python*.

    4.3. Verifique se o comando de checagem de versão e reconhecido no terminal:

    ```powershell
    python --version
    ```

    4.4. Se for reconhecido pode ir para a proxima etapa, caso contrario continue abaixo.

    4.5. Adicione os binários do *Python* no **path** do sistema.

    4.6. Feche qualquer tela ou terminal aberto, reabra o terminal e teste novamente o comando para checar a versão:

    ```powershell
    python --version
    ```

    4.7. Vamos criar um projeto ***Python*** para testarmos o ambiente.

5. Instalar o ***Eclipse***.

    5.1. Descompacte o *Eclipse*.

    5.2. Crie um diretório chamado *apps* no seu diretório home e cole o *Eclipse* ali dentro.

    5.3. Execute o *Eclipse*.

6. Instalação do ***plugin CDT*** no *Eclipse* para integrar o *Eclipse* com o compilador *C/C++*.

   6.1. Com o *Eclipse* aberto, acesse o menu **Help** => ***Install New Software***.

   6.2. Clique no botão ***ADD***.

    * Na caixa *Name* digite: **CDT**.

    * Na caixa *Location* digite:

    ```http
    https://download.eclipse.org/tools/cdt/releases/9.4
    ```

    6.3. Clique em *Add*.

    6.4. Após carregar os dados na lista, selecione ***main*** e finalize a instalação.

    6.5. Reinicie o *Eclipse* após isso.

    6.6. Com o *Eclipse* aberto novamente, acesse o menu **Window** => **Preferences** => **C/C++** => **New C/C++ Project Wizard**.

    6.7. Marque *Empty Project* com o *GCC Toolchain Preferencial*.

    6.8. Clique em **Apply** e **close**.

    6.9. Vamos criar um projeto em **C** par testarmos o ambiente.

7. Instalar o ***Plugin PyDev*** no *Eclipse*.

   7.1. Com o *Eclipse* aberto, acesse o menu **Help** => ***Install New Software***.

   7.2. Clique no Botão ***ADD***.

    * Na caixa *Name* digite: **PyDev**.

    * Na caixa *Location* digite:

    ```http
    https://www.pydev.org/updates
    ```

    7.3. Clique em *Add*.

    7.4. Após carregar os dados na lista, selecione ***main*** e finalize a instalação.

    7.5. Reinicie o *Eclipse* após isso.

    7.6. Vamos criar um projeto **C** para testarmos o ambiente.
<!-- TABLE OF CONTENTS -->
## TABELA DE CONTEÚDO

<!-- * [Vista por cima](#vista-por-cima) -->
<!--  * [Foto da tela](#foto-da-tela) -->
<!--  * [Links](#links) -->
<!-- * [Meu processo](#meu-processo) -->
<!--  * [Construído com](#construido-com) -->
<!--  * [O que aprendi](#o-que-aprendi) -->
<!--  * [Desenvolvimento contínuo](#desenvolvimento-contínuo) -->
<!--  * [Recursos úteis](#recursos-úteis) -->
<!-- * [Autor](#autor) -->
<!-- * [Agradecimentos](#agradecimentos) -->
* [Informações](#informações)

<!-- OVERVIEW -->
<!-- ## VISTA POR CIMA -->

<!-- SCREENSHOT -->
<!-- ### FOTO DA TELA -->

<!-- LINKS -->
<!-- ### LINKS -->

<!-- MY PROCESS -->
<!-- ## MEU PROCESSO -->

<!-- BUILT WITH -->
<!-- ### CONSTRUÍDO COM -->

<!-- WHAT I LEARNED -->
<!-- ### O QUE APRENDI -->

<!-- CONTINUED DEVELOPMENT -->
<!-- ### DESENVOLVIMENTO CONTÍNUO -->

<!-- USEFUL RESOURCES -->
<!-- ### RECURSOS ÚTEIS -->

<!-- AUTHOR -->
<!-- ## AUTOR -->

<!-- ACKNOWLEDGMENTS -->
<!-- ## AGRADECIMENTOS -->

<!-- INFORMATION -->
## INFORMAÇÕES

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-ins-con-win-alg-log-pro-bas-ava&label=VISITANTES&labelColor=%23f9e64f&countColor=%23008000&style=plastic "Total de Visitas")
&nbsp;
![followers](https://img.shields.io/github/followers/Devsgeeknerd?style=plastic&label=SEGUIDORES&labelColor=f9e64f "Total de Seguidores")
&nbsp;
![watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-ins-con-win-alg-log-pro-bas-ava?style=plastic&label=OBSERVADORES&labelColor=f9e64f "Total de Observadores")
&nbsp;
![stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-ins-con-win-alg-log-pro-bas-ava?style=plastic&label=ESTRELAS&labelColor=f9e64f "Total de Estrelas Recebidas")
&nbsp;
![forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-ins-con-win-alg-log-pro-bas-ava?style=plastic&label=BIFURCAÇÕES&labelColor=f9e64f "Total de Bifurcações")
&nbsp;
![repo size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-ins-con-win-alg-log-pro-bas-ava?style=plastic&label=TAMANHO&labelColor=f9e64f "Tamanho do Repositório")
&nbsp;
![license](https://img.shields.io/github/license/Devsgeeknerd/cla-ins-con-win-alg-log-pro-bas-ava?style=plastic&label=LICENÇA&labelColor=f9e64f "Licença do Repositório")
