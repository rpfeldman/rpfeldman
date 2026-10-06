# Hey, I'm Rama 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/ramiro-pablo-feldman-94b33b3b7/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ramirofeldman0@gmail.com)
[![Codewars](https://img.shields.io/badge/Codewars-B1361E?style=for-the-badge&logo=codewars&logoColor=white)](https://www.codewars.com/users/rpfeldman)

I'm **Ramiro Pablo Feldman**, a **.NET Software Engineer** from Argentina.
I've been writing code since I was 10, and today I build cross-platform apps in C# — like [Tradeckr](https://github.com/rpfeldman/Tradeckr), a .NET MAUI finance app and my first paid project.

---

## 🚀 About Me

Between the ages of 10 and 13 I was already shipping small games in GameMaker and Unity, publishing real Minecraft mods and running my own Minecraft servers, which meant managing players and keeping everything alive long before I knew what a backend was.

That's where it clicked: what I love is building systems. Creating them, running them and watching every piece work together. The tools changed over the years, but that drive never did. I don't end a coding session thinking "finally, done"; I end it wishing I could keep going. When I got serious, I chose C# on purpose: I like a language that's explicit about types, structure and control.

I don't stop at *how* to use a tool. I need to know *what it is* and *why it exists*. That's why I take .NET apart: I've rebuilt `Dictionary`, `List<T>` and a lock-striped `ConcurrentDictionary` from scratch just to see how they work, and I document everything I learn in my own 6,000+ line technical manual.

Tradeckr is the clearest example of how I work. I started it without knowing .NET MAUI, learned it while building, and every time I understood something better, I went back and refactored the architecture instead of piling patches on top. I'm the developer behind it, and it's coming soon to the App Store, Google Play and Windows.

I sweat the details (I benchmark my Codewars solutions against the community's just to see whose is faster), but I don't believe in "perfect" code, only in tradeoffs. The one real sin is code that doesn't work.

Native Spanish and fluent English. Open to .NET development roles.

---

## 🔧 Technical Skills

### **Core Stack**
![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![.NET](https://img.shields.io/badge/.NET_10-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=for-the-badge&logo=blazor&logoColor=white)
![.NET MAUI](https://img.shields.io/badge/.NET_MAUI-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

### **Languages**
- **C#**
- **SQL**

### **Application Development**
- **Web:** ASP.NET Core (Web API, MVC, Minimal APIs), Blazor, SignalR, HTML & CSS
- **Desktop:** WPF, Windows Forms
- **Mobile & Cross-Platform:** .NET MAUI (Android, iOS, Windows)
- **UI:** XAML, styling & theming, data visualization (LiveCharts2)

### **Database & Storage**
- **Relational:** SQL Server, SQLite
- **Data Access:** Entity Framework Core, Dapper

### **Architecture & Design**
- **OOP & SOLID:** encapsulation & invariant design, subtype polymorphism, abstract classes vs. interfaces, LSP, sealed-by-default
- **Type Design:** value vs. reference semantics, struct vs. class tradeoffs, generic constraints
- **Patterns:** layered architecture, generic Repository, Dependency Injection, MVVM (CommunityToolkit.Mvvm), event pattern, REST APIs
- **Error Handling:** `Result<T>` / `Option<T>` with factory methods that make invalid states unrepresentable — no exceptions for business logic

### **Networking**
- HTTP/HTTPS, DNS, TCP/IP, request/response lifecycle

### **Testing & Tooling**
- **Testing & Performance:** xUnit, BenchmarkDotNet
- **Tools:** Visual Studio, Git, GitHub, NuGet

### **Under the Hood**
I don't just use .NET — I take it apart to see how it works.
- **Async:** compiler-generated state machines, `ValueTask` / `IValueTaskSource`, `SynchronizationContext`, `ConfigureAwait` & deadlocks, cancellation
- **Type System & CLR:** stack vs. heap, boxing/unboxing, virtual dispatch, reified generics vs. type erasure, covariance & contravariance
- **Delegates & Closures:** closure capture via compiler-generated classes, expression trees vs. `Func<T>`
- **LINQ:** iterator state machines (`yield`), deferred execution & multiple enumeration, `IQueryable` providers & expression translation, N+1 queries, `IAsyncEnumerable` streaming
- **Collections:** hashing, load factor, resizing & rehashing, sorted & immutable collections *(built my own `Dictionary` and `List<T>`)*
- **Concurrency:** locks, lock striping, thread-safe collections *(built a lock-striped `ConcurrentDictionary` from scratch)*
- **Memory & Performance:** LINQ allocations, `Span<T>` / `ReadOnlySpan<T>`, object header layout, PLINQ, LINQ vs. loops tradeoffs
- **EF Core:** short-lived contexts, `AsNoTracking`, efficient projections, owned entities, TPH, `ExecuteUpdate`
- **ASP.NET Core:** hosting model (`WebApplicationBuilder`), middleware pipeline

### **Problem Solving**
[![Codewars](https://www.codewars.com/users/rpfeldman/badges/small)](https://www.codewars.com/users/rpfeldman)

Top 6% of Codewars users, solving in C# and benchmarking my solutions against the community's with BenchmarkDotNet.

---

## 💼 Professional Experience

### **Co-Founder & Lead Developer**
**Tradeckr, Argentina**  
*2026 – Present*  
- Co-founded Tradeckr and own its entire technical side, from architecture and development to UI and release, while my partner leads distribution and community.
- Designed and built a cross-platform finance & trading tracker in .NET MAUI, coming soon to the **App Store**, **Google Play** and **Windows**.
- Architected a clean layered solution (Domain, generic Repository, Data Services, EF Core + SQLite storage, MVVM UI) that has survived several major refactors as the product grew.
- Implemented functional error handling with `Result<T>` and `Option<T>` value types, protecting domain invariants end to end.
- Built a multi-currency system that stores every amount in a fixed internal unit, keeping conversions consistent across the whole app.
- Optimized data access with short-lived EF Core contexts, no-tracking reads and parallel queries.
- Created reusable, theme-aware chart components with LiveCharts2 and a custom typography system.
- Released as open source under the Apache 2.0 license.

---

## 🎓 Education

- **High School Diploma in Economics & Business Administration**  
  *Colegio La Salle La Inmaculada, Bahía Blanca, Argentina*
- **Self-Directed Software Engineering Program (in progress)**  
  *Structured curriculum in C# & .NET, documented in a 6,000+ line technical manual of my own*

---

## 🎯 What I Bring to the Table

- **Depth First:** I learn things down to the runtime, so I fix causes, not symptoms. If something works, I want to know *why* it works.
- **Ownership:** I've taken a product from a blank solution to a client-ready app on my own: architecture, code, UI and delivery. I don't wait to be told what's next.
- **Pragmatism over Ego:** I'm obsessive about details, but I follow one rule above all: no overengineering. The simplest design that solves the real problem wins.
- **Self-Discipline:** I design my own curriculum, set my own deadlines and track my progress with my own system. 
- **Clear Communication:** I explain instead of reciting; my manual is written so someone else could learn from it. Fluent in English, and I'm actively training public speaking.
- **Product & Business Sense:** With a background in economics and business administration, I think about users, pricing and distribution, not just code.
