# Basalt

**Basalt** is a stdlib-first Go toolkit for building REST APIs with minimal boilerplate.

It focuses on:

- 🚀 Using Go’s standard library (`net/http`, `context`) as the foundation  
- 🔑 Built-in support for JWT and PIN-based authentication flows  
- 📦 Generic CRUD controllers for any `IDataSource` implementation  
- 🗄️ First-class support for PostgreSQL and MySQL  
- 🔎 Rich query layer with filters and **dig** (related data loading)  
- 🧹 Minimal dependencies, clear interfaces  

Basalt is **not a web framework** — it’s a toolkit that plugs into whatever routing solution you prefer.

---

## Installation

```bash
go get github.com/zicare/basalt
