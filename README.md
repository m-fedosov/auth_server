# 🔐 OpenID Connect Authorization Server – Spring Security

Микросервис реализует **собственный сервер авторизации** (Authorization Server) по протоколу OAuth 2.1 / OpenID Connect с использованием Spring Authorization Server.

Разработка выполнена в рамках выпускной квалификационной работы:

> **Анализ современных методов аутентификации: устойчивость к угрозам информационной безопасности и перспективы развития беспарольных технологий**  
> НИУ ВШЭ, направление "Информационная безопасность", Федосов М.И., 2025

---

## 📌 Описание

Authorization Server — центральный компонент схемы OpenID Connect, реализующий:

- Авторизацию пользователей (через login-форму).
- Выдачу `Authorization Code`, `Access Token`, `ID Token` и `Refresh Token`.
- Поддержку клиента `client_oidc`.

---

## 🧩 Технологии

- Java 21
- Spring Boot 3
- Spring Authorization Server (`spring-boot-starter-oauth2-authorization-server`)
- Spring Security
- Maven
- JWT

---

## ⚙️ Запуск проекта

```bash
git clone https://github.com/m-fedosov/auth_server.git
cd auth_server
./mvnw spring-boot:run
```