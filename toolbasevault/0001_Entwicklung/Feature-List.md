# App-Struktur von Portfolioland

# Terms
Terms zeigt die Nutzungsbestimmungen für [[0001_Designsystem "Portfolioland"|Portfolioland]] an.
- [ ] Terms (Code of Conduct)
- [x] Konditionales Blocken der Nutzung bis akzeptiert.
- [ ] Datenschutzbedingungen klären
## Auth
Authentikation ist ein Grundbaustein für die Arbeitsweise von [[0001_Designsystem "Portfolioland"|Portfolioland]]. Hier wird sichergestellt, dass die User nur Zugang zu ihren eigenen Daten haben und nur diese verändern/bearbeiten können. 
### Frontend
- [x] Login (E-mail, Password)
- [x] Logout
- [ ] Register
- [ ] [[SAML-Protokol|SAML]]-Auth (nice to have)
## Profil (Protected Place)
Im Profil von [[0001_Designsystem "Portfolioland"|Portfolioland]] können die authentifizierten User ihr Profil anpassen, Arbeiten erstellen und den Status ihrer Arbeit 

- [ ] Einstellungen
	- [x] Name
	- [x] Pronomen
	- [x] Socials
	- [ ] Klasse

- [ ] Create New Work Entry Modal
	- [x] Title
	- [x]  Description
	- [x] Tag
	- [x] Date
	- [ ] First Picture --> New Modal
	- [ ] Template Struktur
	- [x] Public State
	- [x] Submit
  
- [ ] Drag and Drop - Builder
	- [ ] Position of Dragger and Delete
	- 
- [x] Picture
- [x] Headline
- [x] Text
- [ ] Video
- [ ] embed
	- [ ] Linkchecker
	

- [x] List of Works
	- [x] Public State
	- [x] DeleteButton
	- [ ] Drag n Drop - Sortierung der Einträge

# Öffentlicher Bereich
Der Öffentliche Bereich zeigt die Öffentlich gestellten Arbeiten und Profile an. Des Weiteren bietet der Bereich eine Suchfunktion, sowie eine Landing-Page mit einer Auswahl an Arbeiten.
- [x] Artists Page
	- [ ] Profil Page
	- [x] Work Page
- [ ] Search
- [ ] Frontpage
- [x] Tags
- [ ] Meldebutton und Meldeformular
## Admin-Page
Die Admin-Page soll der Rolle des Admin die Möglichkeit geben einfach auf Meldungen zu reagieren. Sperrungen, ebenso wie Löschungen, benötigen allerdings einer Erklärung.
- [ ] Inbox Meldungen
	- [ ] E-mail-Notification
- [ ] Sperrmöglichkeit mit Begründung warum gesperrt.
	- [ ] User
	- [ ] Content
- [ ] Löschfunktion
	- [ ] Content
	- [ ] Tags

