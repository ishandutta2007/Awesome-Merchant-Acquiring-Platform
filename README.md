# Awesome-Merchant-Acquiring-Platform

## Top Merchant Acquiring Platform Ecosystem



**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**

*Focused on Merchant Acquiring, Payment Processing, Payment Orchestration, PSP Connectivity & Payment Infrastructure*

**Last updated: September 2026**



This repository tracks notable **SaaS/Hosted platforms** and **open-source projects** for **Merchant Acquiring Platforms**. These platforms support merchant onboarding, payment acceptance, authorization, transaction routing, payment-method processing, settlement, reconciliation, risk management, fraud prevention, tokenization, chargebacks, reporting, and connectivity to card networks, banks, and payment service providers.



**Examples** include Fiserv, Clover, Worldpay, Checkout.com, Adyen, Stripe, Global Payments, Nuvei, PayU Enterprise, and Rapyd.



Modern merchant-acquiring platforms typically combine **merchant onboarding, payment gateway functionality, processor/acquirer connectivity, payment orchestration, tokenization, 3-D Secure, fraud/risk controls, smart routing, retries, reconciliation, settlements, chargeback management, payouts, reporting, and multi-currency/multi-method payment acceptance**.



**Open-source emphasis**: This section is heavily expanded with projects for **self-hosted payment infrastructure, payment orchestration, billing, merchant payments, payment switching, digital-wallet infrastructure, clearing and settlement, payment-method integration, fraud/risk infrastructure, and developer-facing payment APIs**.



> **Important distinction:** A true merchant acquirer is not simply a software application. Acquiring involves regulated financial entities, card-network membership, sponsor-bank relationships, licenses, scheme rules, settlement accounts, PCI/security obligations, and operational risk controls. Therefore, open-source software generally provides the **technology layer around acquiring**, rather than becoming a Visa/Mastercard acquirer by itself.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites or repositories.



## Table of Contents



* [SaaS/Hosted Platforms](#saashosted-platforms)

* [Open-Source GitHub Projects](#open-source-github-projects)

* [Payment Orchestration & Routing](#payment-orchestration--routing)

* [Open Payment Switching & Interoperability](#open-payment-switching--interoperability)

* [Open-Source Billing & Payment Infrastructure](#open-source-billing--payment-infrastructure)

* [Payment Gateway & Checkout Building Blocks](#payment-gateway--checkout-building-blocks)

* [Merchant & Commerce Platforms](#merchant--commerce-platforms)

* [Fraud, Risk & Authentication](#fraud-risk--authentication)

* [Ledger, Settlement & Reconciliation](#ledger-settlement--reconciliation)

* [Data, Messaging & Infrastructure](#data-messaging--infrastructure)

* [Recommended Open-Source Merchant Acquiring Architecture](#recommended-open-source-merchant-acquiring-architecture)

* [Commercial → Open-Source Mapping](#commercial--open-source-mapping)

* [Open-Source Capability Matrix](#open-source-capability-matrix)

* [How to Contribute](#how-to-contribute)

* [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



* **[Fiserv](https://www.fiserv.com/)**

  Global payments and financial-technology provider offering merchant acquiring, payment acceptance, processing, commerce, and financial-services infrastructure.



* **[Clover](https://www.clover.com/)**

  Fiserv's merchant commerce platform combining point-of-sale, payments, business management, merchant services, and omnichannel capabilities.



* **[Worldpay](https://www.worldpay.com/)**

  Global payments provider offering merchant acquiring, payment processing, gateway services, alternative payment methods, fraud tools, and enterprise payment infrastructure.



* **[Checkout.com](https://www.checkout.com/)**

  Global payments platform providing payment processing, acquiring connectivity, fraud management, authentication, payouts, and alternative payment methods.



* **[Adyen](https://www.adyen.com/)**

  Global payments platform combining payment processing, acquiring, risk management, authentication, issuing, and unified commerce capabilities.



* **[Stripe](https://stripe.com/)**

  Developer-focused payments platform providing payment acceptance, processing, Connect, Billing, Radar, payouts, issuing, and financial infrastructure.



* **[Global Payments](https://www.globalpayments.com/)**

  Global merchant-services and payment-technology provider supporting acquiring, payment acceptance, commerce software, and integrated payments.



* **[Nuvei](https://www.nuvei.com/)**

  Global payments technology provider offering acquiring, payment processing, alternative payment methods, payouts, fraud prevention, and platform payments.



* **[PayU Enterprise](https://corporate.payu.com/)**

  Global payments infrastructure and acquiring/processing ecosystem supporting merchants, platforms, local payment methods, and cross-border commerce.



* **[Rapyd](https://www.rapyd.net/)**

  Fintech infrastructure platform providing payment collection, payouts, local payment methods, wallets, and embedded financial services.



* **[Worldline](https://worldline.com/)**

  European payments technology provider offering acquiring, merchant services, payment acceptance, digital payments, and transaction processing.



* **[Nexi](https://www.nexigroup.com/)**

  European payments group providing merchant acquiring, digital payments, issuing, and payment-processing infrastructure.



* **[Global-e](https://www.global-e.com/)**

  Cross-border commerce and payments platform supporting international merchants and localized payment experiences.



* **[ACI Worldwide](https://www.aciworldwide.com/)**

  Enterprise real-time payments and payment-processing technology provider with merchant, bank, fraud, and payment-switching capabilities.



* **[FIS](https://www.fisglobal.com/)**

  Global financial-technology company providing payment processing, merchant solutions, banking infrastructure, and transaction-processing technology.



* **[Elavon](https://www.elavon.com/)**

  Merchant-acquiring and payment-processing provider serving businesses across multiple markets.



* **[Chase Payment Solutions](https://www.chase.com/business/payments)**

  Merchant acquiring and payment acceptance services integrated with JPMorgan Chase's banking and payment infrastructure.



* **[Moneris](https://www.moneris.com/)**

  Canadian payment-processing and merchant-services provider supporting in-store and online payment acceptance.



* **[Paysafe](https://www.paysafe.com/)**

  Payments platform supporting card processing, digital wallets, alternative payments, and online commerce.



* **[PayPal Braintree](https://www.braintreepayments.com/)**

  Payment gateway and processing platform supporting cards, wallets, PayPal, recurring payments, and marketplace payments.



* **[Mollie](https://www.mollie.com/)**

  European payments platform offering payment acceptance, acquiring-related services, local payment methods, and merchant financial tools.



* **[Airwallex](https://www.airwallex.com/)**

  Global financial infrastructure platform offering payments, acquiring-related services, cards, payouts, and cross-border business infrastructure.



* **[Checkout.com Flow](https://www.checkout.com/)**

  Hosted and embedded payment experience layer supporting multiple payment methods and global processing.



* **[Primer](https://primer.io/)**

  Payment orchestration platform allowing merchants to connect and route transactions across multiple payment service providers.



* **[Gr4vy](https://gr4vy.com/)**

  Cloud-native payment orchestration platform supporting multi-PSP connectivity, routing, and payment operations.



* **[Spreedly](https://www.spreedly.com/)**

  Payment-orchestration and payment-vault infrastructure connecting merchants to multiple payment services.



* **[Paydock](https://paydock.com/)**

  Payment orchestration platform connecting merchants to multiple payment providers and payment methods.



* **[Yuno](https://www.y.uno/)**

  Payment orchestration platform supporting multiple PSPs, payment methods, smart routing, and payment optimization.



* **[BR-DGE](https://www.br-dge.com/)**

  Payment orchestration infrastructure designed to connect merchants with multiple payment providers.



* **[CellPoint Digital](https://cellpointdigital.com/)**

  Digital commerce and payment-orchestration platform with particular focus on travel and enterprise commerce.



## Open-Source GitHub Projects



> The projects below are **not all merchant acquirers**. They are grouped according to their usefulness in constructing an open payment/acquiring technology stack.

>

> The strongest open-source projects are generally **payment orchestration, billing/payment infrastructure, payment switching, merchant-payment interoperability, wallets, ledgers, and gateway integration layers**.



### Payment Orchestration & Routing



* **[Hyperswitch](https://github.com/juspay/hyperswitch)**

  Open-source payments infrastructure and payment orchestration platform built around modular payment processing. Supports routing, retries, connector integrations, vaulting-related functionality, payment operations, and connectivity to numerous processors.



  **Particularly relevant as an open-source alternative to the payment-orchestration layer around platforms such as Adyen, Checkout.com, Stripe, Worldpay, and other PSPs.**



* **[Hyperswitch Documentation](https://github.com/juspay/hyperswitch)**

  Provides the architecture and components for deploying a self-hosted payments stack, including connectors, routing, payment flows, and operational tooling.



* **[Kill Bill](https://github.com/killbill/killbill)**

  Mature open-source billing and payments platform with a modular plugin architecture for connecting payment gateways and processors.



  Supports recurring billing, payments, refunds, payment retries, multiple gateways, payment plugins, and financial reporting.



* **[Kill Bill Payment Plugins](https://github.com/killbill)**

  Kill Bill's plugin ecosystem allows payment integrations to be added without changing core billing logic.



  Existing open-source gateway integrations include providers such as Stripe, Adyen, Braintree, Qualpay, and Hyperswitch.



* **[Hyperswitch–Kill Bill Plugin](https://github.com/juspay/hyperswitch-killbill-plugin)**

  Integration connecting Kill Bill with Hyperswitch for payment orchestration.



### Open Payment Switching & Interoperability



* **[Mojaloop](https://github.com/mojaloop/mojaloop)**

  Open-source reference implementation for interoperable payment platforms connecting financial-service providers.



  Provides core concepts and services for **account lookup, clearing, settlement, transaction orchestration, and merchant payments**.



* **[Mojaloop Specification](https://github.com/mojaloop/mojaloop-specification)**

  Open API specifications for interoperability between financial-service providers and payment systems.



* **[Mojaloop Testing Toolkit](https://github.com/mojaloop)**

  Testing infrastructure for validating payment flows and interoperability within Mojaloop environments.



* **[Mojaloop Merchant Payments](https://github.com/mojaloop)**

  Merchant-payment functionality supporting merchant registration and merchant transaction initiation within the Mojaloop ecosystem.



* **[Mojaloop Central Ledger](https://github.com/mojaloop)**

  Open-source payment infrastructure for processing transfers and supporting clearing/settlement workflows between participating financial institutions.



### Open-Source Billing & Payment Infrastructure



* **[Kill Bill](https://github.com/killbill/killbill)**

  Open-source billing and payments infrastructure with a plugin architecture for multiple payment processors.



* **[Lago](https://github.com/getlago/lago)**

  Open-source usage-based billing platform supporting metering, subscriptions, invoices, credits, and payment-related workflows.



* **[OpenMeter](https://github.com/openmeterio/openmeter)**

  Open-source usage-metering infrastructure for usage-based and consumption-driven payment systems.



* **[Meteroid](https://github.com/meteroid-oss/meteroid)**

  Open-source billing and monetization platform supporting subscriptions, pricing, usage-based billing, invoicing, and payment-related workflows.



* **[ERPNext](https://github.com/frappe/erpnext)**

  Open-source ERP with accounting, invoicing, payments, customers, suppliers, and financial reporting.



* **[Odoo Community](https://github.com/odoo/odoo)**

  Open-source ERP/commerce platform with accounting, invoicing, payment integrations, e-commerce, subscriptions, and merchant workflows.



* **[Apache OFBiz](https://github.com/apache/ofbiz-framework)**

  Open-source enterprise automation framework with order management, accounting, payment, catalog, and commerce capabilities.



* **[Tryton](https://github.com/tryton/tryton)**

  Modular open-source ERP framework with accounting, sales, invoicing, and financial-management capabilities.



### Payment Gateway & Checkout Building Blocks



* **[Medusa](https://github.com/medusajs/medusa)**

  Open-source commerce platform with modular payment-provider integrations, order management, carts, customers, and checkout infrastructure.



* **[Saleor](https://github.com/saleor/saleor)**

  Open-source commerce platform with payment integrations, checkout, orders, customers, and API-first architecture.



* **[Vendure](https://github.com/vendure-ecommerce/vendure)**

  TypeScript/Node.js headless commerce framework with extensible payment-provider architecture.



* **[Solidus](https://github.com/solidusio/solidus)**

  Open-source Ruby commerce platform with checkout, orders, payments, promotions, and payment-provider integrations.



* **[Spree Commerce](https://github.com/spree/spree)**

  Open-source commerce platform supporting checkout, payment methods, orders, customers, and gateway integrations.



* **[Bagisto](https://github.com/bagisto/bagisto)**

  Open-source Laravel commerce platform with checkout, payment integration, orders, customers, and marketplace functionality.



* **[WooCommerce](https://github.com/woocommerce/woocommerce)**

  Open-source commerce platform with an extensive payment-gateway extension ecosystem.



* **[PrestaShop](https://github.com/PrestaShop/PrestaShop)**

  Open-source e-commerce platform supporting payment modules, checkout, orders, refunds, and merchant operations.



* **[OpenCart](https://github.com/opencart/opencart)**

  Open-source e-commerce platform with payment extensions and checkout functionality.



### Merchant & Commerce Platforms



* **[Medusa](https://github.com/medusajs/medusa)**

  API-first commerce infrastructure with payment-provider abstraction.



* **[Saleor](https://github.com/saleor/saleor)**

  GraphQL/API-first commerce platform suitable for custom merchant payment experiences.



* **[Vendure](https://github.com/vendure-ecommerce/vendure)**

  Extensible commerce framework with customizable payment integrations.



* **[Solidus](https://github.com/solidusio/solidus)**

  Modular open-source commerce stack for custom merchant applications.



* **[Spree](https://github.com/spree/spree)**

  Open-source commerce and checkout foundation.



### Fraud, Risk & Authentication



* **[Keycloak](https://github.com/keycloak/keycloak)**

  Open-source identity and access-management platform useful for merchant portals, operator authentication, API security, OAuth2/OIDC, SSO, and RBAC.



* **[Authentik](https://github.com/goauthentik/authentik)**

  Open-source identity provider useful for securing merchant dashboards, operations consoles, APIs, and administrative applications.



* **[OPA — Open Policy Agent](https://github.com/open-policy-agent/opa)**

  Open-source policy engine useful for transaction, merchant, API, and operational authorization rules.



* **[OpenFGA](https://github.com/openfga/openfga)**

  Fine-grained authorization system useful for merchant, platform, operator, and account-level permissions.



* **[Apache Flink](https://github.com/apache/flink)**

  Stream-processing framework suitable for real-time transaction-risk scoring, velocity rules, anomaly detection, and fraud analytics.



* **[Apache Kafka](https://github.com/apache/kafka)**

  Event-streaming infrastructure suitable for real-time payment events, fraud signals, routing decisions, and transaction processing.



* **[Redis](https://github.com/redis/redis)**

  Low-latency data store useful for velocity counters, transaction state, routing decisions, session information, and fraud rules.



* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)**

  Search and analytics engine useful for transaction investigation, fraud analysis, merchant monitoring, and operational search.



### Ledger, Settlement & Reconciliation



* **[Mojaloop](https://github.com/mojaloop/mojaloop)**

  Particularly relevant for payment clearing and settlement architecture.



* **[ERPNext](https://github.com/frappe/erpnext)**

  General ledger, accounts receivable, accounts payable, payment entries, reconciliation, and financial reporting.



* **[Odoo](https://github.com/odoo/odoo)**

  Accounting, payment records, reconciliation, financial reporting, and merchant/commerce workflows.



* **[LedgerSMB](https://github.com/ledgersmb/LedgerSMB)**

  Open-source accounting system useful as a financial ledger and reconciliation component.



* **[GnuCash](https://github.com/Gnucash/gnucash)**

  Open-source accounting software useful for smaller-scale accounting and financial reconciliation use cases.



* **[PostgreSQL](https://github.com/postgres/postgres)**

  Strong relational database foundation for transaction records, merchant accounts, payment states, settlement files, reconciliation data, and audit trails.



### Data, Messaging & Infrastructure



* **[Apache Kafka](https://github.com/apache/kafka)**

  Distributed event streaming for payment events and transaction processing.



* **[Apache Pulsar](https://github.com/apache/pulsar)**

  Distributed messaging and event-streaming infrastructure for payment systems.



* **[NATS](https://github.com/nats-io/nats-server)**

  Lightweight messaging system suitable for low-latency payment-event distribution.



* **[RabbitMQ](https://github.com/rabbitmq/rabbitmq-server)**

  Mature messaging platform for payment workflows and asynchronous processing.



* **[PostgreSQL](https://github.com/postgres/postgres)**

  Transactional database for merchant, payment, ledger, settlement, and reconciliation data.



* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)**

  High-performance analytical database for payment analytics, transaction reporting, merchant KPIs, and fraud analysis.



* **[TimescaleDB](https://github.com/timescale/timescaledb)**

  PostgreSQL extension useful for time-series transaction and operational metrics.



* **[MinIO](https://github.com/minio/minio)**

  S3-compatible object storage useful for settlement files, reconciliation files, reports, logs, and payment artifacts.



* **[Temporal](https://github.com/temporalio/temporal)**

  Durable workflow engine useful for long-running payment workflows, retries, settlement processing, reconciliation, and exception handling.



* **[Apache Airflow](https://github.com/apache/airflow)**

  Workflow orchestration for settlement files, reconciliation pipelines, reporting, and batch payment operations.



* **[Grafana](https://github.com/grafana/grafana)**

  Observability and payment-operations dashboards.



* **[Metabase](https://github.com/metabase/metabase)**

  Self-hosted BI platform for merchant and transaction reporting.



* **[Apache Superset](https://github.com/apache/superset)**

  Open-source BI and analytics platform suitable for transaction and merchant analytics.



## Additional Strong Open-Source Options



* **[Hyperswitch](https://github.com/juspay/hyperswitch)** for payment orchestration, routing, retries, and multi-processor connectivity.

* **[Kill Bill](https://github.com/killbill/killbill)** for open-source payment and billing infrastructure.

* **[Mojaloop](https://github.com/mojaloop/mojaloop)** for interoperable payment switching, clearing, settlement, and merchant-payment architecture.

* **[Lago](https://github.com/getlago/lago)** for usage-based billing and payment-related workflows.

* **[OpenMeter](https://github.com/openmeterio/openmeter)** for real-time usage metering.

* **[Meteroid](https://github.com/meteroid-oss/meteroid)** for open-source monetization and billing.

* **[Medusa](https://github.com/medusajs/medusa)** for headless commerce and payment-provider integrations.

* **[Saleor](https://github.com/saleor/saleor)** for API-first commerce and checkout.

* **[Vendure](https://github.com/vendure-ecommerce/vendure)** for customizable commerce/payment infrastructure.

* **[Solidus](https://github.com/solidusio/solidus)** for Ruby-based commerce and checkout.

* **[Spree](https://github.com/spree/spree)** for open-source commerce and payment integrations.

* **[WooCommerce](https://github.com/woocommerce/woocommerce)** for a large ecosystem of payment-gateway integrations.

* **[ERPNext](https://github.com/frappe/erpnext)** for accounting, payment records, reconciliation, and merchant operations.

* **[Odoo](https://github.com/odoo/odoo)** for ERP, commerce, accounting, and payment integration.

* **[Keycloak](https://github.com/keycloak/keycloak)** for merchant/operator identity and access management.

* **[Open Policy Agent](https://github.com/open-policy-agent/opa)** for transaction and operational policy enforcement.

* **[Apache Flink](https://github.com/apache/flink)** for real-time transaction and fraud-event processing.

* **[Kafka](https://github.com/apache/kafka)** for payment-event streaming.

* **[PostgreSQL](https://github.com/postgres/postgres)** for transactional payment and ledger storage.

* **[ClickHouse](https://github.com/ClickHouse/ClickHouse)** for high-volume payment analytics.

* **[Grafana](https://github.com/grafana/grafana)** and **[Metabase](https://github.com/metabase/metabase)** for payment operations and merchant dashboards.



**Frameworks for building custom systems**: Combine **Hyperswitch + Kill Bill + Mojaloop + PostgreSQL + Kafka + Redis + Open Policy Agent + Flink + Grafana** with a regulated acquiring/processing partner to create a highly customizable payment-processing and merchant-acquiring technology stack.



## Recommended Open-Source Merchant Acquiring Architecture



```text

┌─────────────────────────────────────────────────────────────────────┐

│                         MERCHANT LAYER                              │

│                                                                     │

│  Web Store │ Mobile App │ POS │ Marketplace │ SaaS │ Platform       │

└───────────────────────────────┬─────────────────────────────────────┘

                                │

                                ▼

┌─────────────────────────────────────────────────────────────────────┐

│                    PAYMENT EXPERIENCE LAYER                         │

│                                                                     │

│  Checkout │ Payment Links │ Hosted Payment Page │ APIs │ SDKs       │

└───────────────────────────────┬─────────────────────────────────────┘

                                │

                                ▼

┌─────────────────────────────────────────────────────────────────────┐

│                   PAYMENT ORCHESTRATION LAYER                       │

│                                                                     │

│                     Hyperswitch / Custom                            │

│                                                                     │

│   Smart Routing │ Retries │ Failover │ Cascading │ 3DS │ Tokens    │

└───────────────────────────────┬─────────────────────────────────────┘

                                │

              ┌─────────────────┼──────────────────┐

              ▼                 ▼                  ▼

       ┌─────────────┐   ┌─────────────┐    ┌─────────────┐

       │ PSP /       │   │ Acquirer /  │    │ Alternative │

       │ Gateway     │   │ Processor   │    │ Payments    │

       └──────┬──────┘   └──────┬──────┘    └──────┬──────┘

              │                 │                  │

              └─────────────────┼──────────────────┘

                                ▼

                     ┌──────────────────────┐

                     │ Card Networks /      │

                     │ Payment Rails        │

                     └──────────────────────┘

                                │

                                ▼

                     ┌──────────────────────┐

                     │ Authorization       │

                     │ Capture / Refund     │

                     │ Settlement           │

                     └──────────┬───────────┘

                                │

             ┌──────────────────┼──────────────────┐

             ▼                  ▼                  ▼

       ┌──────────┐       ┌────────────┐     ┌───────────┐

       │ Ledger   │       │ Reconcile  │     │ Reporting │

       │          │       │            │     │           │

       │ ERPNext  │       │ Kafka      │     │ Grafana   │

       │ / Odoo   │       │ PostgreSQL │     │ Metabase  │

       └──────────┘       └────────────┘     └───────────┘

```



## Commercial → Open-Source Mapping



| Commercial Platform                         | Open-Source Building-Block Strategy                                      |

| ------------------------------------------- | ------------------------------------------------------------------------ |

| **Fiserv**                                  | Hyperswitch + Kill Bill + ERPNext/Odoo + processor/acquirer integrations |

| **Clover**                                  | Medusa/Saleor + Hyperswitch + POS application + ERPNext                  |

| **Worldpay**                                | Hyperswitch + Kill Bill + processor connectors + fraud/risk stack        |

| **Checkout.com**                            | Hyperswitch + custom checkout + processor/acquirer connectors            |

| **Adyen**                                   | Hyperswitch + custom acquiring/processor integrations + risk engine      |

| **Stripe**                                  | Hyperswitch + Medusa/Saleor + Kill Bill + merchant platform              |

| **Global Payments**                         | Hyperswitch + Kill Bill + ERPNext/Odoo + regulated processor             |

| **Nuvei**                                   | Hyperswitch + payment connectors + risk/ledger infrastructure            |

| **PayU Enterprise**                         | Hyperswitch + local payment connectors + merchant platform               |

| **Rapyd**                                   | Hyperswitch + Mojaloop + wallet/payment infrastructure                   |

| **Primer**                                  | Hyperswitch + routing engine + merchant control plane                    |

| **Gr4vy**                                   | Hyperswitch + connector abstraction + routing engine                     |

| **Mojaloop-based acquiring infrastructure** | Mojaloop + merchant-payment modules + ledger + settlement                |

| **Custom PSP**                              | Hyperswitch + Kill Bill + PostgreSQL + Kafka + risk engine               |



> These mappings are **architectural equivalents, not drop-in replacements**. Commercial acquiring platforms combine regulated acquiring relationships, card-network connectivity, proprietary risk systems, tokenization infrastructure, settlement operations, compliance, merchant underwriting, and production support that cannot be reproduced merely by installing open-source software.



## Open-Source Merchant Payment Capability Matrix



| Capability             | Hyperswitch | Kill Bill | Mojaloop | Medusa | ERPNext | Odoo | Kafka | Flink |

| ---------------------- | ----------: | --------: | -------: | -----: | ------: | ---: | ----: | ----: |

| Payment Orchestration  |           ✅ |         ✅ |       ⚠️ |     ⚠️ |      ⚠️ |   ⚠️ |     ❌ |     ❌ |

| Multi-PSP Connectivity |           ✅ |         ✅ |       ⚠️ |     ⚠️ |      ⚠️ |   ⚠️ |     ❌ |     ❌ |

| Smart Routing          |           ✅ |         ✅ |       ⚠️ |      ❌ |       ❌ |    ❌ |    ⚠️ |    ⚠️ |

| Payment Retries        |           ✅ |         ✅ |       ⚠️ |     ⚠️ |      ⚠️ |   ⚠️ |    ⚠️ |    ⚠️ |

| Subscription Billing   |          ⚠️ |         ✅ |        ❌ |     ⚠️ |       ✅ |    ✅ |     ❌ |     ❌ |

| Merchant Checkout      |          ⚠️ |        ⚠️ |       ⚠️ |      ✅ |       ✅ |    ✅ |     ❌ |     ❌ |

| Merchant Management    |          ⚠️ |         ✅ |        ✅ |      ✅ |       ✅ |    ✅ |     ❌ |     ❌ |

| Payment Processing     |           ✅ |         ✅ |        ✅ |     ⚠️ |      ⚠️ |   ⚠️ |     ❌ |     ❌ |

| Acquirer Connectivity  |          ⚠️ |         ✅ |       ⚠️ |     ⚠️ |      ⚠️ |   ⚠️ |     ❌ |     ❌ |

| Clearing               |           ❌ |        ⚠️ |        ✅ |      ❌ |      ⚠️ |   ⚠️ |    ⚠️ |    ⚠️ |

| Settlement             |          ⚠️ |        ⚠️ |        ✅ |      ❌ |       ✅ |    ✅ |    ⚠️ |    ⚠️ |

| Reconciliation         |          ⚠️ |         ✅ |       ⚠️ |     ⚠️ |       ✅ |    ✅ |    ⚠️ |    ⚠️ |

| Fraud Rules            |          ⚠️ |        ⚠️ |       ⚠️ |      ❌ |       ❌ |    ❌ |    ⚠️ |     ✅ |

| Event Streaming        |          ⚠️ |        ⚠️ |        ✅ |     ⚠️ |      ⚠️ |   ⚠️ |     ✅ |     ✅ |

| General Ledger         |           ❌ |        ⚠️ |       ⚠️ |      ❌ |       ✅ |    ✅ |     ❌ |     ❌ |

| Self-Hosted            |           ✅ |         ✅ |        ✅ |      ✅ |       ✅ |    ✅ |     ✅ |     ✅ |



> `⚠️` indicates that the capability requires customization, external services, payment-provider integrations, or another component.



## Best Open-Source Combinations



### Open Payment Orchestration



```text

Hyperswitch

   +

PostgreSQL

   +

Redis

   +

Kafka

   +

Merchant Dashboard

   +

External Acquirers / PSPs

```



Useful for:



* Multi-PSP routing

* Payment failover

* Retry strategies

* Payment analytics

* Connector abstraction

* Payment-method normalization



### Open Merchant Payment Platform



```text

Medusa / Saleor

       +

Hyperswitch

       +

Kill Bill

       +

PostgreSQL

       +

Kafka

       +

ERPNext / Odoo

```



Useful for:



* Merchant commerce

* Checkout

* Subscriptions

* Payment processing

* Invoicing

* Accounting

* Reconciliation



### Open Acquiring Technology Stack



```text

Merchant

   ↓

Merchant API / Checkout

   ↓

Payment Orchestrator

   ↓

Hyperswitch

   ↓

Risk / 3DS / Tokenization

   ↓

Acquirer / PSP Connectors

   ↓

Card Networks / Payment Rails

   ↓

Authorization

   ↓

Capture

   ↓

Clearing

   ↓

Settlement

   ↓

Ledger / Reconciliation

   ↓

Merchant Payout

```



### Interoperable Payment Infrastructure



```text

Merchant / Customer

        ↓

Mojaloop APIs

        ↓

Account Lookup

        ↓

Transaction Routing

        ↓

Central Ledger

        ↓

Clearing

        ↓

Settlement

        ↓

Financial Service Providers

```



### Enterprise Payment Data Platform



```text

Payment Events

      ↓

Kafka

      ↓

Flink

      ↓

┌─────────────────────────────┐

│ Risk / Fraud                │

│ Routing                     │

│ Transaction Analytics       │

│ Merchant Monitoring         │

│ Reconciliation              │

└──────────────┬──────────────┘

               ↓

        PostgreSQL

               +

          ClickHouse

               ↓

      Grafana / Metabase

```



## Key Open-Source Components by Function



| Function                           | Recommended Projects          |

| ---------------------------------- | ----------------------------- |

| Payment orchestration              | Hyperswitch                   |

| Gateway abstraction                | Hyperswitch / Kill Bill       |

| Subscription payments              | Kill Bill                     |

| Billing                            | Kill Bill / Lago / Meteroid   |

| Usage metering                     | OpenMeter                     |

| Merchant commerce                  | Medusa / Saleor / Vendure     |

| Merchant ERP                       | ERPNext / Odoo                |

| Payment interoperability           | Mojaloop                      |

| Clearing & settlement architecture | Mojaloop                      |

| Identity                           | Keycloak / Authentik          |

| Policy engine                      | Open Policy Agent             |

| Event streaming                    | Kafka / Pulsar / NATS         |

| Real-time processing               | Apache Flink                  |

| Transaction database               | PostgreSQL                    |

| Analytics                          | ClickHouse                    |

| Cache / velocity                   | Redis                         |

| Object storage                     | MinIO                         |

| Workflow                           | Temporal / Airflow            |

| BI                                 | Grafana / Metabase / Superset |



## What Open Source Can Replace



Open-source software can provide much of the **software infrastructure surrounding merchant acquiring**, including:



* Payment orchestration

* Payment routing

* Multi-PSP connectivity

* Gateway abstraction

* Checkout infrastructure

* Merchant APIs

* Subscription billing

* Invoicing

* Payment-event processing

* Fraud-rule infrastructure

* Merchant portals

* Transaction databases

* Ledgers

* Reconciliation pipelines

* Analytics

* Reporting

* Payment switching

* Clearing/settlement reference architecture

* Digital-wallet infrastructure

* Identity and access management

* Operational monitoring



## What Open Source Cannot Automatically Replace



Open-source software alone does **not** automatically provide:



* Visa membership

* Mastercard membership

* Card-network certification

* Acquirer licenses

* Sponsor-bank relationships

* Regulated acquiring status

* Merchant underwriting

* Scheme compliance

* PCI DSS certification

* Production-grade HSM infrastructure

* Card-network settlement accounts

* Network tokenization agreements

* Acquirer BIN sponsorship

* Chargeback operations

* Financial risk capital

* Banking relationships

* Regulated money-movement permissions



Therefore, a practical open-source acquiring company normally uses:



```text

Open-Source Software

        +

Licensed Acquirer / Processor

        +

Card-Network Connectivity

        +

Banking / Settlement Partner

        +

Compliance Infrastructure

        +

Risk / Fraud Operations

```



## Recommended Technology Stack



### Core



```text

Hyperswitch

+

Kill Bill

+

PostgreSQL

+

Redis

+

Kafka

```



### Merchant Layer



```text

Medusa

/

Saleor

/

Vendure

```



### Financial Layer



```text

ERPNext

/

Odoo

```



### Interoperability



```text

Mojaloop

```



### Risk & Policy



```text

Open Policy Agent

+

Apache Flink

+

Redis

+

Kafka

```



### Identity



```text

Keycloak

/

Authentik

```



### Analytics



```text

ClickHouse

+

Grafana

+

Metabase

```



### Workflow



```text

Temporal

/

Apache Airflow

```



## Example Open-Source Payment Flow



```text

                    CUSTOMER

                       │

                       ▼

                ┌─────────────┐

                │   Checkout  │

                └──────┬──────┘

                       │

                       ▼

                ┌─────────────┐

                │ Merchant API│

                └──────┬──────┘

                       │

                       ▼

             ┌──────────────────┐

             │   Hyperswitch    │

             │                  │

             │ Routing          │

             │ Retry            │

             │ Connector        │

             │ Abstraction      │

             └────────┬─────────┘

                      │

          ┌───────────┼───────────┐

          ▼           ▼           ▼

       Acquirer A  Acquirer B  PSP C

          │           │           │

          └───────────┼───────────┘

                      ▼

                Card / APM Rail

                      │

                      ▼

                 AUTHORIZATION

                      │

                      ▼

                    CAPTURE

                      │

                      ▼

                   CLEARING

                      │

                      ▼

                  SETTLEMENT

                      │

                      ▼

             ┌────────────────┐

             │ Ledger / ERP   │

             │ ERPNext/Odoo   │

             └───────┬────────┘

                     │

                     ▼

              RECONCILIATION

                     │

                     ▼

                MERCHANT PAYOUT

```



## Open-Source Payment Security Stack



A serious self-hosted payment platform should include:



```text

TLS

+

Tokenization

+

HSM / Key Management

+

PCI DSS Controls

+

3-D Secure

+

Strong Authentication

+

Fraud Rules

+

Velocity Limits

+

Device / IP Risk

+

RBAC

+

Audit Logs

+

Immutable Transaction Logs

+

Secrets Management

```



Potential open-source building blocks include:



* **[Keycloak](https://github.com/keycloak/keycloak)** — identity and access management.

* **[Open Policy Agent](https://github.com/open-policy-agent/opa)** — policy enforcement.

* **[HashiCorp Vault](https://github.com/hashicorp/vault)** — secrets-management infrastructure.

* **[OpenBao](https://github.com/openbao/openbao)** — open-source secrets-management alternative.

* **[Apache Flink](https://github.com/apache/flink)** — real-time stream processing.

* **[Kafka](https://github.com/apache/kafka)** — event streaming.

* **[Redis](https://github.com/redis/redis)** — low-latency state and velocity controls.

* **[OpenSearch](https://github.com/opensearch-project/OpenSearch)** — transaction and security analytics.



> Payment-card data requires specialized security architecture. An open-source component being available does not mean that an implementation is automatically PCI DSS compliant.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: project name, official/repository link, 1–2 sentence description, and whether it is SaaS, hosted, open-source, payment orchestration, billing, switching, or infrastructure.

4. For open-source projects, include the actual GitHub repository whenever available.

5. Do not describe a billing, commerce, or gateway project as a regulated merchant acquirer unless it actually provides acquiring services.

6. Mention important licensing, compliance, and maturity limitations where relevant.

7. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



* This is a **community-curated** list — not exhaustive and not an endorsement.

* Merchant acquiring is a regulated financial activity and involves card-network rules, banking relationships, licensing, risk management, settlement, and compliance.

* Most open-source projects listed here are **payment-orchestration platforms, billing systems, commerce frameworks, payment switches, ledgers, interoperability platforms, or infrastructure components**, rather than complete merchant acquirers.

* Open-source software does not by itself provide Visa/Mastercard acquiring membership or the legal authority to acquire card transactions.

* Payment processing systems require appropriate security controls, tokenization, encryption, key management, monitoring, and operational procedures.

* Organizations processing payment-card data should evaluate **PCI DSS**, applicable card-network requirements, local financial regulations, data-protection laws, AML/KYC obligations, and relevant licensing requirements.

* Production payment infrastructure should undergo independent security assessment, penetration testing, disaster-recovery testing, operational validation, and compliance review.

* Always verify current project status, license, dependencies, supported payment methods, processor connectors, and commercial/open-core restrictions before adopting any project.



---



**Made for payment companies, merchant acquirers, PSPs, fintechs, marketplaces, SaaS platforms, payment engineers, and open-source developers.**

Let's make merchant payment infrastructure more **open, interoperable, programmable, transparent, and resilient**.
