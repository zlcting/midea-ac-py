**Example configuration.yaml:**

```yaml
climate:
  platform: midea
  app_key: midea_app_api_key
  username: 'foo@bar.com'
  password: !secret midea_password
  
```

**Configuration variables:**  
  
key | description  
:--- | :---  
**platform (Required)** | The platform name.
**app_key (Required)** | Midea app API key.
**username (Required)** | Username for Midea cloud.
**password (Required)** | Password for Midea cloud.
