
## 🌱 Spring DI — Inversion de Contrôle & Injection de Dépendances

> Projet Maven Java illustrant les principes fondamentaux de Spring IoC/DI à travers plusieurs approches de configuration.

---

## 🛠️ Technologies

| Technologie | Version |
|---|---|
| ☕ Java | JDK 25 |
| 🍃 Spring Context | 6.1.2 |
| 🔨 Maven | 3.x |
| 🧪 JUnit | 4.13.2 |
| 💡 IntelliJ IDEA | 2025.2.3 |


---

## 🖥️ Résultats d'exécution

### ▶️ Capture 1 — Exécution avec `@Qualifier("dao")` — DaoImpl (profil prod)

<img width="1425" height="413" alt="Screenshot 2026-03-10 160931" src="https://github.com/user-attachments/assets/b80f48e5-75ac-4466-a185-029dee773e0e" />


---

### ▶️ Capture 2 — Exécution avec profil `dev` — DaoImpl2
<img width="1332" height="380" alt="Screenshot 2026-03-10 161136" src="https://github.com/user-attachments/assets/7e8069d1-014f-4208-8ae4-2e0fe779f935" />


## ✅ Conclusion

Ce projet illustre les concepts fondamentaux de Spring :

| Concept | Implémentation |
|---|---|
| 🔄 IoC (Inversion de Contrôle) | `ApplicationContext` gère les beans |
| 💉 Injection par champ | `@Autowired` |
| 🎯 Sélection d'implémentation | `@Qualifier("dao2")` |
| 🔍 Scan automatique | `@ComponentScan` |
| 🌍 Profils d'environnement | `@Profile("dev")` / `@Profile("prod")` |
| 📄 Configuration XML | `ClassPathXmlApplicationContext` |
| 🧪 Test sans Spring | Injection manuelle via `setDao()` |
