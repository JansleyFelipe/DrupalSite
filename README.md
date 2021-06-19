# DrupalSite

*Estamos usando Drupal 7.81.*

**Entregas:**

 1. v1.0: Instalação padrão do Drupal 7 funcionando.
 2. v1.1: Criar um Content Type de eventos e registrar alguns eventos no CMS. Conter foto, endereço, dias e horários, staff e palestrantes, outras informações que achar interessante. Considerar que nem todos os eventos possuem todas as informações. Ex.: eventos online não possuem endereço.
 3. v1.2: Adicionar um tema da comunidade e ativar ele para mudar a aparência do site.
 4. v1.3: Criação de um módulo custom, seguir a estrutura de módulos indicada pelo site da comunidade do Drupal. Esse módulo deve criar um Block (usando hooks) que vai adicionar um conteúdo simples nas páginas de eventos (texto e/ou imagem).

# Comentários sobre o meu trabalho:

 - v1.1 -> Criei o Content Type Eventos;
 - v1.2 -> Adicionei o tema chamdo "Mayo";
 - v1.3 -> Criei um módulo que adiciona um block no banner top da página com os links dos eventos.

# Preparando o ambiente de desenvolvimento
Os items da lista abaixo é uma forma de preparar o ambiente local usando "Xampp":

**Local:**
 1. Baixe e instale o "Xampp" na versão 7.3.28 / PHP 7.3.28 no seguinte link -> [https://www.apachefriends.org/pt_br/download.html](https://www.apachefriends.org/pt_br/download.html);
 2. Clone este repositório na pasta "xampp/htdocs";
 3. Dê um start no apache e mysql do "xampp";
 4. Entre em http://localhost/phpmyadmin, crie um database para o site em drupal e faça um import utilizando uns dos dump em .sql encontradas no root do repositório (drupalsite_v1-1.sql, drupalsite_v1-2.sql ou drupalsite_v1-3.sql);
 5. Acesse http://localhost/DrupalSite, faça as configurações básicas da aplicação básicas como o nome do database, linguagem e na última etapa escolha "visualizar site existente".
