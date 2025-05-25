# OCA - Arthur Vargas - Sistema de Treinos

Sistema completo de treinos personalizados com área do cliente e painel administrativo.

## 🏗️ Estrutura da Aplicação

```
arthur-novo/
├── index.html                    # Página de login principal
├── cadastre-se.html             # Página de cadastro
├── area-cliente/                # Área restrita do cliente
│   ├── dashboard.html           # Dashboard principal (após login)
│   ├── perfil/                  # Gerenciamento de perfil
│   │   ├── index.html          # Visualizar perfil
│   │   └── editar.html         # Editar perfil
│   └── planos/                  # Planos e treinos
│       ├── index.html          # Lista de planos de treino
│       └── contratar.html      # Contratar novos planos
├── treinos/                     # Treinos organizados por categoria
│   ├── feminino-iniciante/
│   ├── masculino-avancado/
│   ├── masculino-iniciante/
│   └── masculino-intermediario/
│       ├── 2xsemana/
│       ├── 3xsemana/
│       └── 6xsemana/
├── painel-adm/                  # Painel administrativo
└── arthurbase/                  # Backup/versão anterior
```

## 🚀 Funcionalidades

### Área Pública
- **Login/Cadastro**: Sistema de autenticação com validação
- **Design Responsivo**: Interface adaptável para todos os dispositivos

### Área do Cliente
- **Dashboard**: Visão geral com estatísticas e acesso rápido
- **Perfil**: Gerenciamento completo de dados pessoais
- **Treinos**: Acesso aos planos baseados no nível do usuário
- **Sistema de Exercícios Flexível**: Alternativas quando equipamentos estão ocupados

### Sistema de Treinos
- **Níveis**: Iniciante, Intermediário, Avançado
- **Categorias**: Masculino e Feminino
- **Frequências**: 2x, 3x, 6x por semana
- **Exercícios Alternativos**: Sistema inteligente de substituição

## 🎯 Fluxo de Navegação

1. **Login** (`index.html`)
   ↓
2. **Dashboard** (`area-cliente/dashboard.html`)
   ↓
3. **Escolher Seção**:
   - Perfil (`area-cliente/perfil/index.html`)
   - Treinos (`area-cliente/planos/index.html`)
   - Contratar Planos (`area-cliente/planos/contratar.html`)

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização avançada com gradientes e animações
- **JavaScript**: Interatividade e validações
- **LocalStorage**: Simulação de autenticação
- **Design System**: Componentes reutilizáveis

## 📱 Responsividade

- **Desktop**: Layout completo com sidebar e grid
- **Tablet**: Adaptação de layout com navegação otimizada
- **Mobile**: Interface simplificada com menu colapsável

## 🎨 Design

- **Tema**: Dark com elementos glassmorphism
- **Cores**: Gradientes em tons de cinza e preto
- **Tipografia**: System fonts para melhor performance
- **Animações**: Transições suaves e micro-interações

## 🔐 Sistema de Autenticação

### Simulação de Login
- Utiliza `localStorage` para manter estado
- Validação de campos obrigatórios
- Redirecionamento automático após login
- Proteção de rotas da área do cliente

### Dados de Teste
- **Email**: qualquer email válido
- **Senha**: qualquer senha (exceto "123456" que simula erro)

## 📊 Funcionalidades Avançadas

### Sistema de Exercícios Flexível
- Painel lateral com exercícios alternativos
- Busca e filtro de exercícios
- Marcação de exercícios como concluídos
- Navegação inteligente entre treinos

### Estatísticas do Usuário
- Treinos completos
- Semanas ativas
- Tempo médio por semana
- Taxa de conclusão

## 🚀 Como Usar

1. **Acesso**: Abra `index.html` no navegador
2. **Login**: Use qualquer email válido e senha
3. **Navegação**: Use o dashboard para acessar as funcionalidades
4. **Treinos**: Acesse via "Meus Treinos" no dashboard
5. **Perfil**: Gerencie dados via "Meu Perfil"

## 📝 Notas de Desenvolvimento

- **Modular**: Cada seção é independente
- **Escalável**: Fácil adição de novos treinos e funcionalidades
- **Manutenível**: Código organizado e documentado
- **Performance**: Otimizado para carregamento rápido

## 🔄 Atualizações Recentes

- ✅ Reorganização completa da estrutura
- ✅ Dashboard centralizado
- ✅ Sistema de autenticação melhorado
- ✅ Navegação consistente entre páginas
- ✅ Design system unificado
- ✅ Responsividade aprimorada

---

**Desenvolvido por Arthur Vargas** - Sistema de Treinos Personalizado 