# SGH Cat POC

This is a minimal proof-of-concept showing that a static GitHub Pages frontend can connect to Supabase as a backend database.

## What this POC demonstrates

- Static HTML hosted on GitHub Pages
- Simple frontend form
- Browser JavaScript connection to Supabase
- Insert-only database write into `cat_messages`
- No backend server
- No Docker
- No Streamlit
- No Flask
- No patient data

## Data Safety Notice

This POC is for demo purposes only.

Do not enter:

- patient data
- confidential SGH information
- internal system details
- passwords
- real sensitive information

Only fake/demo data should be submitted.

## Architecture

User browser  
→ GitHub Pages static HTML  
→ Supabase JavaScript client  
→ Supabase Postgres table
