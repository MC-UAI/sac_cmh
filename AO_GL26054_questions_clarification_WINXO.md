**De :** Mohamed CHAGRAOUI <m.chagraoui@proorgaconsulting.com>
**À :** Ghita Labtarni <glabtarni@winxo.com>
**Cc :** Mohammed Youssef Matmata <mmatmata@winxo.com> ; abentoumia@winxo.com ; Mustapha Amane <amane@winxo.com>
**Objet :** RE: Appel d'offre N° GL26054 relatif à la mise en place des tableaux de bord SAP Analytics Cloud (SAC) – Demande de clarifications

---

Bonjour Madame Labtarni,

Nous vous remercions pour l'envoi du dossier de l'appel d'offres N° GL26054 relatif à la mise en place des tableaux de bord SAP Analytics Cloud (SAC). Vous trouverez ci-joint l'accusé de réception, dûment signé et cacheté.

Dans le cadre de la préparation de notre offre, nous avons analysé avec attention le cahier des charges (document GL26054-01) et les deux maquettes Excel en annexe. Afin de vous remettre, dans le délai fixé au lundi 12/10/2026, une offre forfaitaire, ferme et non révisable qui soit précise et engageante, nous vous serions reconnaissants de bien vouloir nous apporter des précisions sur les points ci-dessous.

Compte tenu de ce délai, une réponse d'ici le vendredi 09/10/2026, même partielle, nous serait très utile. Les points prioritaires sont signalés par la mention **(prioritaire)**. Les autres pourront, si vous le préférez, être traités lors de la phase de cadrage.

### 1. Architecture et environnement technique

1. **Base de données de S/4HANA (prioritaire) :** le schéma d'architecture (§2.2) mentionne une base Oracle 18 sur AIX, alors que S/4HANA 2023 fonctionne uniquement sur SAP HANA. Pouvez-vous nous confirmer la version et la base de données réelles de l'environnement de production PR1 ?
2. **Fréquence de rafraîchissement :** le §1.1 évoque une « analyse en temps réel », tandis que les §5 et §6 demandent une actualisation quotidienne le soir. Pouvez-vous confirmer qu'une actualisation nocturne (données à J-1) répond à votre besoin ?
3. **Connectivité :** WINXO dispose-t-elle déjà de SAP Cloud Connector, ou peut-elle mettre à disposition un serveur pour son installation et celle de l'agent SAC ?
4. **Authentification :** une authentification unique (SSO) via votre annuaire d'entreprise (Azure AD, ADFS…) est-elle souhaitée pour l'accès à SAC ?
5. **Convention de nommage :** pouvez-vous nous communiquer la convention de nommage des objets en vigueur chez WINXO ?

### 2. Données et règles de gestion

6. **Potentiel client et objectifs (prioritaire) :** ces données n'existent pas aujourd'hui dans SAP. Qui les tient à jour, où sont-elles conservées actuellement (fichier Excel, autre outil) et à quelle fréquence sont-elles révisées ? Avez-vous une préférence pour leur saisie : directement dans SAC (ce qui nécessite des licences SAC Planning pour les personnes qui saisissent) ou dans une table de S/4HANA ?
7. **Classement par canal :** sur quel critère SAP repose aujourd'hui le classement des clients en Industrie, Confrères et Revendeurs (canal de distribution, groupe client, autre attribut) ? Ce classement est-il identique pour le Fuel 02 et les Lubrifiants (la maquette Lubrifiants mentionne « Canal 1, Canal 2… ») ?
8. **Volumes :** les volumes doivent-ils être fondés sur les livraisons ou sur les factures ? L'unité de référence est-elle la tonne métrique pour les deux familles de produits, et la conversion est-elle assurée par IS-Oil ?
9. **Marge et coût de revient :** quels composants entrent dans le CA net et dans la marge brute (remises, frais de transport, taxes, éléments de coût) ? La marge est-elle aujourd'hui calculée à partir de l'analyse de la rentabilité (CO-PA / analyse des marges) ou des conditions de prix de la facture ? Un interlocuteur du contrôle de gestion pourra-t-il valider ces règles pendant la phase de conception ?
10. **PMP :** quel centre ou quel niveau de valorisation doit être retenu pour le PMP article ? Le Material Ledger est-il activé ?
11. **Date de recrutement du client :** doit-on utiliser la date de création du client dans SAP ou une autre source ?
12. **Exclusion des produits connexes (AdBlue, antigel, graisse) :** ces articles sont-ils identifiables par un groupe de marchandises, une hiérarchie produit ou une autre classification de SAP ?
13. **Historique :** combien d'exercices d'historique faut-il charger (N-1, N-2 ou davantage) ? Ces données sont-elles toutes présentes dans S/4HANA, ou une partie provient-elle d'un système antérieur ?
14. **Écarts relevés dans les maquettes :** nous avons relevé quelques incohérences dans les fichiers d'exemple (par exemple, des colonnes de marge unitaire et de marge totale inversées dans la vue Fuel Industrie). Pouvez-vous nous confirmer qu'il s'agit de données fictives et que les règles de calcul seront validées lors de la conception ?

### 3. Utilisateurs, sécurité et diffusion

15. **Population cible (prioritaire) :** combien d'utilisateurs sont prévus, par profil (direction générale, responsables commerciaux, contrôle de gestion, administrateurs) ?
16. **Restrictions d'accès :** des restrictions de données par canal, par commercial ou par entité sont-elles attendues dès le démarrage ?
17. **Diffusion par WhatsApp :** SAC ne permet pas d'envoyer nativement des contenus vers WhatsApp. Une diffusion par mail planifiée (PDF ou PowerPoint) et l'application mobile SAC répondent-elles à votre besoin ?

### 4. Organisation du projet

18. **Démarrage :** quelle est la date de démarrage envisagée, et existe-t-il une échéance métier à respecter (clôture, comité de direction…) ?
19. **Équipe WINXO :** quelle équipe interne sera mobilisée (référents métier, DSI, contrôle de gestion), et avec quelle disponibilité pour les ateliers et la recette ?
20. **Présence sur site :** une présence à temps plein sur site est-elle exigée, ou une organisation mixte sur site / à distance est-elle envisageable pour certaines activités (développements techniques) ?

### 5. Points administratifs et contractuels

21. **Durée de garantie :** le cahier des charges mentionne « six (03) mois » (§7.3 et §7.12) et « trois (3) mois minimum » (§7.11). Pouvez-vous confirmer la durée de garantie attendue ?
22. **Bordereau de prix (prioritaire) :** le §7.5 fait référence au document n° YM26054-03. S'agit-il bien du bordereau de l'AO GL26054 ? Pouvez-vous nous le transmettre s'il ne figure pas dans le dossier ?
23. **Modalités de dépôt (prioritaire) :** l'offre doit être remise sous pli fermé au plus tard le lundi 12/10/2026. Pouvez-vous nous préciser l'heure limite et le lieu de dépôt (Département Achats & Marchés, siège de Casablanca ?), le nombre d'exemplaires attendus, ainsi que la nécessité de présenter l'offre technique et l'offre financière sous des plis séparés ?

Nous restons à votre disposition pour échanger sur ces points lors d'un appel, à votre convenance, si cela peut faciliter votre retour.

Nous vous remercions par avance de votre retour et vous prions d'agréer, Madame, l'expression de nos salutations distinguées.

Mohamed CHAGRAOUI
[Fonction]
Proorga Consulting
[Téléphone] – m.chagraoui@proorgaconsulting.com

*Pièce jointe : accusé de réception de l'appel d'offres N° GL26054, signé et cacheté.*
