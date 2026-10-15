# Política de Privacidade — Copiloto Pro

**Última atualização:** 15 de Outubro de 2026

Esta Política de Privacidade descreve como o aplicativo **Copiloto Pro** ("nós", "nosso" ou "aplicativo") coleta, usa, armazena e protege as informações dos usuários ("você" ou "motorista/entregador").

Respeitamos a sua privacidade e estamos comprometidos em proteger os seus dados pessoais em conformidade com a **Lei Geral de Proteção de Dados (LGPD - Lei nº 13.709/2018)** e com as **Diretrizes de Segurança da Google Play Store**.

---

## 1. Informações Importantes sobre Recursos e Permissões

### ♿ 1.1. Uso do Serviço de Acessibilidade (`AccessibilityService API`)
O **Copiloto Pro** solicita e utiliza a **API de Acessibilidade (`AccessibilityService`)** com o propósito único e exclusivo de fornecer a funcionalidade principal do aplicativo: **leitura em tempo real e análise passiva de ofertas de corridas/entregas**.

* **O que lemos:** Apenas os elementos visuais contendo o valor da oferta (R$), a distância (KM), o tempo estimado e o nome do estabelecimento quando um aplicativo de entregas/transporte (como iFood, KeeTa, 99, Rappi, etc.) exibe uma chamada na tela.
* **O que NÃO fazemos:**
  * **NÃO** lemos, coletamos ou armazenamos senhas, dados bancários, mensagens pessoais, chats, contatos ou fotos.
  * **NÃO** alteramos as configurações do dispositivo nem realizamos cliques involuntários sem o consentimento ou configuração ativa do usuário.
  * **NÃO** vendemos nem compartilhamos os dados lidos com terceiros para fins publicitários.

A permissão de Acessibilidade é opcional, porém indispensável para que o HUD flutuante de rentabilidade por KM funcione. Você pode revogá-la a qualquer momento nas Configurações de Acessibilidade do seu Android.

---

### 📍 1.2. Localização e GPS em Segundo Plano (`ACCESS_FINE_LOCATION` / `ACCESS_BACKGROUND_LOCATION`)
O aplicativo utiliza o GPS do dispositivo para as seguintes finalidades:

* **Odômetro de Expediente:** Registrar a quilometragem percorrida pelo motorista durante o turno de trabalho, permitindo o cálculo do gasto estimado com combustível.
* **Mapa de Calor Colaborativo (Heatmap):** Enviar pontos geográficos anônimos de alta demanda de pedidos para alimentar o mapa de calor em tempo real compartilhado entre os motoristas.

> **Nota:** As coordenadas coletadas para o mapa de calor são **100% anonimizadas** e não possuem qualquer vínculo com seu nome, e-mail ou número de telefone.

---

### 💳 1.3. Processamento de Pagamentos e Assinaturas
Todas as assinaturas do **Copiloto Pro** (Mensal, Trimestral e Anual) são processadas nativamente pela **Google Play Billing Library v8**.
* Não coletamos nem armazenamos números de cartão de crédito, dados bancários ou códigos de segurança.
* As transações e o gerenciamento de assinaturas seguem rigorosamente os termos e garantias da **Google Play Store**.

---

## 2. Coleta e Uso de Dados Pessoais

Coletamos o mínimo de dados necessários para garantir a autenticação e o funcionamento das ferramentas:

| Dado Coletado | Finalidade | Armazenamento |
| :--- | :--- | :--- |
| **E-mail e Nome do Perfil** | Autenticação do usuário e vinculação da licença/assinatura Ativa. | Firebase Authentication / Realtime Database |
| **Ganhos e Metas Diárias** | Exibição do progresso financeiro e histórico de faturamento no aplicativo. | Armazenamento Local no dispositivo (SharedPreferences) e backup encriptado no Firebase |
| **Quilometragem Diária** | Cálculo de desgaste e custo de combustível. | Armazenamento Local no dispositivo |

---

## 3. Compartilhamento de Dados

**Não vendemos, alugamos nem comercializamos seus dados pessoais com terceiros.**

Podemos compartilhar dados estritamente anonimizados com os seguintes provedores de serviços para manter a infraestrutura do aplicativo funcionando:

* **Google Firebase / Google Cloud Platform:** Para autenticação de usuários, banco de dados em tempo real e hospedagem segura.
* **Google Play Services / Google Play Billing:** Para gestão de assinaturas nativas e serviços de localização/GPS.

---

## 4. Segurança dos Dados

Adotamos medidas de segurança técnicas e administrativas avançadas para proteger seus dados contra acesso não autorizado, alteração, divulgação ou destruição:

* **Encriptação SSL/TLS:** Todo o tráfego de dados entre o aplicativo e os servidores do Firebase é encriptado.
* **Zero-Trust Security Rules:** O banco de dados do Firebase é protegido por regras rígidas de acesso, garantindo que apenas você possa visualizar ou alterar suas informações financeiras.

---

## 5. Retenção e Exclusão de Dados

Seus dados são mantidos enquanto a sua conta estiver ativa ou conforme necessário para fornecer os serviços do aplicativo.

### 🗑️ Como Solicitar a Exclusão da Sua Conta e Dados:
Você tem o direito de solicitar a exclusão definitiva da sua conta e de todos os seus dados pessoais armazenados em nossos servidores a qualquer momento:

1. Envie um e-mail para **sangustavo190@gmail.com** com o assunto `"Exclusão de Conta - Copiloto Pro"`.
2. Informe o endereço de e-mail cadastrado no aplicativo.
3. Processaremos a exclusão completa dos seus dados no Firebase no prazo máximo de **5 dias úteis** e enviaremos uma confirmação por e-mail.

---

## 6. Alterações nesta Política de Privacidade

Podemos atualizar esta Política de Privacidade periodicamente para refletir melhorias no aplicativo ou mudanças regulatórias. Quando alterações significativas forem realizadas, notificaremos você através de um aviso visível no aplicativo ou atualizando a data de *"Última atualização"* no topo deste documento.

---

## 7. Contato e Suporte

Se você tiver dúvidas, sugestões ou preocupações sobre esta Política de Privacidade ou sobre o tratamento dos seus dados, entre em contato conosco:

* **E-mail de Suporte:** sangustavo190@gmail.com
* **Desenvolvedor:** Copiloto Pro Team
* **Repositório Oficial:** [GitHub — Copiloto Pro](https://github.com)
