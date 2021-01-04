# Metatags para redes sociais
Retirado de http://codigofonte.uol.com.br/artigos/conheca-as-meta-tags-sociais-do-twitter-facebook-google-e-outras

3) Modelo Completo

Este é o modelo para quem obter o máximo de impacto no uso das Meta Tags sociais, ainda que se arriscando a perder um pouco em performance… Além de todos os dados presentes no modelo padrão acima, o modelo completo ainda traz suporte para:

Google Authorship e Publisher Markup. Embora estes dados não alterem a aparência do seu conteúdo no Google+, eles podem adicionar links para suas páginas no Google+ nos resultados da busca.

* Marcação de artigo para o Schema.org
* Twitter Summary Card com imagem larga.
* Dados expandidos de artigo para o Open Graph

Substitua o texto em negrito, pelos dados reais da sua página:

```
<!– Altere sua tag HTML para incluir os atributos “itemscope” e “itemtype” conforme a linha abaixo. –>
<html itemscope itemtype=”http://schema.org/Article”>

```

```
<!– Coloque este código antes da tag <head> da sua página –>
<title>Título da página. Máximo de 60-70 caracteres</title>
<meta name=”description” content=”Descrição da página. No máximo 155 caracteres.” />

<!– Código para Google Authorship e Publisher–>
<link rel=”author” href=”https://plus.google.com/(Google+_Profile)/posts“/>
<link rel=”publisher” href=”https://plus.google.com/(Google+_Page_Profile)“/>

<!– Código do Schema.org também para o Google+ –>
<meta itemprop=”name” content=”Título ou nome“>
<meta itemprop=”description” content=”Descrição da página“>
<meta itemprop=”image” content=”http://www.example.com/image.jpg“>

<!– para o Twitter Card–>
<meta name=”twitter:card” content=”summary_large_image”>
<meta name=”twitter:site” content=”Conta do Twitter do site (incluindo arroba)“>
<meta name=”twitter:title” content=”Título da página“>
<meta name=”twitter:description” content=”Descrição da página. No máximo 200 caracteres“>
<meta name=”twitter:creator” content=”Conta do Twitter do autor do texto (incluindo arroba)“>
<– imagens largas para o Twitter Summary Card precisam ter pelo menos 280x150px –>
<meta name=”twitter:image” content=”http://www.example.com/image.jpg“>

<!– para o sistema Open Graph–>
<meta property=”og:title” content=”Título da página” />
<meta property=”og:type” content=”article” />
<meta property=”og:url” content=”http://www.example.com/” />
<meta property=”og:image” content=”http://example.com/image.jpg” />
<meta property=”og:description” content=”Descrição da Página” />
<meta property=”og:site_name” content=”Nome do site” />
<meta property=”article:published_time” content=”2013-09-17T05:59:00+01:00” />
<meta property=”article:modified_time” content=”2013-09-16T19:08:47+01:00” />
<meta property=”article:section” content=”Seção do artigo” />
<meta property=”article:tag” content=”Tags do artigo” />
<meta property=”fb:admins” content=”Facebook numeric ID” />

```
