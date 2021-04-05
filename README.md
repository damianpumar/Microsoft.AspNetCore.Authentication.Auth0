## :pencil: In your startup.cs

```
public void ConfigureServices(IServiceCollection services)
{
    services.AddAuth0();
}
```

## :pick: In your controller use this.

```
    this.HttpContext.User.GetId();
```

## :mag: In your setting we need auth0 information like this

```
"Auth0": {
    "Authority": "xxxxxx/",
    "Audience": "xxxxxx/api/v2/"
  },

```
