# Blog autorstwa Kamila Pietrzaka

## 🔗 Linki

- **Blog**: [https://monetapietrzak.com](https://monetapietrzak.com)
- **Oryginalny motyw Qubit**: [https://github.com/Chrede88/qubit](https://github.com/chrede88/qubt)
- **Hugo**: [https://gohugo.io/](https://gohugo.io/)
- **Dokumentacja Hugo**: [https://gohugo.io/documentation/](https://gohugo.io/documentation/)
- **Dokumentacja motywu Qubit**: [https://github.com/Chrede88/qubit/wiki](https://github.com/chrede88/qubt/wiki)

### ℹ️ Dodatkowe o blogu

Blog powstał na silniku **Hugo**. Użytym motywem bloga jest **Qubit**, który został zmodyfikowany przeze mnie. 

- **Hosting**: Cloudflare
- **Logo**: Obraz wygenerowany przez DALL-E 2

## 🛠️ Komendy

### Uruchomienie serwera lokalnego
```bash
hugo server
```
Serwer będzie dostępny pod adresem `http://localhost:1313`

### Aktualizacja motywu
Aktualizacja do najnowszej wersji:
```bash
hugo mod get -u
```

Aktualizacja do konkretnej wersji:
```bash
hugo mod get github.com/Chrede88/qubt@vX.Y.Z
```
Zastąp `X.Y.Z` numerami odpowiedniej wersji. Lista dostępnych wersji: [releases](https://github.com/chrede88/qubt/releases)

### Aktualizacja Hugo
```bash
# Na macOS (używając Homebrew)
brew upgrade hugo

# Na Windows (używając Chocolatey)
choco upgrade hugo

# Na Linux (używając Snap)
snap refresh hugo
```

## 📝 Zarządzanie treścią

- Posty blogowe dodawaj do katalogu `content/blog/`
- Strona "O mnie" w pliku `content/about.md`
- Strona "Kontakt" w pliku `content/contact.md`
- Konfigurację znajdziesz w plikach:
  - `config/_default/hugo.yaml`
  - `config/_default/params.yaml`
  - `config/_default/menus.yaml`

> Nowe wpisy należy umieścić w `content/blog/post{{ kolejny numer }}` wraz z plikiem `index.md` i dodatkowymi plikami jak zdjęcia. W `assets/post{{ kolejny numer }}` umieszcza się grafiki banerów i grafiki okładkowe. Więcej przykładów tu: https://github.com/chrede88/qubtTemplate

## 📚 Dodatkowe informacje

Więcej informacji o konfiguracji i możliwościach znajdziesz w [dokumentacji motywu](https://github.com/chrede88/qubt/wiki).
