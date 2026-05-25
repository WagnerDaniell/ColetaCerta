# PRD — Coleta Certa 📍🗑️

# 1. Visão Geral

O **Coleta Certa** é um aplicativo mobile/web voltado para moradores, prefeituras e empresas de coleta urbana, com o objetivo de melhorar e otimizar a coleta de lixo nas cidades.

O aplicativo funciona como um mapa colaborativo, onde moradores podem informar locais com lixo aguardando coleta, acompanhar dias e horários do caminhão e receber atualizações em tempo real.

Além de resolver problemas dos moradores, o principal objetivo do sistema é ajudar prefeituras e empresas responsáveis pela limpeza urbana a tomarem decisões mais inteligentes através de dados e insights gerados pelo próprio aplicativo.

---

# 2. Problema

Hoje, muitos moradores:

* Não sabem exatamente os dias e horários da coleta.
* Não sabem se houve mudança na rota.
* Não sabem se o caminhão já passou.
* Colocam o lixo cedo demais ou tarde demais.

Isso gera:

* Acúmulo de lixo.
* Mau cheiro.
* Poluição urbana.
* Lixo espalhado nas ruas.
* Falta de comunicação entre população e coleta urbana.

Além disso, prefeituras e empresas de coleta também enfrentam dificuldades como:

* Falta de dados sobre regiões com maior volume de lixo.
* Rotas pouco otimizadas.
* Desperdício de combustível e tempo.
* Dificuldade em identificar bairros que precisam de mais frequência de coleta.
* Falta de monitoramento em tempo real da demanda da cidade.

---

# 3. Principal Objetivo do Sistema

O principal objetivo do **Coleta Certa** é utilizar os registros dos moradores para gerar inteligência operacional para a coleta urbana.

Com os dados coletados pelo aplicativo, prefeituras e empresas poderão:

* Identificar regiões com maior acúmulo de lixo.
* Intensificar coletas em bairros mais críticos.
* Criar rotas mais eficientes para os caminhões.
* Reduzir tempo e custo operacional.
* Melhorar distribuição das equipes.
* Aumentar frequência da coleta em determinadas regiões.
* Tomar decisões baseadas em dados reais da cidade.
* Melhorar a limpeza urbana e qualidade de vida da população.

Ao mesmo tempo, o aplicativo também resolve problemas do dia a dia dos moradores, informando horários da coleta e trazendo mais transparência para o serviço.

---

# 4. Público-Alvo

## Primário

* Prefeituras.
* Empresas de coleta urbana.

## Secundário

* Moradores da cidade.
* Garis.
* Motoristas da coleta.

---

# 5. Funcionalidades Principais

## 5.1 Cadastro e Login

O aplicativo deverá possuir autenticação de usuários para garantir segurança e confiabilidade dos registros.

### Funcionalidades:

* Cadastro de usuário.
* Login com e-mail e senha.
* Recuperação de senha.
* Sessão persistente.
* Perfil do usuário.

### Dados do usuário:

* Nome.
* E-mail.
* Senha.
* Endereço principal.
* Foto de perfil (opcional).

---

## 5.2 Mapa Interativo

O usuário visualizará um mapa da região contendo:

* Pontos de lixo aguardando coleta.
* Caminhão em rota.
* Coletas concluídas.
* Status da coleta nas ruas.

### Legenda:

* 🟢 Lixo no local.
* 🔵 Coleta confirmada.
* ⚫ Coleta concluída.

---

## 5.3 Registro de Lixo com Foto

O morador poderá registrar um ponto de lixo no mapa.

### Fluxo:

1. Usuário clica em “Marcar lixo no local”.
2. O aplicativo solicita:

   * Foto do lixo.
   * Localização automática.
   * Tipo ou quantidade de lixo (opcional).
3. O sistema envia o registro para validação.
4. Após validado, o ponto aparece no mapa.

### Objetivo:

* Evitar spam.
* Garantir que os pontos sejam reais.
* Manter confiabilidade do sistema.

---

## 5.4 Agenda de Coleta

O sistema mostrará:

* Próximo dia da coleta.
* Frequência semanal.
* Horários previstos.
* Alterações de rota.

### Exemplo:

* Terça, Quinta e Sábado.
* A partir das 07:00.

---

## 5.5 Notificações

O usuário receberá notificações como:

* “O caminhão passará hoje.”
* “Coleta iniciada na sua região.”
* “Mudança no horário da coleta.”
* “Seu ponto foi coletado.”

---

## 5.6 Rotas e Inteligência Operacional

O sistema fornecerá um painel inteligente para prefeituras e empresas de coleta contendo:

* Regiões com maior volume de lixo.
* Ruas prioritárias.
* Rotas otimizadas.
* Status das coletas.
* Volume de registros por bairro.
* Regiões críticas.
* Frequência ideal de coleta.
* Mapas de calor.
* Histórico operacional.

Esses dados ajudarão diretamente na tomada de decisões da coleta urbana.

---

# 6. Insights Gerados Pelo Sistema

O aplicativo poderá gerar informações importantes como:

* Ruas com maior quantidade de lixo.
* Horários com maior volume de descarte.
* Bairros que precisam de coleta extra.
* Regiões com recorrência de lixo acumulado.
* Locais prioritários para coleta.
* Rotas mais eficientes para caminhões.
* Histórico de coleta por bairro.
* Mapas de calor de descarte urbano.

---

# 7. Fluxo Principal do Usuário

1. Usuário cria uma conta ou faz login.
2. O app identifica sua localização.
3. O mapa mostra status da coleta da região.
4. Usuário registra lixo com foto.
5. Sistema valida o registro.
6. O ponto aparece no mapa.
7. Caminhão realiza coleta.
8. Status muda para “Coleta concluída”.

---

# 8. Diferenciais

* Mapa colaborativo em tempo real.
* Integração entre moradores e coleta urbana.
* Inteligência operacional para prefeituras.
* Validação com foto.
* Rotas otimizadas.
* Redução de custos operacionais.
* Redução de lixo acumulado.
* Melhor comunicação com moradores.
* Decisões baseadas em dados reais.

---

# 9. Telas Principais

## Home

Baseada no protótipo desenvolvido:

* Barra de busca.
* Mapa interativo.
* Próxima coleta.
* Frequência da rua.
* Botão “Marcar lixo no local”.
* Botão “Ver rotas e horários”.
* Navegação inferior.

## Outras telas

* Login.
* Cadastro.
* Perfil.
* Histórico de registros.
* Configurações.
* Comunidade.
* Painel administrativo.
* Dashboard analítico.

---

# 10. Requisitos Funcionais

* Cadastro de usuários.
* Login/autenticação JWT.
* Geolocalização.
* Upload de imagens.
* Mapa em tempo real.
* Registro de lixo.
* Sistema de notificações.
* Consulta de rotas.
* Painel administrativo.
* Dashboard analítico.
* Sistema de validação de registros.

---

# 11. Requisitos Não Funcionais

* Interface simples e acessível.
* Atualização em tempo real.
* Compatibilidade Android/iOS.
* Baixo consumo de internet.
* Segurança de dados.
* Escalabilidade para múltiplas cidades.
* Alta disponibilidade do sistema.

---

# 12. Tecnologias

## Front-end

* React ou Angular.

## Back-end

* NodeJS.

## Banco de Dados

* PostgreSQL.

## Mapas

* Google Maps API ou OpenStreetMap.

## Upload de Imagens

* Cloud Storage.

## Notificações

* Firebase Cloud Messaging (FCM).

---

# 13. Possíveis Melhorias Futuras

* IA para validar fotos automaticamente.
* Rastreamento em tempo real do caminhão.
* Dashboard avançado para prefeituras.
* Sistema de denúncias.
* Gamificação para moradores ativos.
* Detecção de descarte irregular.
* Previsão automática de volume de lixo.
* Sugestão inteligente de rotas.

---

# 14. Exemplo Real do Problema

Na minha rua, o caminhão costumava passar quinta e sábado, mas recentemente não passou no sábado.

Hoje os moradores não sabem:

* Se houve mudança na coleta.
* Se o caminhão atrasou.
* Qual o melhor horário para colocar o lixo.

Ao mesmo tempo, a prefeitura também não possui informações em tempo real sobre regiões com maior demanda de lixo.

O aplicativo resolveria esses problemas através de notificações, mapa colaborativo, análise de dados e inteligência operacional para otimizar toda a coleta urbana da cidade.
