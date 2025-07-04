# Dashboard Educação Corporativa

Um dashboard web responsivo e interativo para visualização de indicadores de educação corporativa, com dados extraídos diretamente de uma planilha Google Sheets pública no formato JSON.

---

## Descrição

Este projeto apresenta um **dashboard de visualização de dados** focado em métricas essenciais para programas de treinamento corporativo. Através da integração com uma planilha Google Sheets, o dashboard exibe:

- Indicadores principais (KPIs) como colaboradores treinados, treinamentos oferecidos, taxa de conclusão, NPS e orçamento utilizado.
- Gráficos interativos que mostram desempenho antes/depois, acessos por período, tipos de conteúdo acessados e adesão por setor.
- Layout responsivo, que se adapta a diferentes tamanhos de tela, facilitando o acesso em desktops, tablets e smartphones.
- Interface moderna e limpa com usabilidade aprimorada, usando Bootstrap e Chart.js.

---

## Tecnologias Utilizadas

- **HTML5 / CSS3 / JavaScript (ES6)**
- [Bootstrap 5.3](https://getbootstrap.com/)
- [Chart.js](https://www.chartjs.org/)
- Google Sheets (como fonte pública de dados JSON via [OpenSheet](https://opensheet.elk.sh/))
  -> Acesse a Planilha em : https://docs.google.com/spreadsheets/d/1woSDU28xltH6qhdPm6OFNXO-PVu3GajkyDMRJli16FU/edit?usp=sharing

---

## Funcionalidades

- **Carregamento dinâmico de dados:** Busca automaticamente dados atualizados da planilha Google Sheets via API pública.
- **KPIs destacados:** Cards com números-chave para fácil visualização rápida.
- **Gráficos interativos:** Barras, linhas e pizza com cores diferenciadas, legendas e tooltips para melhor entendimento dos dados.
- **Responsividade:** Organização em grids que adaptam o layout para até 2 gráficos por linha em desktops e 1 por linha em dispositivos móveis.
- **Acessibilidade básica:** Uso de atributos `aria` para suporte a leitores de tela.
- **Atualização da data:** Mostra a última data de atualização no rodapé.

---

## Como usar

1. **Hospedagem:** Basta hospedar o arquivo HTML em um servidor web, ou abrir localmente em um navegador moderno (Chrome, Firefox, Edge).
2. **Planilha Google:** Os dados são obtidos da planilha pública configurada no código, podendo ser trocada a URL na variável `url` no script.
3. **Atualização de dados:** Atualize os valores na planilha Google Sheets e eles serão refletidos automaticamente no dashboard.
4. **Requisitos:** Internet para carregar as bibliotecas CDN (Bootstrap e Chart.js) e para acessar a planilha pública.

---

## Estrutura do Projeto

- `index.html` - arquivo principal contendo o dashboard, estilos e scripts embutidos.
- Dados carregados dinamicamente da planilha Google Sheets pública.

---

## Como contribuir

Contribuições são bem-vindas! Para propor melhorias:

1. Fork o repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-funcionalidade`).
3. Faça commits com mensagens claras.
4. Envie um Pull Request detalhando suas alterações.

---

## Licença

Este projeto está sob a licença MIT — veja o arquivo [LICENSE](LICENSE) para detalhes.

---

## Contato

Para dúvidas ou sugestões, abra uma issue ou me contate.
isaacdemelorocha@gmail.com

---

**Obrigado por visitar o Dashboard Educação Corporativa!**  
Criado por @isaacdemelorocha
