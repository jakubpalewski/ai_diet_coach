# AI Diet Coach 🍎🤖

Inteligentny asystent dietetyczny, który eliminuje ręczne wprowadzanie danych do liczników kalorii. Aplikacja pozwala użytkownikowi "rozmawiać" o swoich posiłkach, a AI automatycznie wylicza kalorie, makroskładniki i mikroskładniki, zapisując je w bazie danych.

## 🚀 Jak to działa?

1.  **Czat:** Użytkownik pisze naturalnie: *"Zjadłem 200g kurczaka z ryżem i brokułami"*.
2.  **Analiza AI:** LLM (OpenAI/DeepSeek) analizuje tekst, dopytuje o szczegóły w razie potrzeby i konwertuje opis na ustrukturyzowane dane JSON.
3.  **Baza Danych:** Dane są automatycznie zapisywane w tabelach Supabase.
4.  **Kontekst:** System pamięta preferencje użytkownika (np. dieta keto, alergie) i dostosowuje porady dietetyczne w czasie rzeczywistym.

## 🛠 Tech Stack

* **Frontend:** Next.js 15 (App Router), React, Tailwind CSS
* **AI/LLM:** Vercel AI SDK, OpenAI API (Function Calling / JSON Mode)
* **Backend/Database:** Supabase (PostgreSQL, Auth)
* **UI Components:** shadcn/ui, Lucide React
* **Validation:** Zod (Type-safe schemas)

## ✨ Główne funkcjonalności

* **Natural Language Logging:** Logowanie posiłków bez szukania w bazach produktów.
* **Macro & Micro Tracking:** Śledzenie nie tylko B/T/W, ale też witamin i minerałów.
* **Personalized Context:** AI zna Twoje cele i historię, działając jak prawdziwy trener.
* **Visual Dashboard:** Wykresy postępu i podsumowania dnia.
