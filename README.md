# Edelweiss Mutual Fund case study

## About project

Edelweiss Mutual Fund ([edelweissmf.com](https://www.edelweissmf.com/)) is India’s digital front door for mutual fund investing—SIP and lumpsum, fund discovery, portfolio tools, and self-service support in one place. The platform serves both **Investors** (retail and direct) and **Partners** (distributors and advisors), with toll-free and regional phone support alongside online journeys.

The live site is built around making investing feel simple: browse funds by category, compare options, start SIP or lumpsum from the same screen, and use guided bundles when someone wants a ready-made allocation mix. An AI assistant named **Ellie** helps with questions and portfolio access. A separate **eInvest** mobile app extends the same experience on the go. Behind the scenes, the business runs on a cloud-first, API-led stack so the site can stay up during busy periods like new fund offers (NFOs) and handle growth without slowing investors down.

This case study describes that digital mutual fund platform—what problem it solves, how it is put together, who it is for, what was delivered, and where to see it live.

## Technology stack

- **Frontend (web)**: **Angular** — investor and partner portal at [edelweissmf.com](https://www.edelweissmf.com/) (fund discovery, SIP/lumpsum, compare/cart, bundles, self-service)
- **Mobile**: **Ionic** + **Angular** — cross-platform **eInvest** app and mobile-aligned experiences (portfolio tracking, investing, withdrawals on iOS/Android)
- **Cloud & scale**: Amazon Web Services (AWS) as the preferred cloud; workloads sized for high concurrent traffic (e.g. NFO peaks) and 24×7 availability
- **Architecture**: API-based digital ecosystem, modular microservices, shared Angular/Ionic codebase across web and mobile where applicable, CI/CD and DevSecOps practices
- **Platform delivery**: Responsive UI with HTTPS, secure session handling, and regulatory-aligned flows (KYC, scheme documents, disclaimers)
- **AI & automation**: **Ellie** chatbot for investor support and portfolio access; ML for predictive analytics (e.g. redemption trends) and personalization; exploration of generative AI for richer advisory-style interactions
- **Data & reporting**: Snowflake AI Data Cloud (with implementation partners) for unified analytics, faster NAV/benchmark reporting, risk/compliance, and governed data for finance, sales, and client reporting
- **Integrations**: Market and portfolio data feeds, business intelligence dashboards, Straight Through Processing (STP) for transactions, stock/market APIs for near real-time performance views
- **Security & compliance**: ISO 27001:2022–aligned practices, encryption, MFA, penetration testing; alignment with SEBI cloud security and cybersecurity frameworks

## The client

**Edelweiss Asset Management Company Ltd.** (Edelweiss Mutual Fund) is a leading Indian asset manager offering equity, debt, hybrid, index/ETF, target maturity, and precious metals funds, among others. The brand sits within the broader Edelweiss financial services group and competes on trust, transparency, and service quality—not only on fund performance.

Their audience includes:

- **Retail and direct investors** who want to research funds, start SIPs from as low as ₹100, invest lumpsum from ₹1,000, compare schemes, and manage life-cycle needs (statements, NAV, downloads, factsheets) online
- **Digital-first users** who expect fast pages, clear risk/return cues (e.g. risk labels, investor counts, inception returns on fund cards), and paperless onboarding in minutes when KYC is ready
- **Partners and distributors** who need reliable access, co-branded journeys, and operational support alongside the investor experience
- **Internal teams** (operations, compliance, product, marketing) who need scalable systems, accurate reporting, and shorter time-to-market for new offerings

As mutual fund adoption grew in India, a legacy digital stack could not keep up: limited concurrency, slow UI, security gaps, and expensive change cycles. Edelweiss needed a modern platform that matches how people actually invest today—mostly online, often on mobile, with instant information and strong regulatory guardrails.

## The solution

- **Unified online investment hub**: One site for discovering funds (Equity, Hybrid, Debt, Index/ETFs, Target Maturity, Precious Metals), reading scheme details, and acting—**Compare**, **Add to Cart**, **SIP**, **Lumpsum**, and **Invest Now** on fund cards and detail flows
- **SIP and lumpsum made frictionless**: Preset amounts (e.g. ₹500 / ₹1,000 / ₹10,000), date picker for monthly SIP, and cart-style checkout so investors do not restart the journey for every fund
- **Curated portfolio bundles**: Goal-oriented combos with recommended horizon, allocation mix, bundle return, and “value of ₹1 lakh invested” style illustrations—always paired with clear disclaimers that combos are illustrative and not personalized advice unless the user seeks it
- **Investor education layer**: “Proud To Have” and knowledge hub surfacing podcasts, webinars, Klassroom, blogs, and book summaries so users can learn before they commit
- **Self-service utilities**: Quick links to digital factsheet, types of mutual funds, account statement, office locator, NAV, and downloads—reducing call-center load for routine needs
- **Ellie (AI assistant)**: Chat-based help for common questions and portfolio-oriented tasks, improving reach without forcing every query through phone support
- **eInvest mobile experience**: Parity with web for tracking, transacting, and staying engaged outside the browser
- **Partner-ready operating model**: Separate **Investors** vs **Partners** entry points, plus published toll-free **1800 425 0090** and non-toll **+91-40-23001181** for human escalation
- **Cloud-native resilience**: Elastic capacity for traffic spikes, microservices for easier upgrades, API fabric to connect AMC systems with group entities where joint services are offered
- **Data-driven operations**: Centralized data platform for faster regulatory and client reporting, analytics for fund flows and risk, and a foundation for AI-led recommendations and liquidity planning
- **Security-by-design**: DevSecOps, encrypted transport, transaction history with controlled access, and ongoing investment in cybersecurity (reported at 10%+ of annual tech budget)

## The results

Public transformation programs around Edelweiss’s mutual fund digital stack have reported outcomes in this range (replace with your own measured KPIs if you led the delivery):

- **~37% faster time to market** for new fund offerings (NFOs)
- **~77% reduction** in time to process mutual fund transactions
- **~23% increase** in revenue attributed to the improved digital channel
- **250+ employee hours saved per month** through automation and smoother operations
- **Higher customer satisfaction** from faster, more reliable web and mobile experiences
- **Stronger investor engagement** via 24×7 access, real-time portfolio views, and educational content
- **Improved compliance posture** with governed data, quicker NAV/benchmark reporting, and security frameworks aligned to SEBI expectations
- **Better scalability**—from handling hundreds of concurrent users on legacy infrastructure to thousands during peak campaigns without degrading the investor journey

On the live product today, visitors see tangible proof of adoption on the homepage itself—popular funds showing large investor bases (e.g. tens of thousands to lakhs of investors on flagship equity schemes) and clear return snapshots—signaling that the platform is a primary sales and servicing channel, not a brochure site.

## Demo

**Live product**: [https://www.edelweissmf.com/](https://www.edelweissmf.com/)
