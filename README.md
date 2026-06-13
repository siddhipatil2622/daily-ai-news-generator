# Daily AI News Generator

An automated AI-powered news digest built with n8n.

## Overview

This workflow automatically:

- Fetches the latest articles from TechCrunch RSS feeds
- Filters the latest news items
- Uses Cohere AI to analyze and summarize articles
- Aggregates summaries into a single digest
- Sends the digest to Gmail automatically

## Workflow

RSS Feed → Limit → AI Agent (Cohere) → Aggregate → Gmail

## Tech Stack

- n8n
- Cohere AI
- Gmail
- RSS Feed (TechCrunch)

## Features

- Automated news collection
- AI-generated summaries
- Email delivery
- No-code workflow automation

## Use Case

Receive a daily AI-generated technology news digest directly in your inbox without manually browsing multiple news websites.

## Author

Siddhi Patil
