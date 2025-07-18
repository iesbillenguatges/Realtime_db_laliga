# Realtime_db_laliga: gestió de Jugadors de Futbol

Aplicació web per gestionar una base de dades de jugadors de futbol utilitzant **Firebase Realtime Database**. Permet afegir, eliminar i llistar jugadors amb una interfície simple i funcional estilitzada amb **W3.CSS**.

## Funcionalitats

- **Afegir jugadors** amb dades com:
  - Nom
  - Equip
  - Posició
  - Dorsal
  - Edat
- **Eliminar jugadors** mitjançant el seu ID únic.
- **Visualitzar** tots els jugadors en una taula dinàmica.

## Tecnologies utilitzades

- HTML5
- CSS3 (amb [W3.CSS](https://www.w3schools.com/w3css/))
- JavaScript
- [Firebase Realtime Database](https://firebase.google.com/products/realtime-database)

## Estructura del projecte

```
/
├── index.html # Interfície principal
├── README.md # Aquest fitxer
└── firebaseConfig # Inserit dins l'script
```

## Com executar el projecte

1. **Clona aquest repositori**:
   ```bash
   git clone https://github.com/el-teu-usuari/gestio-jugadors-futbol.git
   cd gestio-jugadors-futbol
   ```
2. **Obre index.html al navegador:
Pots obrir-lo directament o servir-lo amb una extensió de "Live Server" si estàs utilitzant VS Code.

3. **Configura Firebase:

    - Ves a Firebase Console.
    - Crea un nou projecte.
    - Afegeix una base de dades de tipus Realtime Database.
    - Substitueix l’objecte firebaseConfig del fitxer index.html amb les dades del teu projecte.

4, **Assegura’t que les regles de la base de dades (durant desenvolupament) permetin lectura/escriptura:
```
    {
      "rules": {
        ".read": true,
        ".write": true
      }
    }
```
