# In your startup.cs

```
public void ConfigureServices(IServiceCollection services)
{
    services.AddAuth0();
}
```

# In your controller use this.

```
    this.HttpContext.User.GetId();
```

# In your setting we need auth0 information like this

```
"Auth0": {
    "Authority": "xxxxxx/",
    "Audience": "xxxxxx/api/v2/"
  },

```
