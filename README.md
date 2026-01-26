# n8n-SEO-Agent

## 🤖 SEO Content Agent v1
🇺🇸 An advanced n8n workflow designed for automated, high-volume keyword research and SEO content generation. It identifies high-intent keywords from multiple sources (Google Autocomplete, People Also Ask, DataForSEO) and uses specialized AI Agents to research and write 4000+ word articles, saving them directly to Google Workspace. <br /><br />
**Business Case**: "I run an SEO agency and onboarding a new local service client usually takes weeks of manual labor just to map out the content strategy. I need to find what people are actually searching for, check if the competition is beatable, and write long-form content that actually provides value. I need an Agent where I can just type 'Electrician', and it automatically researches 20 trending topics, writes deep-dive 4000-word guides for each, and organizes everything in a spreadsheet for my team to review."

🇵🇱 Zaawansowany workflow n8n zaprojektowany do automatycznego, masowego badania słów kluczowych i generowania treści SEO. Identyfikuje frazy o wysokiej intencji zakupowej z wielu źródeł (Google Autocomplete, People Also Ask, DataForSEO) i wykorzystuje wyspecjalizowanych agentów AI do przeprowadzania researchu oraz pisania artykułów o długości ponad 4000 słów, zapisując je bezpośrednio w Google Workspace. <br /><br />
**Business Case**: "Prowadzę agencję SEO i wdrożenie nowego klienta usługowego zazwyczaj zajmuje tygodnie ręcznej pracy przy samym planowaniu strategii treści. Muszę znaleźć to, czego ludzie naprawdę szukają, sprawdzić, czy konkurencja jest do przeskoczenia i napisać obszerne treści, które faktycznie dają wartość. Potrzebuję Agenta, w którym po prostu wpiszę 'Elektryk', a on automatycznie wyszuka 20 trendujących tematów, napisze wyczerpujący poradnik na 4000 słów dla każdego z nich i zorganizuje wszystko w arkuszu dla mojego zespołu."

<img width="1609" height="295" alt="Zrzut ekranu 2026-01-26 o 20 35 08" src="https://github.com/user-attachments/assets/f0c507da-bcb7-4fe4-a10f-316f58b1a1ae" />

## **🇺🇸 English Version** ##
### 🌟 Overview
This workflow automates the most time-consuming part of SEO: the transition from raw keyword discovery to publication-ready long-form content. By combining real-time search data with deep AI research, it ensures that every article is backed by current facts and optimized for search intent.

### 🛠 Tech Stack <br />
Automation: n8n

AI Engine: Azure OpenAI (GPT-4o)

SEO Data: DataForSEO (Keywords for Keywords), SerpApi (Autocomplete, PAA), Tavily (Research & Extract)

Storage: Google Sheets, Google Docs

### 🚀 Key Features <br />
Multi-Source Keyword Discovery: Choose between Autocomplete expansion, semantic 'Keywords for Keywords', or 'People Also Ask' questions.

Deep Web Research: Every article is preceded by a real-time web scan via Tavily to ensure technical accuracy.

Massive Content Generation: Specifically tuned to produce long-form content (4000+ words) with proper H2/H3 structures and CTAs.

Smart Filtering: Integrates with DataForSEO to filter keywords by search volume and competition levels before writing.

### 📋 Prerequisites <br />
n8n instance (installed or cloud)

Azure OpenAI API credentials

DataForSEO API credentials

SerpApi & Tavily API keys

Google Cloud Console credentials (Google Docs & Sheets APIs)

---

## **🇵🇱 Wersja Polska** ##
### 🌟 Przegląd <br />
Ten workflow automatyzuje najbardziej czasochłonną część SEO: przejście od surowego odkrywania słów kluczowych do gotowych do publikacji, obszernych treści. Łącząc dane wyszukiwania w czasie rzeczywistym z głębokim researchem AI, zapewnia, że każdy artykuł jest oparty na aktualnych faktach i zoptymalizowany pod intencję wyszukiwania.

### 🛠 Stack Techniczny <br />
Automatyzacjan: n8n

Silnik AI: Azure OpenAI (modele GPT-4o)

Dane SEO: DataForSEO (Keywords for Keywords), SerpApi (Autocomplete, PAA), Tavily (Research & Extract)

Integracje: Arkusze Google, Dokumenty Google

### 🚀 Główne Funkcje <br />
Wielozródłowe Odkrywanie Fraz: Wybór między rozszerzeniem Autocomplete, semantycznym 'Keywords for Keywords' lub pytaniami z sekcji 'People Also Ask'.

Głęboki Research Webowy: Każdy artykuł jest poprzedzony skanowaniem sieci w czasie rzeczywistym przez Tavily w celu zapewnienia dokładności technicznej.

Masowe Generowanie Treści: Skonfigurowany pod kątem tworzenia długich form (ponad 4000 słów) z poprawną strukturą nagłówków i wezwaniami do działania.

Inteligentne Filtrowanie: Integracja z DataForSEO pozwala na filtrowanie słów kluczowych według wolumenu wyszukiwań i poziomu konkurencji przed rozpoczęciem pisania.

### 📋 Wymagania <br />
Instancja n8n

Klucze API Azure OpenAI

Poświadczenia API DataForSEO

Klucze API SerpApi oraz Tavily

Poświadczenia Google Cloud Console (włączone API Dokumentów i Arkuszy Google)
