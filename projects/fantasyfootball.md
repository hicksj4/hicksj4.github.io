---
layout: project
type: project
image: img/sports-data.jpg
title: "Fantasy Football Sentiment Terminal"
date: 2026
published: true
labels:
  - C#
  - ASP.NET Core
  - PostgreSQL
summary: "Built a full-stack fantasy football analytics platform that batch processes weekly Reddit discussion snapshots into player-level sentiment, fantasy intent, discussion share, and team analytics."
---

<hr>

<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="text-align: center; margin-right: 10px;">
    <img class="img-fluid" src="../img/Screenshot 2026-09-24 181348.png" alt="Landing Page" style="max-width: 100%; height: auto;">
    <p><em>Front page dashboard.</em></p>
  </div>
</div>

## Overview

<hr>

A local MVP web app for analyzing fantasy-football Reddit discussion as a completed weekly snapshot.

This branch intentionally runs from deterministic, editable JSON fixture data instead of live Reddit polling. That keeps the product focused on one clear workflow:

    Load a game-week discussion fixture.
    Batch-analyze player mentions, sentiment, intent, and vote-weighted impact.
    Serve snapshot-level dashboard APIs to the Next.js frontend.

<hr>

