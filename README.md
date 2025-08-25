
# Plataforma EAD Gtek - Moodle

![Logo Gtek](https://gtek.eco.br/wp-content/uploads/2023/03/logo-gtek.png)

## 📘 Visão Geral
Este repositório contém os arquivos e instruções para o desenvolvimento da plataforma de ensino a distância da **Gtek**, utilizando o ambiente **Moodle**. A Gtek atua com soluções em energia limpa, sistemas off-grid, infraestrutura de TI e produtos Victron Energy.

## 🎯 Objetivo do Projeto
Desenvolver uma plataforma EAD moderna e responsiva para capacitação técnica e comercial de clientes, parceiros e colaboradores da Gtek.

## 🚀 Funcionalidades
- Cursos interativos com vídeos, quizzes e certificados
- Emissão automática de certificados com QR Code
- Sistema de verificação de autenticidade
- Interface responsiva e mobile-friendly
- Integração com plugins Moodle (Custom Certificate, H5P, etc.)

## 📚 Estrutura dos Cursos
- Fundamentos de Energia Solar e Sistemas Off-Grid
- Instalação e Configuração de Equipamentos Victron Energy
- Infraestrutura de TI para Ambientes Críticos
- Vendas Consultivas em Soluções de Energia
- Manutenção de Sistemas Fotovoltaicos
- Energia Solar Aplicada ao Agronegócio

## 🧰 Tecnologias Utilizadas
- [Moodle](https://moodle.org/) - LMS principal
- HTML, PHP - Sistema de verificação de certificados
- Python - Geração de certificados e tutoriais
- Plugins Moodle: Custom Certificate, H5P, Quiz, Lição

## 🛠️ Instalação
1. Clone o repositório:
```bash
git clone https://github.com/gtek-eco/plataforma-ead.git
```
2. Instale o Moodle em seu servidor (versão recomendada: 4.x)
3. Importe os cursos e configure os plugins necessários
4. Adicione os arquivos de verificação em `/public_html/verificar-certificado`

## 🔐 Verificação de Certificados
- Cada certificado possui um código único
- A verificação pode ser feita via QR Code ou página web
- Exemplo: `https://gtek.eco.br/verificar-certificado?codigo=CERT20250825-JFS`

## 🤝 Contribuições
Contribuições são bem-vindas! Para colaborar:
1. Fork este repositório
2. Crie uma branch: `git checkout -b feature/nome-da-funcionalidade`
3. Commit suas alterações: `git commit -m 'Adiciona nova funcionalidade'`
4. Push para o repositório: `git push origin feature/nome-da-funcionalidade`
5. Abra um Pull Request

## 📞 Contato
Para dúvidas ou sugestões, entre em contato:
- 📧 dimas@gtek.eco.br
- 🌐 [gtek.eco.br](https://gtek.eco.br)

---
© 2025 Gtek Soluções Tecnológicas. Todos os direitos reservados.
