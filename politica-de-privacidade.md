# Política de privacidade — Airlock

**Última atualização:** maio de 2026  

Esta política descreve como o **Airlock** (“nós”, “aplicação” ou “software”) trata informações quando você instala e usa o aplicativo de desktop **Airlock** — um cliente REST local (coleções, ambientes, histórico, scripts, JWT e recursos relacionados).  

A organização deste documento segue tópicos usuais em declarações de privacidade de produtos de software (incluindo a [Política de Privacidade da Microsoft](https://www.microsoft.com/pt-br/privacy/privacystatement)), **mas aplica-se apenas ao Airlock** e **não** substitui nem se confunde com a política da Microsoft ou de qualquer outro fornecedor.

---

## Índice

1. [Resumo](#resumo)
2. [Dados que podem ser tratados](#dados-que-podem-ser-tratados)
3. [Finalidades do tratamento](#finalidades-do-tratamento)
4. [Com quem os dados podem ser compartilhados](#com-quem-os-dados-podem-ser-compartilhados)
5. [Cookies HTTP, certificados e conteúdo de requisições](#cookies-http-certificados-e-conteúdo-de-requisições)
6. [Onde os dados são armazenados e processados](#onde-os-dados-são-armazenados-e-processados)
7. [Segurança](#segurança)
8. [Retenção e controles do titular](#retenção-e-controles-do-titular)
9. [Crianças e adolescentes](#crianças-e-adolescentes)
10. [Alterações nesta política](#alterações-nesta-política)
11. [Contato e exercício de direitos](#contato-e-exercício-de-direitos)

---

## Resumo

- O Airlock **não** exige cadastro em serviço online nosso para funcionar.
- Os dados de trabalho (coleções, ambientes, histórico, cookies da sessão de testes, certificados importados, planos de execução, metadados de “tenants”/espaços de trabalho) são **gravados localmente** no seu computador, na pasta de dados do usuário do Electron (por exemplo, em Windows, tipicamente sob `%APPDATA%`, em nome associado à identificação do aplicativo).
- O aplicativo **envia tráfego de rede apenas para os destinos que você configurar** (URLs de APIs, servidores de autenticação, etc.). Esse tráfego **não passa pelos nossos servidores** como intermediário da aplicação.
- **Não** incorporamos, nesta versão do código analisada para esta política, telemetria de produto, relatório de falhas remoto ou atualização automática forçada para os nossos servidores.

Se algo nesta política divergir de uma **build** ou **fork** que você obteve de terceiros, prevaleça a documentação fornecida com essa distribuição.

---

## Dados que podem ser tratados

Dependem de como você usa o aplicativo. Podem incluir:

| Categoria | Descrição |
|-----------|-----------|
| **Dados que você insere** | URLs, métodos HTTP, cabeçalhos, corpo de requisições, scripts, variáveis de ambiente, tokens ou chaves que você colar em ambientes ou cabeçalhos, nomes de coleções e pastas, notas, etc. |
| **Dados persistidos em disco** | Ficheiros JSON (e estruturas equivalentes) com coleções, ambientes, histórico de pedidos, “cookie jar” usado pelo cliente, certificados que importar, planos de execução e metadados de tenants. |
| **Dados gerados pelo uso** | Registos de histórico de chamadas que você mantiver ativos, respostas guardadas conforme a funcionalidade do app. |
| **Dados técnicos implícitos** | O sistema operativo e a rede podem expor endereço IP, DNS e metadados de ligação aos **serviços de terceiros** que você contactar; isso é inerente à Internet e não é controlado pelo Airlock como “serviço na nuvem” nosso. |

O Airlock **não** foi desenhado para tratar categorias sensíveis (saúde, origem racial, opinião política, etc.). Se você armazenar esse tipo de conteúdo em coleções ou ambientes, fará por sua conta e risco e deve avaliar a base legal e as medidas de segurança adequadas.

---

## Finalidades do tratamento

Tratamos os dados descritos acima **apenas no dispositivo**, para:

- Fornecer as funcionalidades do cliente REST (criar, editar, enviar e repetir pedidos).
- Guardar o seu trabalho entre sessões (persistência local).
- Aplicar configurações que você definir (ambientes, certificados, cookies de teste).

**Base legal (LGPD):** execução de medidas pré-contratuais a seu pedido, legítimo interesse na prestação do software local, e, quando aplicável, consentimento para operações opcionais que você ativar em versões futuras (se houver).

---

## Com quem os dados podem ser compartilhados

- **Responsável pelo aplicativo (distribuição que você usa):** em princípio **não recebe** automaticamente o conteúdo das suas coleções ou dos corpos das respostas. Não há backend “Airlock” obrigatório descrito nesta política.
- **Terceiros que você escolher:** sempre que clicar em “Enviar” (ou equivalente), o pedido segue para o **servidor indicado por você**. As políticas de privacidade desse servidor aplicam-se a esse fluxo.
- **Fornecedores de sistema:** Microsoft, Apple ou outros, na medida em que o sistema operativo, antivírus ou cópias de segurança acedam aos ficheiros da pasta de dados do aplicativo — fora do nosso controlo direto.

---

## Cookies HTTP, certificados e conteúdo de requisições

- **“Cookies” neste contexto** referem-se a **cookies HTTP** que o Airlock pode armazenar localmente para reproduzir sessões de API, **não** a cookies de rastreio de um site nosso.
- **Certificados** que importar ficam no armazenamento local; proteja o acesso ao seu utilizador do sistema.
- O **conteúdo** das requisições e respostas pode conter dados pessoais se você os colocar lá; a responsabilidade pela minimização e legalidade do envio é **sua** em relação aos destinos que contactar.

---

## Onde os dados são armazenados e processados

Todo o processamento descrito como “do aplicativo” ocorre **no seu equipamento**. Não há, nesta política, transferência internacional de dados **para nós** como operador de um serviço em nuvem do Airlock.  

Transferências internacionais **podem** ocorrer quando **você** envia pedidos para servidores noutros países; nesse caso aplicam-se as regras do destino e do seu contrato com esse fornecedor.

---

## Segurança

- Recomendamos **disco encriptado**, **palavra-passe de sessão** no SO e **cópias de segurança** conscientes do risco (ficheiros de ambiente podem conter segredos).
- Mantenha o **Airlock** e o **sistema operativo** atualizados.
- Não partilhe exportações de coleções/ambientes que contenham credenciais.

Limitações: nenhum software é isento de vulnerabilidades; se descobrir problema de segurança, contacte-nos pelo canal indicado abaixo.

---

## Retenção e controles do titular

- Os dados permanecem até você **apagá-los na aplicação**, **apagar os ficheiros** na pasta de dados do usuário ou **desinstalar** e remover resíduos manualmente, conforme o seu SO.
- Você pode **exportar** ou **copiar** dados conforme as funcionalidades disponíveis na sua versão.
- Em relação a dados que **já tenham sido enviados** a terceiros, o apagamento deve ser pedido **diretamente** a esses responsáveis.

Direitos LGPD (confirmar existência, acesso, correção, anonimização, portabilidade, eliminação, informação sobre partilhas, revogação de consentimento quando aplicável): em relação aos dados **apenas locais** no Airlock, você exerce esses direitos na prática **controlando os ficheiros e as configurações** no seu dispositivo. Para tratamentos feitos por **terceiros** (APIs que você chama), dirija-se a eles.

---

## Crianças e adolescentes

O Airlock é uma ferramenta técnica para desenvolvedores e equipas de software. **Não se destina** a crianças. Se for responsável legal e permitir o uso por menor, supervisione o conteúdo enviado e armazenado.

---

## Alterações nesta política

Podemos atualizar este documento quando o comportamento do software mudar (novas funcionalidades de rede, armazenamento ou integrações). A data no topo indica a última revisão. Para alterações relevantes, recomendável consultar o repositório ou notas de versão da distribuição que utiliza.

---

## Contato e exercício de direitos

**Responsável / editor do software (distribuição de referência):** MrChase95 — produto **Airlock** (ver `package.json` e metadados do projeto).

Para questões sobre **esta política** ou dados tratados **no contexto da distribuição que mantemos**, utilize um dos seguintes (ajuste conforme o canal real do seu projeto):

- **Website / repositório de suporte:** https://github.com/MrChase95/airlock  
- **E-mail de suporte e privacidade:** mferreira95@protonmail.com

Se não houver resposta em canal privado, pode registrar reclamação junto da **Autoridade Nacional de Proteção de Dados (ANPD)** no Brasil, conforme a legislação aplicável.

---

**Outros idiomas e suplementos:** [Privacy Policy (English) e suplementos regionais](./privacy-policy.md) — inclui política global em inglês, suplemento para leis estaduais dos EUA (CCPA/CPRA e afins) e suplemento LGPD em inglês.

---

*Este texto é informativo e não constitui aconselhamento jurídico. Adapte contactos, identificação da entidade responsável e detalhes à sua realidade de publicação (pessoa singular, empresa, loja de aplicações, etc.).*
