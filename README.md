# Previsão do Tempo - Angular

Uma aplicação web moderna desenvolvida em Angular para consultar a previsão do tempo de qualquer cidade do mundo, utilizando a API do Visual Crossing Weather.

## 🌟 Funcionalidades

- **Busca por cidade**: Digite o nome de qualquer cidade para obter a previsão do tempo
- **Previsão de 3 dias**: Visualize a previsão para hoje, amanhã e depois de amanhã
- **Informações detalhadas**: Temperatura máxima e mínima, condições climáticas, umidade, velocidade do vento e chance de chuva
- **Interface responsiva**: Funciona perfeitamente em desktop e dispositivos móveis
- **Ícones intuitivos**: Representação visual das condições climáticas
- **Tratamento de erros**: Mensagens claras para cidades não encontradas ou problemas de conexão
- **Design moderno**: Interface elegante com gradiente azul e animações suaves

## 🚀 Tecnologias Utilizadas

- **Angular 18** - Framework TypeScript para desenvolvimento web
- **TypeScript** - Linguagem de programação tipada
- **CSS3** - Estilização moderna com gradientes e animações
- **HttpClient** - Cliente HTTP do Angular para consumo de APIs
- **FormsModule** - Módulo do Angular para formulários
- **Visual Crossing Weather API** - Dados meteorológicos precisos e atualizados

## 📋 Pré-requisitos

- Node.js (versão 18 ou superior)
- npm (versão 9 ou superior)
- Angular CLI (versão 18 ou superior)
- Chave de API do Visual Crossing Weather

## 🔧 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/weather-app-angular.git
cd weather-app-angular
```

2. Instale as dependências:
```bash
npm install
```

3. Configure a chave da API:
   - Abra o arquivo `src/app/app.ts`
   - Substitua `'SUA_CHAVE_DA_API'` pela sua chave da API do Visual Crossing Weather na linha:
   ```typescript
   private readonly API_KEY = 'SUA_CHAVE_DA_API';
   ```

4. Execute o projeto em modo de desenvolvimento:
```bash
ng serve
```

5. Abra [http://localhost:4200](http://localhost:4200) no seu navegador

## 🔑 Obtendo a Chave da API

1. Acesse [Visual Crossing Weather](https://www.visualcrossing.com/)
2. Crie uma conta gratuita
3. Acesse o painel de controle e copie sua chave de API
4. Cole a chave no arquivo `src/app/app.ts` conforme mostrado acima

## 📱 Como Usar

1. Digite o nome de uma cidade no campo de busca
2. Clique no botão "Buscar" ou pressione Enter
3. Visualize a previsão do tempo para os próximos 3 dias
4. Experimente com diferentes cidades ao redor do mundo!

## 🏗️ Build para Produção

Para criar uma versão otimizada para produção:

```bash
ng build --prod
```

Os arquivos otimizados serão gerados na pasta `dist/weather-app-angular/`.

## 🌐 Deploy

O projeto pode ser facilmente deployado em plataformas como:
- Vercel
- Netlify
- GitHub Pages
- Firebase Hosting
- AWS S3 + CloudFront

### Deploy no Netlify

1. Faça build do projeto: `ng build --prod`
2. Arraste a pasta `dist/weather-app-angular` para o Netlify
3. Configure as variáveis de ambiente se necessário

### Deploy no Vercel

1. Instale o Vercel CLI: `npm i -g vercel`
2. Execute: `vercel --prod`
3. Siga as instruções do CLI

## 📄 Estrutura do Projeto

```
weather-app-angular/
├── src/
│   ├── app/
│   │   ├── app.ts           # Componente principal
│   │   ├── app.html         # Template da aplicação
│   │   ├── app.css          # Estilos do componente
│   │   └── app.config.ts    # Configuração da aplicação
│   ├── styles.css           # Estilos globais
│   ├── index.html           # Página principal
│   └── main.ts              # Ponto de entrada
├── angular.json             # Configuração do Angular
├── package.json             # Dependências do projeto
├── tsconfig.json            # Configuração do TypeScript
└── README.md                # Documentação
```

## 🎨 Recursos de Design

- **Gradiente azul**: Background moderno e atrativo
- **Cards com sombra**: Elementos visuais elegantes
- **Animações CSS**: Transições suaves e loading spinner
- **Responsividade**: Layout adaptável para mobile e desktop
- **Tipografia moderna**: Fontes system para melhor legibilidade
- **Ícones emoji**: Representação visual intuitiva do clima

## 🔧 Funcionalidades Técnicas

### Integração com API
- Consumo da API Visual Crossing Weather via HttpClient
- Tratamento de erros HTTP com mensagens personalizadas
- Formatação de dados meteorológicos
- Conversão de ícones de clima para emojis

### Interface de Usuário
- Two-way data binding com ngModel
- Diretivas estruturais (*ngFor, *ngIf)
- Event binding para interações do usuário
- Pipe para formatação de datas

### Responsividade
- CSS Grid para layout dos cards
- Media queries para dispositivos móveis
- Flexbox para alinhamento de elementos
- Viewport meta tag configurada

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📝 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## 🙏 Agradecimentos

- [Visual Crossing Weather](https://www.visualcrossing.com/) pelos dados meteorológicos
- [Angular Team](https://angular.io/) pelo excelente framework
- [TypeScript Team](https://www.typescriptlang.org/) pela linguagem tipada
- Comunidade open source pelas contribuições e inspirações

## 📞 Suporte

Se você encontrar algum problema ou tiver dúvidas:

1. Verifique se sua chave de API está configurada corretamente
2. Confirme se você tem conexão com a internet
3. Consulte a documentação da API Visual Crossing Weather
4. Abra uma issue no GitHub com detalhes do problema

---

Desenvolvido com ❤️ usando Angular para demonstrar integração com APIs de clima

