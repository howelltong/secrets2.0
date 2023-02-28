Secrets App (minimalistic version of "Whispers")

Real world application of

- Data bases (mongoDB)
- Routing (Express)
- Hashing + Salt Rounds, Encryption
- Authentication => Local registration/login AND google oauth2.0 (passport)

This application allows any user to register an account via a local option or using their google details. All data regarding the users will be saved into a database where only relevant data (secrets) is retrieved. Passwords are all hashed, making them undecipherable to anyone with access to the data base.
