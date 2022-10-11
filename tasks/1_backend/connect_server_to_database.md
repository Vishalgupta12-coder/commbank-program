# Connect Server To Database

- [ ] Navigate to “Database Deployments”
- [ ] Click “Connect”
- [ ] Click “Connect Your Application”
- [ ] Select “C# / .NET” for the driver
- [ ] Select “2.13 or later” for the version
- [ ] Copy the connection string
- [ ] Add the connection string to `Secrets.json`

```json
// Secrets.json

{
  "ConnectionStrings": {
    "CommBank": "{mongodb+srv://new_user1:<p9oKuL8CB7AulgIa>@cluster0.gccc21g.mongodb.net/?retryWrites=true&w=majority}"
  }
}
```
