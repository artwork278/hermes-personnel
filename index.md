---
layout: default
title: Hermes Personnel
description: Outil privé et auto-hébergé pour examiner, organiser et nettoyer une messagerie Gmail.
permalink: /
page_class: home
---

<section class="hero" aria-labelledby="hero-title">
  <div class="hero__copy">
    <p class="eyebrow"><span class="status-dot" aria-hidden="true"></span> Outil privé · Auto-hébergé</p>
    <h1 id="hero-title">Votre messagerie.<br><span>Sous contrôle.</span></h1>
    <p class="hero__lead">Hermes Personnel examine, organise et nettoie une boîte Gmail selon les décisions de son propriétaire — rien de plus.</p>
    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/privacy.html' | relative_url }}">
        Politique de confidentialité
        <svg aria-hidden="true" viewBox="0 0 20 20"><path d="M4 10h12M11 5l5 5-5 5"/></svg>
      </a>
      <a class="text-link" href="#capacites">Découvrir son fonctionnement</a>
    </div>
  </div>

  <aside class="trust-panel" aria-label="Statut de l’application">
    <div class="trust-panel__topline">
      <span>État de l’accès</span>
      <span class="status-pill"><span class="status-dot" aria-hidden="true"></span> Actif sur autorisation</span>
    </div>
    <div class="trust-panel__visual" aria-hidden="true">
      <span class="orbit orbit--outer"></span>
      <span class="orbit orbit--inner"></span>
      <img src="{{ '/assets/hermes-mark.svg' | relative_url }}" alt="">
    </div>
    <dl class="trust-panel__facts">
      <div><dt>Utilisateurs</dt><dd>1 propriétaire</dd></div>
      <div><dt>Hébergement</dt><dd>Infrastructure privée</dd></div>
      <div><dt>Publicité</dt><dd>Aucune</dd></div>
    </dl>
  </aside>
</section>

<section class="capabilities" id="capacites" aria-labelledby="capabilities-title">
  <div class="section-heading">
    <p class="eyebrow">Fonctionnement</p>
    <h2 id="capabilities-title">Trois actions. Un contrôle explicite.</h2>
    <p>Chaque opération reste limitée à la messagerie autorisée et aux règles définies par son propriétaire.</p>
  </div>

  <div class="card-grid">
    <article class="capability-card">
      <span class="card-index" aria-hidden="true">01</span>
      <svg class="card-icon" aria-hidden="true" viewBox="0 0 24 24"><path d="M2 12s3.5-6 10-6 10 6 10 6-3.5 6-10 6S2 12 2 12Z"/><circle cx="12" cy="12" r="2.5"/></svg>
      <h3>Examiner</h3>
      <p>Consulter uniquement les messages et pièces jointes nécessaires à l’action demandée.</p>
    </article>

    <article class="capability-card">
      <span class="card-index" aria-hidden="true">02</span>
      <svg class="card-icon" aria-hidden="true" viewBox="0 0 24 24"><path d="M4 7h16M7 4v6M17 4v6M5 12h6v7H5zM14 12h5v3h-5zM14 18h5"/></svg>
      <h3>Organiser</h3>
      <p>Créer, appliquer ou retirer des libellés, puis archiver les éléments déjà traités.</p>
    </article>

    <article class="capability-card">
      <span class="card-index" aria-hidden="true">03</span>
      <svg class="card-icon" aria-hidden="true" viewBox="0 0 24 24"><path d="M4 7h16M9 7V4h6v3M7 7l1 13h8l1-13M10 11v5M14 11v5"/></svg>
      <h3>Nettoyer</h3>
      <p>Déplacer vers la corbeille les messages inutiles, uniquement selon les décisions du propriétaire.</p>
    </article>
  </div>
</section>

<section class="principle" aria-labelledby="principle-title">
  <div>
    <p class="eyebrow">Principe directeur</p>
    <h2 id="principle-title">Privé par destination.<br>Transparent par conception.</h2>
  </div>
  <div class="principle__copy">
    <p>Hermes Personnel n’est ni commercialisé ni proposé à d’autres utilisateurs. Son accès peut être révoqué à tout moment depuis le compte Google concerné.</p>
    <a class="text-link text-link--bright" href="{{ '/privacy.html' | relative_url }}">Lire les engagements de confidentialité</a>
  </div>
</section>
