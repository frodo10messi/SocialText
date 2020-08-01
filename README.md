# Social Text

Social Media Application

## Features
- Lazy Loading Data From Database
- Multiple Language
- Realtime Chat
- Firebase CRUD Operations
- Firebase Cloud Firestore, Storage and Authentication synced

##
```text
 ├── assets
 |   ├── lang
 |       ├── en.json             # English translation
 |       ├── tr.json             # Turkish translation
 |    
 ├── lib
     ├── helper                  
     |   ├── app_localizations   # Multi language helper
     |   ├── ImageHelper         # End-to-end, integration tests (alternatively `e2e`)
     |
     ├── models                  
     ├── screens                 # User Interfaces
     ├── services                
     |   ├── auth.dart           # Firebase Authenticattion Service
     |   |── database.dart       # Firebase Cloud Firestore Service
     |   |── storage.dart        # Firebase Storage Service
     |
     ├── shared                  # Common Widgets
     ├── validation              # Input Validators
     └── wrapper.dart            # User auth checker. 
```
