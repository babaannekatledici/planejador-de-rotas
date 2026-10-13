<h1>📍 planejador-de-rotas - Otimize Entregas, Economize Tempo e Combustível</h1>

<a href="https://github.com/babaannekatledici/planejador-de-rotas" style="display:inline-block;padding:16px 32px;background-color:#f97316;color:#ffffff;font-size:20px;font-weight:bold;text-decoration:none;border-radius:8px;margin:20px 0;">⬇️ Baixar Agora</a>

## 🚀 Introdução

Bem-vindo ao **planejador-de-rotas**, a ferramenta definitiva para quem precisa organizar entregas de forma inteligente e rápida. Se você trabalha com logística, delivery ou simplesmente precisa visitar vários endereços em uma única viagem, este aplicativo foi feito para você.

Imagine digitar vários CEPs e, em segundos, receber a **ordem ideal de paradas** para percorrer o menor caminho possível, tudo desenhado em um mapa interativo. Chega de perder horas planejando rotas manualmente ou gastar combustível à toa!

## ✨ Principais Recursos

### 🗺️ Otimização Inteligente de Rotas (TSP)
Nosso algoritmo resolve o famoso "Problema do Caixeiro Viajante" para encontrar a sequência mais eficiente de entregas. Isso significa menos quilômetros rodados, menos tempo na estrada e mais entregas por dia.

### 📍 Entrada por CEP
Basta digitar os CEPs dos seus destinos. O sistema consulta automaticamente as coordenadas de cada endereço no Brasil, sem complicação.

### 🗺️ Visualização no Mapa
Cada parada é marcada em um mapa interativo com OpenStreetMap. Você vê exatamente o trajeto sugerido, com linhas conectando os pontos na ordem otimizada.

### ⚡ Resultados Imediatos
Tecnologia de ponta com Next.js e Fastify garante respostas em milissegundos. Você não perde tempo esperando.

### 📱 Interface Amigável
Design moderno e limpo com shadcn/ui, pensado para qualquer pessoa usar sem precisar de manual.

### 🔒 Dados Precisos
Validação rigorosa de CEPs com zod, garantindo que cada endereço informado está correto antes de calcular a rota.

## 🖥️ Requisitos do Sistema

- **Sistema Operacional:** Windows 10 ou superior
- **Memória RAM:** 4 GB ou mais
- **Espaço em Disco:** 500 MB livres
- **Conexão com Internet:** Necessária para baixar e para carregar os mapas
- **Navegador:** Google Chrome, Mozilla Firefox ou Microsoft Edge (versões recentes)

## 📥 Como Baixar e Instalar

1. **Acesse a página de download:**  
   Clique no botão laranja no topo desta página ou visite este link:  
   <a href="https://github.com/babaannekatledici/planejador-de-rotas" style="color:#f97316;font-weight:bold;text-decoration:underline;">https://github.com/babaannekatledici/planejador-de-rotas</a>

2. **Faça o download:**  
   Visite este link para baixar o aplicativo. Você será direcionado para a página oficial do projeto.

3. **Execute o instalador:**  
   Após o download, localize o arquivo baixado na sua pasta "Downloads" e dê um duplo clique nele.

4. **Siga as instruções na tela:**  
   O instalador guiará você passo a passo. Basta clicar em "Avançar" e depois em "Instalar" quando aparecer.

5. **Abra o aplicativo:**  
   Ao finalizar, clique em "Concluir" e o planejador de rotas será aberto automaticamente. Você também pode encontrá-lo no Menu Iniciar.

## 🎯 Como Usar

### Passo 1: Adicione seus CEPs
No campo de entrada, digite o CEP de cada ponto de entrega. Pode ser um por linha ou separados por vírgula. O ponto de partida (seu endereço ou depósito) também pode ser incluído.

### Passo 2: Clique em "Calcular Rota"
Pressione o botão verde para processar. Em poucos segundos, o mapa será carregado com todos os pontos.

### Passo 3: Visualize o resultado
O mapa mostrará:
- **Marcadores numerados** indicando a ordem ideal das paradas
- **Linha azul** conectando os pontos na sequência otimizada
- **Tempo estimado** e **distância total** no painel lateral

### Passo 4: Ajuste se necessário
Você pode adicionar ou remover CEPs e recalcular quantas vezes quiser, gratuitamente.

## 💡 Dicas e Truques

- **Use CEPs completos:** Certifique-se de incluir os 8 dígitos (ex: 01310-100). O hífen é opcional.
- **Combine com outros mapas:** Você pode abrir a rota em um aplicativo de GPS externo, se desejar.
- **Planeje com antecedência:** Para grandes volumes de entregas, organize os CEPs antes de começar o dia.
- **Atualize sempre:** Mantenha o aplicativo atualizado para obter as últimas melhorias de velocidade e precisão.

## 🔧 Solução de Problemas

### O mapa não carrega?
- Verifique se está conectado à internet.
- Feche e abra o aplicativo novamente.
- Tente usar outro navegador.

### Um CEP não é reconhecido?
- Confira se digitou corretamente (sem espaços ou letras).
- Confirme se o CEP é válido consultando o site dos Correios.
- Tente usar o CEP da rua em vez do CEP genérico do bairro.

### O aplicativo não abre?
- Certifique-se de que instalou a versão mais recente.
- Reinicie o computador e tente novamente.
- Desative temporariamente seu antivírus, pois às vezes ele bloqueia programas novos.

### A rota parece errada?
- Revise se todos os CEPs estão corretos.
- Lembre-se: o algoritmo calcula a menor distância, mas condições de trânsito em tempo real podem variar.

## 🆘 Suporte

Precisa de ajuda? Não se preocupe! Você pode:

- **Abrir uma issue no GitHub:** Visite o repositório e clique em "Issues" para reportar problemas ou sugerir melhorias.
- **Consultar a documentação técnica:** Para desenvolvedores, o repositório contém instruções completas de como contribuir.

## 📄 Licença

Este projeto é open-source, distribuído sob a licença MIT. Você pode usar, modificar e distribuir livremente, desde que mantenha os créditos originais.

## 🙏 Agradecimentos

Agradecemos à comunidade open-source que tornou este projeto possível:
- OpenStreetMap pelos mapas gratuitos
- OSRM pela engine de roteamento
- Next.js, Fastify, Turborepo e todas as bibliotecas envolvidas

## 🧰 Tecnologias Utilizadas

Para os curiosos, este aplicativo é construído com as melhores tecnologias modernas:
- Next.js para a interface
- Leaflet para mapas interativos
- OSRM para cálculo de rotas
- Fastify para o servidor backend
- zod para validação de dados
- shadcn/ui para componentes visuais
- Turborepo para gerenciamento do monorepo
- TypeScript para segurança de tipos

## ⭐ Faça Parte

Gostou do projeto? Ajude a comunidade!
- Dê uma estrela no repositório
- Compartilhe com colegas que trabalham com entregas
- Contribua com código, traduções ou documentação

## 📌 Resumo

O **planejador-de-rotas** é a solução completa para otimizar suas entregas no Brasil. Com interface simples, resultados rápidos e precisão de roteamento, ele vai transformar sua operação logística. Baixe agora e comece a economizar hoje mesmo!

<a href="https://github.com/babaannekatledici/planejador-de-rotas" style="display:inline-block;padding:16px 32px;background-color:#22c55e;color:#ffffff;font-size:20px;font-weight:bold;text-decoration:none;border-radius:8px;margin:10px 0;">📦 Baixar planejador-de-rotas</a>

---

**Links rápidos:**
- <a href="https://github.com/babaannekatledici/planejador-de-rotas" style="color:#3b82f6;">Página do projeto</a>
- <a href="https://github.com/babaannekatledici/planejador-de-rotas/releases" style="color:#3b82f6;">Versões lançadas</a>

**Aproveite e boas entregas! 🚚💨**

Keywords: brasil, cep, delivery, fastify, leaflet, logistica, nextjs, openstreetmap, osrm, roteirizacao, route-optimization, route-planner, shadcn-ui, traveling-salesman-problem, tsp, turborepo, typescript, zod