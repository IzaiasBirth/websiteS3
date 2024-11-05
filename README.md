# Atividade 1 - "Recursos Computacionais na AWS"

Este repositório contém o código-fonte do site estático desenvolvido para a disciplina **Recursos Computacionais na AWS**. O objetivo é criar uma página web estática que será hospedada em um bucket S3 na AWS, com o versionamento habilitado para demonstrar o armazenamento e controle de versões de arquivos estáticos.

## Descrição da Atividade

Na disciplina **Recursos Computacionais na AWS**, foi solicitado o desenvolvimento de dois ambientes distintos usando os serviços da AWS. A **Atividade 1** envolve a criação de um ambiente altamente disponível utilizando instâncias EC2 e recursos de rede. Como parte desta atividade, precisamos também hospedar um site estático em um bucket S3, com versionamento habilitado, para aprender como a AWS gerencia arquivos de diferentes versões no S3.

### Objetivos da Atividade

1. **Configuração de Bucket S3 com Versionamento**: 
   - Configurar um bucket S3 com versionamento habilitado para gerenciar diferentes versões do conteúdo hospedado.
   
2. **Hospedagem de Site Estático**:
   - Configurar o bucket S3 para hospedagem de site estático e disponibilizar uma página web para acesso via HTTP.

3. **Demonstração do Versionamento**:
   - Demonstrar a funcionalidade de versionamento enviando arquivos de mesmo nome com conteúdo atualizado para o bucket e acessando suas diferentes versões.

### Funcionalidades do Site

O site criado para esta atividade é uma página simples em HTML e CSS, contendo informações sobre:
- O projeto da disciplina;
- Identificação do aluno e do professor;
- Estrutura básica para visualização e entendimento do funcionamento da hospedagem de site estático no S3.

## Estrutura do Projeto

- `index.html`: Página principal do site, contendo informações da atividade, nome do aluno e do professor, e breve descrição do projeto.
- `styles.css`: Arquivo CSS para estilização da página.

## Tecnologias Utilizadas

- **HTML** e **CSS**: Linguagens para criação e estilização do site estático.
- **Amazon S3**: Serviço de armazenamento da AWS utilizado para hospedar a página web.
- **Amazon S3 Versioning**: Funcionalidade de controle de versões do S3, que permite manter múltiplas versões de um arquivo no bucket.

## Passo a Passo de Configuração no AWS S3

1. **Criar um bucket S3**:
   - No console da AWS, vá para o serviço S3 e crie um novo bucket para hospedar o site.
   
2. **Ativar Versionamento**:
   - No bucket criado, habilite a funcionalidade de versionamento para permitir o controle de versões dos arquivos enviados.

3. **Configurar a Hospedagem de Site Estático**:
   - Acesse as configurações do bucket e habilite a opção de site estático. Defina `index.html` como a página de entrada.
   
4. **Enviar Arquivos**:
   - Faça o upload dos arquivos `index.html` e `styles.css` para o bucket.
   
5. **Testar o Versionamento**:
   - Modifique o conteúdo do `index.html` e faça o upload novamente para o bucket. Acesse o arquivo pela URL do site e verifique as mudanças.

## Acessando o Site

Após a configuração, o site estático poderá ser acessado através da URL pública gerada pela configuração do bucket S3.

---

**Nota**: Lembre-se de configurar as permissões do bucket corretamente para permitir o acesso público ao site estático.

---

**Disciplina**: Recursos Computacionais na AWS  
**Aluno**: Izaias Nascimento  
**Professor**: Carlos Alberto Quintanilha
