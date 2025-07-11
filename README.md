# 🌿 Myrtle - Major Incident Reporting Tool

Uma ferramenta web para gestão estruturada de incidentes de IT, seguindo as melhores práticas de Service Operations.

## 🎯 Sobre o Projeto

Myrtle é uma aplicação web single-page que guia equipas de IT através de processos estruturados para:
- **Resolução de Incidentes** - Para alertas automáticos com origem clara
- **Investigação de Mistérios** - Para problemas vagos que requerem investigação

## ✨ Funcionalidades

- 📋 **Guias Passo-a-Passo**: Workflows estruturados baseados em melhores práticas
- 📊 **Gestão de Contactos**: Registo detalhado de todas as comunicações
- 📄 **Relatórios Automáticos**: Geração automática de documentation em Markdown
- 💾 **Armazenamento Local**: Dados guardados localmente no browser (IndexedDB)
- 📤 **Import/Export**: Backup e restauro de dados
- 🎨 **Interface Moderna**: Design responsivo com tema verde inspirado na natureza

## 🚀 Como Usar

1. **Abrir o ficheiro `myrtle.html` no browser**
2. **Escolher o tipo de incidente:**
   - 🚨 **Caso** - Para alertas automáticos
   - 🔍 **Mistério** - Para problemas que requerem investigação
3. **Seguir os passos guiados**
4. **Gerar relatório final**

## 📋 Workflow para Incidentes

1. **Origem do Alerta** - Identificar fonte e sistema afetado
2. **Interpretação** - Análise de códigos de erro e palavras-chave
3. **Pesquisa de Soluções** - KEDB, Runbooks, ITSM
4. **Verificação do Ambiente** - Estado da infraestrutura
5. **Decisão e Ação** - Resolver, reatribuir ou escalar
6. **War Room** - Para problemas complexos
7. **Resolução** - Identificar causa raiz e aplicar solução
8. **Contactos** - Documentar comunicações
9. **Post-Mortem** - Lições aprendidas

## 🔍 Workflow para Mistérios

1. **Avaliação Inicial** - Documentar sintomas e impacto
2. **Procurar Pistas** - Pesquisa em bases de conhecimento
3. **Estado da Infraestrutura** - Verificação geral
4. **Registo ITSM** - Criação de ticket oficial
5. **Verificar Mudanças** - Análise de alterações recentes
6. **Primeiras Deduções** - Formulação de hipóteses
7. **Investigação** - Recolha de informação
8. **Troubleshooting** - Colaboração com especialistas
9. **Feedback** - Atualização de stakeholders
10. **Resolução Final** - Identificação e correção
11. **Contactos** - Documentar comunicações
12. **Post-Mortem** - Análise detalhada

## 🛠️ Tecnologias

- **HTML5** - Estrutura da aplicação
- **CSS3** - Estilização moderna com gradientes
- **JavaScript (ES6+)** - Lógica da aplicação
- **IndexedDB** - Armazenamento local de dados
- **Responsive Design** - Compatível com dispositivos móveis

## 📁 Estrutura do Projeto

```
myrtle/
├── myrtle.html          # Aplicação principal (self-contained)
├── README.md            # Este ficheiro
├── LICENSE              # Licença MIT
└── docs/               # Documentação adicional
    ├── workflows.md     # Detalhes dos workflows
    └── screenshots/     # Capturas de ecrã
```

## 🔧 Instalação

Não requer instalação! É um ficheiro HTML único que funciona diretamente no browser.

```bash
# Clonar o repositório
git clone https://github.com/andrefbfsilva/myrtle-incident-tool.git

# Abrir o ficheiro
open myrtle.html
```

## 💾 Dados

- **Armazenamento**: IndexedDB (local no browser)
- **Export**: Ficheiros JSON com backup completo
- **Import**: Restauro de backups anteriores
- **Relatórios**: Gerados em formato Markdown

## 🤝 Contribuições

Contribuições são bem-vindas! Por favor:

1. Fork o projeto
2. Cria uma branch para a tua feature (`git checkout -b feature/AmazingFeature`)
3. Commit as tuas alterações (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abre um Pull Request

## 📝 Roadmap

- [ ] Integração com APIs de ITSM
- [ ] Templates customizáveis
- [ ] Modo dark/light
- [ ] Sincronização em cloud
- [ ] Relatórios em PDF
- [ ] Dashboard de métricas
- [ ] Multi-idiomas

## 📄 Licença

Este projeto está licenciado sob a Licença MIT - vê o ficheiro [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**André** - Criador das AndréTools

## 🙏 Agradecimentos

- Inspirado nas melhores práticas de ITIL e Service Operations
- Design inspirado na natureza (daí o nome Myrtle, uma planta)
- Comunidade de IT Service Management

## 🐛 Reportar Bugs

Encontraste um bug? Por favor cria uma [issue](https://github.com/andrefbfsilva/myrtle-incident-tool/issues) com:
- Descrição do problema
- Passos para reproduzir
- Browser e versão
- Screenshots (se aplicável)

## 📞 Suporte

- 📧 Email: andrefbfsilva@gmail.com
- 💬 Issues: GitHub Issues
---

*Myrtle - Porque cada incidente merece uma resolução estruturada* 🌿
