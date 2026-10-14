# Galeria de Raças de Cães

#Equipe 8, problema 8

Aplicação web desenvolvida para consulta de raças e sub-raças de cães, com exibição dinâmica de galeria de imagens e atualizações em tempo real.

## Integrantes
* João Pedro Aguiar Teixeira - 2025012506
* Marcos Vinicius Mendes de Carvalho - 2025031790

## Principais Funcionalidades
* **Listagem Inicial (RF01):** Carregamento e exibição automática de todas as raças de cães e suas respectivas sub-raças disponíveis na API.
* **Busca e Filtragem em Tempo Real (RF02):** Campo de busca responsivo que filtra raças e sub-raças digitadas, ignorando diferenças entre letras maiúsculas e minúsculas, com botão para limpar e restaurar a lista completa.
* **Galeria Dinâmica (RF03):** Exibição de 6 imagens da raça ou sub-raça selecionada.
* **Atualização de Imagens (RF04):** Botão "Recarregar" que sorteia e carrega 6 novas fotos da raça atual sem atualizar a página.
* **Apresentação e Tratamento de Erros (RF05):** Identificação clara da raça exibida, textos alternativos (`alt`) em todas as imagens, ocultação de imagens com erro de carregamento e tratamento visual de mensagens de status (carregando, sem resultados ou falhas de conexão).

## API Utilizada
* **Dog CEO API:** [https://dog.ceo/dog-api/](https://dog.ceo/dog-api/)
  * Recursos consumidos:
    * Listagem de todas as raças e sub-raças: `https://dog.ceo/api/breeds/list/all`
    * Obtenção de fotos aleatórias por raça/sub-raça: `https://dog.ceo/api/breed/{breed}/images/random/6`

## Tecnologias Utilizadas
* **HTML5:** Estrutura semântica e acessível.
* **CSS3:** Estilização moderna, responsiva (layout flexível/grid) e componentes acessíveis.
* **JavaScript (ES6+):** Manipulação assíncrona do DOM, consumo REST via `fetch` nativo e tratamento dinâmico de dados.

## Instruções de Execução

1. **Clonar o repositório:**
   ```bash
   git clone https://github.com/pedroaguiarcd/dog-breed-gallery.git

2. **Acessar a pasta do projeto**

3. **Executar o arquivo index.hmtl**
     
