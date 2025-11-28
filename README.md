# FIAP FinTech - Projeto Front-end

## Sobre o Projeto

Projeto desenvolvido para a disciplina de **Front-end Web Development** da FIAP, Fase 4. Trata-se de uma interface web responsiva para um aplicativo de serviços bancários digitais (FinTech), com foco em experiência do usuário e design moderno.

---

## Informações Acadêmicas

- **Aluno:** Felipo Blanc
- **RM:** 567636
- **Turma:** 1TDSOT-2025
- **Curso:** Análise e Desenvolvimento de Sistemas
- **Instituição:** FIAP (Faculdade de Informática e Administração Paulista)
- **Disciplina:** Front-end Web Development
- **Fase:** 4

---

## Tecnologias Utilizadas

- **HTML5** - Estrutura semântica e acessível
- **CSS3** - Estilização customizada e animações
- **Bootstrap 5.3.8** - Framework responsivo e componentes
- **Bootstrap Icons 1.13.1** - Ícones vetoriais

---

## Características do Projeto

### Requisitos Atendidos

- Interface responsiva 
- Uso extensivo do Bootstrap
- HTML e CSS em arquivos separados
- Identidade visual única
- Componentes interativos
- Código semântico e acessível
- Sem uso de JavaScript (conforme requisito)

### Funcionalidades Implementadas

1. **Menu de Navegação Colapsável** - Navbar responsiva do Bootstrap
2. **Área de Saldo** - Exibição destacada do saldo do usuário
3. **Menu Principal** - Grid responsivo com 6 opções de serviços:
   - Open Finance
   - Empréstimo
   - Pix
   - Cartão de Crédito
   - Planos FinTech
   - Boletos
4. **Botão de Extrato** - Call-to-action destacado
5. **Menu Secundário** - Acesso rápido a Investimentos, Ajuda e Compras
6. **Footer** - Informações de copyright

---

## Paleta de Cores

```css
:root {
    --fiap-pink: #FF1866;      /* Rosa principal */
    --fiap-pink-hover: #e6005c; /* Rosa hover */
    --fiap-dark: #000000;       /* Preto */
    --fiap-gray: #999999;       /* Cinza */
}
```

---

## Estrutura de Arquivos

```
fiap-fintech/
├── pdf
    ├── Referência - Figma - Projeto Fintech - Rm567636
├── index.html              # Página principal
├── src/
│   ├── css/
│   │   └── style.css      # Estilos customizados
│   └── image/
│       └── fiap-logo-pink.jpg  # Logo da marca
├── README.md              # Este arquivo
```

---
## Explicação pasta PDF 
O documento Referência - Figma - Projeto Fintech - Rm567636 foi realizado na Fase 2 - Cap 8 - Quem vê interface, vê coração. Com isso a tela foi criada com base neste projeto da fase 2, sendo desenvolvido na fase 4. 

## Como Executar o Projeto


### Opção: Usando Live Server (VS Code)
1. Instale a extensão "Live Server" no VS Code
2. Clique com botão direito em `index.html`
3. Selecione "Open with Live Server"


---

## Responsividade

O projeto foi desenvolvido com abordagem **mobile-first** e é totalmente responsivo:

- **Mobile** (< 576px): Layout em coluna única
- **Tablet** (≥ 576px): Grid 2 colunas
- **Desktop** (≥ 992px): Grid 3 colunas (design completo)

---

## Conceitos Aplicados

### Bootstrap
- Sistema de Grid responsivo (`row`, `col-*`)
- Componentes (`card`, `navbar`, `collapse`)
- Classes utilitárias (`d-flex`, `mb-4`, `text-center`, etc.)
- Responsividade com breakpoints

### CSS Customizado
- Variáveis CSS (`:root`)
- Transições e animações
- Pseudo-classes (`:hover`, `:focus`)
- Flexbox e Grid
- Border-radius e shadows

### HTML Semântico
- Tags semânticas (`<main>`, `<nav>`, `<section>`, `<footer>`)
- Atributos de acessibilidade (`aria-label`)
- Estrutura hierárquica de headings


---

## Boas Práticas Implementadas

1. **Separação de responsabilidades** - HTML, CSS e imagens em pastas específicas
2. **Comentários no código** - Explicação de uso de `!important`
3. **Nomenclatura consistente** - Classes descritivas em inglês
4. **Acessibilidade** - Labels e navegação por teclado
5. **Performance** - CDN para bibliotecas externas
6. **Versionamento** - Projeto versionado no Git/GitHub

---

## Problemas Conhecidos

### Uso de `!important` no CSS
O `!important` foi utilizado estrategicamente para 
sobrescrever estilos padrão do Bootstrap apenas quando 
necessário, mantendo a especificidade do CSS organizada. 
Todos os usos estão comentados no código.

---

## Observações Técnicas

### Uso de `!important` no CSS
O `!important` foi utilizado estrategicamente para sobrescrever estilos padrão do Bootstrap apenas quando necessário, mantendo a especificidade do CSS organizada. Todos os usos estão comentados no código.

### Bootstrap Icons
Os ícones foram importados via CDN e utilizados com classes do Bootstrap Icons, garantindo consistência visual e facilidade de manutenção.

---

## Licença

Este projeto foi desenvolvido para fins acadêmicos.

© 2025 Felipo Blanc - RM 567636 - Turma: 1TDSOT - Análise e Desenvolvimento de Sistemas
Graduação - Todos os direitos reservados.

---

## Agradecimentos

- FIAP - Pela oportunidade de aprendizado
- Professores - Pelo suporte e orientação

---

⭐ **Se gostou do projeto, deixe uma estrela no repositório!**