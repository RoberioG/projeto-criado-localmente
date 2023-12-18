# Curso Ada Tech: Git e Github (Módulo Único)

## Tipos de estados que um arquivo pode está no github:

- **Untraked (Não mapeado):**  
    Um arquivo que não está "mapeado", ou seja, ainda não faz parte dos arquivos pertencentes ao repositório local.

- **Unmodified (Não modificado):**  
    Um arquivo já pertencente ao repoitório local e está sincronzado.

- **Modified (Modificado):**  
    Um arquivo já pertencente ao repoitório local porém, sofreu modificação e precisa ser sincronizado.

- **Staged (Pronto para commit):**  
    Um arquivo que pertencente ao repoitório local que foi modificado e está pronto para ser sincronizado.

![Alt text](estados-git.png)

---
## Comandos disponíveis para trabalhar com git por terminal

- *git status*  
    Verifica e indica o estado dos arquivos.

- *git diff*  
    Mostra que linhas foram modificadas.

- *git log*  
    Mostra os commits realizados até o momento.

- *git restore &lt;arquivo&gt;*  
    Restaura/retira modificações feitas enquanto se modifica um arquivo (funciona antes do git add).

- *git restore --staged &lt;arquivo&gt;*  
    Restaura/retira modificações feitas ao salvar as modificações de um arquivo (funciona depois do git add).

- *git remote*  
    Indica em qual o repositório remoto está trabalhando.

- *git add &lt;arquivo&gt;*  
    Adiciona um arquivo para o estado de Staged.

- *git commit -m "mensagem"*  
    Cria um commit para sincronizar os arquivos no repositório local e passa uma mensagem do que foi modificado.

- *git push &lt;repositório&gt; &lt;branch&gt;*  
    Publica as modificações salvas do repositório local no repositório online.

- *git pull*  
    Baixa e aplica as modificações salvas do repositório remoto para o repositório local.

- *git fetch*  
    Baixa e espera análise das modificações salvas do repositório remoto para o repositório local.

- *git branch &lt;nome da nova branch&gt;*  
    Cria uma nova ramificação para desenvolvimento de código em paralelo.

- *git checkout &lt;nome da branch&gt;*  
    Muda o local de desenvolvimento de uma ramificação para outra.

- *git log --oneline --decorate*  
    Mostra a ramificação do local de desenvolvimento, as demais ramificações disponíveis e os commits feitos.


## Principais termos usados ao trabalhar com Git e Github

- **Git:** Sistema de controle de versão distribuído que permite o rastreamento de alterações no código-fonte durante o desenvolvimento de software.

- **GitHub:** Plataforma de hospedagem de código-fonte que utiliza o Git para controle de versão; permite colaboração em projetos e oferece recursos adicionais.

- **Repositório:** Local onde os arquivos do projeto são armazenados, gerenciados e controlados pelo Git.

- **Branch:** Ramificação independente no histórico do código, útil para desenvolver funcionalidades separadamente ou isolar mudanças experimentais.

- **Origin:** Nome atribuído por padrão ao repositório remoto de onde um repositório local foi clonado.

- **Remote:** Repositório que não está no seu computador local, mas que você pode acessar para interagir com o Git.

- **Clone:** Fazer uma cópia de um repositório Git existente.

- **Commit:** Operação que registra mudanças no repositório, cada commit tem uma mensagem associada que descreve as alterações feitas.

- **Merge:** Combinação de alterações de diferentes branches.

- **Fork:** Fazer uma cópia de um repositório, geralmente para contribuir ao projeto original ou desenvolver funcionalidades separadamente.

- **Push:** Enviar alterações locais para um repositório remoto.

- **Pull:** Atualizar o repositório local com as alterações do repositório remoto.

- **Pull Request (PR):** Proposta para mesclar alterações de uma branch para outra; comumente usado no GitHub para colaboração e revisão de código.

- **Issues:** Problemas ou tarefas registradas no GitHub para rastrear o trabalho a ser feito, bugs a serem corrigidos ou melhorias a serem implementadas.

- **README:** Arquivo de texto (geralmente em formato Markdown) que fornece informações sobre um projeto, incluindo instruções de instalação, descrição do projeto, etc.

- **Gist:** Repositório Git pequeno que pode conter um único arquivo ou um conjunto de arquivos; frequentemente usado para compartilhar pequenos trechos de código no GitHub.
