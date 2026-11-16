---
layout: page
permalink: /research/
title: Research
description: 
nav: true
nav_order: 4
---

## Working Papers

I am happy to share working papers upon request.

### State Legitimacy and Migration

I show that recent accounts of democratic legitimacy based on collective autonomy cannot explain how state coercion is compatible with the autonomy of certain kinds of dissenters. I argue that preserving autonomy requires robust exit rights and make two key theoretical contributions: first, I offer a response to the classic Humean objection, according to which exit cannot justify a right to coerce given its high cost. I show that while the objection might hold against Lockean, consent-based accounts of legitimacy, the right of exit suffices for autonomy in a Kantian-Rousseauian approach. Second, I establish that state legitimacy requires active institutional support for exit, such as emigration subsidies and participation in multilateral immigration treaties. I argue that, much like respecting the autonomy of majorities requires elections, respect for the autonomy of dissenters requires active support for exit.

### State Authority and Its Limits

I argue that state legitimacy requires polycentric models. To do this, I identify a tension in influential accounts of state legitimacy. These theories hold that democratic rule is legitimate as long as it remains within a certain boundary of “basic justice.” However, in order to establish state legitimacy in the first place, these theories rely on the indeterminacy of justice in the state of nature. I show that these two moves are in tension: the indeterminacy of “basic justice” is a problem for these accounts. I argue, then, that legitimate political order must be “polycentric:” it must accommodate radically diverse communities, including those that defy standard definitions of (basic) justice. Alongside the above paper, this establishes that individuals must have meaningful choice among diverse polities within a polycentric system in order for state coercion to be justified.

### Further work

Whereas the above papers focus on legitimacy, the remaining chapters of my dissertation explore _stability_. I am particularly interested in how minorities can have leverage to bargain with majorities for their rights. I study how a right to territorial self-government (e.g., secession) may lead to that goal. I argue that regularly scheduled referenda on territorial self-government can be a self-enforcing tool for defending minority interests.

{% if site.data.research.github_users %}

## GitHub users

<div class="research d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.research.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.research.github_users %}
{% if site.data.research.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="research d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.research.github_repos %}

## GitHub research

<div class="research d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.research.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
