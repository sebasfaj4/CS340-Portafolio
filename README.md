# CS 340 Portfolio – Grazioso Salvare Dashboard (Project Two)

## Portfolio Artifacts
- Project Two Dashboard Code (final)
- Project Two README (Word document)

---

## Journal Reflection

### 1) How do you write programs that are maintainable, readable, and adaptable?
I write maintainable programs by separating responsibilities and keeping code modular, consistent, and well documented. In this course, the CRUD Python module from Project One helped a lot because it isolated all database operations (create, read, update, delete) in one reusable class. That made the dashboard code easier to read because the dashboard could focus on the user interface and callbacks, while the CRUD module handled MongoDB access. The advantage of working this way is that changes to database logic can be made in one place without rewriting the UI code. In the future, I could reuse the CRUD module for other dashboards, scripts, or automation tasks that need to interact with MongoDB (for example, reporting, data cleanup, importing/exporting, or adding new search filters for another client).

### 2) How do you approach a problem as a computer scientist?
I approach problems by first understanding the requirements, then breaking the work into smaller steps, implementing one piece at a time, and testing as I go. For Grazioso Salvare, I started by confirming the database structure and access requirements, then built secure authentication, then added query logic, and finally connected the UI components to the database through the CRUD module. This differed from smaller assignments in other courses because it required thinking about a full workflow (data + database + reusable module + UI dashboard). In the future, I would continue using this approach: gather requirements, design the data model, create secure access, implement modular code, and validate with test queries and screenshots before final delivery.

### 3) What do computer scientists do, and why does it matter?
Computer scientists design and build systems that solve real problems efficiently and securely. This matters because organizations rely on software to make better decisions, save time, and reduce risk. In this project, the database and dashboard help Grazioso Salvare quickly find and categorize dogs that match rescue-training requirements. Instead of manually searching through data, users can filter and view relevant animals faster and more accurately. This type of system helps a company operate more efficiently, supports better outcomes, and makes it easier to scale their work as data grows.
