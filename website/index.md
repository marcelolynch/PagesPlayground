---
layout: default
title: Dashboard
---

# Upstreaming dashboard

## Files ready to upstream

The following files are `sorry`-free and do not depend on any other file, meaning they can be readily PRed to Mathlib.

{% include_relative ready_to_upstream.md %}

## Files easy to unlock

The following files do not depend on any other file but still contain `sorry`, usually indicating that working on eliminating those sorries might unblock some part of the project.

{% include_relative easy_to_unlock.md %}
