# git-commit-methodology

# Table of Contents
- [git-commit-methodology](#git-commit-methodology)
- [Git Commit useful links](#git-commit-useful-links)
- [Commit Message Convention](#commit-message-convention)
- [Rules](#rules)
- [Icon Rules & Description in Table Format](#icon-rules--description-in-table-format)


# Git Commit useful links

- [Gitmoji](https://gitmoji.dev) : Icon for commit message

# Commit Message Convention

## Rules:

**1. Follow this rule:**

```
<Icon>[<What Happend>]: <File Path>: <File Name Or Section Name>: <Description>
```

Example:

```
✨[Added]: website//package: model: `included`, `excluded` add to as model property
```

## [Icon Rules:](#icon-rules--description-in-table-format)

**✨[Added]:**  
```
✨[Added]: 
```  
```
✨[Added]: module/counter: Added counterSlice buttons
```

**✅[Updated]:**  
```
✅[Updated]: 
```  
```
✅[Updated]: module/counter: Updated counterSlice buttons
```

**🐛[Fix]:**  
```
🐛[Fix]: 
```  
```
🐛[Fix]: module/counter: Fixed counting logic in counterSlice
```

**💄[UI]:**  
```
💄[UI]: 
```  
```
💄[UI]: module/header: Redesigned navigation bar
```

**🚧[Processing]:**  
```
🚧[Processing]: 
```  
```
🚧[Processing]: module/orders: Working on order history
```

**🚨[Error]:**  
```
🚨[Error]: 
```  
```
🚨[Error]: module/api: Resolved unhandled exception
```

**🔥[Remove]:**  
```
🔥[Remove]: 
```  
```
🔥[Remove]: module/legacy: Removed deprecated files
```

**⚡️[Improve]:**  
```
⚡️[Improve]: 
```  
```
⚡️[Improve]: module/db: Optimized database queries
```

**🔧[Config]:**  
```
🔧[Config]: 
```  
```
🔧[Config]: project/setup: Configured Babel settings
```

**✏️[Fix]:**  
```
✏️[Fix]: 
```  
```
✏️[Fix]: docs/readme: Fixed typo in instructions
```

**♻️[Refactor]:**  
```
♻️[Refactor]: 
```  
```
♻️[Refactor]: module/auth: Refactored login flow
```

**📝[Documentation]:**  
```
📝[Documentation]: 
```  
```
📝[Documentation]: module/api: Updated API usage guide
```

**🚀[Deploy]:**  
```
🚀[Deploy]: 
```  
```
🚀[Deploy]: project: Deployed version 1.0.0 to production
```
---
## Icon Rules & Description in Table Format:

| Icon Type          | Description                                | Example                                                |
| ------------------ | ------------------------------------------ | ------------------------------------------------------ |
| ✨[Added]:         | Add New Feature or Something               | ✨[Added]: module/auth: Added login functionality      |
| ✅[Updated]:       | Updated Feature or Something               | ✅[Updated]: module/ui: Updated button styles          |
| 🐛[Fix]:           | Fixed a Bug                                | 🐛[Fix]: module/cart: Fixed item count calculation     |
| 💄[UI]:            | Update UI                                  | 💄[UI]: module/header: Redesigned navigation bar       |
| 🚧[Processing]:    | Feature or Something under construction    | 🚧[Processing]: module/orders: Building order history  |
| 🚨[Error]:         | Error in Code So be warning                | 🚨[Error]: module/api: Unhandled exception resolved    |
| 🔥[Remove]:        | Remove code or files.                      | 🔥[Remove]: module/legacy: Removed old API endpoints   |
| ⚡️[Improve]:      | Improve performance or better Code         | ⚡️[Improve]: module/db: Optimized query execution      |
| 🔧[Config]:        | Configurate project of Something           | 🔧[Config]: module/setup: Configured ESLint rules      |
| ✏️[Fix]:           | Fix Typo Or Rename Something               | ✏️[Fix]: module/readme: Fixed typo in documentation    |
| ♻️[Refactor]:      | Code Refactor                              | ♻️[Refactor]: module/auth: Refactored login logic      |
| 📝[Documentation]: | Update Documentation                      | 📝[Documentation]: module/api: Added API usage guide  |
| 🚀[Deploy]:        | Deploy                                     | 🚀[Deploy]: project: Deployed version 1.0.0 to production |