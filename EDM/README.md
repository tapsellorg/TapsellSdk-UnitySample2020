# Unity 2019 Sample
TapsellSdk sample for unity 2019

### How:
1. Add google ScopedRegisteries to manifest.json of your project:
    ```
    "scopedRegistries": [
        {
          "name": "Google",
          "url": "https://unityregistry-pa.googleapis.com",
          "scopes": [
            "com.google"
          ]
        }
      ]
    ```

2. Add TapsellSdk-UnityPlugin:  
    in unity goto Window > Package Manager. Click (+) Sign, from dropdown menu select Add package from git URL.
    put https://github.com/tapsellorg/TapsellSdk-UnityPlugin.git in input field and click add.


3. switch to Android platform.

4. goto Assets > External Dependency Manager > Android Resolver > Resolve(Force Resolve).
