# Exemple d'exécution – Gabi SEO Cannibalisation

Cet exemple illustre une session complète avec un site fictif `exemple-agence-seo.fr`.

---

## Étape 1 – Démarrage

**Utilisateur** : Lance l'agent Gabi SEO

**Gabi** :
> Tu as quoi pour que je travaille : un repo GitHub, un site web, ou les deux ?
> Envoie-moi le lien du site, le lien du repo, ou les deux.

---

## Étape 2 – Saisie des sources

**Utilisateur** :
> Site : https://exemple-agence-seo.fr
> Repo : https://github.com/agence/site-seo

**Gabi** :
> Parfait, j'ai les deux. Je lance l'analyse en parallèle :
> - **seo-site-crawler** → crawl du site public
> - **seo-repo-analyzer** → analyse du repo GitHub
>
> Je reviens avec un rapport combiné. Aucune modification ne sera effectuée.

---

## Étape 3 – Résultats du crawl (seo-site-crawler)

```
Pages crawlées : 24
Pages inaccessibles : 2 (auth requise)
Sitemap trouvé : oui (/sitemap.xml)

Groupes suspects détectés :
- Groupe A : /seo, /referencement-naturel, /blog/guide-seo → intention "apprendre le SEO"
- Groupe B : /audit-seo, /audit-technique, /bilan-seo → intention "audit de site"
```

---

## Étape 4 – Résultats du repo (seo-repo-analyzer)

```
Framework : Next.js 14 (App Router)
Pages statiques : 18
Templates dynamiques : /blog/[slug], /service/[service]
Limites : les articles de blog ont des titres dynamiques depuis Contentful

Groupes suspects détectés :
- src/pages/seo.tsx → route /seo (title statique : "Agence SEO – Référencement naturel")
- src/pages/referencement.tsx → route /referencement (title : "Référencement naturel – Agence")
- src/content/blog/guide-seo.mdx → route /blog/guide-seo (H1 : "Guide complet du SEO")
```

---

## Étape 5 – Rapport de cannibalisation (seo-cannibalization-reporter)

**Gabi** présente le rapport :

```
=== RAPPORT SEO – CANNIBALISATION ===

Résumé exécutif :
- 24 pages analysées
- 3 groupes suspects détectés
- 1 risque élevé, 2 risques moyens

GROUPE 1 – Intention "référencement naturel/SEO" [CONFIANCE : ÉLEVÉE 🔴]
Pages : /seo, /referencement-naturel, /blog/guide-seo

Faits observés :
- /seo → Title "Agence SEO – Référencement naturel" | H1 "Expert SEO"
- /referencement-naturel → Title "Référencement naturel" | H1 "Le référencement naturel"
- /blog/guide-seo → Title "Guide SEO complet 2024" | H1 "Guide du SEO"
- Les 3 pages ont des H2 similaires : "Qu'est-ce que le SEO ?", "Pourquoi le SEO ?"
- /seo reçoit 12 liens internes, /referencement-naturel 3, /blog/guide-seo 5

Hypothèse : Ces 3 pages ciblent probablement l'intention "comprendre/faire du SEO"

Page principale recommandée : /seo (la plus liée, la plus complète)

Action recommandée :
- Fusionner /referencement-naturel dans /seo + 301 permanent
- Différencier /blog/guide-seo → repositionner sur "tutoriel pratique SEO pas à pas"

Risque SEO si inaction : Élevé (dilution d'autorité sur 3 pages au lieu d'une)
```

---

## Étape 6 – Demande de validation

**Gabi** :
> Voici le plan d'action. Avant tout, confirmez chaque action :
>
> **T01** : Fusionner `/referencement-naturel` dans `/seo` + redirection 301 → Valide ? (oui/non)
> **T02** : Repositionner `/blog/guide-seo` sur intention "tutoriel pratique" → Valide ? (oui/non)
> **T03** : Renforcer maillage interne vers `/seo` depuis 8 articles de blog → Valide ? (oui/non)
>
> ⚠️ Rien ne sera modifié tant que vous n'avez pas répondu.

---

## Étape 7 – Réponse de l'utilisateur

**Utilisateur** :
> T01 valide, T02 valide, T03 refuse

**Gabi** :
> Reçu. Je mets à jour `agent_todo.md` :
> - T01 → ✅ Validée
> - T02 → ✅ Validée
> - T03 → ❌ Refusée
>
> Souhaitez-vous que j'exécute T01 et T02 maintenant, ou préparer d'abord
> un récapitulatif des modifications à effectuer ?

---

## Fichier agent_todo.md généré

```markdown
| ID  | Page                    | Problème                        | Action              | Priorité | Risque | Confiance | État      |
|-----|-------------------------|---------------------------------|---------------------|----------|--------|-----------|-----------|
| T01 | /referencement-naturel  | Cannibalise /seo                | Fusionner + 301     | 🔴 Haute | Élevé  | Élevée    | ✅ Validée |
| T02 | /blog/guide-seo         | Overlap intention avec /seo     | Différencier        | 🟡 Moy.  | Moyen  | Élevée    | ✅ Validée |
| T03 | /seo                    | Maillage interne faible         | Renforcer maillage  | 🟡 Moy.  | Faible | Moyenne   | ❌ Refusée |
```

---

## Notes importantes sur cet exemple
1. Les URLs, contenus et données sont **entièrement fictifs** – illustratifs uniquement.
2. Dans une vraie session, Gabi ne fournit que des données réellement crawlées/analysées.
3. Le niveau de détail dépend de l'accessibilité réelle du site et du repo.
