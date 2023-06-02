# Rendezvény és Meghívottjai Kezelő Webalkalmazás
Ez a webalkalmazás lehetővé teszi, hogy a lehető legegyszerűbben hozza össze az embereket közösségi eseményeken, és minél könnyebb legyen a résztvevők meghívása és a visszajelzések begyűjtése. Az alkalmazás a rendezvény szervezőinek és adminisztrátorainak szól, nem pedig a meghívottaknak. Célja, hogy az adott rendezvényen résztvevőkről a szükséges adatok, információk legyenek tárolva.

Alkalmazás Funkciói
Események létrehozása, módosítása és törlése: Az adminisztrátorok és a szervezők létrehozhatnak új eseményeket, módosíthatják a meglévő események adatait vagy törölhetnek eseményeket.

Vendégek hozzáadása és kezelése: A felhasználók hozzáadhatnak új vendégeket, módosíthatják a vendégek adatait, és kezelhetik a vendéglistákat. Minden vendéghez tartozik egy név, titulus, születési dátum, telefonszám, e-mail cím és egy opcionális megjegyzés. A vendégek adatait a szerveren tárolják.

Képfeltöltés: A felhasználók feltölthetnek képet a vendégekről. Ha nincs kép feltöltve, akkor a rendszer egy alapértelmezett képet használ.

Autorizáció és szerepkörök: Az alkalmazás támogatja az autorizációt, a felhasználók "Admin" vagy "User" szerepkörben léphetnek be. Mindkét szerepkörben lévő felhasználók hozzáadhatnak és kezelhetnek eseményeket és vendégeket, de vannak bizonyos funkciók, amelyek csak az adminisztrátorok számára érhetőek el.

Technikai Részletek
Az alkalmazás a Blazor keretrendszert használja, amely a .NET Core-on alapul, és lehetővé teszi a böngészőben futó interaktív webes felhasználói felületek létrehozását C# nyelven. Az adatok tárolására MySQL adatbázist használunk, ami egy népszerű nyílt forráskódú relációs adatbázis-kezelő rendszer.

Event and Guest Management Web Application
This web application enables to connect people at community events in the simplest possible way, and to make inviting participants and collecting feedback as easy as possible. The application is intended for event organizers and administrators, not the invitees. Its purpose is to store necessary data and information about participants at the given event.

Application Features
Creating, modifying, and deleting events: Administrators and organizers can create new events, modify the data of existing events, or delete events.

Adding and managing guests: Users can add new guests, modify the data of guests, and manage guest lists. Each guest has a name, title, date of birth, phone number, e-mail address, and an optional note. The guest data is stored on the server.

Image upload: Users can upload images of guests. If no image is uploaded, the system uses a default image.

Authorization and roles: The application supports authorization, users can log in as "Admin" or "User". Users in both roles can add and manage events and guests, but there are certain features that are only available to administrators.

Technical Details
The application uses the Blazor framework, which is based on .NET Core, and allows the creation of interactive web user interfaces in the browser in C# language. For data storage, we use a MySQL database, which is a popular open-source relational database management system.
