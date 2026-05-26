# LucidGrasp Test Repo

This is a test repository for GitHub webhook auto-update feature.

## Files:
- calculator.py - Basic math operations
- greeter.js - Greeting functions
- config.json - App configuration

## Webhook Test Plan:
1. Add this file → should NOT create embeddings (.md is context only)
2. Modify calculator.py → should update embeddings
3. Delete greeter.js → should remove embeddings
