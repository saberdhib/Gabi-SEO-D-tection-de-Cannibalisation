# Rapport SEO – Detection de Cannibalisation
**Site analyse** : https://useinbox.com
**Repo analyse** : N/A
**Mode d'analyse** : Site seul (snippets Google Search)
**Date** : 2026-06-11
**Genere par** : Gabi SEO – Detection de Cannibalisation

---

## Resume executif
- **Pages analysees** : 50+ (liste non exhaustive — limitee aux pages indexees visibles dans les SERPs)
- **Groupes suspects detectes** : 7
- **Risque critique** : 1 groupe (G3)
- **Risque eleve** : 5 groupes (G1, G2, G4, G5, G7)
- **Risque moyen** : 1 groupe (G6)
- **Anomalies techniques identifies** : 6
- **Action prioritaire recommandee** : Resoudre en urgence les doublons exacts blog/standalone et la multiplication de pages sur l'affiliate marketing, qui fragmentent l'autorite SEO sur les intentions les plus commerciales du site.

> Ce rapport est en lecture seule. Aucune modification n'a ete effectuee.
> Chaque recommandation necessite une validation explicite avant execution.

---

## Limites de l'analyse

- **Acces HTTP 403 sur toutes les pages** : aucune page n'a ete chargee directement. Toutes les donnees (title, meta description, H1) proviennent de snippets Google Search, de resultats en cache, ou d'inferences.
- **H2, canonical, noindex, word count non confirmes** : ces champs sont indisponibles ou infers — leur absence ne signifie pas qu'ils n'existent pas sur les pages reelles.
- **Niveau de confiance global des donnees brutes** : Moyen pour title + meta description, Faible pour H2, canonical, noindex, maillage interne.
- **Liste de pages non exhaustive** : seules les pages indexees et visibles dans les SERPs ont ete incluses. Des pages hors-index, sous authentification ou non crawlees peuvent exister.
- **robots.txt inaccessible** : les directives de crawl sont inconnues. Des pages possiblement bloquees au crawl peuvent apparaitre indexees.
- **Donnees de trafic absentes** : aucune donnee Google Search Console, Google Analytics, CTR ou position reelle n'est disponible. Les recommandations de "page principale" reposent sur des signaux structurels, pas sur la performance observee.
- **Maillage interne non mesure** : le nombre de liens internes recus par chaque page n'a pas pu etre etabli par crawl direct.
- **Sous-domaine www. partiellement couvert** : une seule page du sous-domaine www.useinbox.com a ete identifiee.

---

## Inventaire des pages analysees

| # | URL | Title | H1 | Noindex | Notes |
|---|-----|-------|----|---------|-------|
| 1 | / | "Create email marketing your subscribers will admire INBOX \| Email" | "Create email marketing your subscribers will admire" | non | |
| 2 | /pricing | "Pricing \| Create email marketing your subscribers will admire INBOX" | null | non | H1 absent |
| 3 | /pricing-cold-email | "Cold E-mail Pricing \| INBOX" | null | non | H1 absent |
| 4 | /pricing-verify | "E-mail Verification Pricing \| INBOX" | null | non | H1 absent |
| 5 | /email-marketing/ | "Email Marketing: What It Is & How to Master It with INBOX" | "Email Marketing: What It Is & How to Master It with INBOX" | non | Page pilier |
| 6 | /mailing | "Mailing: What It Is & How It Works \| 2025 Guide \| INBOX" | "Mailing: What It Is & How It Works" | non | |
| 7 | /tutorials/ | "INBOX Tutorials: The Ultimate Guide to Email Marketing" | "INBOX Tutorials: The Ultimate Guide to Email Marketing" | non | |
| 8 | /transactional-email | "The Ultimate Guide to Transactional Emails: Definition, Best Practices, and Advanced Strategies Meta Description - Create email marketing your subscribers will admire INBOX \| Email" | "The Ultimate Guide to Transactional Emails" | non | ANOMALIE : title corrompu |
| 9 | /transactional-emails-service/what-is-transactional-email | "Transactional Email Service for OTP, Password Reset & Order Emails" | "Transactional Email Service for OTP, Password Reset & Order Emails" | non | |
| 10 | /cold-email | "INBOXCold: Unlock the Power of Cold Email Marketing for Your Business" | "INBOXCold: Unlock the Power of Cold Email Marketing for Your Business" | non | |
| 11 | /what-is-cold-email | "Cold Email: An Effective Way to Reach Potential Customers - INBOX" | "Cold Email: An Effective Way to Reach Potential Customers" | non | |
| 12 | /mailchimp-alternative/ | "Why INBOX is the Best Mailchimp Alternative" | "Why INBOX is the Best Mailchimp Alternative" | non | |
| 13 | /landing-pages/ | "Landing Pages: The Key to Success - UseINBOX" | "Landing Pages: The Key to Success" | non | |
| 14 | /subscription-forms/ | "Grow Your Email List Effectively - INBOX" | "Grow Your Email List Effectively" | non | |
| 15 | /email-api/ | "Email API - Streamline Your Communication - inbox" | "Email API - Streamline Your Communication" | non | |
| 16 | /notify/features/ | "Features - Transactional Emails, Notification Emails \| Transactional Emails" | "Features" | non | |
| 17 | /notify/features/email-api | "Create email marketing your subscribers will admire INBOX \| Email" | null | non | ANOMALIE : title = homepage title |
| 18 | /notify/features/email-delivery/ | "Email Delivery - Transactional Emails, Notification Emails \| Transactional Emails" | "Email Delivery" | non | |
| 19 | /notify/features/webhooks/ | "Webhooks - Transactional Emails, Notification Emails \| Transactional Emails" | "Webhooks" | non | |
| 20 | /notify/features/insight/ | "Insight - Transactional Emails, Notification Emails \| Transactional Emails" | "Insight" | non | |
| 21 | /casl | "CASL Compliance 2025: Simple Guide to Smarter Email Marketing \| INBOX" | "CASL Compliance 2025: Simple Guide to Smarter Email Marketing" | non | |
| 22 | /knowledgebase/canadas-anti-spam-legislation-casl | "Canada's Anti-Spam Legislation (CASL) - INBOX" | "Canada's Anti-Spam Legislation (CASL)" | non | DOUBLON de #23 |
| 23 | /knowledge-base/general/canadas-anti-spam-legislation-casl/ | "Canada's Anti-Spam Legislation (CASL) \| INBOX" | "Canada's Anti-Spam Legislation (CASL)" | non | DOUBLON de #22 |
| 24 | /what-is-kpi | "The Ultimate Guide to KPIs in Email & Digital Marketing \| INBOX" | "The Ultimate Guide to KPIs in Email & Digital Marketing" | non | |
| 25 | /best-workflows-to-automate-your-email-campaigns/ | "Best Workflows to Automate Your Email Campaigns - INBOX" | "Best Workflows to Automate Your Email Campaigns" | non | DOUBLON de /blog/best-workflows-.../ |
| 26 | /automation/lead-generation-email | "Lead Generation Email Automation Workflow Example - INBOX" | "Lead Generation Email Automation Workflow Example" | non | DOUBLON de /automation-3/lead-generation-example/ |
| 27 | /automation-3/lead-generation-example/ | "Lead Generation Automation Workflow Example- Create More Leads" | "Lead Generation Automation Workflow Example" | non | DOUBLON de #26 |
| 28 | /automation-3/welcome-email-workflow-example/ | "Welcome Email Workflow Example \| INBOX" | "Welcome Email Workflow Example" | non | |
| 29 | /automation-3/customerloyality-email-workflow-example/ | "Customer Feedback Email Workflow Example - inbox" | "Customer Feedback Email Workflow Example" | non | |
| 30 | /automation/email-series-email | "Email Series Email Automation Workflow Example - INBOX" | "Email Series Email Automation Workflow Example" | non | |
| 31 | /automation/goodbye-email | "Good Bye Email Automation Workflow Example - INBOX" | "Good Bye Email Automation Workflow Example" | non | |
| 32 | /affiliate-marketing-what-is-it-faq/ | "Affiliate Marketing: What is it? & FAQ - INBOX" | "Affiliate Marketing: What is it? & FAQ" | non | DOUBLON de /blog/affiliate-marketing-what-is-it-faq/ |
| 33 | /guide-for-affiliate-marketing/ | "Guide for Affiliate Marketing" | "Guide for Affiliate Marketing" | non | |
| 34 | /how-to-use-affiliate-marketing-via-mail-marketing/ | "How to Use Affiliate Marketing Via Mail Marketing" | "How to Use Affiliate Marketing Via Mail Marketing" | non | DOUBLON de /blog/how-to-use-.../ |
| 35 | /email-verify/security-email-verify-who-to-trust-your-data-to/ | "Security & Email Verify: Who to Trust Your Data to - INBOXVerify" | "Security & Email Verify: Who to Trust Your Data to" | non | DOUBLON de /blog/security-email-verify-.../ |
| 36 | /email-verify/number-1-email-verify-tool/ | "Number 1 Email verify tool" | "Number 1 Email verify tool" | non | DOUBLON de /blog/number-1-email-verify-tool/ |
| 37 | www.useinbox.com/mass-email-verify-tool-.../ | "Mass Email Verify tool: Clean Your Email Directory List For Best Email Marketing ROI" | null | non | Sous-domaine + DOUBLON de /blog/mass-email-verify-tool-.../ |
| 38 | /industries | "Industries - INBOX" | "Industries" | non | Hub |
| 39 | /industries/email-marketing-for-manufacturers | "E-mail Marketing For Manufacturers - INBOX" | — | non | |
| 40 | /industries/email-marketing-for-media-and-publishing | "E-mail Marketing For Media and Publishing - INBOX" | — | non | |
| 41 | /industries/email-marketing-for-retail | "E-mail Marketing For Retail - INBOX" | — | non | |
| 42 | /industries/email-marketing-for-residential-and-consumer-services | "E-mail Marketing For Residential and Consumer Services - INBOX" | — | non | |
| 43 | /industries/email-marketing-for-sports-and-recreation | "E-mail Marketing For Sports and Recreation - INBOX" | — | non | |
| 44 | /industries/email-marketing-for-staffing-and-recruiting | "Email Marketing for Staffing & Recruiting - UseINBOX" | — | non | |
| 45 | /industries/email-marketing-for-hospitality | "Email Marketing for Hospitality: Enhancing Guest Engagement - INBOX" | — | non | |
| 46 | /industries/email-marketing-for-travel-agencies | "E-mail Marketing For Travel Agencies - INBOX" | — | non | |
| 47 | /industries/email-marketing-for-marketing-advertising | "E-mail Marketing For Marketing Advertising - INBOX" | — | non | |
| 48 | /blog/affiliate-marketing-what-is-it/ | "Affiliate Marketing: What is it? - UseINBOX" | — | non | |
| 49 | /blog/affiliate-marketing-a-beginners-guide/ | "Affiliate Marketing: A Beginner's Guide" | — | non | |
| 50 | /blog/affiliate-marketing-what-is-it-faq/ | "Affiliate Marketing: What is it? & FAQ - UseINBOX" | — | non | |
| 51 | /blog/affiliate-marketing-what-is-it-and-how-to-use-it/ | "Affiliate Marketing: What is it and how to use it?" | — | non | |
| 52 | /blog/the-ultimate-guide-to-saas-affiliate-marketing-in-2026-inbox-affiliate-program/ | "The Ultimate Guide to SaaS Affiliate Marketing in 2026" | — | non | |
| 53 | /blog/how-to-use-affiliate-marketing-via-mail-marketing/ | "How to Use Affiliate Marketing Via Mail Marketing - UseINBOX" | — | non | |
| 54 | /blog/8-best-email-newsletter-examples-how-to-design/ | "8 Best Email Newsletter Examples, How to Design" | — | non | |
| 55 | /blog/innovative-email-newsletter/ | "Innovative Email Newsletter - UseInbox" | — | non | |
| 56 | /blog/19-hints-for-incredible-email-newsletter-design-outline/ | "19 Hints For Incredible Email Newsletter Design Outline" | — | non | |
| 57 | /blog/newsletter-design-ideas-for-inspiration/ | "Newsletter Design Ideas for Inspiration" | — | non | |
| 58 | /blog/email-newsletter-best-practices/ | "Email Newsletter Best Practices" | — | non | |
| 59 | /blog/10-tips-to-make-your-newsletter-visually-appealing/ | "10 Tips to Make Your Newsletter Visually Appealing" | — | non | |
| 60 | /blog/main-tips-for-beautiful-newsletter-designs/ | "Main Tips For Beautiful Newsletter Designs" | — | non | |
| 61 | /blog/12-best-design-tips-for-newsletter-to-guarantee-email-marketing-success/ | "12 Best Design Tips for Newsletter" | — | non | |
| 62 | /blog/best-email-designs/ | "Best Email Designs - UseINBOX" | — | non | |
| 63 | /blog/best-practices-for-newsletter-signup-designs/ | "The Best Practices for Newsletter Signup Designs" | — | non | |
| 64 | /blog/5-most-essential-tips-for-creating-responsive-newsletters/ | "5 Expert Tips for Designing Responsive Newsletters that Convert" | — | non | |
| 65 | /blog/best-workflows-to-automate-your-email-campaigns/ | "Best Workflows to Automate Your Email Campaigns" | — | non | |
| 66 | /blog/transactional-email-guide-best-practices-setup/ | "TRANSACTIONAL EMAIL GUIDE: BEST PRACTICES & SETUP" | — | non | |
| 67 | /blog/mass-email-verify-tool-.../ | "Mass Email Verify tool: Clean Your Email Directory List" | — | non | |
| 68 | /blog/number-1-email-verify-tool/ | "Number 1 Email verify tool - UseINBOX" | — | non | |
| 69 | /blog/security-email-verify-who-to-trust-your-data/ | "Security & Email Verify: Who to Trust About Your Data" | — | non | |
| 70 | /blog/easiest-and-cheapest-email-verify-solution-inboxverify/ | "The Easiest and Cheapest 'Email Verify' Solution: INBOXVerify" | — | non | |

---

## Anomalies techniques identifiees

### A1 – Title tag corrompu : /transactional-email
- **Fait** : Le title tag contient le texte "Meta Description - Create email marketing your subscribers will admire INBOX | Email", ce qui indique que le contenu de la balise meta description a ete insere dans le title, probablement par erreur de template.
- **Impact** : Ce title est non pertinent pour Google et degrade le CTR sur cette page qui est supposee etre un guide pilier sur les emails transactionnels.
- **Action requise** : Correction technique du title tag — priorite haute.

### A2 – Title tag identique a la homepage : /notify/features/email-api
- **Fait** : Le title de cette page est "Create email marketing your subscribers will admire INBOX | Email", identique a celui de la homepage.
- **Impact** : Google ne peut pas distinguer les deux pages par leur title. La page features/email-api ne sera jamais correctement positionee sur ses mots-cles propres.
- **Action requise** : Rediger un title specifique a cette page — priorite haute.

### A3 – Pattern doublon blog/standalone (6 cas confirmes)
- **Fait** : Six URLs sont accessibles a la fois depuis /blog/[slug]/ et depuis /[slug]/ ou /email-verify/[slug]/ avec un contenu identique ou quasi-identique.
- **Liste des doublons confirms** :
  - /affiliate-marketing-what-is-it-faq/ = /blog/affiliate-marketing-what-is-it-faq/
  - /how-to-use-affiliate-marketing-via-mail-marketing/ = /blog/how-to-use-affiliate-marketing-via-mail-marketing/
  - /best-workflows-to-automate-your-email-campaigns/ = /blog/best-workflows-to-automate-your-email-campaigns/
  - /email-verify/number-1-email-verify-tool/ = /blog/number-1-email-verify-tool/
  - /email-verify/security-email-verify-who-to-trust-your-data-to/ = /blog/security-email-verify-who-to-trust-your-data/
  - www.useinbox.com/mass-email-verify-tool-.../ = /blog/mass-email-verify-tool-.../
- **Impact** : Dilution du PageRank, signal contradictoire pour Google sur quelle URL est canonique, risque de penalite contenu duplique.
- **Action requise** : Implementer des canonicals ou des redirections 301 — priorite critique.

### A4 – Sous-domaine www. indexe separement
- **Fait** : www.useinbox.com/mass-email-verify-tool-.../ est indexe comme URL distincte de useinbox.com.
- **Hypothese** : Il est probable que d'autres pages du sous-domaine www. soient egalement indexees separement, mais non couvertes par ce crawl.
- **Impact** : Duplication de contenu inter-domaine, fragmentation de l'autorite de lien.
- **Action requise** : Verifier la configuration canonique et les redirections entre www. et non-www. — priorite critique.

### A5 – Double section knowledgebase
- **Fait** : Deux sections coexistent avec des URLs distinctes pour le meme contenu :
  - /knowledgebase/canadas-anti-spam-legislation-casl
  - /knowledge-base/general/canadas-anti-spam-legislation-casl/
- **Impact** : Contenu duplique, signaux de lien fragmentes entre deux sections structurellement differentes.
- **Action requise** : Consolider en une section unique avec redirections 301 — priorite haute.

### A6 – Double section automation
- **Fait** : Deux sections coexistent avec des contenus similaires :
  - /automation/ (ex : /automation/lead-generation-email)
  - /automation-3/ (ex : /automation-3/lead-generation-example/)
- **Hypothese** : /automation-3/ semble etre une version renommee ou reorganisee de /automation/, mais les deux restent accessibles et indexees.
- **Impact** : Cannibalisation structurelle entre les pages d'automation.
- **Action requise** : Identifier la version canonique et rediriger l'ancienne — priorite haute.

---

## Groupes suspects de cannibalisation

---

### Groupe G1 – "Email marketing : definition et guide"
**Niveau de confiance : Eleve**

**Pages impliquees** :

| Page | Title | H1 | Notes |
|------|-------|----|-------|
| /email-marketing/ | "Email Marketing: What It Is & How to Master It with INBOX" | Identique au title | Page pilier — meta description presente |
| /mailing | "Mailing: What It Is & How It Works \| 2025 Guide \| INBOX" | "Mailing: What It Is & How It Works" | Meta description presentant le guide 2025 |
| /tutorials/ | "INBOX Tutorials: The Ultimate Guide to Email Marketing" | Identique au title | Positionnee sur "email marketing guide" |
| /blog/10-basic-email-marketing-tips-to-improve-your-performance/ | "10 Basic Email Marketing Tips to Improve Your Performance" | — | Ciblage des conseils generaux email marketing |
| /blog/6-parameters-to-follow-for-a-successful-email-marketing/ | "6 Parameters to Follow For A Successful Email Marketing" | — | Meme intention que ci-dessus |

**Signaux detectes** :
- **Fait** : Les trois pages principales (/email-marketing/, /mailing, /tutorials/) partagent toutes "email marketing" et "guide" ou "ultimate guide" dans leur title ou H1.
- **Fait** : /mailing et /email-marketing/ ont toutes deux une meta description positionnant la page comme un guide complet sur l'email marketing / le mailing.
- **Fait** : /tutorials/ se presente explicitement comme "The Ultimate Guide to Email Marketing" — titre identique en intention a /email-marketing/.
- **Fait** : Les deux articles de blog ciblent des conseils pratiques sur l'email marketing, ce qui chevauche le contenu attendu d'un guide pilier.
- **Hypothese** : "Mailing" et "Email Marketing" peuvent en theorie cibler des intentions legerement differentes (mailing = envoi en masse, email marketing = strategie globale), mais leur meta description respective ne marque pas cette distinction clairement.
- **Hypothese** : Sans acces aux H2 reels, il est impossible de confirmer si ces pages se differentient par leur structure de contenu.
- **Limite** : Aucune donnee de positionnement reel ne permet de confirmer qu'elles se concurrencent sur les memes requetes dans les SERPs.

**Page principale recommandee** : /email-marketing/
Justification : title et H1 les plus pertinents pour l'intention "email marketing definition/guide", meta description presente, structure URL claire.

**Action recommandee** :
- /email-marketing/ : Conserver et renforcer comme page pilier
- /mailing : Reecrire pour cibler distinctement l'intention "mailing transactionnel / envoi en masse" si cette distinction existe dans la strategie produit — sinon fusionner dans /email-marketing/
- /tutorials/ : Repositionner comme hub de tutoriels pratiques (how-to), pas comme guide definitoire — differencier l'intention
- /blog/10-basic-email-marketing-tips-... et /blog/6-parameters-... : Conserver comme articles complementaires si leur contenu est suffisamment specifique, ou fusionner en un seul article "conseils email marketing" et pointer en maillage interne vers /email-marketing/

**Risque SEO si inaction** : Moyen — fragmentation de l'autorite sur une intention centrale pour le site.

---

### Groupe G2 – "Email transactionnel : guide et service"
**Niveau de confiance : Eleve**

**Pages impliquees** :

| Page | Title | H1 | Notes |
|------|-------|----|-------|
| /transactional-email | "The Ultimate Guide to Transactional Emails..." (title corrompu) | "The Ultimate Guide to Transactional Emails" | ANOMALIE title — page pilier presumee |
| /transactional-emails-service/what-is-transactional-email | "Transactional Email Service for OTP, Password Reset & Order Emails" | Identique au title | Page produit/service |
| /notify/features/ | "Features - Transactional Emails, Notification Emails" | "Features" | Hub features du produit Notify |
| /blog/transactional-email-guide-best-practices-setup/ | "TRANSACTIONAL EMAIL GUIDE: BEST PRACTICES & SETUP" | — | Article blog guide |

**Signaux detectes** :
- **Fait** : /transactional-email et /blog/transactional-email-guide-best-practices-setup/ partagent l'intention "guide complet sur les emails transactionnels".
- **Fait** : /transactional-emails-service/what-is-transactional-email contient "what is" dans l'URL, ciblage definitoire partage avec /transactional-email.
- **Fait** : /notify/features/ est positionne sur "transactional emails" dans son title tag.
- **Fait** : Le title tag de /transactional-email est corrompu (voir A1).
- **Hypothese** : /transactional-emails-service/what-is-transactional-email est probablement une page produit avec intention commerciale — peut coexister si differenciee.
- **Limite** : Sans acces aux contenus reels, impossible de confirmer la concurrence effective.

**Page principale recommandee** : /transactional-email (apres correction du title tag)

**Action recommandee** :
- /transactional-email : Corriger le title tag en urgence (T01) — conserver comme pilier informatif
- /transactional-emails-service/what-is-transactional-email : Repositionner clairement en page produit/service
- /notify/features/ : Supprimer "transactional emails" du title si hors-sujet
- /blog/transactional-email-guide-best-practices-setup/ : Evaluer fusion dans /transactional-email

**Risque SEO si inaction** : Moyen a eleve.

---

### Groupe G3 – "Affiliate marketing : definition, guide, FAQ"
**Niveau de confiance : Critique (le plus eleve)**

**Pages impliquees** :

| Page | Title | Type | Notes |
|------|-------|------|-------|
| /blog/affiliate-marketing-what-is-it/ | "Affiliate Marketing: What is it? - UseINBOX" | Article blog | |
| /blog/affiliate-marketing-a-beginners-guide/ | "Affiliate Marketing: A Beginner's Guide" | Article blog | |
| /blog/affiliate-marketing-what-is-it-faq/ | "Affiliate Marketing: What is it? & FAQ - UseINBOX" | Article blog | DOUBLON exact de #7 |
| /blog/affiliate-marketing-what-is-it-and-how-to-use-it/ | "Affiliate Marketing: What is it and how to use it?" | Article blog | |
| /blog/the-ultimate-guide-to-saas-affiliate-marketing-in-2026-.../ | "The Ultimate Guide to SaaS Affiliate Marketing in 2026" | Article blog | |
| /blog/how-to-use-affiliate-marketing-via-mail-marketing/ | "How to Use Affiliate Marketing Via Mail Marketing - UseINBOX" | Article blog | DOUBLON exact de #8 |
| /affiliate-marketing-what-is-it-faq/ | "Affiliate Marketing: What is it? & FAQ - INBOX" | Page standalone | DOUBLON de /blog/affiliate-marketing-what-is-it-faq/ |
| /guide-for-affiliate-marketing/ | "Guide for Affiliate Marketing" | Page standalone | |
| /how-to-use-affiliate-marketing-via-mail-marketing/ | "How to Use Affiliate Marketing Via Mail Marketing" | Page standalone | DOUBLON de /blog/how-to-use-.../ |

**Signaux detectes** :
- **Fait** : Cinq des neuf pages contiennent "Affiliate Marketing: What is it" ou variante dans leur title — chevauchement >70%.
- **Fait** : Deux doublons exacts confirmes.
- **Fait** : Trois articles blog ciblent la meme requete "affiliate marketing qu'est-ce que c'est".
- **Hypothese** : /blog/the-ultimate-guide-to-saas-affiliate-marketing-in-2026-.../ peut cibler une sous-niche (SaaS + 2026) distincte — a verifier.

**Page principale recommandee** : A creer ou consolider — aucune page existante n'est clairement dominante.

**Action recommandee** :
- Identifier ou creer une page pilier unique "affiliate marketing"
- Rediriger 301 les deux standalone vers /blog/ ou page pilier (T03, T04)
- Fusionner /blog/affiliate-marketing-what-is-it/, /blog/affiliate-marketing-a-beginners-guide/, /blog/affiliate-marketing-what-is-it-and-how-to-use-it/
- /guide-for-affiliate-marketing/ : fusionner dans la page pilier
- /blog/the-ultimate-guide-to-saas-affiliate-marketing-in-2026-.../ : conserver si reellement specifique SaaS

**Risque SEO si inaction** : Critique.

---

### Groupe G4 – "Newsletter design / conseils / exemples"
**Niveau de confiance : Eleve**

**Pages impliquees** :

| Page | Title |
|------|-------|
| /blog/8-best-email-newsletter-examples-how-to-design/ | "8 Best Email Newsletter Examples, How to Design" |
| /blog/innovative-email-newsletter/ | "Innovative Email Newsletter - UseInbox" |
| /blog/19-hints-for-incredible-email-newsletter-design-outline/ | "19 Hints For Incredible Email Newsletter Design Outline" |
| /blog/newsletter-design-ideas-for-inspiration/ | "Newsletter Design Ideas for Inspiration" |
| /blog/email-newsletter-best-practices/ | "Email Newsletter Best Practices" |
| /blog/10-tips-to-make-your-newsletter-visually-appealing/ | "10 Tips to Make Your Newsletter Visually Appealing" |
| /blog/main-tips-for-beautiful-newsletter-designs/ | "Main Tips For Beautiful Newsletter Designs" |
| /blog/12-best-design-tips-for-newsletter-to-guarantee-email-marketing-success/ | "12 Best Design Tips for Newsletter" |
| /blog/best-email-designs/ | "Best Email Designs - UseINBOX" |
| /blog/best-practices-for-newsletter-signup-designs/ | "The Best Practices for Newsletter Signup Designs" |
| /blog/5-most-essential-tips-for-creating-responsive-newsletters/ | "5 Expert Tips for Designing Responsive Newsletters that Convert" |

**Signaux detectes** :
- **Fait** : 9 des 11 articles contiennent "newsletter" et soit "design", "tips", "best practices" ou "examples" dans leur title.
- **Fait** : Les intentions se recoupent directement : newsletter design tips, exemples, best practices, responsive.

**Page principale recommandee** : /blog/email-newsletter-best-practices/ (a confirmer)

**Action recommandee** :
- Auditer le contenu de chaque article
- Conserver 2-3 articles avec angles distincts
- Fusionner les redondants (notamment articles design tips)
- Rediriger les versions fusionnees

**Risque SEO si inaction** : Eleve.

---

### Groupe G5 – "Email verify : outil et guide"
**Niveau de confiance : Eleve (doublons exacts confirmes)**

**Pages impliquees** :

| Page | Title | Notes |
|------|-------|-------|
| /blog/number-1-email-verify-tool/ | "Number 1 Email verify tool - UseINBOX" | |
| /email-verify/number-1-email-verify-tool/ | "Number 1 Email verify tool" | DOUBLON exact |
| /blog/mass-email-verify-tool-.../ | "Mass Email Verify tool: Clean Your Email Directory List" | |
| www.useinbox.com/mass-email-verify-tool-.../ | "Mass Email Verify tool: Clean Your Email Directory List For Best Email Marketing ROI" | Sous-domaine — DOUBLON |
| /blog/security-email-verify-who-to-trust-your-data/ | "Security & Email Verify: Who to Trust About Your Data" | |
| /email-verify/security-email-verify-who-to-trust-your-data-to/ | "Security & Email Verify: Who to Trust Your Data to - INBOXVerify" | DOUBLON |
| /blog/easiest-and-cheapest-email-verify-solution-inboxverify/ | "The Easiest and Cheapest 'Email Verify' Solution: INBOXVerify" | |

**Signaux detectes** :
- **Fait** : Trois doublons exacts confirmes.
- **Fait** : Quatre articles ciblent "outil de verification d'email — INBOXVerify".
- **Fait** : www.useinbox.com/ indexe comme domaine separe.

**Page principale recommandee** : Version /blog/ dans chaque cas.

**Action recommandee** :
- Redirections 301 des URLs standalone vers /blog/
- Canonical www. -> non-www.
- Evaluer consolidation /blog/number-1-.../ et /blog/easiest-and-cheapest-.../

**Risque SEO si inaction** : Eleve.

---

### Groupe G6 – "Automation email : workflows et exemples"
**Niveau de confiance : Moyen**

**Pages impliquees** :

| Page | Title | Notes |
|------|-------|-------|
| /automation/lead-generation-email | "Lead Generation Email Automation Workflow Example - INBOX" | Section /automation/ |
| /automation-3/lead-generation-example/ | "Lead Generation Automation Workflow Example- Create More Leads" | Section /automation-3/ — DOUBLON |
| /best-workflows-to-automate-your-email-campaigns/ | "Best Workflows to Automate Your Email Campaigns - INBOX" | Standalone — DOUBLON |
| /blog/best-workflows-to-automate-your-email-campaigns/ | "Best Workflows to Automate Your Email Campaigns" | Blog |

**Action recommandee** :
- Clarifier quelle section (/automation/ ou /automation-3/) est active
- Rediriger 301 la section obsolete
- Rediriger /best-workflows-.../ standalone vers /blog/

**Risque SEO si inaction** : Moyen.

---

### Groupe G7 – "CASL conformite email Canada"
**Niveau de confiance : Eleve (triplons confirmes)**

**Pages impliquees** :

| Page | Title | H1 |
|------|-------|----||
| /casl | "CASL Compliance 2025: Simple Guide to Smarter Email Marketing \| INBOX" | "CASL Compliance 2025: Simple Guide to Smarter Email Marketing" |
| /knowledgebase/canadas-anti-spam-legislation-casl | "Canada's Anti-Spam Legislation (CASL) - INBOX" | "Canada's Anti-Spam Legislation (CASL)" |
| /knowledge-base/general/canadas-anti-spam-legislation-casl/ | "Canada's Anti-Spam Legislation (CASL) \| INBOX" | "Canada's Anti-Spam Legislation (CASL)" |

**Signaux detectes** :
- **Fait** : /knowledgebase/ et /knowledge-base/general/ ont des titles et H1 quasi-identiques.
- **Fait** : /casl chevauche directement l'intention des deux pages knowledge base.
- **Hypothese** : /casl est une page pilier SEO recente, les pages /knowledge-base/ sont du support plus ancien — coexistence possible si intentions differenciees.

**Page principale recommandee** : /casl

**Action recommandee** :
- Ajouter canonical /knowledgebase/ et /knowledge-base/general/ -> /casl
- Resoudre la double section /knowledgebase/ vs /knowledge-base/

**Risque SEO si inaction** : Eleve.

---

## Recapitulatif des recommandations

| # | Page(s) concernee(s) | Probleme | Action | Priorite | Risque SEO | Valide ? |
|---|---------------------|----------|--------|----------|------------|----------|
| R01 | /transactional-email | Title tag corrompu (A1) | Corriger le title tag | Critique | Eleve | En attente |
| R02 | /notify/features/email-api | Title = homepage (A2) | Rediger un title specifique | Haute | Moyen | En attente |
| R03 | /affiliate-marketing-what-is-it-faq/ (standalone) | Doublon exact de /blog/ | Redirection 301 vers /blog/ ou page pilier | Critique | Eleve | En attente |
| R04 | /how-to-use-affiliate-marketing-via-mail-marketing/ (standalone) | Doublon exact de /blog/ | Redirection 301 vers /blog/ ou page pilier | Critique | Eleve | En attente |
| R05 | www.useinbox.com/mass-email-verify-tool-.../ | Doublon sous-domaine + canonical manquant | Redirection 301 + configuration canonical www->non-www | Critique | Eleve | En attente |
| R06 | /email-verify/number-1-email-verify-tool/ | Doublon exact de /blog/number-1-email-verify-tool/ | Redirection 301 vers /blog/ | Haute | Moyen | En attente |
| R07 | /email-verify/security-email-verify-who-to-trust-your-data-to/ | Doublon de /blog/ | Redirection 301 vers /blog/ | Haute | Moyen | En attente |
| R08 | /knowledgebase/canadas-anti-spam-legislation-casl | Doublon de /knowledge-base/general/... | Redirection 301 vers /casl ou ajout canonical | Haute | Eleve | En attente |
| R09 | /knowledge-base/general/canadas-anti-spam-legislation-casl/ | Doublon de /knowledgebase/... | Redirection 301 vers /casl ou ajout canonical | Haute | Eleve | En attente |
| R10 | /best-workflows-to-automate-your-email-campaigns/ | Doublon de /blog/ | Redirection 301 vers /blog/ | Haute | Moyen | En attente |
| R11 | /automation/lead-generation-email | Doublon de /automation-3/ | Redirection 301 vers /automation-3/ (ou inverse) | Haute | Moyen | En attente |
| R12 | Groupe G3 – affiliate marketing (9 pages) | Cannibalisation critique | Consolider en 1 page pilier + redirections | Critique | Critique | En attente |
| R13 | Groupe G4 – newsletter design (11 articles) | 11 articles sur la meme intention | Auditer + fusionner les redondants | Haute | Eleve | En attente |
| R14 | /tutorials/ | Overlap avec /email-marketing/ | Repositionner en hub de tutoriels pratiques | Moyenne | Moyen | En attente |
| R15 | /mailing | Overlap partiel avec /email-marketing/ | Reecrire ou fusionner | Moyenne | Moyen | En attente |
| R16 | /transactional-email (apres R01) | Overlap avec autres pages transactional | Conserver comme pilier informatif + differencier | Moyenne | Moyen | En attente |
| R17 | /blog/transactional-email-guide-best-practices-setup/ | Overlap avec /transactional-email | Evaluer fusion ou conserver si angle distinct | Moyenne | Faible | En attente |
| R18 | /guide-for-affiliate-marketing/ | Overlap avec groupe G3 | Fusionner dans la page pilier affiliate marketing | Haute | Eleve | En attente |
| R19 | /automation/ et /automation-3/ (toutes pages) | Double section active | Identifier section canonique, rediriger l'autre | Haute | Moyen | En attente |

---

## Decisions requises par l'utilisateur

Avant toute modification, confirmez chaque action ci-dessous.

**Actions critiques (a traiter en priorite) :**

1. Corriger le title tag de /transactional-email — Valide ? [oui/non]
2. Rediriger 301 /affiliate-marketing-what-is-it-faq/ (standalone) vers /blog/ — Valide ? [oui/non]
3. Rediriger 301 /how-to-use-affiliate-marketing-via-mail-marketing/ (standalone) vers /blog/ — Valide ? [oui/non]
4. Configurer redirection + canonical www.useinbox.com -> useinbox.com — Valide ? [oui/non]
5. Audit de contenu groupe G3 (affiliate marketing, 9 pages) — Valide ? [oui/non]

**Actions hautes priorites :**

6. Title specifique pour /notify/features/email-api — Valide ? [oui/non]
7. Rediriger 301 /email-verify/number-1-email-verify-tool/ vers /blog/ — Valide ? [oui/non]
8. Rediriger 301 /email-verify/security-email-verify-who-to-trust-your-data-to/ vers /blog/ — Valide ? [oui/non]
9. Rediriger 301 /best-workflows-to-automate-your-email-campaigns/ standalone vers /blog/ — Valide ? [oui/non]
10. Canonical /knowledgebase/casl et /knowledge-base/general/casl -> /casl — Valide ? [oui/non]
11. Identifier section automation canonique + redirections — Valide ? [oui/non]
12. Audit contenu groupe G4 (newsletter design, 11 articles) — Valide ? [oui/non]

**Actions moyennes priorites :**

13. Repositionner /tutorials/ comme hub how-to — Valide ? [oui/non]
14. Reecrire /mailing pour "mailing transactionnel" ou fusionner — Valide ? [oui/non]
15. Evaluer fusion /blog/transactional-email-guide-.../ dans /transactional-email — Valide ? [oui/non]
